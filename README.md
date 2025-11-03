# SEO Dashboard

Dashboard profesional de análisis SEO con integración de Google Search Console y Google Analytics 4.

## 📁 Estructura del Proyecto

```
seo_dashboard/
├── frontend/          # Aplicación Next.js
│   ├── app/          # App Router de Next.js
│   ├── components/   # Componentes React
│   ├── hooks/        # Custom hooks
│   ├── lib/          # Utilidades y API client
│   └── public/       # Archivos estáticos
│
├── backend/          # API FastAPI
│   ├── app/
│   │   ├── api/      # Endpoints de la API
│   │   ├── services/ # Lógica de negocio
│   │   ├── models/   # Modelos de datos
│   │   └── core/     # Configuración
│   ├── main.py       # Punto de entrada
│   └── requirements.txt
│
├── start.bat         # Script de inicio rápido
├── QUICK_START.md    # Guía de inicio
└── README.md         # Este archivo
```

## 🚀 Inicio Rápido

### Opción 1: Script Automático (Windows)

```bash
start.bat
```

### Opción 2: Manual

**Backend:**
```bash
cd backend
python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt
python main.py
```

**Frontend:**
```bash
cd frontend
npm install --legacy-peer-deps
npm run dev
```

## 🔑 Configuración

### 1. Configurar credenciales de Google

Edita `backend/.env` y añade:
```env
GOOGLE_CLIENT_ID=tu-client-id.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=tu-client-secret
```

### 2. Acceder a la aplicación

- **Frontend:** http://localhost:3000
- **Backend API:** http://localhost:8000
- **Documentación API:** http://localhost:8000/api/docs

## ✨ Funcionalidades

### Integraciones
- ✅ Google Search Console
- ✅ Google Analytics 4
- ✅ OAuth2 Authentication

### Análisis SEO
- 📊 Métricas de rendimiento
- 🔍 Top queries y páginas
- 🎯 Análisis de competidores
- 💡 Quick wins y oportunidades
- 📈 Tendencias estacionales
- ⚙️ SEO técnico
- 🔗 Análisis de backlinks

### Funciones Expertas
- Detección de canibalización de keywords
- Optimización de CTR
- Análisis de brechas de contenido
- Descubrimiento automático de competidores

## 📚 Documentación

- [Guía de Inicio Rápido](QUICK_START.md)
- [Integración Backend Completa](BACKEND_INTEGRATION_COMPLETE.md)
- [API Documentation](http://localhost:8000/api/docs) (cuando el backend esté corriendo)

## 🛠️ Stack Tecnológico

### Frontend
- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- Radix UI
- Framer Motion
- Recharts

### Backend
- FastAPI
- Python 3.10+
- SQLAlchemy
- Google API Client
- OAuth2

## 📝 Licencia

Este proyecto es privado.

## 👥 Soporte

Para más información, consulta la documentación en la carpeta del proyecto.
