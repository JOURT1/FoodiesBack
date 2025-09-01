# FoodiesBNB Backend

Backend API para la aplicación FoodiesBNB desarrollado con Node.js, Express y MongoDB.

## 🚀 Deploy en Render

Este backend está configurado para desplegarse automáticamente en Render.

### Variables de entorno requeridas:

- `MONGODB_URI` - Conexión a MongoDB Atlas
- `JWT_SECRET` - Clave secreta para JWT
- `NODE_ENV` - production
- `PORT` - Se configura automáticamente en Render

## 📋 Endpoints disponibles:

### Autenticación
- `POST /api/auth/registro` - Registrar usuario
- `POST /api/auth/login` - Iniciar sesión
- `GET /api/auth/verificar` - Verificar token
- `PUT /api/auth/actualizar-rol` - Actualizar rol de usuario

### Salud
- `GET /api` - Estado del servidor

## 🛠️ Tecnologías

- Node.js
- Express.js
- MongoDB con Mongoose
- JWT para autenticación
- bcryptjs para encriptación
- CORS configurado

## 🔧 Instalación local

```bash
npm install
npm start
```

El servidor se ejecutará en el puerto definido en la variable de entorno PORT o 3002 por defecto.
