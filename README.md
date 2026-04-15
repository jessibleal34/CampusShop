# CampusShop - E-commerce Mobile First
CampusShop es una aplicación web de comercio electrónico diseñada con un enfoque Mobile-First. El objetivo principal es ofrecer 
una experiencia de usuario fluida, limpia y moderna para la compra de artículos universitarios, optimizada para dispositivos 
móviles pero totalmente funcional en escritorio.
#Tabla de Contenido
Características

Arquitectura del Proyecto

Tecnologías Utilizadas

Estructura Semántica

Instalación y Uso
 # Características
Interfaz Mobile-First: Diseño pensado para el pulgar del usuario, con botones grandes y navegación accesible.

Catálogo Dinámico: Rejilla de productos adaptable (2 columnas en móvil).

Estados de Pedido: Sistema visual de historial de pedidos con códigos de color (Entregado, En Camino, Cancelado).

Carrito de Compras: Gestión de productos con estados de "Carrito Vacío" para mejorar la experiencia de usuario (UX).

Navegación Intuitiva: Barra de navegación inferior (Bottom Nav) persistente para acceso rápido a secciones clave.

# Arquitectura del Proyecto
El proyecto sigue una estructura de archivos organizada para separar las responsabilidades del diseño:

Plaintext
CampusShop/
├── css/
│   ├── base.css       # Variables (colores, fuentes) y reseteo.
│   ├── layout.css     # Estructura (Main, Header, Grid).
│   ├── components.css # Elementos reutilizables (Botones, Tarjetas, Badges).
│   └── responsive.css # Ajustes específicos para pantallas grandes.
├── img/               # Recursos visuales (JPG, PNG, SVG).
├── index.html         # Página de Catálogo (Principal).
├── carrito.html       # Vista de producto individual.
├── catalogo.html       # Resumen de compra.
├── checkout.html       # Historial de órdenes.
└── historial.html        # Información del usuario.
|__ index.html
|__ perfil.html
|__ producto.html
|__ vacio

# Tecnologías Utilizadas
HTML5: Uso de etiquetas semánticas para SEO y accesibilidad.

CSS3:

Flexbox: Para alineación de elementos en el Header y Footer.

CSS Grid: Para la maquetación del catálogo y formularios.

Variables CSS: Para una gestión de colores centralizada.

Lucide Icons: Librería de iconos vectoriales ligeros para una estética moderna.

# Estructura Semántica
Para este proyecto, se evitó el uso excesivo de <div> y se optó por una estructura que el navegador pueda entender:

<header>: Contiene el logo y acciones rápidas (carrito).

<nav>: Implementado en la parte inferior para la navegación principal entre vistas.

<main>: Contenedor del contenido único de cada página.

<section>: Divide áreas temáticas como "Productos" o "Resumen de Pago".

<article>: Utilizado para cada tarjeta de producto e ítem del historial, tratándolos como entidades independientes.

<footer>: Usado para fijar botones de acción importantes como "Proceder al Pago".

# Instalación y Uso
Clonar el repositorio:

Bash
git clone(https://github.com/jessibleal34/CampusShop.git)
Abrir el proyecto:
Simplemente abre el archivo index.html en tu navegador preferido.

Modo Desarrollador:
Para ver el formato de celular en tu PC, presiona F12 y activa la Vista de Dispositivo en las herramientas de desarrollador.

# Notas de Diseño
Colores: Se utilizó una paleta basada en verdes profundos (#1a4327) para transmitir confianza y frescura.

Accesibilidad: Se incluyeron etiquetas alt en todas las imágenes y un contraste adecuado de colores para facilitar la lectura.
