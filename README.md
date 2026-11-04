# 🌍 Travel & Places Web App

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-%23CC6699.svg?style=for-the-badge&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

Aplicación web multipágina interactiva orientada al descubrimiento de destinos turísticos y experiencias de viaje.

[🌐 Ver Demo en vivo](https://theewiick.github.io/App-Lugares/)

</div>

## 🚀 Características Principales

- **Arquitectura Multipágina:** Secciones independientes (`index`, `lugares`, `nosotros`, `contacto`) conectadas de forma fluida.
- **Diseño Responsive:** Maquetación adaptada a diferentes dispositivos mediante media queries modulares.
- **Estilos Avanzados con SCSS:** Uso de partials, variables, configuraciones y rejillas personalizadas para mantener un código limpio y escalable.
- **Interactividad Web:** Experiencia de usuario dinámica con JavaScript nativo.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Marcado semántico para cada una de las vistas de la aplicación.
* **SCSS (Sass):** Preprocesador CSS organizado en componentes modulares y configuraciones.
* **JavaScript (ES6+):** Lógica del cliente y dinamismo en la interfaz.

---

## 📂 Estructura del Proyecto

```text
app_lugares/
├── css/                # Hojas de estilo compiladas e imágenes estáticas
│   ├── main.css
│   └── img/            # Recursos gráficos (items, recomendados, testimonios)
├── scss/               # Archivos fuente SCSS
│   ├── _configuraciones.scss  # Variables y ajustes globales
│   ├── _media.scss            # Diseño responsive (Media Queries)
│   ├── _rejilla_item.scss     # Estilos de componentes y grids
│   ├── _utilidades.scss       # Clases de utilidad
│   └── main.scss              # Punto de entrada principal de estilos
├── contacto.html       # Página de contacto
├── index.html          # Página principal
├── lugares.html        # Galería / buscador de destinos
├── nosotros.html       # Sección corporativa / sobre nosotros
└── package.json        # Dependencias y scripts del proyecto
