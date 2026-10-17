# Tienda deportiva

Proyecto frontend realizado en equipo durante la formación de Generation México. Presenta un catálogo de artículos deportivos y un carrito interactivo con HTML, CSS, JavaScript y Bootstrap.

**[Abrir demo](https://miguel-asc.github.io/Tienda-Deportiva/)** · [Portafolio de Miguel](https://miguel-asc.netlify.app/)

## Funciones de la interfaz

- Catálogo renderizado desde datos definidos en JavaScript.
- Panel de carrito con cantidades, eliminación de artículos y subtotal.
- Límite de diez unidades por identificador de producto.
- Menú y componentes visuales con Bootstrap.

## Ejecutar

Clona el repositorio y sirve su carpeta raíz con Live Server en VS Code o con Python:

```sh
git clone https://github.com/Miguel-ASC/Tienda-Deportiva.git
cd Tienda-Deportiva
python -m http.server 5500
```

Abre `http://localhost:5500/`. Bootstrap se carga desde un CDN y necesita conexión. No hay un proceso de compilación.

## Estructura

- `index.html`: página principal y estructura del carrito.
- `style.css`: estilos del sitio.
- `script.js`: catálogo y estado del carrito en memoria.
- `Pictures/`: imágenes de productos y recursos.

## Alcance

Demo formativa del frontend: no integra pagos reales, usuarios ni persistencia en un servidor. El carrito está en memoria y se reinicia al recargar. La navegación por categorías y la acción final de compra requieren desarrollo adicional. También debe revisarse la unicidad de los identificadores de producto para evitar que variantes distintas compartan cantidades.

## Equipo

Aldo Briones Martínez, Denisse Azucena Garza Ascacio, Miguel Sánchez y Roberto Carlos, según los créditos originales del repositorio. Se conserva el reconocimiento del trabajo colectivo.

[Perfil de Miguel](https://github.com/Miguel-ASC) · [LinkedIn](https://www.linkedin.com/in/miguel-asc/)
