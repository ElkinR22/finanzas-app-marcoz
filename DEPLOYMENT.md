# 🚀 Guía de Despliegue - FinanzasApp

## Opción 1: Despliegue con Vercel (Recomendado)

### Paso 1: Preparar el Repositorio en GitHub

1. **Crear repositorio en GitHub**
   - Ve a [github.com](https://github.com) y crea una cuenta si no tienes
   - Haz clic en "New repository"
   - Nombre: `finanzas-app-peru`
   - Descripción: `Aplicación de finanzas personales para Perú`
   - Público o Privado (tu elección)

2. **Subir código a GitHub**
   ```bash
   # En la terminal de Replit:
   git init
   git add .
   git commit -m "🎉 Initial commit - FinanzasApp completa"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/finanzas-app-peru.git
   git push -u origin main
   ```

### Paso 2: Desplegar en Vercel

1. **Ir a Vercel**
   - Ve a [vercel.com](https://vercel.com)
   - Regístrate con tu cuenta de GitHub

2. **Importar proyecto**
   - Haz clic en "New Project"
   - Selecciona tu repositorio `finanzas-app-peru`
   - Vercel detectará automáticamente que es un proyecto Node.js

3. **Configurar build**
   - Framework Preset: `Other`
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Install Command: `npm install`

4. **Deploy**
   - Haz clic en "Deploy"
   - Espera 2-3 minutos
   - ¡Listo! Tendrás un enlace como `https://finanzas-app-peru.vercel.app`

## Opción 2: Despliegue con Netlify

1. **Ir a Netlify**
   - Ve a [netlify.com](https://netlify.com)
   - Regístrate con GitHub

2. **Nuevo sitio desde Git**
   - "New site from Git" → GitHub
   - Selecciona tu repositorio

3. **Configurar build**
   - Build command: `npm run build`
   - Publish directory: `dist`

## Opción 3: Despliegue con Railway

1. **Railway**
   - Ve a [railway.app](https://railway.app)
   - "Deploy from GitHub repo"
   - Selecciona tu repositorio
   - Railway detectará automáticamente la configuración

## Credenciales para Compartir

Una vez desplegado, comparte estas credenciales:

**🔐 Acceso a la App:**
- **URL**: `https://tu-app.vercel.app` (el enlace que te genere)
- **Usuario**: `elkin`
- **Contraseña**: `990680240`

## ✅ Verificación Post-Despliegue

Después del despliegue, verifica:

1. **Login funciona** ✓
2. **Dashboard carga correctamente** ✓
3. **Gráficos se visualizan** ✓
4. **Transacciones se pueden crear/editar** ✓
5. **Responsive en móvil** ✓

## 🛠️ Solución de Problemas

### Error de Build
Si hay errores de build:
```bash
# Prueba localmente primero
npm run build
npm start
```

### Error de Dependencias
```bash
# Limpia caché y reinstala
rm -rf node_modules package-lock.json
npm install
```

## 📱 Compartir tu App

Una vez desplegada:

1. **Copia el enlace** de Vercel/Netlify
2. **Compártelo** con quien quieras
3. **Proporciona las credenciales** de acceso
4. **Muestra las funcionalidades**:
   - Dashboard financiero
   - Creación de transacciones
   - Presupuestos
   - Metas de ahorro

¡Tu aplicación estará disponible 24/7 en internet! 🌐