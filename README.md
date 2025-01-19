# Tabla Interactiva de Productos - E-commerce

Este proyecto es una tabla interactiva construida en React para mostrar productos obtenidos desde una API. Ofrece funcionalidades como ordenación por columnas y paginación para mejorar la navegación del usuario.

---

## **Tecnologías utilizadas**

- **React**: Framework de JavaScript para construir la interfaz de usuario.
- **Axios**: Librería para realizar peticiones HTTP a la API.
- **FakeStore API**: API externa utilizada para obtener los datos de los productos.

---

## **Características principales**

1. **Visualización de productos**:
   - Muestra tres columnas principales: Título, Categoría y Precio.

2. **Ordenación**:
   - Permite ordenar los productos haciendo clic en el encabezado de cada columna.
   - Soporta orden ascendente y descendente.

3. **Paginación**:
   - Divide los productos en páginas para una mejor navegación.
   - El usuario puede moverse entre las páginas mediante botones.

---

## **Instalación y configuración**

### **Requisitos previos**

- Tener instalado [Node.js](https://nodejs.org/) (v16 o superior).
- Tener instalado [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/).

### **Pasos de instalación**

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tabla-interactiva.git
   ```

2. Accede al directorio del proyecto:
   ```bash
   cd tabla-interactiva
   ```

3. Instala las dependencias necesarias:
   ```bash
   npm install
   ```
   o, si usas yarn:
   ```bash
   yarn install
   ```

4. Inicia el servidor de desarrollo:
   ```bash
   npm start
   ```
   o, si usas yarn:
   ```bash
   yarn start
   ```

5. Abre el proyecto en tu navegador en: `http://localhost:3000`.

---

## **Estructura del código**

El código principal se encuentra en el archivo `ProductTable.js`, donde se implementan las siguientes funcionalidades:

1. **Carga de datos desde la API**:
   Se utiliza el hook `useEffect` para realizar una petición HTTP con Axios a la API [FakeStore](https://fakestoreapi.com/).


2. **Ordenación**:
   Se implementa una función que ordena los productos según la columna seleccionada y alterna entre ascendente y descendente.

3. **Paginación**:
   Se divide la lista de productos en páginas y se actualiza según el índice de la página actual.

---

## **Uso del proyecto**

1. **Explorar los productos:** Los productos aparecen en una tabla con tres columnas: Título, Categoría y Precio.
2. **Ordenar por columnas:** Haz clic en los encabezados de las columnas para ordenar los productos alfabéticamente o por precio.
3. **Cambiar de página:** Usa los botones "Anterior" y "Siguiente" para navegar entre páginas.

---

## **Mejoras futuras**

1. **Búsqueda**:
   - Agregar una barra de búsqueda para filtrar productos por título o categoría.

2. **Filtro por categoría**:
   - Implementar un filtro para mostrar productos de una sola categoría.

3. **Diseño mejorado**:
   - Usar una librería de estilos como Bootstrap o Material-UI para mejorar la apariencia.

4. **Soporte para más columnas**:
   - Agregar información adicional como descripción o rating del producto.

---

## **Licencia**

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

---

Si tienes dudas o sugerencias, no dudes en contactarme. ¡Espero que disfrutes el proyecto!

