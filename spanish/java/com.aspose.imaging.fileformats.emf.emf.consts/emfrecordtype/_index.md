---
title: "EmfRecordType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración RecordType define valores que identifican de forma única los registros EMF."
type: docs
weight: 38
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

La enumeración RecordType define valores que identifican de forma única los registros EMF. Estos valores se proporcionan en el campo Type de cada registro.
## Campos

| Campo | Descripción |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | Este registro define el inicio del metafichero y especifica sus características; su contenido, incluidas las dimensiones de la imagen incrustada; el número de registros en el metafichero; y la resolución del dispositivo en el que se creó la imagen incrustada. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | Este registro define una o más curvas de Bézier. |
| [EMR_POLYGON](#EMR-POLYGON) | Este registro define un polígono compuesto por dos o más vértices conectados por líneas rectas. |
| [EMR_POLYLINE](#EMR-POLYLINE) | Este registro define una serie de segmentos de línea conectando los puntos en la matriz especificada. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | Este registro define una o más curvas de Bézier basadas en la posición actual. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | Este registro define una o más líneas rectas basadas en la posición actual. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | Este registro define múltiples series de segmentos de línea conectados. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | Este registro define una serie de polígonos cerrados. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | Este registro define la extensión de la ventana. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | Este registro define el origen de la ventana. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | Este registro define la extensión del viewport. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | Este registro define el origen del viewport. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | Este registro define el origen del pincel actual. |
| [EMR_EOF](#EMR-EOF) | Este registro indica el final del metafichero. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | Este registro define el color del píxel en las coordenadas lógicas especificadas. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | Este registro especifica los parámetros del proceso de emparejamiento de fuentes lógicas con fuentes físicas, que es realizado por el asignador de fuentes. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | Este registro define el modo de mapeo del contexto del dispositivo de reproducción. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | Este registro define el modo de mezcla de fondo del contexto del dispositivo de reproducción. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | Este registro define el modo de relleno del polígono. |
| [EMR_SETROP2](#EMR-SETROP2) | Este registro define el modo de operación raster binaria. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | Este registro define el modo de estiramiento de mapa de bits. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | Este registro define la alineación de texto. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | Este registro define los valores de ajuste de color para el contexto del dispositivo de reproducción usando los valores especificados. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | Este registro define el color de texto actual. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | Este registro define el color de fondo. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | Este registro redefine la región de recorte del contexto del dispositivo de reproducción mediante los desplazamientos especificados. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | Este registro define las coordenadas de la nueva posición actual, en unidades lógicas. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | Este registro intersecta la región de recorte actual del contexto del dispositivo de reproducción con la meta región actual y guarda la región combinada como la nueva meta región. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | Este registro define una nueva región de recorte que consiste en la región de recorte existente menos el rectángulo especificado. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | Este registro define una nueva región de recorte a partir de la intersección de la región de recorte actual y el rectángulo especificado. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | Este registro redefine la ventana de visualización para el contexto del dispositivo de reproducción usando las proporciones formadas por los multiplicadores y divisores especificados. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | Este registro redefine la ventana para el contexto del dispositivo de reproducción usando las proporciones formadas por los multiplicadores y divisores especificados. |
| [EMR_SAVEDC](#EMR-SAVEDC) | Este registro guarda el estado actual del contexto del dispositivo de reproducción copiando los datos que describen los objetos seleccionados y los modos gráficos\\u2014incluyendo el mapa de bits, el pincel, la paleta, la fuente, la pluma, la región, el modo de dibujo y el modo de mapeo\\u2014a una pila de contextos de dispositivo guardados. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | Este registro restaura el contexto del dispositivo de reproducción al estado guardado especificado. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | Este registro define una transformación lineal bidimensional entre el espacio mundial y el espacio de página (para más información, consulte [MSDN-WRLDPGSPC]) para el contexto del dispositivo de reproducción. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | Este registro redefine la transformación mundial para el contexto del dispositivo de reproducción usando el modo especificado. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | Este registro agrega un objeto al contexto del dispositivo de reproducción, identificándolo por su índice en la Tabla de Objetos EMF (sección 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | Este registro define una pluma lógica que tiene el estilo, ancho y color especificados. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | Este registro define un pincel lógico para el relleno de figuras en operaciones gráficas. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | Este registro elimina un objeto gráfico, borrando su índice en la Tabla de Objetos EMF. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | Este registro define un segmento de línea de un arco. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | Este registro define una elipse. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | Este registro define un rectángulo. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | Este registro define un rectángulo con esquinas redondeadas. |
| [EMR_ARC](#EMR-ARC) | Este registro define un arco elíptico. |
| [EMR_CHORD](#EMR-CHORD) | Este registro define una cuerda (una región delimitada por la intersección de una elipse y un segmento de línea, llamado una secante). |
| [EMR_PIE](#EMR-PIE) | Este registro define una cuña en forma de sector delimitada por la intersección de una elipse y dos radiales. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | Este registro agrega un objeto LogPalette (sección 2.2.17) al contexto del dispositivo de reproducción, identificándolo por su índice en la tabla de objetos EMF. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | Este registro define un objeto LogPalette. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | Este registro define valores de color RGB (rojo-verde-azul) en un rango de entradas en un objeto LogPalette. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | Este registro aumenta o disminuye el tamaño de una paleta lógica. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | Este registro asigna entradas de la paleta lógica actual a la paleta del sistema. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | Este registro rellena un área de la superficie de visualización con el pincel actual. |
| [EMR_LINETO](#EMR-LINETO) | Este registro define una línea desde la posición actual hasta, pero sin incluir, el punto especificado. |
| [EMR_ARCTO](#EMR-ARCTO) | Este registro define un arco elíptico. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | Este registro define un conjunto de segmentos de línea y curvas de Bézier. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | Este registro define la dirección de dibujo que se usará para operaciones de arco y rectángulo. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | Este registro define el límite para la longitud de uniones en inglete para el contexto del dispositivo de reproducción. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | Este registro abre un corchete de ruta en el contexto del dispositivo de reproducción. |
| [EMR_ENDPATH](#EMR-ENDPATH) | Este registro cierra un corchete de ruta y selecciona la ruta definida por el corchete en el contexto del dispositivo de reproducción. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | Este registro cierra una figura abierta en una ruta. |
| [EMR_FILLPATH](#EMR-FILLPATH) | Este registro cierra cualquier figura abierta en la ruta actual y rellena el interior de la ruta usando el pincel actual y el modo de relleno de polígonos. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta usando la pluma actual y rellena su interior usando el pincel actual. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | Este registro renderiza la ruta especificada usando la pluma actual. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | Este registro transforma cualquier curva en la ruta que esté seleccionada en el contexto del dispositivo de reproducción, convirtiendo cada curva en una secuencia de líneas. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | Este registro redefine la ruta actual como el área que se pintaría si la ruta se trazara usando la pluma actualmente seleccionada en el contexto del dispositivo de reproducción. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | Este registro define la ruta actual como una región de recorte para el contexto del dispositivo de reproducción, combinando la nueva región con cualquier región de recorte existente usando el modo especificado. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | Este registro aborta un corchete de ruta o descarta la ruta de un corchete de ruta cerrado. |
| [EMR_COMMENT](#EMR-COMMENT) | Este registro especifica datos privados arbitrarios. |
| [EMR_FILLRGN](#EMR-FILLRGN) | Este registro rellena la región especificada usando el pincel especificado. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | Este registro dibuja un borde alrededor de la región especificada usando el pincel especificado. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | Este registro invierte los colores en la región especificada. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | Este registro pinta la región especificada usando el pincel actualmente seleccionado en el contexto del dispositivo de reproducción. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | Este registro combina la región especificada con la región de recorte actual usando el modo especificado. |
| [EMR_BITBLT](#EMR-BITBLT) | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster especificada. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario. |
| [EMR_MASKBLT](#EMR-MASKBLT) | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel y con la aplicación de un mapa de bits de máscara de color, según operaciones raster de primer plano y fondo especificadas. |
| [EMR_PLGBLT](#EMR-PLGBLT) | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un paralelogramo de destino, con la aplicación de un mapa de bits de máscara de color. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | Este registro especifica una transferencia de bloque de píxeles desde líneas de exploración especificadas de un mapa de bits de origen a un rectángulo de destino. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | Este registro define una fuente lógica que tiene las características especificadas. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | Este registro dibuja una cadena de texto ASCII usando la fuente y los colores de texto actuales. Nota EMR\_EXTTEXTOUTA DEBE ser emulado con un registro EMR\_EXTTEXTOUTW (sección 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | Este registro dibuja una cadena de texto Unicode usando la fuente y los colores de texto actuales. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | Este registro define una o más curvas de Bézier. |
| [EMR_POLYGON16](#EMR-POLYGON16) | Este registro define un polígono compuesto por dos o más vértices conectados por líneas rectas. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | Este registro define una serie de segmentos de línea conectando los puntos en la matriz especificada. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | Este registro define una o más curvas de Bézier basadas en la posición actual. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | Este registro define una o más líneas rectas basadas en la posición actual. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | Este registro define múltiples series de segmentos de línea conectados. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | Este registro define una serie de polígonos cerrados. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | Este registro define un conjunto de segmentos de línea y curvas de Bézier. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | Este registro define un pincel lógico con el patrón de mapa de bits especificado. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | Este registro define un pincel lógico que tiene el patrón especificado por el DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | Este registro define un lápiz lógico cosmético o geométrico que tiene el estilo, ancho y atributos de pincel especificados. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | Este registro dibuja una o más cadenas de texto ASCII usando la fuente y los colores de texto actuales. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | Este registro dibuja una o más cadenas de texto Unicode usando la fuente y los colores de texto actuales. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | Este registro especifica el modo de Gestión de Color de Imagen (ICM) para operaciones gráficas. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | Este registro crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres ASCII |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | Este registro define el objeto de espacio de color lógico actual para operaciones gráficas. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | Este registro elimina un objeto de espacio de color lógico. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | Este registro especifica una función OpenGL. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | Este registro especifica una función OpenGL con un rectángulo delimitador para la salida. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | Este registro especifica el formato de píxel a usar para operaciones gráficas |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | Este registro pasa información arbitraria al controlador. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | Este registro pasa información arbitraria al controlador. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | Este registro genera una cadena. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | Este registro obliga al asignador de fuentes a coincidir fuentes basándose en su UniversalFontId en preferencia a su información LogFont. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | Este registro pasa información arbitraria al controlador nombrado especificado. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | Este registro especifica cómo corregir las entradas de un objeto de paleta lógica usando los valores del Sistema de Color de Windows (WCS) 1.0. |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | Este registro especifica un perfil de color en un archivo con un nombre compuesto por caracteres ASCII, para la salida gráfica. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | Este registro especifica un perfil de color en un archivo con un nombre compuesto por caracteres Unicode, para la salida gráfica. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | Este registro especifica una transferencia de bloque de píxeles de un mapa de bits fuente a un rectángulo de destino, incluyendo datos de transparencia alfa, según una operación de mezcla especificada. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | Este registro especifica el orden en que se dibujan el texto y los gráficos. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | Este registro especifica una transferencia de bloque de píxeles de un mapa de bits fuente a un rectángulo de destino, tratando un color especificado como transparente, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | Este registro especifica el relleno de rectángulos o triángulos con degradados de color. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | Este registro establece los UniversalFontIds de las fuentes vinculadas para usar durante la búsqueda de caracteres. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | Este registro especifica la cantidad de espacio extra que se debe añadir a los caracteres de salto para fines de justificación. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | Este registro especifica si se debe realizar la coincidencia de color con un perfil de color que está especificado en un archivo con un nombre compuesto por caracteres Unicode. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | Este registro crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres Unicode. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


Este registro define el inicio del metafile y especifica sus características; su contenido, incluyendo las dimensiones de la imagen incrustada; el número de registros en el metafile; y la resolución del dispositivo en el que se creó la imagen incrustada. Estos valores hacen posible que el metafile sea independiente del dispositivo.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


Este registro define una o más curvas Bézier. Las curvas Bézier cúbicas se definen usando puntos finales y puntos de control especificados, y se dibujan con el lápiz actual.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


Este registro define un polígono compuesto por dos o más vértices conectados por líneas rectas. El polígono se contornea usando el lápiz actual y se rellena usando el pincel actual y el modo de relleno de polígono. El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


Este registro define una serie de segmentos de línea conectando los puntos en la matriz especificada.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


Este registro define una o más curvas de Bézier basadas en la posición actual.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


Este registro define una o más líneas rectas basadas en la posición actual. Se dibuja una línea desde la posición actual hasta el primer punto especificado en el campo points usando el lápiz actual. Para cada línea adicional, el dibujo se realiza desde el punto final de la línea anterior hasta el siguiente punto especificado en points.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


Este registro define múltiples series de segmentos de línea conectados. Los segmentos de línea se dibujan usando el lápiz actual. Las figuras formadas por los segmentos no se rellenan. La posición actual no se usa ni se actualiza con este registro.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


Este registro define una serie de polígonos cerrados. Cada polígono se contornea usando el lápiz actual y se rellena usando el pincel actual y el modo de relleno de polígono. Los polígonos definidos por este registro pueden superponerse.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


Este registro define la extensión de la ventana.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


Este registro define el origen de la ventana.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


Este registro define la extensión del viewport.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


Este registro define el origen del viewport.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


Este registro define el origen del pincel actual.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


Este registro indica el final del metafichero.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


Este registro define el color del píxel en las coordenadas lógicas especificadas.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


Este registro especifica los parámetros del proceso de emparejamiento de fuentes lógicas con fuentes físicas, que es realizado por el asignador de fuentes.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


Este registro define el modo de mapeo del contexto de dispositivo de reproducción. El modo de mapeo define la unidad de medida utilizada para transformar unidades del espacio de página en unidades del espacio de dispositivo, y también define la orientación del eje x y del eje y del dispositivo.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


Este registro define el modo de mezcla de fondo del contexto de dispositivo de reproducción. El modo de mezcla de fondo se usa con texto, pinceles rayados y estilos de lápiz que no son líneas sólidas.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


Este registro define el modo de relleno del polígono.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


Este registro define el modo de operación raster binaria.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


Este registro define el modo de estiramiento de mapa de bits.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


Este registro define la alineación de texto.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


Este registro define los valores de ajuste de color para el contexto del dispositivo de reproducción usando los valores especificados.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


Este registro define el color de texto actual.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


Este registro define el color de fondo.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


Este registro redefine la región de recorte del contexto del dispositivo de reproducción mediante los desplazamientos especificados.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


Este registro define las coordenadas de la nueva posición actual, en unidades lógicas.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


Este registro intersecta la región de recorte actual del contexto de dispositivo de reproducción con la región meta actual y guarda la región combinada como la nueva región meta. La región de recorte se restablece a una región nula.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


Este registro define una nueva región de recorte que consiste en la región de recorte existente menos el rectángulo especificado.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


Este registro define una nueva región de recorte a partir de la intersección de la región de recorte actual y el rectángulo especificado.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


Este registro redefine la ventana de visualización para el contexto del dispositivo de reproducción usando las proporciones formadas por los multiplicadores y divisores especificados.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


Este registro redefine la ventana para el contexto del dispositivo de reproducción usando las proporciones formadas por los multiplicadores y divisores especificados.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


Este registro guarda el estado actual del contexto del dispositivo de reproducción copiando los datos que describen los objetos seleccionados y los modos gráficos\\u2014incluyendo el mapa de bits, el pincel, la paleta, la fuente, la pluma, la región, el modo de dibujo y el modo de mapeo\\u2014a una pila de contextos de dispositivo guardados.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


Este registro restaura el contexto de dispositivo de reproducción al estado guardado especificado. El contexto de dispositivo de reproducción se restaura extrayendo la información de estado de una pila de contextos de dispositivo guardados creada por registros EMR\_SAVEDC (sección 2.3.11) anteriores.

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


Este registro define una transformación lineal bidimensional entre el espacio mundial y el espacio de página (para más información, vea [MSDN-WRLDPGSPC]) para el contexto de dispositivo de reproducción. Esta transformación puede usarse para escalar, rotar, sesgar o trasladar la salida gráfica.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


Este registro redefine la transformación mundial para el contexto del dispositivo de reproducción usando el modo especificado.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


Este registro agrega un objeto al contexto del dispositivo de reproducción, identificándolo por su índice en la Tabla de Objetos EMF (sección 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


Este registro define un lápiz lógico que tiene el estilo, ancho y color especificados. El lápiz puede seleccionarse posteriormente en el contexto de dispositivo de reproducción y usarse para dibujar líneas y curvas.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


Este registro define un pincel lógico para el relleno de figuras en operaciones gráficas.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


Este registro elimina un objeto gráfico, borrando su índice en la Tabla de Objetos EMF. Si el objeto eliminado está seleccionado en el contexto de dispositivo de reproducción, el objeto predeterminado para esa propiedad del contexto DEBE ser restaurado.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


Este registro define un segmento de línea de un arco. El segmento de línea se dibuja desde la posición actual hasta el comienzo del arco. El arco se dibuja a lo largo del perímetro de un círculo con el radio y centro dados. La longitud del arco se define por los ángulos de inicio y barrido dados.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


Este registro define una elipse. El centro de la elipse es el centro del rectángulo delimitador especificado. La elipse se contornea usando la pluma actual y se rellena usando el pincel actual.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


Este registro define un rectángulo. El rectángulo se contornea usando la pluma actual y se rellena usando el pincel actual.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


Este registro define un rectángulo con esquinas redondeadas. El rectángulo se contornea usando la pluma actual y se rellena usando el pincel actual.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


Este registro define un arco elíptico.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


Este registro define una cuerda (una región delimitada por la intersección de una elipse y un segmento de línea, llamado secante). La cuerda se contornea usando la pluma actual y se rellena usando el pincel actual.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


Este registro define una cuña en forma de pastel delimitada por la intersección de una elipse y dos radiales. El pastel se contornea usando la pluma actual y se rellena usando el pincel actual.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


Este registro agrega un objeto LogPalette (sección 2.2.17) al contexto del dispositivo de reproducción, identificándolo por su índice en la tabla de objetos EMF.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


Este registro define un objeto LogPalette.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


Este registro define valores de color RGB (rojo-verde-azul) en un rango de entradas en un objeto LogPalette.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


Este registro aumenta o disminuye el tamaño de una paleta lógica.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


Este registro asigna entradas de la paleta lógica actual a la paleta del sistema.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


Este registro rellena un área de la superficie de visualización con el pincel actual.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


Este registro define una línea desde la posición actual hasta, pero sin incluir, el punto especificado. Restablece la posición actual al punto especificado.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


Este registro define un arco elíptico. Restablece la posición actual al punto final del arco.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


Este registro define un conjunto de segmentos de línea y curvas de Bézier.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


Este registro define la dirección de dibujo que se usará para operaciones de arco y rectángulo.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


Este registro define el límite para la longitud de uniones en inglete para el contexto del dispositivo de reproducción.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


Este registro abre un corchete de ruta en el contexto del dispositivo de reproducción.

--------------------

Después de que se abre un corchete de ruta, una aplicación puede comenzar a procesar registros para definir los puntos que pertenecen a la ruta. Una aplicación DEBE cerrar un corchete de ruta abierto procesando el registro EMR\_ENDPATH. Cuando una aplicación procesa el registro EMR\_BEGINPATH, todas las rutas anteriores DEBEN descartarse del contexto del dispositivo de reproducción.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


Este registro cierra un corchete de ruta y selecciona la ruta definida por el corchete en el contexto del dispositivo de reproducción.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


Este registro cierra una figura abierta en una ruta.

--------------------

Procesar el registro EMR\_CLOSEFIGURE DEBE cerrar la figura dibujando una línea desde la posición actual hasta el primer punto de la figura, y luego DEBE conectar las líneas usando el estilo de unión de líneas. Si una figura se cierra procesando el registro EMR\_LINETO en lugar del registro EMR\_CLOSEFIGURE, se utilizan extremos de línea para crear la esquina en lugar de una unión. EMR\_LINETO se especifica en la sección 2.3.5.13. El registro EMR\_CLOSEFIGURE SOLO DEBERÍA usarse si hay un corchete de ruta abierto en el contexto del dispositivo de reproducción. Una figura en una ruta está abierta a menos que se cierre explícitamente procesando este registro. Nota: Una figura puede estar abierta incluso si el punto actual y el punto inicial de la figura son el mismo. Después de procesar el registro EMR\_CLOSEFIGURE, agregar una línea o curva a la ruta DEBE iniciar una nueva figura.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


Este registro cierra cualquier figura abierta en la ruta actual y rellena el interior de la ruta usando el pincel actual y el modo de relleno de polígonos.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta usando la pluma actual y rellena su interior usando el pincel actual.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


Este registro renderiza la ruta especificada usando la pluma actual.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


Este registro transforma cualquier curva en la ruta que esté seleccionada en el contexto del dispositivo de reproducción, convirtiendo cada curva en una secuencia de líneas.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


Este registro redefine la ruta actual como el área que se pintaría si la ruta se trazara usando la pluma actualmente seleccionada en el contexto del dispositivo de reproducción.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


Este registro define la ruta actual como una región de recorte para el contexto del dispositivo de reproducción, combinando la nueva región con cualquier región de recorte existente usando el modo especificado.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


Este registro aborta un corchete de ruta o descarta la ruta de un corchete de ruta cerrado.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


Este registro especifica datos privados arbitrarios.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


Este registro rellena la región especificada usando el pincel especificado.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


Este registro dibuja un borde alrededor de la región especificada usando el pincel especificado.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


Este registro invierte los colores en la región especificada.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


Este registro pinta la región especificada usando el pincel actualmente seleccionado en el contexto del dispositivo de reproducción.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


Este registro combina la región especificada con la región de recorte actual usando el modo especificado.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster especificada.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel y con la aplicación de un mapa de bits de máscara de color, según operaciones raster de primer plano y fondo especificadas.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un paralelogramo de destino, con la aplicación de un mapa de bits de máscara de color.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


Este registro especifica una transferencia de bloque de píxeles desde líneas de exploración especificadas de un mapa de bits de origen a un rectángulo de destino.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


Este registro define una fuente lógica que tiene las características especificadas. La fuente puede seleccionarse posteriormente como la fuente actual para el contexto del dispositivo de reproducción.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


Este registro dibuja una cadena de texto ASCII usando la fuente actual y los colores de texto. Nota EMR\_EXTTEXTOUTA DEBERÍA emularse con un registro EMR\_EXTTEXTOUTW (sección 2.3.5.8). Esto requiere que la cadena de texto ASCII en el objeto EmrText se convierta a codificación Unicode UTF16-LE.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


Este registro dibuja una cadena de texto Unicode usando la fuente y los colores de texto actuales.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


Este registro define una o más curvas de Bézier. Las curvas se dibujan usando la pluma actual.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


Este registro define un polígono compuesto por dos o más vértices conectados por líneas rectas. El polígono se contornea usando el lápiz actual y se rellena usando el pincel actual y el modo de relleno de polígono. El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


Este registro define una serie de segmentos de línea conectando los puntos en la matriz especificada.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


Este registro define una o más curvas de Bézier basadas en la posición actual.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


Este registro define una o más líneas rectas basadas en la posición actual. Se dibuja una línea desde la posición actual hasta el primer punto especificado por el campo Points usando la pluma actual. Para cada línea adicional, el dibujo se realiza desde el punto final de la línea anterior hasta el siguiente punto especificado por Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


Este registro define múltiples series de segmentos de línea conectados.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


Este registro define una serie de polígonos cerrados. Cada polígono se contornea usando la pluma actual y se rellena usando el pincel actual y el modo de relleno de polígonos. Los polígonos especificados por este registro pueden superponerse.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


Este registro define un conjunto de segmentos de línea y curvas de Bézier.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


Este registro define un pincel lógico con el patrón de mapa de bits especificado. El mapa de bits puede ser un mapa de bits de sección independiente del dispositivo (DIB) o puede ser un mapa de bits dependiente del dispositivo.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


Este registro define un pincel lógico que tiene el patrón especificado por el DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


Este registro define un lápiz lógico cosmético o geométrico que tiene el estilo, ancho y atributos de pincel especificados.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


Este registro dibuja una o más cadenas de texto ASCII usando la fuente actual y los colores de texto. Nota EMR\_POLYTEXTOUTA DEBERÍA emularse con una serie de registros EMR\_EXTTEXTOUTW, uno por cadena.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


Este registro dibuja una o más cadenas de texto Unicode usando la fuente actual y los colores de texto. Nota EMR\_POLYTEXTOUTW DEBERÍA emularse con una serie de registros EMR\_EXTTEXTOUTW, uno por cadena.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


Este registro especifica el modo de Gestión de Color de Imagen (ICM) para operaciones gráficas.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


Este registro crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres ASCII

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


Este registro define el objeto de espacio de color lógico actual para operaciones gráficas.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


Este registro elimina un objeto de espacio de color lógico. Nota: Un registro EMR\_DELETEOBJECT DEBERÍA usarse en lugar de EMR\_DELETECOLORSPACE para eliminar un objeto de espacio de color lógico.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


Este registro especifica una función OpenGL.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


Este registro especifica una función OpenGL con un rectángulo delimitador para la salida.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


Este registro especifica el formato de píxel a usar para operaciones gráficas

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


Este registro pasa información arbitraria al controlador. La intención es que la información resulte en la realización de dibujo.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


Este registro pasa información arbitraria al controlador. La intención es que la información no resulte en la realización de dibujo.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


Este registro genera una cadena.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


Este registro obliga al asignador de fuentes a coincidir fuentes basándose en su UniversalFontId en preferencia a su información LogFont.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


Este registro pasa información arbitraria al controlador nombrado especificado.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


Este registro especifica cómo corregir las entradas de un objeto de paleta lógica usando los valores del Sistema de Color de Windows (WCS) 1.0.

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


Este registro especifica un perfil de color en un archivo con un nombre compuesto por caracteres ASCII, para la salida gráfica.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


Este registro especifica un perfil de color en un archivo con un nombre compuesto por caracteres Unicode, para la salida gráfica.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


Este registro especifica una transferencia de bloque de píxeles de un mapa de bits fuente a un rectángulo de destino, incluyendo datos de transparencia alfa, según una operación de mezcla especificada.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


Este registro especifica el orden en que se dibujan el texto y los gráficos.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


Este registro especifica una transferencia de bloque de píxeles de un mapa de bits fuente a un rectángulo de destino, tratando un color especificado como transparente, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


Este registro especifica el relleno de rectángulos o triángulos con degradados de color.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


Este registro establece los UniversalFontIds de las fuentes vinculadas para usar durante la búsqueda de caracteres.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


Este registro especifica la cantidad de espacio extra que se debe añadir a los caracteres de salto para fines de justificación.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


Este registro especifica si se debe realizar la coincidencia de color con un perfil de color que está especificado en un archivo con un nombre compuesto por caracteres Unicode.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


Este registro crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres Unicode.

