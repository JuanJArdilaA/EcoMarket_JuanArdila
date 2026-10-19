# EcoMarket - Tienda Ecológica

Maquetación web responsiva para **EcoMarket**, una tienda en línea de productos ecológicos, reutilizables y de consumo consciente, desarrollada únicamente con HTML5 semántico y CSS3 puro.

## Descripción del Proyecto

El sitio cuenta con 4 vistas principales interconectadas que permiten explorar productos sostenibles, filtrar el catálogo por categorías o rango de precio, conocer la historia y misión ecológica de la marca y enviar consultas mediante un formulario con validación nativa.

## Tecnologías Utilizadas

- **HTML5 Semántico**: Uso estructurado de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` y `<footer>`.
- **CSS3 Puro (Sin JavaScript)**:
  - Variables CSS (`:root`) para la paleta de colores.
  - Diseño **Mobile First** con CSS Grid y Flexbox (`768px` para tablet y `1024px` para desktop).
  - Barra lateral de filtros fija con `position: sticky`.
  - Animaciones e interacciones con `:hover`, `:active`, `:target` y validación de formularios con `:valid` e `:invalid`.

## Estructura de Carpetas

```text
EcoMarket_JuanArdila/
├── index.html
├── README.md
├── css/
│   ├── main.css
│   ├── layout.css
│   ├── components.css
│   └── animations.css
├── img/
│   ├── hero/
│   ├── icons/
│   └── products/
└── views/
    ├── productos.html
    ├── sobre-nosotros.html
    └── contacto.html
```

## Vistas del Proyecto

1. **Inicio (`index.html`)**: Cabecera de navegación, banner principal (Hero), filtros rápidos, grilla responsiva de 6 productos destacados y suscripción al boletín.
2. **Catálogo (`views/productos.html`)**: Buscador superior, barra lateral (`sticky`) de filtros de categorías y precios, grilla adaptable de 20 productos con selección de favoritos y paginación visual.
3. **Sobre Nosotros (`views/sobre-nosotros.html`)**: Principios ecológicos, sección de historia alineada con Flexbox y carrusel horizontal de testimonios.
4. **Contacto (`views/contacto.html`)**: Formulario de soporte con bordes de validación en tiempo real (`:valid` / `:invalid`), mapa estático de sede e íconos de redes sociales animados.

## Cómo Ejecutar el Proyecto Localmente

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone <url-del-repositorio>
   ```
2. Abre la carpeta del proyecto en tu editor de código (como VS Code).
3. Abre el archivo `index.html` directamente en tu navegador web o utilizando la extensión **Live Server**.
