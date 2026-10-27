# Ferretería El Quilar — catálogo web

## Qué incluye
- Catálogo de 10,380 registros de productos exportados desde el inventario.
- Buscador por nombre, código y categoría.
- Filtros por categoría estimada a partir del nombre y del departamento del inventario.
- Sin precios: el archivo publicado `products.json` no contiene columnas de precios ni costes.
- Botón para preparar consultas por WhatsApp.
- Diseño adaptable a móvil y ordenador.

## Datos ya configurados
- WhatsApp: `56957266524` (formato internacional, sin `+`).
- Ubicación mostrada: El Quilar km 3,2, Ancud, Chile.
- Los botones de consulta abren WhatsApp con un mensaje preparado por producto.

## Incorporar el logotipo
Cuando tengas la imagen del logotipo, guárdala como `logo.png` en la misma carpeta. Después se puede actualizar `index.html` para mostrarlo en la cabecera. Conviene usar PNG o SVG con buena resolución y fondo transparente si está disponible.

## Publicación gratuita con GitHub Pages
1. Crea una cuenta gratuita en GitHub si todavía no tienes una.
2. Crea un repositorio público llamado `el-quilar-catalogo`.
3. Sube `index.html` y `products.json` a la raíz del repositorio.
4. En el repositorio, entra en **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y `/ (root)`, y guarda.
6. GitHub mostrará la dirección pública de la web cuando termine de publicarla.

El alojamiento de GitHub Pages es gratuito para este tipo de web estática. Un dominio propio no está incluido y puede costar dinero.

## Importante sobre el inventario
El Excel original contiene 10,380 filas y 10,129 nombres de producto distintos. Se ha mantenido el listado para no perder referencias. La mayoría de los productos no tenían departamento, por lo que las categorías se han inferido automáticamente a partir del nombre y conviene revisarlas antes de publicar. Las existencias reflejan el archivo compartido y pueden quedar desactualizadas; la página invita a confirmar disponibilidad por WhatsApp. No se han exportado precios ni costes.
