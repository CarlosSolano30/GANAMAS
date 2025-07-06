
# 💰 Gana+

**Gana+** es una plataforma web profesional en español que permite a los usuarios ganar dinero completando tareas, invitando referidos y solicitando retiros por Nequi o PayPal.

---

## 🚀 Funcionalidades principales

- 🧾 Registro con nombre, correo, teléfono y referido
- 📱 Dashboard con puntos y navegación
- 👥 Sistema de referidos escalonado
- 🧱 Integración con muros de ofertas: AyetStudios y Monlix
- 💸 Solicitud de retiros con validación automática
- 🛡️ Panel de administración para aprobar/rechazar pagos
- 🔒 Protección para rutas de administrador

---

## 🖥️ Tecnologías usadas

| Capa       | Tecnología                 |
|------------|----------------------------|
| Frontend   | React + Vite + TailwindCSS |
| Backend    | Node.js + Express          |
| Base datos | MongoDB Atlas              |
| Deploy FE  | Vercel                     |
| Deploy BE  | Render                     |

---

## 📦 Instalación local

```bash
# Clona el repositorio
git clone https://github.com/tu_usuario/ganaplus.git

# Backend
cd ganaplus/backend
npm install
npm run dev

# Frontend
cd ../frontend
npm install
npm run dev
```

---

## ⚙️ Variables de entorno

### 📁 `backend/.env`

```env
PORT=5000
MONGODB_URI=mongodb+srv://usuario:clave@cluster.mongodb.net/ganaplus
```

### 📁 `frontend/.env`

```env
VITE_API_URL=https://ganaplus-backend.onrender.com
```

---

## 🌐 Despliegue

### 🔷 Backend (Render)

1. Crea un servicio en https://render.com
2. Ruta raíz: `backend`
3. Build: `npm install`
4. Start: `node index.js`

### 🔷 Frontend (Vercel)

1. Crea un proyecto en https://vercel.com
2. Ruta raíz: `frontend`
3. Variables de entorno:
   - `VITE_API_URL=https://tu-backend.onrender.com`

---

## 🧑‍💼 Acceso administrador

1. Crea manualmente un usuario en MongoDB con `isAdmin: true`
2. Accede a `/admin`
3. Ingresa el correo para administrar retiros

---

## 📬 Contacto

Desarrollado por [Tu Nombre o Marca].
