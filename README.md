# Libres Trabaja

**Libres Trabaja** es una aplicación móvil Android para la vinculación laboral en la región de Libres, Puebla. Conecta candidatos con reclutadores de forma directa y sencilla.

## ✨ Funcionalidades

### Para candidatos
- Explorar vacantes disponibles con búsqueda por puesto, sector o empresa
- Postularse a vacantes con un solo clic
- Perfil personal con foto y datos editables
- Subir currículum (PDF o imagen) con vista previa integrada
- Chat en tiempo real con reclutadores
- Seguimiento de postulaciones activas

### Para reclutadores
- Publicar y gestionar vacantes
- Ver postulantes por vacante con filtro de búsqueda
- Revisar CV de candidatos (PDF e imagen) con zoom
- Chat en tiempo real con candidatos
- Perfil de empresa con galería de instalaciones

## 📱 Capturas

| | | |
|---|---|---|
| Inicio candidato | Vacantes | Chat |
| Perfil reclutador | Postulantes | CV Preview |

## 🛠️ Tecnologías

- **Frontend**: Android (Kotlin, Jetpack Compose)
- **Backend**: Node.js, Express, MongoDB
- **Almacenamiento**: Cloudinary (CVs, fotos de perfil e instalaciones)
- **Tiempo real**: Chat con polling cada 2 segundos
- **Notificaciones**: Firebase Cloud Messaging (FCM)
- **Base de datos**: MongoDB con Mongoose

## 📦 Requisitos

- Android 7.0 (API 24) o superior
- Conexión a internet
- Permiso de almacenamiento para descargar CVs

## 🔧 Instalación

1. Descarga el archivo `app-debug.apk`
2. En tu dispositivo Android, ve a **Ajustes → Seguridad** y habilita "Instalar apps de orígenes desconocidos"
3. Abre el archivo APK y presiona "Instalar"
4. Una vez instalada, regístrate como **Candidato** o **Reclutador**

## 🚀 Despliegue del backend

El backend está desplegado en Render:
```
https://libres-trabaja-proyecto.onrender.com/
```

## 📄 Licencia

Este proyecto es de uso educativo y no comercial.
