# 🌍 Interactive World Map

This project is an interactive web page that displays an SVG world map. Clicking on a country highlights it visually and displays a card with detailed information obtained from the [restcountries.com](https://restcountries.com/) API.

## 🗂 Project Structure

- `index.html`: Contains the main structure of the web page, including the SVG map and the information card.
- `styles.css`: Defines the styles for the map and the information card.
- `countryCodes.js`: Exports an object with country names and their respective codes.
- `main.js`: Manages the user interaction logic, highlighting the selected country and displaying the information card.

## 🚀 How to Use

1. **Open the Web Page:**
   Simply open `index.html` in your browser to view the interactive map.

2. **Interaction:**
   - Click on any country on the map to highlight it and display its detailed information.
   - The information card will update with data fetched from the [restcountries.com](https://restcountries.com/) API.

## 🔍 Technical Details

### `index.html`
Defines the basic structure of the page with a container for the SVG map and the information card.

### `styles.css`
Provides styles for the map and the card, including transitions and hover effects to enhance the user experience.

### `countryCodes.js`
Contains an object that maps country names to their ISO codes, which is essential for making API calls correctly.

### `main.js`
Imports `countryCodes.js` and handles:
- Assigning `name` and `id` attributes to the SVG `<path>` elements.
- Click logic to highlight countries and display information.
- API calls to fetch and display data for the selected country in the information card.

## 🎨 Credits

- Data API: [restcountries.com](https://restcountries.com/)
- Icons: [Unicode Emojis](https://unicode.org/emoji/)

Thank you for using this project! If you have any questions or suggestions, feel free to open an issue or contact us.

<hr>

# 🌍 Mapa Mundi Interactivo

Este proyecto es una página web interactiva que muestra un mapa mundi SVG. Al hacer clic en un país, se destaca visualmente y se muestra una tarjeta con información detallada obtenida de la API [restcountries.com](https://restcountries.com/).

## 🗂 Estructura del Proyecto

- `index.html`: Contiene la estructura principal de la página web, incluyendo el mapa SVG y la tarjeta de información.
- `styles.css`: Define los estilos para el mapa y la tarjeta de información.
- `countryCodes.js`: Exporta un objeto con los nombres de los países y sus respectivos códigos.
- `main.js`: Maneja la lógica de interacción del usuario, destacando el país seleccionado y mostrando la tarjeta con información.

## 🚀 Uso del Proyecto

1. **Abrir la Página Web:**
   Simplemente abre `index.html` en tu navegador para ver el mapa interactivo.

2. **Interacción:**
   - Haz clic en cualquier país del mapa para resaltarlo y mostrar su información detallada.
   - La tarjeta de información se actualizará con datos obtenidos de la API [restcountries.com](https://restcountries.com/).

## 🔍 Detalles Técnicos

### `index.html`
Define la estructura básica de la página con un contenedor para el mapa SVG y la tarjeta de información.

### `styles.css`
Proporciona estilos para el mapa y la tarjeta, incluyendo transiciones y efectos hover para mejorar la experiencia del usuario.

### `countryCodes.js`
Contiene un objeto que mapea los nombres de los países a sus códigos ISO, lo cual es esencial para realizar las llamadas a la API correctamente.

### `main.js`
Importa `countryCodes.js` y gestiona:
- La asignación de atributos `name` y `id` a los elementos `<path>` del SVG.
- La lógica de clics para resaltar países y mostrar información.
- Las llamadas a la API para obtener y mostrar los datos del país seleccionado en la tarjeta de información.

## 🎨 Créditos

- API de datos: [restcountries.com](https://restcountries.com/)
- Iconos: [Emojis Unicode](https://unicode.org/emoji/)

¡Gracias por utilizar este proyecto! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o contactarnos.
