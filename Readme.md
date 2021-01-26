Gitpay
Una plataforma Open Source Bounty para resolver problemas desde Git, desde código abierto y bibliotecas hasta demandas de proyectos reales

https://gitpitch.com/worknenjoy/gitpay

Canal flojo
Disponemos de un canal slack para colaborar con soluciones y para ayudarte, y para divertirte

Únase a nosotros en holgura

¿Qué es Gitpay?
Ofrecemos un mercado para contribuyentes y proyectos que utilizan git para las necesidades de proyectos bajo demanda, utilizando el flujo de trabajo de Git como contrato para resolver problemas y recompensar a los contribuyentes.

Puede completar tareas con colaboración abierta y recibir recompensas por ello
Las empresas pueden recibir informes, correcciones y mejoras sobre el proyecto por parte de los desarrolladores y ofrecer recompensas para completar las tareas requeridas.
Quien esta contribuyendo


Únete al equipo
Únase al equipo de Github para que se le asigne tareas y sea parte del núcleo.

Únete al equipo de Gitpay en Github

Requisitos
Node.js (actualmente en v8.6.0)
Reaccionar con webpack
Ejecutando pruebas
Para ejecutar la prueba: npm run migrate-test(primera vez)

npm run test (hacer las pruebas) a.

Entorno de instalación
Para una integración completa con los servicios de API utilizados por la plataforma, necesitará las claves de API. Debe hacer una copia de su .env.exampleto.env con las credenciales correctas. Por favor, avíseme si necesita alguno de ellos para resolver un problema (envíe un correo electrónico a tarefas@gitpay.me )

Puedes hacer esto con: cp .env.example .env

Debe ejecutar create the .env para ejecutar el proyecto: cp .env.example .env
Base de datos
Instalar postgres
instalar: brew install postgres(mac)
iniciar el servicio: brew services start postgresql
crear usuario de postgres: createuser postgres -s
Inicie sesión en postgres cli: psql -U postgres
Crear base de datos de prueba: create database gitpay_test;
Crea una base de datos de desarrollo: create database gitpay_dev;
Salida: \q
Ejecutar la migración
Para ejecutar las migraciones

npm run migrate

Para crear una nueva migración

sequelize migration:create --name modelname

Siembra de base de datos
Para obtener más información relacionada con la siembra de bases de datos, consulte: https://en.wikipedia.org/wiki/Database_seeding

Para sembrar la base de datos

npm run seed

Para entorno de prueba

npm run seed-test

Para obtener una lista exhaustiva de opciones disponibles, consulte el migration.jsdirectorio raíz

Ejecutar proyecto
Servidor frontend
primero vaya a la frontendcarpeta:cd frontend
Luego ejecuta el servidor: npm run dev
Backend (node.js)
npm run start:dev

Entonces puede acceder en http: // localhost: 8082

Estibador
Requisitos
Docker Engine
Docker Compose
Linux
Ubuntu
Instalando
Motor de Docker: https://docs.docker.com/install/linux/docker-ce/ubuntu/
Docker Compose: https://docs.docker.com/compose/install/
Arch Linux / Manjaro / Antergos
Instalando
Docker y Docker componen: sudo pacman -S docker docker-compose
Corriendo
Entorno de desarrollo
Ejecutar docker-compose up Luego puede acceder en http: // localhost: 8082
Entorno de prueba
correr docker-compose -f docker-compose.test.yml up
Primerizos
Aquí puede comenzar a aprender cómo crear su primera solicitud de extracción y comenzar a ser un colaborador: https://github.com/worknenjoy/gitpay/issues/247

Prerna Verma
Yo Gede Wicaksana
Luísa Barros
Caio Reis
Shivam Latawa
Md. Al Amin
Siso
Amrut
Usman Sakirat Kehinde
Qiwei
Adam Ash
Shawn Noruzi
Alex Ssentongo
Licencia
Estado FOSSA

Lanzamientos
 10 etiquetas
Patrocine este proyecto
open_collective
opencollective.com/ opencollective
