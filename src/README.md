# OMDb Search React App

<div align="center" markdown="1">

API a usar:






[![Lighthouse Performance Badge](./target/lighthouse/lighthouse_performance.svg)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fdavorpa.github.io%2Fomdb-search-react-app%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa#performance) [![Lighthouse Accessibility Badge](./target/lighthouse/lighthouse_accessibility.svg)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fdavorpa.github.io%2Fomdb-search-react-app%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa#accessibility) [![Lighthouse Best Practices Badge](./target/lighthouse/lighthouse_best-practices.svg)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fdavorpa.github.io%2Fomdb-search-react-app%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa#best-practices) [![Lighthouse SEO Badge](./target/lighthouse/lighthouse_seo.svg)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fdavorpa.github.io%2Fomdb-search-react-app%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa#seo) [![Lighthouse PWA Badge](./target/lighthouse/lighthouse_pwa.svg)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fdavorpa.github.io%2Fomdb-search-react-app%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa#pwa)

![screenshot](screenshot.png)

</div>

Aplicación para buscar películas usando la API de <https://www.omdbapi.com>

Requerimientos:

- [x] Necesita mostrar un input para buscar la película y un botón para buscar.
- [x] Lista las películas y muestra el título, año y poster.
- [x] Que el formulario funcione
- [x] Haz que las películas se muestren en un grid responsive.
- [x] Hacer el fetching de datos a la API

Primera iteración:

- [x] Evitar que se haga la misma búsqueda dos veces seguidas.
- [x] Haz que la búsqueda se haga automáticamente al escribir.
- [x] Evita que se haga la búsqueda continuamente al escribir (debounce)