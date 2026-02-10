# 📚 BszComics API – Sistema de Carga y Visualización de Cómics

La **API de BszComics** permite integrar un sistema completo de búsqueda, filtrado y visualización de cómics en cualquier sitio web usando solo HTML, CSS y un script externo.

Incluye:
- 🔍 Barra de búsqueda
- 🎯 Filtros por categoría
- 📊 Contador de resultados
- 🃏 Tarjetas de cómics
- 🖼️ Modal con visualización de páginas

---

## 🚀 Integración rápida

Agrega los siguientes contenedores en tu HTML:

```html
<!-- Para la barra de búsqueda -->
<div id="comicsLupa"></div>

<!-- Para la visualización de cómics -->
<div id="comicsVisualizados"></div>

<!-- API de cómics -->
<script src="https://bszcomics.foroactivo.com/10061.js"></script>
```

El script se encarga automáticamente de:
- Renderizar la búsqueda
- Cargar los cómics
- Aplicar filtros
- Gestionar el modal

## 🔍 Barra de búsqueda
 Contenedor principal

 ```css
.comics-search-container
 ```

Contiene el input de búsqueda.

 ```css
.comics-search-input
 ```

Campo donde el usuario escribe el nombre del cómic.

## 🎯 Filtros

Contenedor de filtros
 ```css
.comics-filters-container
 ```

Select de categorías

 ```css
.comics-category-select
 ```

### Permite filtrar los cómics por categoría.

Contador de resultados
 ```css
.comics-results-count
 ```

Muestra cuántos cómics coinciden con la búsqueda o filtro actual.

## 🃏 Tarjetas de cómics

Cada cómic se renderiza como una tarjeta con la siguiente estructura:

Tarjeta completa

 ```css
.vistacomic-card
 ```

Imagen de portada

 ```css
.vistacomic-cover
 ```

Información del cómic

 ```css
.vistacomic-info
 ```

Título

 ```css
.vistacomic-title
 ```

Metadatos

 ```css
.vistacomic-meta
 ```

Incluye:

## 📂 Categoría
 ```css
.vistacomic-category
 ```

## 📄 Número de páginas

 ```css
.vistacomic-pages
 ```

## 🖼️ Modal de visualización

Al hacer clic en una tarjeta, se abre un modal con las páginas del cómic.
 ```css
Modal completo
.vistacomic-modal

Contenido del modal
.vistacomic-modal-content

Cabecera
.vistacomic-modal-header

Título del cómic
.vistacomic-modal-title

Grid de imágenes
.vistacomic-images-grid

Imagen individual
.vistacomic-image
 ```

## 🎨 Personalización

Todo el sistema es 100% personalizable vía CSS usando las clases listadas arriba.
Puedes adaptar colores, tamaños, animaciones y layout sin modificar el script.

## 📌 Requisitos

- Navegador moderno
- Conexión a internet
- No requiere backend propio

## 🧠 Notas
El script gestiona automáticamente la carga y renderizado.
<br>
No es necesario inicializar funciones manualmente.
<br>
Compatible con proyectos estáticos.

# 🔥 Créditos

API desarrollada para BszComics By AvastrOficial
