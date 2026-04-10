# DnD Inventory React

Una aplicación web para gestionar inventarios en Dungeons & Dragons (D&D). Permite a los jugadores organizar sus ítems, gestionar dinero, calcular pesos y mucho más, todo de manera intuitiva y persistente en el navegador.

## Características

- **Múltiples Inventarios**: Crea y gestiona varios inventarios para diferentes personajes o campañas.
- **Categorías de Ítems**: Organiza tus ítems en categorías como Equipamiento, Consumibles, Crafteo, Misión y Misceláneo.
- **Gestión de Dinero**: Maneja monedas de oro, plata y cobre, con opciones para agregar, quitar y redondear valores.
- **Cálculo de Peso**: Calcula el peso total de tus ítems y establece una capacidad máxima de carga.
- **Venta de Ítems**: Vende ítems directamente desde el inventario y agrega el dinero ganado a tu billetera.
- **Persistencia Local**: Todos los datos se guardan automáticamente en el almacenamiento local del navegador.
- **Importar/Exportar**: Exporta tus inventarios como archivos JSON para backup o comparte con otros.
- **Interfaz Intuitiva**: Diseño limpio y fácil de usar, con modales y dropdowns para una experiencia fluida.

## Tecnologías Utilizadas

- **React**: Biblioteca para construir la interfaz de usuario.
- **Vite**: Herramienta de construcción rápida para desarrollo moderno.
- **Sass**: Preprocesador CSS para estilos avanzados.
- **PureCSS**: Framework CSS minimalista para layouts.
- **ESLint**: Linter para mantener la calidad del código.
- **gh-pages**: Para despliegue en GitHub Pages.

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/dnd-inventory-react.git
   cd dnd-inventory-react
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

4. Abre tu navegador en `http://localhost:5173` (o el puerto que indique Vite).

## Uso

- **Agregar Ítems**: Haz clic en el botón "+" para abrir el formulario de creación de ítems. Selecciona una categoría, ingresa nombre, descripción, peso, cantidad y valor.
- **Gestionar Cantidades**: Usa los botones "+" y "-" en la lista de ítems para ajustar cantidades.
- **Equipar Ítems**: En la categoría de Equipamiento, marca la casilla para equipar/desequipar ítems.
- **Gestionar Dinero**: Haz clic en el botón de dinero (💲) para agregar o quitar monedas. Usa la opción de redondeo para convertir monedas menores en oro.
- **Vender Ítems**: Haz clic en el botón de venta (💲) en un ítem para venderlo y agregar el valor a tu billetera.
- **Cambiar Inventarios**: Usa el selector en la parte superior para cambiar entre inventarios.
- **Crear/Eliminar Inventarios**: Abre el menú desplegable (tres puntos) para crear o eliminar inventarios.
- **Importar/Exportar**: En el menú, usa las opciones para descargar tus datos como JSON o subir un archivo para importar.

## Despliegue

El proyecto está configurado para desplegarse en GitHub Pages usando `gh-pages`.

1. Construye el proyecto:
   ```bash
   npm run build
   ```

2. Despliega:
   ```bash
   npm run deploy
   ```

Asegúrate de configurar el repositorio en GitHub y ajustar la URL base en `vite.config.js` si es necesario.

## Contribución

¡Las contribuciones son bienvenidas! Si encuentras un bug o tienes una idea para mejorar la aplicación:

1. Haz un fork del repositorio.
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`).
3. Haz commit de tus cambios (`git commit -am 'Agrega nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
