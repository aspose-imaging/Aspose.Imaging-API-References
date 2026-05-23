---
title: "Enumeración EmfPlusRecordType"
type: docs
weight: 360
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

La enumeración RecordType define tipos de registros utilizados en metarchivos EMF+.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | Este registro abre un nuevo contenedor de estado gráfico y especifica una transformación para él. Los contenedores gráficos se utilizan para retener elementos del estado gráfico. |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | Este registro abre un nuevo contenedor de estado gráfico. |
| EMF_PLUS_CLEAR | Este registro borra el <c>coordinate space</c> de salida y lo inicializa con un color de fondo y transparencia especificados. |
| EMF_PLUS_COMMENT | Este registro especifica datos privados arbitrarios. |
| EMF_PLUS_DRAW_ARC | El registro define los trazos de la pluma para dibujar un arco de una elipse. |
| EMF_PLUS_DRAW_BEZIERS | Este registro define los trazos de la pluma para dibujar una spline de Bézier. |
| EMF_PLUS_DRAW_CLOSED_CURVE | Este registro define la pluma y los trazos para dibujar una spline cardinal cerrada. |
| EMF_PLUS_DRAW_CURVE | Este registro define los trazos de la pluma para dibujar una spline cardinal. |
| EMF_PLUS_DRAW_DRIVER_STRING | Este registro especifica la salida de texto con posiciones de caracteres. |
| EMF_PLUS_DRAW_ELLIPSE | Este registro define los trazos de la pluma para dibujar una elipse. |
| EMF_PLUS_DRAW_IMAGE | Este registro define un objeto [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) escalado (sección 2.2.1.4). Una imagen puede consistir en datos de mapa de bits o de metarchivo. |
| EMF_PLUS_DRAW_IMAGE_POINTS | Este registro define un objeto EmfPlusImage escalado dentro de un paralelogramo. Una imagen puede consistir en datos de mapa de bits o de metarchivo. |
| EMF_PLUS_DRAW_LINES | Este registro define los trazos de la pluma para dibujar una serie de líneas conectadas. |
| EMF_PLUS_DRAW_PATH | El registro define los trazos de lápiz para dibujar las figuras en una ruta gráfica. Una ruta es un objeto que define una secuencia arbitraria de líneas, curvas y formas. |
| EMF_PLUS_DRAW_PIE | Este registro define los trazos de lápiz para dibujar una sección de una elipse. |
| EMF_PLUS_DRAW_RECTS | Este registro define los trazos de lápiz para dibujar una serie de rectángulos. |
| EMF_PLUS_DRAW_STRING | Este registro define una cadena de texto basada en una fuente, un rectángulo de diseño y un formato. |
| EMF_PLUS_END_CONTAINER | Este registro cierra un contenedor de estado gráfico que fue abierto previamente mediante una operación de inicio de contenedor. |
| EMF_PLUS_END_OF_FILE | Este registro especifica el final de los datos EMF+ en el metarchivo. |
| EMF_PLUS_FILL_CLOSED_CURVE | Este registro define cómo rellenar el interior de una spline cardinal cerrada usando un pincel especificado. |
| EMF_PLUS_FILL_ELLIPSE | Este registro define cómo rellenar los interiores de una elipse, usando un pincel especificado. |
| EMF_PLUS_FILL_PATH | El registro define cómo rellenar los interiores de las figuras definidas en una ruta gráfica con un pincel especificado. Una ruta es un objeto que define una secuencia arbitraria de líneas, curvas y formas. |
| EMF_PLUS_FILL_PIE | Este registro define cómo rellenar una sección del interior de una elipse usando un pincel especificado. |
| EMF_PLUS_FILL_POLYGON | Este registro define los datos para rellenar el interior de un polígono, usando un pincel especificado. |
| EMF_PLUS_FILL_RECTS | Este registro define cómo rellenar los interiores de una serie de rectángulos, usando un pincel especificado. |
| EMF_PLUS_FILL_REGION | Este registro define cómo rellenar el interior de una región usando un pincel especificado. |
| EMF_PLUS_GET_DC | Este registro especifica que los registros EMF subsecuentes encontrados en el metafichero DEBERÍAN ser procesados. Los registros EMF dejan de procesarse cuando se encuentra el siguiente registro EMF+. |
| EMF_PLUS_HEADER | Este registro especifica el inicio de los datos EMF+ en el metafichero. DEBE estar incrustado en el primer registro EMF después del registro [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) ([MS-EMF] sección 2.3.4.2 registro). |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | Este registro multiplica el espacio mundial actual por una matriz de transformación especificada. |
| EMF_PLUS_MULTI_FORMAT_END | Este registro está reservado y NO DEBE ser utilizado. |
| EMF_PLUS_MULTI_FORMAT_SECTION | Este registro está reservado y NO DEBE ser utilizado. |
| EMF_PLUS_MULTI_FORMAT_START | Este registro está reservado y NO DEBE ser utilizado. |
| EMF_PLUS_OBJECT | Este registro especifica un objeto para su uso en operaciones gráficas. |
| EMF_PLUS_OFFSET_CLIP | Este registro aplica una transformación de traslación en la región de recorte actual del espacio mundial. |
| EMF_PLUS_RESET_CLIP | Este registro restablece la región de recorte actual del espacio mundial a infinito. |
| EMF_PLUS_RESET_WORLD_TRANSFORM | Este registro restablece la transformación del espacio mundial actual a la matriz identidad. |
| EMF_PLUS_RESTORE | Este registro restaura el estado gráfico, identificado por un índice especificado, desde una pila de estados gráficos guardados. Cada índice de la pila está asociado con un estado guardado particular, y el índice está definido por un registro [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) (sección 2.3.7.5) para guardar el estado. |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | Este registro rota el espacio mundial actual por un ángulo especificado. |
| EMF_PLUS_SAVE | Este registro guarda el estado gráfico, identificado por un índice especificado, en una pila de estados gráficos guardados. Cada índice de la pila está asociado con un estado guardado particular, y el índice es usado por un registro [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) (sección 2.3.7.4) para restaurar el estado. |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | Este registro aplica una transformación de escala al espacio mundial actual mediante factores de escala horizontal y vertical especificados. |
| EMF_PLUS_SERIALIZABLE_OBJECT | Este registro define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos. |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | Este registro define si habilitar o deshabilitar el antialiasing de texto. El antialiasing de texto es un método para que las líneas y bordes de los glifos de caracteres aparezcan más suaves cuando se dibujan en una superficie de salida. |
| EMF_PLUS_SET_CLIP_PATH | Este registro combina la región de recorte actual con una ruta gráfica. |
| EMF_PLUS_SET_CLIP_RECT | Este registro combina la región de recorte actual con un rectángulo. |
| EMF_PLUS_SET_CLIP_REGION | Este registro combina la región de recorte actual con otra región gráfica. |
| EMF_PLUS_SET_COMPOSITING_MODE | Este registro define el modo de composición según el estado de la mezcla alfa, que especifica cómo se combinan los colores de origen con los colores de fondo. |
| EMF_PLUS_SET_COMPOSITING_QUALITY | Este registro define la calidad de composición, que describe el nivel deseado de calidad para crear imágenes compuestas a partir de múltiples objetos. |
| EMF_PLUS_SET_INTERPOLATION_MODE | Este registro define el modo de interpolación de un objeto según el tipo especificado de filtrado de imagen. El modo de interpolación influye en cómo se realiza el escalado (estiramiento y reducción). |
| EMF_PLUS_SET_PAGE_TRANSFORM | Este registro especifica factores de escalado adicionales para la transformación del espacio mundial actual. |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | Este registro define el modo de desplazamiento de píxeles según el valor especificado de centrado de píxeles. |
| EMF_PLUS_SET_RENDERING_ORIGIN | Este registro define el origen del renderizado a las coordenadas horizontales y verticales especificadas. Esto se aplica a los pinceles de trama y a los patrones de dithering de 8 y 16 bits por píxel. |
| EMF_PLUS_SET_TEXT_CONTRAST | Este registro establece el contraste del texto según el valor gamma de texto especificado. |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | Este registro define el proceso utilizado para renderizar texto. |
| EMF_PLUS_SET_TS_CLIP | Este registro especifica áreas de recorte en el contexto del dispositivo gráfico para un servidor de terminal. |
| EMF_PLUS_SET_TS_GRAPHICS | Este registro especifica el estado del contexto del dispositivo gráfico para un servidor de terminal. |
| EMF_PLUS_SET_WORLD_TRANSFORM | Este registro define la transformación del espacio mundial actual en el device_context de reproducción, según una matriz de transformación especificada. |
| EMF_PLUS_STROKE_FILL_PATH | Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta usando la pluma actual y rellena su interior usando el pincel actual. |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | Este registro aplica una transformación de traslación al espacio mundial actual mediante distancias horizontales y verticales especificadas. |
