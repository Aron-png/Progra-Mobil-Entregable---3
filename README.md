# Progra-Mobil-Entregable---3


Hay herramientas que usarán en el entorno de desarrollo con su descripción detallando el proceso de instalación.
_Cursiva_


## Instalación 🔧

Para instalar ionic primero debemos de instalar el node js. Para ello ingresamos al siguiente link:
[Instalar Node js](https://nodejs.org/en/download)
 

### Instalar node js 
---

**Paso 1: Descargar el archivo ejecutable**

Seleccionar la opcion correspondiente al sistema operativo a ejecutar.
![No se pudo cargar la imagen](images/node1.PNG)

**Paso 2: Abrir el archivo descargado, con extension _".msi"_**

![No se pudo cargar la imagen](images/node2.PNG)

**Paso 3: Aceptamos terminos y condiciones**
![No se pudo cargar la imagen](images/node3.PNG)

**Paso 4: Ubicamos la ruta de guardado**
![No se pudo cargar la imagen](images/node4.PNG)

**Paso 5: Aceptar instalar herramientas adicionales**

La siguiente pestaña le daremos a _Instalar_
![No se pudo cargar la imagen](images/node5.PNG)

### Probar instalacion de node js 
---
**Paso 1: instalar ionic**
_Debes ingresar al buscador "cmd" para abrir el Simbolo de sistema. En el, debes ingresar el siguiente codigo:_
```
node -v
```
Se mostrara la siguiente imagen:

![No se pudo cargar la imagen](images/node6.PNG)

### Instalar ionic
---
_Debemos ingresar el siguiente comando en el cmd_
```
npm install -g ionic
```
_Luego comprobamos la instalacion con:_
```
ionic --version
```
Se mostrara la siguiente imagen:
![No se pudo cargar la imagen](images/cmd1.PNG)

**Paso 2: Crear proyecto**

El siguiente paso sera crear una carpeta:
![No se pudo cargar la imagen](images/carpeta1.PNG)

Luego, escribimos cmd en su ruta y le damos a enter:
_Te deberia abrir un cmd_

![No se pudo cargar la imagen](images/carpeta2.PNG)

Ingresaremos el siguiente comando:
_podemos personalizar el nombre del proyecto y agregamos "tabs/sidemenu/blank" segun nos convenga_

tabs = tablas, sidemenu = menu o blank = completamente en blanco.

```
ionic start “nombre” blank
```
Deberia quedar asi:

_Nos pedira elegir un framework, en este caso elegimos react._
![No se pudo cargar la imagen](images/proyecto1.PNG)

Si tenemos el proyecto de esta forma significa que el proyecto esta creado:

![No se pudo cargar la imagen](images/proyecto2.PNG)

**Paso 3: Instalar dependencias**

Escribimos cmd en la ruta del proyecto y le damos a enter.

_Luego, ingresamos el siguiente comando para poder verlo en el navegador:_
```
ionic serve
```

Deberia aparecer asi:
_Le damos a "y" para instalar react-scrpits y esperamos unos minutos._
![No se pudo cargar la imagen](images/proyecto3.PNG)

### Fuentes
---
[Guia para instalar ionic](https://www.digitaldot.es/crear-app-ionic-visual-studio-code/)

[Guia para instalar Node js](https://codigofacilito.com/articulos/instalar-nodejs-windows)

## Diagrama de despliegue 📦

Diagrama elaborado relacionado correctamente a los
requisitos no funcionales

_Cursiva_

```
Da un ejemplo
```

## Requermiemientos no funcionales ⚙️

Los requerimientos están relacionados con el diagrama de despliegue

_Cursiva_

## Diagrama de casos de uso 📋

Diagrama elaborado relacionado correctamente a los
requisitos funcionales.

_Cursiva_

```
Da un ejemplo
```

### Descripción de casos de uso 
Las descripciones están relacionadas correctamente a los
requisitos funcionales y los mockups

_Cursiva_


## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS


## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

