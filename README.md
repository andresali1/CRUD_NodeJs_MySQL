Proyecto en Node-js realizando conexión a base de datos MySQL y motor de plantillas hbs, utilización bootstrap.

para correr el proyecto es necesario:

1. en raiz del proyecto correr "npm install" utilizando la terminal

2. Tener en funcionamiento la base de datos MySQL

3. Abrir la carpeta "database" y ejecutar las sentencias sql que están dentro del archivo  "bd.sql"

4. en la raiz del proyecto crear un archivo llamado keys.js con el sguiente código (agregar las credenciales propias de la base de datos):

 * module.exports = {
    database: {
        host: 'localhost',
        user: '(usuario de mysql)',
        password: '(password de mysql)',
        database: 'database_links'
    }
   }

5. Asegurarse de tener instalado nodemon y luego correr en terminal "npm run dev"