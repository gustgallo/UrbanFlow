# UrbanFlow

## Descripción breve
UrbanFlow es un dashboard interactivo de control logístico diseñado para gestionar despachos, visualizar indicadores operativos en tiempo real y coordinar eficientemente flotas de reparto en un entorno urbano Caso de Estudio UNADM 2026.

## Objetivo y funcionalidad principal
El objetivo principal de UrbanFlow es centralizar y optimizar la gestión de pedidos logísticos a través de una interfaz moderna y eficiente. Sus funcionalidades principales incluyen:
- Visualización dinámica del estado de los pedidos (pendientes y en curso).
- Panel de control interactivo con Indicadores Clave de Rendimiento (KPIs) como tiempo promedio de entrega y actividad de la flota.
- Sistema de filtros avanzados por prioridad de envío y disponibilidad de los repartidores.
- Simulación de creación y asignación rápida de nuevos pedidos.

## Requisitos necesarios
Para ejecutar este proyecto, necesitas tener instalado:
- **Node.js** (versión 16.x o superior)
- **NPM** o **Yarn** (gestores de paquetes)
- Un navegador web moderno (Chrome, Firefox, Edge, Safari)


## Cómo ejecutar o usar el proyecto
Una vez instaladas las dependencias, puedes iniciar el servidor de desarrollo ejecutando:
```bash
npm run dev
```
La terminal te proporcionará una URL local (generalmente `http://localhost:5173/`). Abre esta dirección en tu navegador web para comenzar a interactuar con el dashboard de UrbanFlow.

## Estructura básica de carpetas y archivos
```text
UrbanFlow/
├── public/                 # Archivos estáticos accesibles públicamente
├── src/                    # Código fuente principal de la aplicación React
│   ├── components/         # Componentes modulares (Sidebar, Header, MapArea, etc.)
│   ├── index.css           # Archivo principal de estilos globales (CSS)
│   ├── App.jsx             # Componente raíz que organiza la vista principal
│   └── main.jsx            # Punto de entrada para renderizar la aplicación
├── index.html              # Plantilla HTML base donde se inyecta la aplicación
├── package.json            # Dependencias del proyecto y scripts de ejecución
├── vite.config.js          # Configuración del empaquetador Vite
└── README.md               # Documentación principal del proyecto
```
