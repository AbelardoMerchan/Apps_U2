🚀 Características principales

🧩 Arquitectura MVC (Modelo - Vista - Controlador)

🛠️ Framework Express.js

🧰 Motor de plantillas Express-Handlebars

💾 Conexión a base de datos MongoDB (Mongoose)

🔐 Manejo de sesiones y autenticación

🧠 Uso de middlewares, rutas modulares y controladores

🗂️ Archivos estáticos y sistema de vistas organizadas

📦 Configuración mediante variables de entorno (.env)

🗂️ Estructura del proyecto
``` bash
MiInventarioExpress/
│
├── src/
│   ├── config/           # Configuración de la base de datos (db.js)
│   ├── controllers/      # Lógica del negocio (Auth, Product)
│   ├── middlewares/      # Middlewares personalizados
│   ├── models/           # Esquemas de MongoDB (User, Product)
│   ├── public/           # Archivos estáticos (CSS, JS)
│   ├── routes/           # Rutas modulares (index, auth, products)
│   ├── uploads/          # Archivos subidos
│   ├── views/            # Vistas Handlebars (.hbs)
│   └── server.js         # Punto de entrada del servidor
│
├── .env                  # Variables de entorno
├── package.json          # Dependencias del proyecto
└── README.md             # Documentación del proyecto
```



⚙️ Instalación y ejecución
1️⃣ Clonar el repositorio
```` bash
git clone https://github.com/AbelardoMerchan/Apps_U2.git
cd MiInventarioExpress
````

2️⃣ Instalar dependencias
````
npm install
````
3️⃣ Crear archivo .env

Agrega tus variables de entorno:
````
PORT=3000
MONGO_URI=mongodb://localhost:27017/miinventario
SESSION_SECRET=clave_segura
````

4️⃣ Ejecutar en modo desarrollo
````
npm run dev
````

5️⃣ Verificar en el navegador
````
http://localhost:3000/
````

💡 Tecnologías utilizadas
Tecnología	Descripción
Node.js	Entorno de ejecución JavaScript
Express.js	Framework para crear el servidor web
Handlebars	Motor de plantillas para las vistas
MongoDB + Mongoose	Base de datos NoSQL y modelado de datos
Dotenv	Variables de entorno
Session + Connect-Mongo	Manejo de sesiones en base de datos
Method-Override	Métodos HTTP extendidos (PUT, DELETE)
🧠 Objetivos del proyecto

Aplicar la estructura MVC en un proyecto real.

Implementar rutas modulares y controladores.

Conectar el servidor con una base de datos MongoDB.

Utilizar Handlebars para las vistas dinámicas.

Gestionar sesiones y cookies de usuario.

Desarrollar un entorno Express con middleware y persistencia de datos.

👨‍💻 Autor

Abelardo Merchán Guevara
Estudiante de Ingeniería en Software
📘 Universidad Politécnica Salesiana

🏁 Estado del proyecto

✅ Versión entregable: El servidor responde correctamente en ````http://localhost:3000/````
🧱 Estructura MVC completa lista para ampliación (rutas Auth y Products configuradas)
