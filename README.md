# 🎬 Buscador de Películas con OMDb API

## Características

* **Búsqueda en tiempo real:** Conexión con la [OMDb API](http://www.omdbapi.com/) para obtener datos de películas y series.
* **Gestión de Favoritos (Toggle):**
    * Añadir películas a favoritos con un solo clic.
    * Eliminar de favoritos haciendo clic nuevamente (lógica de *toggle* inteligente).
    * Indicadores visuales (SVG interactivos) para saber qué películas ya están guardadas.
* **Persistencia de Datos:** Uso de `localStorage` para que tus favoritos no se pierdan al recargar la página.

## Tecnologías Utilizadas

* **HTML5:** Estructura semántica.
* **CSS3:** Estilos personalizados, variables CSS y diseño responsivo.
* **JavaScript (ES6+):**
    * `fetch` API para peticiones asíncronas.
    * Manipulación del DOM (`closest`, `delegación de eventos`).
    * Lógica de arrays (`map`, `filter`, `splice`, `includes`).
    * `LocalStorage` para persistencia.

## Desplegar
* **https://alex1245re.github.io/BuscadorPeliculas/**
