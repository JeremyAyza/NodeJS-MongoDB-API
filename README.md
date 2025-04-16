<h1 align="center">🛠️ Node.js MongoDB API</h1>
<p align="center">Backend básico con Express y Mongoose para gestionar usuarios y productos. Ideal como punto de partida para proyectos RESTful en Node.js.</p>

<p align="center">
  <a href="https://expressjs.com"><img src="https://img.shields.io/badge/Express.js-4.x-lightgrey?logo=express" /></a>
  <a href="https://www.mongodb.com"><img src="https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb" /></a>
  <a href="https://mongoosejs.com"><img src="https://img.shields.io/badge/Mongoose-ODM-red?logo=mongoose" /></a>
  <a href="https://nodejs.org"><img src="https://img.shields.io/badge/Node.js-18-green?logo=node.js" /></a>
</p>

---

### 📦 Tech Stack

| Tecnología   | Descripción                    |
| ------------ | ------------------------------ |
| **Node.js**  | Entorno de ejecución backend   |
| **Express**  | Framework minimalista para APIs REST |
| **MongoDB**  | Base de datos NoSQL            |
| **Mongoose** | ODM para modelar objetos Mongo |
| **dotenv**   | Variables de entorno           |
| **nodemon**  | Recarga automática en desarrollo |

---

### ✨ Funcionalidades

- 📄 CRUD completo para **usuarios**
- 🛒 CRUD completo para **productos**
- 🔌 Endpoints REST simples y bien organizados
- 🧱 Arquitectura base modular para escalar fácilmente

---

### ⚙️ Instalación

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/nodejs-mongodb-api
cd nodejs-mongodb-api

# Instalar dependencias
npm install

# Crear archivo .env con la conexión a MongoDB
cp .env.example .env
# Edita el archivo con tus variables

# Iniciar servidor en desarrollo
npm run start
