# N2O

## Resumen ejecutivo

### Descripción

El propósito de este proyecto es crear una estructura base de código para la implementación de una página web dedicada a un grupo de jugadores de e-sports mexicanos. Esta es una gran oportunidad para poner en práctica todo lo que he aprendido hasta el momento en este certificado y en mi carrera en el TecMilenio. Por otro lado, es una necesidad que la empresa ha tenido desde hace tiempo, pero debido a que los trabajadores de esta empresa no tienen las habilidades para poder desarrollar una página web, no se ha llevado a cabo. Este es un proyecto que ayudará mucho a la comunidad gamer en México y también le permitirá a la empresa Huum desplegar sus fortalezas en la creación de diseño amigable para el usuario final.

### problema identificado

Actualmente, los jugadores del equipo N2O, no tienen una herramienta donde puedan encontrar toda la información de su desempeño individual y en equipo así como estadísticas de juego. Por otro lado, estos jugadores tienen un gran número de seguidores interesados en conocer toda la información relevante de estos jugadores y su participación en los diferentes torneos en los que compiten.

### Solución

La solución propuesta es crear una página web que se conecte a una base de datos donde se almacene toda la información de cada jugador, así como de los torneos en los que juegan y cualquier otra información relevante. De esta manera, tanto los jugadores como sus seguidores podrán acceder a esta página web y ver toda la información en un solo lugar.

### Arquitectura

La arquitectura del proyecto sigue el stack PERN, que utiliza las siguientes tecnologías: PostgreSQL como base de datos, Express como servidor backend, React como front end y Node.js como entorno de ejecución del servidor.

La arquitectura contiene las siguientes capas:

Frontend (React): Esta es la capa de interfaz de usuario donde los jugadores y seguidores interactúan con la página web. Se utilizó React para crear componentes reutilizables y dinámicos que renderizan la interfaz.

Backend (Node.js y Express): La capa de backend maneja la lógica empresarial y se comunica con la base de datos. Se utiliza Express para crear rutas y controladores que manejan las solicitudes HTTP y las respuestas.

Base de Datos (PostgreSQL): Se utiliza PostgreSQL como base de datos relacional. Almacena y maneja los datos de la aplicación, como perfiles de jugadores, partidas, estadísticas de juegos, etc.

## Requerimientos

Los requerimientos tanto para ejecutar el proyecto como para editarlo son mínimos. Por un lado, para poder ejecutar el proyecto se debe tener un browser y una terminal para el front end y tener la instalación de node en tu sistema para la ejecución del servidor back end. Por otro lado, para editar este proyecto, se necesitan de los mismo requerimientos de ejecución para poder visualizar el proyecto, aparte de un IDE, VSC como recomendación, para poder trabajar en el código de la app.

## Instalación

Para instalar, primero se debe copiar el código de la liga de github: https://github.com/Raul-Andre/N2O para poder abrir el proyecto en VSC o cualquier IDE que utilices. Después, simplemente se deben instalar los paquetes y dependencias del package.json con el siguiente comando:

```
npm install
```

## Configuración

Para consultar la configuración del backend, se debe revisar en el archivo server.ts, si se desean hacer modificaciones, por ejemplo, cambiar el puerto del servidor, se debe modificar este archivo. Para consultar la configuración del front end, se debe acceder al archivo de tsconfig.json así como al index.html dentro del folder public y hacer las ediciones necesarias.

## Uso

Esta parte se encuentra pendiente a la espera de la implementación de la experiencia de usuario. Por el momento, debido a que el proyecto está en sus etapas iniciales, se mantendrá pendiente esta sección.

## Contribución

Para comenzar a contribuir al proyecto, se deba clonar el folder con los archivos de la aplicación de:

```
https://github.com/Raul-Andre/N2O.
```

Para poder hacer modificaciones al proyecto, se debe solicitar el acceso en github. Una vez que se obtenga acceso, para hacer modificaciones, se debe hacer una branch con los últimos cambios realizado a la branch main. Con esta branch se debe abrir un Pull Request con una descripción de todos los cambios realizados. Una vez se obtenga una aprobación de parte de André Vega, se puede hacer merge, mientras GitHub no indique que hay merge.

## Estado Actual

En este momento, el proyecto se encuentra en una etapa inicial. El código contiene el template básico de react typescript, así como unas cuantas modificaciones a la configuración en el front end. Por otro lado, se tiene el código para ejecutar un servidor con express en el backend y se ha creado una base de datos en Postgres con una tabla inicial para los jugadores y su información personal.

### Jira

En este momento se encuentran todos los tickets de la etapa inicial finalizados en el board de Jira, excepto el de crear la conexión entre la base de datos y el servidor del back end. Para poder acceder al board de Jira, favor de solicitar acceso y será otorgado a la brevedad, utilizando la siguiente liga:

```
https://eyecancerinstitute.atlassian.net/jira/software/projects/N2O/boards/2
```

## Roadmap

Para el primer release de la app, se busca tener una landing page, donde los jugadores de N2O puedan acceder con un usuario y ver información personal, de su equipo y compañeros y la de otros equipos y sus integrantes. También se tendrá acceso sin necesidad de hacer login, para que los seguidores de los jugadores puedan consultar esta información también pero con una experiencia ajustada.
