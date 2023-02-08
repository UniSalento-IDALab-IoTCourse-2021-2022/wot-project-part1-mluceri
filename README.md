
# wot-project-FrontEnd-LuceriPalma

Project Road Condition Monitoring System based on Nordic Thingy:52


The complete project is composed by:
- FrontEnd (https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-FrontEnd-LuceriPalma)
- BackEnd (https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-BackEnd-LuceriPalma)
- presentation (https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-presentation-LuceriPalma)



## Authors

- [@mluceri ](https://www.github.com/mluceri)
- [@cpalma-usal](https://www.github.com/cpalma-usal)


## Installation and instruction

In the development environment, a local machine was utilized, with the following needed services:
- A web server (http-server, live-server, ‘express’ in node app, or apache web server) working on port 8080 on localhost. This project mainly uses live-server, a little development server with live reload capability.
- A database (JSON Server, MongoDB, PostgreSQL), working on port 3000 on localhost. This project mainly uses json-server, a little development database (DB) server, with live reload capability to create a quick REST API for a DB stored on file in .json format (db.json file).
- A node application serverApp.js with extra functionalities such as web socket, routing control, access control, and more. ServerApp.js works on port 3002 on localhost.


This repository contains the frontend : html, css, js files in order to run the web application.


### Setting and launch of the web-server

Assuming node and npm installed.

```bash
  npm i -g http-server
  http-server
```

The server will be listening on :
  http://localhost:8080



## Acknowledgements
 - [Nordic Thingy js library](https://github.com/NordicPlayground/Nordic-Thingy52-Thingyjs)
 - [Leaflet interactive map](https://leafletjs.com/)
 - [json-server](https://github.com/typicode/json-server/)
