# 💰 FinanzasApp - Aplicación de Finanzas Personales

Una moderna aplicación web para gestión de finanzas personales diseñada específicamente para usuarios peruanos. Incluye seguimiento de transacciones, presupuestos y metas de ahorro con una interfaz profesional y atractiva.

## 🌟 Características

- **📊 Dashboard Interactivo**: Visualización completa de tus finanzas con gráficos y estadísticas
- **💳 Gestión de Transacciones**: CRUD completo para ingresos y gastos
- **📈 Presupuestos**: Planificación y seguimiento de gastos por categoría
- **🎯 Metas de Ahorro**: Establecimiento y seguimiento de objetivos financieros
- **🔐 Autenticación Segura**: Sistema de login protegido
- **🇵🇪 Localizado para Perú**: Moneda en soles peruanos (PEN)
- **📱 Responsive**: Diseño adaptable a móviles y escritorio

## 🚀 Tecnologías

### Frontend
- **React 18** con TypeScript
- **Vite** como build tool
- **Tailwind CSS** + **shadcn/ui** para styling
- **TanStack Query** para manejo de estado del servidor
- **Recharts** para visualización de datos
- **React Hook Form** + **Zod** para formularios

### Backend
- **Node.js** + **Express.js**
- **TypeScript** para type safety
- **Drizzle ORM** para base de datos
- **In-memory storage** para desarrollo/demo

## 🛠️ Instalación

1. **Clona el repositorio**
   ```bash
   git clone <tu-repo-url>
   cd finanzas-app
   ```

2. **Instala dependencias**
   ```bash
   npm install
   ```

3. **Inicia la aplicación**
   ```bash
   npm run dev
   ```

4. **Accede a la aplicación**
   - Abre tu navegador en `http://localhost:5000`
   - Usuario: `elkin`
   - Contraseña: `990680240`

## 📦 Scripts Disponibles

- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm start` - Ejecuta la aplicación en modo producción
- `npm run check` - Verifica tipos de TypeScript

## 🎨 Capturas de Pantalla

### Login Moderno
- Diseño con gradientes y animaciones
- Autenticación segura
- Interfaz intuitiva

### Dashboard Completo
- Resumen financiero en tiempo real
- Gráficos de gastos por categoría
- Progreso de presupuestos
- Transacciones recientes

## 👤 Credenciales de Demo

Para probar la aplicación utiliza:
- **Usuario**: `elkin`
- **Contraseña**: `990680240`

## 🗃️ Estructura del Proyecto

```
├── client/          # Frontend React
│   ├── src/
│   │   ├── components/  # Componentes reutilizables
│   │   ├── pages/       # Páginas principales
│   │   ├── lib/         # Utilidades y configuración
│   │   └── hooks/       # Custom hooks
├── server/          # Backend Express
│   ├── index.ts     # Servidor principal
│   ├── routes.ts    # API endpoints
│   └── storage.ts   # Capa de datos
├── shared/          # Tipos y schemas compartidos
└── README.md
```

## 🔐 Seguridad

- Autenticación basada en sesiones
- Validación de datos con Zod
- Protección de rutas
- Middleware de autorización

## 🌍 Despliegue

### GitHub + Vercel/Netlify

1. **Sube a GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Conecta con Vercel/Netlify**
   - Conecta tu repositorio GitHub
   - Configura build command: `npm run build`
   - Configura output directory: `dist`

### Variables de Entorno (Opcional)

Si usas base de datos externa:
```env
DATABASE_URL=your_database_url
NODE_ENV=production
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una feature branch (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la branch (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

## 📞 Contacto

Desarrollado para la gestión financiera personal en Perú.

---

💡 **Nota**: Esta aplicación utiliza datos de demostración. En producción, conecta una base de datos real para persistencia de datos.
