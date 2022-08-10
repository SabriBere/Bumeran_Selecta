# Proyecto Profesional | Bumeran_Selecta :woman_teacher:

## About the proyect.

Bienvenidos a [**_Bumeran Selecta_**](https://www.bumeran.com.ar/selecta/) un proyecto que consistió en la reproducción de los servicios ofrecidos por la compañía [Jobint](https://www.linkedin.com/company/jobint/). El mismo tenía la finalidad de proveer de reclutadores a empresas que no cuentan con un departamento de Recursos Humanos o necesitan cubrir puestos de trabajo de forma expeditiva.


## :name_badge: Must Have:
<li>Ingreso, registro y cierre de sesión del usuario.</li>
<li>Cuenta de Administrador de la web para cargar las búsquedas</li>
<li>Persistencia del la sesión del usuario logueado.</li>

## :blue_square: Should Have:
<li>Grilla de búsquedas.</li>
<li>Vista individual de cada búsqueda.</li>
<li>Buscar reclutadores por nombre, área y/o país.</li>
<li>ABM de reclutadores.</li>
<li>Finalizar la búsqueda.</li>
<li>Calificar a los reclutadores</li>
<li>Reportes y estadisticas</li>

## :green_square: Nice to Have:
<li>Full responsive.</li>

## :heavy_check_mark: Achievements:
<li>Desempeñe en tareas de front - end. </li>
<li>Logre la persistencia de la sesión, registro y logueo de usuario.</li>
<li>Dasarrollé las vistas del Home, Login, Register, Reclutadores y Estadisticas, alcanzando que el cliente obtenga una experiencia satisfactoria dentro del sitio.</li>

## :dolls: Team Developers:

[Ariel Ferencak](https://www.linkedin.com/in/arielferencak/),
[Lorenzo Olmedo](https://www.linkedin.com/in/lorenzo-olmedo/),
[Matias Goni](https://www.linkedin.com/in/matiashgoni/),
[Mariangel Ruiz](https://www.linkedin.com/in/mariangel-ruiz/),
Sabrina Demetrio

## :hammer_and_wrench: Technologys:

|![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)|![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)|![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)|
|-------- |--------|--------|
|![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)|![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)|![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)|
|![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)|Passport.JS|![MYSQL](https://img.shields.io/badge/mysql-%23E34F26.svg?style=for-the-badge&logo=mysql&logoColor=white)|

## 	:arrow_forward: Demo

Próximamente!


## Other proyects :point_down:

|[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://sabrinademetrio96.netlify.app/)| [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sabrina-demetrio/) |
|-------- |--------|


## Install and Instrucction of user. 

**_**Set up:**_**

1. Forkear y clonar el repositorio.

2. Para instalar todas las dependencias, utilizar el comando **_yarn_**.

3. Luego para levantar los servidores, utilizar **_**yarn run dev o yarn dev**_** para correr el servidor front-end en **_local host 3000_**. Si se desear correr el back-end, utilizar el comando **_**yarn server**_**, que levantá el **_local host en el puerto 8000_**.

4. Para poder probar las funcionalidades del sitio es necesario seedear una base de datos, para ello se deberá crear una base de datos en mySQL, por lo que es necesario instalar mySQL.
   Una vez instalado a mySQL, se deberá crear una base de datos llamada bumeranSelecta.

**Nota: En Linux puedes acceder a mySQL usando el comando sudo mySQL -u root -p. Primero ingresa tu contraseña de Linux y luego la contraseña de mySQL. Una vez ingresado estos datos, deberás crear una base de datos usando \*****create database bumeranSelecta;****\*.**

5. Luego deberás ingresar a la capeta **_api/config_** y utilizando el comando **node seed.js** para crear información en la base de datos. La terminal debe indicar un mensaje de ****seed succesfully****

**_MANUAL DEL USUARIO_**

**_**Flujo del Reclutador:**_**
Estando posicionado en el **_Home_** dirigite a la botón de **_**Crear cuenta**_**, esto permitirá crear una cuenta para un reclutador. Y una vez creada, te redirigirá a la página de ingreso, donde ingresarás tu email y contraseña recién creados.

Finalizado el ingreso, como reclutador verás el **_**Home**_** y tu **_**Perfil**_**. En este último podrás ver tus busquedas activas, terminar las mismas y editar tu perfil.

**_**Flujos del Administrador:**_**

A fines de evitar que cualquier persona pueda ser designada administradora, primero deberás crear una cuenta, para ello sigue los mismo pasos que se indican en **_**Flujo del Reclutador**_**.
Realizado esto, deberás dirigirte hacía la base de datos de mySQL, ingresar en **_**bumeranSelecta**_**, buscar al usuario al cual se le quieren brindar los permisos de admin y cambiar el campo de **_admin_** por el valor **_1_**.
**_No olvides aplicar los cambios._**

Finalizado este proceso, deberas reingresar a tu cuenta pudiendo visualizar como Administrador las siguientes funcionalidades:

**_Home_**
**_Busquedas_**
**_Selección de Reclutadores_**
**_Repostes y Estadísticas_**
**_Perfil_**

**_Busquedas:_**
En esta sección podrás visualizar las publicaciones que se encuentran dentro de Bumeran Selecta, pudiendo filtrar por: País, Área, Fecha y Estado de las mismas. A su vez visualizarás que en las cards se encuentran los **_**estados de las busquedas en función de: No iniciada, En proceso y Finalizada.**_**
Además encontrás información ilustrativa sobre la cantidad de postulaciones, el reclutador asigando (en caso de estar la busqueda En proceso) y su ranking, y para el país el cuál se realiza la busqueda.

Al hacer click en alguna de las cards podrás ver la vista indivual de las busquedas. Allí podrás asignar a un reclutador recomendado según su ranking. También podrás eliminar la busqueda y editar la misma en caso de ser necesario.

Si se asigna un reclutador, el sistema ya no te permitirá asignar más reclutadores y la busqueda se da por iniciada cambiando su estado a **_En proceso_**.

Por último, en esta sección también se podrán ingresar nuevas busqudas al sitio mediante el boton **_+_**. Esta funcionalidad te redirigirá a un formulario en el cual podrás ingresar toda la información necesaría que desees que se visualize luego en la publicación.

**_Selección de Reclutadores:_**
En este apartado, al igual que en **_Busquedas_** podrás filtrar la información, pero en este caso te será de utilidad para encontrar un reclutador apto según el ranking, país y área de experiencia. También podrás encontrar a un reclutador por su nombre y/o apellido.

Si realizas click en el nombre del reclutador o foto accederás a su perfil, obteniendo mayor información sobre este y las busquedas que tiene asigdadas. Al mismo tiempo, esto te permitirá evitar asignar más busquedas de las que puede abarcar dicha persona.

**_A su vez, en esta sección podrás editar y eliminar un reclutador en caso de ser necesario._**

**_Reportes y Estadisticas_**
Al igual que las dos anteriores secciones podrás utilizar filtros que te facilitarán la accesibilidad a la información.

Aquí podrás visualizar una tabla que mostrará el titulo de la busqueda, su estado, fecha de creación o cambio de estado, país, aŕea, vacantes disponibles y personas postuladas en caso de que la bsuqueda se encuentra finalizada.
**_Nota: Dicha tabla también puede ser descargada en un archivo csv, en caso de ser necesario._**

Por último, como Administrador visualizarás gráficos que proporcionarán información de manera mucho más ilustrativa sobre: **_El estado de las busquedas por país y el tiempo de finalización de las busquedas por aŕea._** Esta información te será de utilidad para la toma de deciones rápida en caso de que algún área este teniendo un cuello de botella en las busquedas y este necesitando más reclutadores para mejorar el servicio de Bumeran Selecta.
