# Client-Side Web Scraper

Una aplicación web que permite realizar scraping de contenido web directamente desde el navegador utilizando JavaScript, XPath y Tailwind CSS.

## Características

- Interfaz de usuario intuitiva y responsiva construida con Tailwind CSS
- Realiza scraping web desde el lado del cliente usando `fetch()` y XPath
- Manejo asíncrono para obtener el HTML y procesar los resultados
- Visualización clara de los resultados obtenidos
- Compatible con GitHub Pages para un fácil despliegue

## Vista previa

La aplicación permite ingresar una URL y un patrón XPath, y muestra los resultados encontrados en la página web objetivo.

## Limitaciones

Esta aplicación está sujeta a las restricciones de seguridad de navegadores web:
- Solo funcionará con sitios web que permitan CORS (Cross-Origin Resource Sharing)
- Utiliza un servicio proxy (AllOrigins) para intentar superar algunas limitaciones de CORS

## Instalación y desarrollo local

### Requisitos previos

- Node.js (v14 o superior)
- npm o yarn

### Pasos para la instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/client-side-web-scraper.git
   cd client-side-web-scraper
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Compila los estilos de Tailwind CSS:
   ```bash
   npm run build
   ```

4. Para desarrollo, puedes usar el modo observador (watch):
   ```bash
   npm run watch
   ```

5. Abre el archivo `index.html` en tu navegador o usa un servidor local como Live Server de VS Code.

## Despliegue en GitHub Pages

1. Asegúrate de tener todos los archivos compilados (ejecuta `npm run build` para generar el CSS).
2. Sube el proyecto a un repositorio de GitHub.
3. Ve a la sección "Settings" del repositorio.
4. Navega a "Pages" en el menú lateral.
5. En "Source", selecciona la rama "main" y la carpeta "/ (root)".
6. Haz clic en "Save".
7. GitHub te proporcionará una URL donde tu aplicación estará disponible.

## Uso

1. Ingresa la URL de la página web que deseas analizar
2. Escribe el patrón XPath para seleccionar los elementos que te interesan
3. Haz clic en "Realizar Scraping"
4. Revisa los resultados que se mostrarán en la parte inferior

## Ejemplos de XPath

- `//h1` - Selecciona todos los encabezados H1
- `//a/@href` - Obtiene todas las URLs de los enlaces
- `//div[@class="producto"]//span[@class="precio"]` - Selecciona los precios dentro de elementos de producto
- `//title/text()` - Obtiene el texto del título de la página
- `//meta[@name="description"]/@content` - Obtiene la descripción meta de la página

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.# Client-Side Web Scraper

Una aplicación web que permite realizar scraping de contenido web directamente desde el navegador utilizando JavaScript, XPath y Tailwind CSS.

## Características

- Interfaz de usuario intuitiva y responsiva construida con Tailwind CSS
- Realiza scraping web desde el lado del cliente usando `fetch()` y XPath
- Manejo asíncrono para obtener el HTML y procesar los resultados
- Visualización clara de los resultados obtenidos
- Compatible con GitHub Pages para un fácil despliegue

## Vista previa

La aplicación permite ingresar una URL y un patrón XPath, y muestra los resultados encontrados en la página web objetivo.

## Limitaciones

Esta aplicación está sujeta a las restricciones de seguridad de navegadores web:
- Solo funcionará con sitios web que permitan CORS (Cross-Origin Resource Sharing)
- Utiliza un servicio proxy (AllOrigins) para intentar superar algunas limitaciones de CORS

## Instalación y desarrollo local

### Requisitos previos

- Node.js (v14 o superior)
- npm o yarn

### Pasos para la instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/client-side-web-scraper.git
   cd client-side-web-scraper
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Compila los estilos de Tailwind CSS:
   ```bash
   npm run build
   ```

4. Para desarrollo, puedes usar el modo observador (watch):
   ```bash
   npm run watch
   ```

5. Abre el archivo `index.html` en tu navegador o usa un servidor local como Live Server de VS Code.

## Despliegue en GitHub Pages

1. Asegúrate de tener todos los archivos compilados (ejecuta `npm run build` para generar el CSS).
2. Sube el proyecto a un repositorio de GitHub.
3. Ve a la sección "Settings" del repositorio.
4. Navega a "Pages" en el menú lateral.
5. En "Source", selecciona la rama "main" y la carpeta "/ (root)".
6. Haz clic en "Save".
7. GitHub te proporcionará una URL donde tu aplicación estará disponible.

## Uso

1. Ingresa la URL de la página web que deseas analizar
2. Escribe el patrón XPath para seleccionar los elementos que te interesan
3. Haz clic en "Realizar Scraping"
4. Revisa los resultados que se mostrarán en la parte inferior

## Ejemplos de XPath

- `//h1` - Selecciona todos los encabezados H1
- `//a/@href` - Obtiene todas las URLs de los enlaces
- `//div[@class="producto"]//span[@class="precio"]` - Selecciona los precios dentro de elementos de producto
- `//title/text()` - Obtiene el texto del título de la página
- `//meta[@name="description"]/@content` - Obtiene la descripción meta de la página
