# Aplicación web para la gestión de membresías de la Asociación Civil [![Build Status](https://travis-ci.org/PyAr/asoc.svg?branch=master)](https://travis-ci.org/PyAr/asoc)

## Desarrollo (con Docker)

```bash
make build-dev
make start-dev
make install-dev
```

If you need to create a Django's superuser:

```bash
$ make createsuperuser
Username (leave blank to use 'root'): admin
Email address: admin@example.com
Password:
Password (again):
Superuser created successfully.
```

## Deploy a staging (PENDING TO CONFIGURE)

Cada merge a master genera una imagen actualizada en docker hub con el tag `latest` y automaticamente se actualiza el deploy.

## Deploy a producción.

Si se crea un tag con el formato x.y.z automaticamente se va a generar una imagen de Docker en docker hub con el tag `stable` y `prod-x.y.z` y una vez generada la imagen se va a deployar automaticamente. 




## Producción

Chequear documentación en https://github.com/PyAr/pyar_infra/

## Contribuyendo con Asoc Members

Existen varias maneras de contribuir con la web de la Asociación Civil de Python Argentina, reportando bugs, revisando que esos bugs se encuentren vigentes, etc, los pasos que se encuentran a continuación describen como realizar contribuciones a nivel de la aplicación.

Todas las contribuciones son mas que bienvenidas, pero para empezar a contribuir (con código) estos serían los siguientes pasos:

    Lee el archivo CONTRIBUTING.md para entender cómo funciona git, git-flow y tener una calidad mínima del código

    Recuerda hacer tests! (en lo posible) de los cambios que hagas, si bien la base de tests en este momento no es muy grande es algo que estaremos intentando cambiar

    Una vez tengas todo revisado haz un pull request al branch master de este proyecto https://github.com/PyAr/asoc_members/ , haciendo referencia al issue.

Una vez tu pull request sea aprobado tu código pasará a la inmortalidad de PyAr :)
