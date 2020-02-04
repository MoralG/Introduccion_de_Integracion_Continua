# Introducción a la integración continua

![Travis](image/Travis.png)

#### Vamos a realizar una integración continua con Travis con la ayuda de django.

### [Tarea 1](https://github.com/MoralG/Introduccion_de_Integracion_Continua/blob/master/Intergracion_Continua.md#tarea-1-despliegue-de-una-p%C3%A1gina-web-est%C3%A1tica-build-deploy)

#### Despliegue de una página web estática (build, deploy)

Generar una página web estática con un generador de paginas estáticas y desplegarla.

* En el repositorio GitHub sólo tienen que estar los ficheros markdown.
* La página se debe generar en el sistema de integración continúa, por lo tanto debemos instalar las herramientas necesarias.
* Investiga si podemos desplegar de forma automática en el servicio elegido (si es necesario cambia el servicio de hosting para el despliegue).

### [Tarea 2](https://github.com/MoralG/Introduccion_de_Integracion_Continua/blob/master/Intergracion_Continua.md#tarea-2-integraci%C3%B3n-contin%C3%BAa-de-aplicaci%C3%B3n-django-test--deploy) 

#### Integración continúa de aplicación django (Test + Deploy)

Vamos a trabajar con el repositorio de la aplicación django_tutorial. Esta aplicación tiene definidas una serie de test, que podemos estudiar en el fichero `tests.py` del directorio `polls`.

Para ejecutar las pruebas unitarias, ejecutamos la instrucción `python3 manage.py test`.

* Estudia las distintas pruebas que se han realizado, y modifica el código de la aplicación para que al menos una de ella no se ejecute de manera exitosa.

A continuación vamos a configurar la integración continúa para que cada vez que hagamos un commit se haga la ejecución de test en travis.

* Crea un fichero .travis.yml para realizar de los tests en travis. Entrega el fichero .travis.yml, una captura de pantalla con un resltado exitoso de la IC y otro con un error.

Siguiendo la guía de esta página: [Continuous delivery of a Django app from Travis CI to PythonAnywhere](https://flowfx.de/blog/continuous-delivery-of-a-django-app-from-travis-ci-to-pythonanywhere/). Para además de realizar los tests, se haga un despliegue al servicio **pythonanyhere**.

* Entrega un breve descripción de los pasos más importantes para realizar el despliegue desde travis.

