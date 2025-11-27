Nombre del Proyecto
restaurante-crud

Integrantes
Santiago Varela Peña
Miguel Angel Rendon
Juan Buritica

Descripción
Este proyecto es una api rest desarrollada con node.js que gestiona la carta de un restaurante, mostrando sus categorias y sus platos. Usamos sql lite3 como base de datos la cual tiene las tablas categorias y platos y se relacionan mediante una llave foranea.

La api esta desarrollada para recibir las peticiones CRUD (GET, POST, PUT, DELETE).

Instalación
Instrucciones paso a paso:

Clonar el repositorio: Para esto es necesario ejecutar Git bush y escribir:
git clone https://github.com/10-Miguel/restaurante-crud
Instalar dependencias: 
npm install
install express sqlite3
npm install no demon --save-dev
install express cors
Node.js instalación local
Ejecutar en la terminal: npm run dev
Abrir: http://localhost:3000/platos
Base de Datos
Fue necesario crear dos tablas llamadas platos y categorias, las cuales se relacionan mediante una llave foranea, esta se encuentra en la tabla principal platos y se relaciona con la tabla categorias.

Endpoints Disponibles
Lista completa de endpoints con ejemplos 
-platos: 
GET: http://localhost:3000/api/platos --> obtener todos 
GET: http://localhost:3000/api/platos/1 --> obtener por ID
POST: http://localhost:3000/api/platos/ --> Crear plato json: { "nombre": "Cualquiera", "precio": 10000, "categoria_id": 1 }
PUT: http://localhost:3000/api/platos/2 --> Actualizar plata json: { "nombre": "cualquiera", "precio": 10000, "categoria_id": 1 } 
DELETE: http://localhost:3000/api/platos/2 --> plato eliminado

Tecnologías Utilizadas
Node.js
Express
SQLite3
Ejemplos de Uso

Hay documentación en capturas de pantalla en restaurante-crud/images