## Desafio 16 - Documentar API

- Se agrego el paquete de swagger con su configuracion en el app.js para documentar mis APIS
- Se agrego una carpeta llamada docs donde genero la estructura en formato .yaml con swagger para mostrar la informacion
- Despues de dar inicio a la ejecucion como dice abajo, hay que ir a la ruta "http://localhost:3000/apidocs/"
- Alli vamos a ver toda la documentacion necesaria tanto para carritos, productos y usuarios

### cosas a tener en cuenta:

- inicie la ejecucion de la aplicacion con "npm run start"
- en el config.js de la carpeta config (en src) la aplicacion se esta ejecutando en el entorno productivo, para cambiarlo solo tenes que cambiar en la linea 5 "PRODUCTION" por "DEVELOPMENT"
- al estar en el entorno productivo cuando hagamos un GET al endpoint "/loggerTest" se mostraran por consola los loggers a partir del nivel info, si queremos ver todos los loggers hay que cambiar al entorno desarrollo como esta explicado en el item anterior
