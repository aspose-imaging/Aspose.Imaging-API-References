---
title: "Enumeración EmfRecordType"
type: docs
weight: 290
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

La enumeración RecordType define valores que identifican de forma única los registros EMF.<br/>            Estos valores se proporcionan en el campo Type de cada registro.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| EMR_ABORTPATH | Este registro aborta un corchete de ruta o descarta la ruta de un corchete de ruta cerrado. |
| EMR_ALPHABLEND | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino,<br/>             incluyendo datos de transparencia alfa, según una operación de mezcla especificada. |
| EMR_ANGLEARC | Este registro define un segmento de línea de un arco. El segmento de línea se dibuja desde la <br/>            posición actual hasta el inicio del arco. El arco se dibuja a lo largo del perímetro <br/>            de un círculo con el radio y centro dados. La longitud del arco se define por los <br/>            ángulos de inicio y barrido proporcionados. |
| EMR_ARC | Este registro define un arco elíptico. |
| EMR_ARCTO | Este registro define un arco elíptico. Restablece la posición actual al <br/>            punto final del arco. |
| EMR_BEGINPATH | Este registro abre un corchete de ruta en el contexto del dispositivo de reproducción. |
| EMR_BITBLT | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino<br/>             opcionalmente en combinación con un patrón de pincel, según una operación rasterizada especificada. |
| EMR_CHORD | Este registro define una cuerda (una región delimitada por la intersección de una elipse <br/>            y un segmento de línea, llamado secante). La cuerda se perfila usando la pluma actual <br/>            y se rellena usando el pincel actual. |
| EMR_CLOSEFIGURE | Este registro cierra una figura abierta en una ruta. |
| EMR_COLORCORRECTPALETTE | Este registro especifica cómo corregir las entradas de un objeto de paleta lógica usando Windows <br/>            Sistema de Color (WCS) 1.0 valores. |
| EMR_COLORMATCHTOTARGETW | Este registro especifica si se debe realizar la coincidencia de color con un perfil de color que está especificado en un archivo cuyo nombre consta de caracteres Unicode. |
| EMR_COMMENT | Este registro especifica datos privados arbitrarios. |
| EMR_CREATEBRUSHINDIRECT | Este registro define un pincel lógico para el relleno de figuras en operaciones gráficas. |
| EMR_CREATECOLORSPACE | Este registro crea un objeto de espacio de color lógico a partir de un perfil de color cuyo nombre consta de caracteres ASCII |
| EMR_CREATECOLORSPACEW | Este registro crea un objeto de espacio de color lógico a partir de un perfil de color cuyo nombre consta de caracteres Unicode |
| EMR_CREATEDIBPATTERNBRUSHPT | Este registro define un pincel lógico que tiene el patrón especificado por el DIB. |
| EMR_CREATEMONOBRUSH | Este registro define un pincel lógico con el patrón de mapa de bits especificado. El mapa de bits puede<br/>             ser un mapa de bits independiente del dispositivo (DIB) de sección o puede ser un mapa de bits dependiente del dispositivo. |
| EMR_CREATEPALETTE | Este registro define un objeto LogPalette. |
| EMR_CREATEPEN | Este registro define una pluma lógica que tiene el estilo, ancho y color especificados. <br/>            La pluma puede seleccionarse posteriormente en el contexto del dispositivo de reproducción y usarse para dibujar líneas y curvas. |
| EMR_DELETECOLORSPACE | Este registro elimina un objeto de espacio de color lógico. Nota: Un registro EMR_DELETEOBJECT DEBERÍA ser <br/>            usado en lugar de EMR_DELETECOLORSPACE para eliminar un objeto de espacio de color lógico |
| EMR_DELETEOBJECT | Este registro elimina un objeto gráfico, borrando su índice en la tabla de objetos EMF. <br/>            Si el objeto eliminado está seleccionado en el contexto del dispositivo de reproducción, el objeto predeterminado <br/>            para esa propiedad de contexto DEBE ser restaurado. |
| EMR_DRAWESCAPE | Este registro pasa información arbitraria al controlador. La intención es que la información <br/>            resulte en la realización de dibujo. |
| EMR_ELLIPSE | Este registro define una elipse. El centro de la elipse es el centro del <br/>            rectángulo delimitador especificado. La elipse se contornea usando la pluma actual y <br/>            se rellena usando el pincel actual. |
| EMR_ENDPATH | Este registro cierra un corchete de ruta y selecciona la ruta definida por el corchete <br/>            en el contexto del dispositivo de reproducción. |
| EMR_EOF | Este registro indica el final del metafile. |
| EMR_EXCLUDECLIPRECT | Este registro define una nueva región de recorte que consiste en la región de recorte existente <br/>            menos el rectángulo especificado. |
| EMR_EXTCREATEFONTINDIRECTW | Este registro define una fuente lógica que tiene las características especificadas. La fuente <br/>            puede seleccionarse posteriormente como la fuente actual para el contexto del dispositivo de reproducción. |
| EMR_EXTCREATEPEN | Este registro define una pluma lógica cosmética o geométrica que tiene el estilo, <br/>            ancho y atributos de pincel especificados. |
| EMR_EXTESCAPE | Este registro pasa información arbitraria al controlador. La intención es que la información <br/>            no resulte en la realización de dibujo. |
| EMR_EXTFLOODFILL | Este registro rellena un área de la superficie de visualización con el pincel actual. |
| EMR_EXTSELECTCLIPRGN | Este registro combina la región especificada con la región de recorte actual usando el <br/>            modo especificado. |
| EMR_EXTTEXTOUTA | Este registro dibuja una cadena de texto ASCII usando la fuente actual y los colores de texto. Nota <br/>            EMR_EXTTEXTOUTA DEBE ser emulado con un registro EMR_EXTTEXTOUTW (sección 2.3.5.8).  <br/>            Esto requiere que la cadena de texto ASCII en el objeto EmrText sea convertida a codificación Unicode UTF16-LE. |
| EMR_EXTTEXTOUTW | Este registro dibuja una cadena de texto Unicode usando la fuente actual y los colores de texto. |
| EMR_FILLPATH | Este registro cierra cualquier figura abierta en la ruta actual y rellena el interior de la ruta <br/>            usando el pincel actual y el modo de relleno de polígonos. |
| EMR_FILLRGN | Este registro rellena la región especificada usando el pincel especificado. |
| EMR_FLATTENPATH | Este registro transforma cualquier curva en la ruta que está seleccionada en el dispositivo de reproducción <br/>            contexto, convirtiendo cada curva en una secuencia de líneas. |
| EMR_FORCEUFIMAPPING | Este registro obliga al asignador de fuentes a que coincida las fuentes basándose en su UniversalFontId <br/>            en preferencia a su información LogFont. |
| EMR_FRAMERGN | Este registro dibuja un borde alrededor de la región especificada usando el pincel especificado. |
| EMR_GLSBOUNDEDRECORD | Este registro especifica una función OpenGL con un rectángulo delimitador para la salida. |
| EMR_GLSRECORD | Este registro especifica una función OpenGL. |
| EMR_GRADIENTFILL | Este registro especifica el relleno de rectángulos o triángulos con degradados de color |
| EMR_HEADER | Este registro define el inicio del metafichero y especifica sus características; su contenido, <br/>            incluyendo las dimensiones de la imagen incrustada; el número de registros en el metafichero; y la <br/>            resolución del dispositivo en el que se creó la imagen incrustada. Estos valores hacen posible que el metafichero sea independiente del dispositivo. |
| EMR_INTERSECTCLIPRECT | Este registro define una nueva región de recorte a partir de la intersección de la región de recorte actual <br/>            y el rectángulo especificado. |
| EMR_INVERTRGN | Este registro invierte los colores en la región especificada. |
| EMR_LINETO | Este registro define una línea desde la posición actual hasta, pero sin incluir,<br/>             el punto especificado. Restablece la posición actual al punto especificado. |
| EMR_MASKBLT | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits fuente a un rectángulo de destino<br/>             , opcionalmente en combinación con un patrón de pincel y con la aplicación de un <br/>            mapa de bits de máscara de color, de acuerdo con las operaciones raster de primer plano y fondo especificadas. |
| EMR_MODIFYWORLDTRANSFORM | Este registro redefine la transformación mundial para el contexto del dispositivo de reproducción usando el modo especificado. |
| EMR_MOVETOEX | Este registro define las coordenadas de la nueva posición actual, en unidades lógicas. |
| EMR_NAMEDESCAPE | Este registro pasa información arbitraria al controlador nombrado especificado. |
| EMR_OFFSETCLIPRGN | Este registro redefine la región de recorte del contexto del dispositivo de reproducción mediante los desplazamientos especificados. |
| EMR_PAINTRGN | Este registro pinta la región especificada usando el pincel actualmente seleccionado en <br/>            el contexto del dispositivo de reproducción. |
| EMR_PIE | Este registro define una cuña en forma de pastel delimitada por la intersección de una elipse <br/>            y dos radiales. El pastel se contornea usando la pluma actual y se rellena usando <br/>            el pincel actual. |
| EMR_PIXELFORMAT | Este registro especifica el formato de píxel a usar para operaciones gráficas |
| EMR_PLGBLT | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits fuente a un paralelogramo de destino <br/>            con la aplicación de un mapa de bits de máscara de color. |
| EMR_POLYBEZIER | Este registro define una o más curvas de Bézier. Las curvas de Bézier cúbicas se definen usando<br/>            puntos finales y puntos de control especificados, y se dibujan con la pluma actual. |
| EMR_POLYBEZIER16 | Este registro define una o más curvas de Bézier. Las curvas se dibujan usando la pluma actual. |
| EMR_POLYBEZIERTO | Este registro define una o más curvas de Bézier basadas en la posición actual. |
| EMR_POLYBEZIERTO16 | Este registro define una o más curvas de Bézier basadas en la posición actual. |
| EMR_POLYDRAW | Este registro define un conjunto de segmentos de línea y curvas de Bézier. |
| EMR_POLYDRAW16 | Este registro define un conjunto de segmentos de línea y curvas de Bézier. |
| EMR_POLYGON | Este registro define un polígono compuesto por dos o más vértices conectados por rectas <br/>            líneas. El polígono se delinea utilizando la pluma actual y se rellena utilizando el pincel actual <br/>            y el modo de relleno de polígonos. El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero. |
| EMR_POLYGON16 | Este registro define un polígono compuesto por dos o más vértices conectados por líneas rectas. <br/>            El polígono se delinea utilizando la pluma actual y se rellena utilizando el pincel actual y el modo de relleno de polígonos. El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero. |
| EMR_POLYLINE | Este registro define una serie de segmentos de línea conectando los puntos en la <br/>            matriz especificada. |
| EMR_POLYLINE16 | Este registro define una serie de segmentos de línea conectando los puntos en la matriz especificada. |
| EMR_POLYLINETO | Este registro define una o más líneas rectas basadas en la posición actual. <br/>            Se dibuja una línea desde la posición actual hasta el primer punto especificado por el campo points <br/>            utilizando la pluma actual. Para cada línea adicional, el dibujo se realiza desde el punto final <br/>            de la línea anterior hasta el siguiente punto especificado por points. |
| EMR_POLYLINETO16 | Este registro define una o más líneas rectas basadas en la posición actual.<br/>             Se dibuja una línea desde la posición actual hasta el primer punto especificado por el campo Points <br/>            utilizando la pluma actual. Para cada línea adicional, el dibujo se realiza desde el <br/>            punto final de la línea anterior hasta el siguiente punto especificado por Points. |
| EMR_POLYPOLYGON | Este registro define una serie de polígonos cerrados. Cada polígono se delinea utilizando la <br/>            pluma actual y se rellena utilizando el pincel actual y el modo de relleno de polígonos. Los polígonos definidos por este registro pueden superponerse. |
| EMR_POLYPOLYGON16 | Este registro define una serie de polígonos cerrados. Cada polígono se delinea utilizando <br/>            la pluma actual y se rellena utilizando el pincel actual y el modo de relleno de polígonos. Los polígonos<br/>             especificados por este registro pueden superponerse. |
| EMR_POLYPOLYLINE | Este registro define múltiples series de segmentos de línea conectados. Los segmentos de línea son <br/>            dibujados utilizando la pluma actual. Las figuras formadas por los segmentos no se rellenan. L<br/>            a posición actual no se usa ni se actualiza con este registro. |
| EMR_POLYPOLYLINE16 | Este registro define múltiples series de segmentos de línea conectados. |
| EMR_POLYTEXTOUTA | Este registro dibuja una o más cadenas de texto ASCII utilizando la fuente actual y los colores de texto.<br/>             Nota EMR_POLYTEXTOUTA DEBE ser emulado con una serie de registros EMR_EXTTEXTOUTW, uno por cadena |
| EMR_POLYTEXTOUTW | Este registro dibuja una o más cadenas de texto Unicode utilizando la fuente actual y los colores de texto.<br/>            Nota EMR_POLYTEXTOUTW DEBE ser emulado con una serie de registros EMR_EXTTEXTOUTW, uno por cadena |
| EMR_REALIZEPALETTE | Este registro asigna entradas de la paleta lógica actual a la paleta del sistema. |
| EMR_RECTANGLE | Este registro define un rectángulo. El rectángulo se delimita usando la pluma actual <br/>            y se rellena usando el pincel actual. |
| EMR_RESIZEPALETTE | Este registro aumenta o disminuye el tamaño de una paleta lógica. |
| EMR_RESTOREDC | Este registro restaura el contexto del dispositivo de reproducción al estado guardado especificado. <br/>            El contexto del dispositivo de reproducción se restaura extrayendo la información de estado de una pila de <br/>            contextos de dispositivo guardados creados por registros EMR_SAVEDC anteriores (sección 2.3.11). |
| EMR_ROUNDRECT | Este registro define un rectángulo con esquinas redondeadas. El rectángulo se delimita <br/>            usando la pluma actual y se rellena usando el pincel actual. |
| EMR_SAVEDC | Este registro guarda el estado actual del contexto del dispositivo de reproducción copiando datos <br/>            que describen los objetos seleccionados y los modos gráficos—incluyendo el mapa de bits, el pincel, la paleta, <br/>            la fuente, la pluma, la región, el modo de dibujo y el modo de mapeo a una pila de contextos de dispositivo guardados. |
| EMR_SCALEVIEWPORTEXTEX | Este registro redefine la ventana de visualización para el contexto del dispositivo de reproducción usando las proporciones <br/>            formadas por los multiplicadores y divisores especificados. |
| EMR_SCALEWINDOWEXTEX | Este registro redefine la ventana para el contexto del dispositivo de reproducción usando las proporciones formadas <br/>            por los multiplicadores y divisores especificados. |
| EMR_SELECTCLIPPATH | Este registro define la ruta actual como una región de recorte para el contexto del dispositivo de reproducción <br/>            combinando la nueva región con cualquier región de recorte existente usando el modo especificado. |
| EMR_SELECTOBJECT | Este registro agrega un objeto al contexto del dispositivo de reproducción, identificándolo por su <br/>            índice en la tabla de objetos EMF (sección 3.1.1.1). |
| EMR_SELECTPALETTE | Este registro agrega un objeto LogPalette (sección 2.2.17) al contexto del dispositivo de reproducción <br/>            identificándolo por su índice en la tabla de objetos EMF. |
| EMR_SETARCDIRECTION | Este registro define la dirección de dibujo que se usará para operaciones de arco y rectángulo<br/>             . |
| EMR_SETBKCOLOR | Este registro define el color de fondo. |
| EMR_SETBKMODE | Este registro define el modo de mezcla de fondo del contexto del dispositivo de reproducción. El modo de mezcla de fondo<br/>             se utiliza con texto, pinceles tramados y estilos de lápiz que no son líneas sólidas. |
| EMR_SETBRUSHORGEX | Este registro define el origen del pincel actual. |
| EMR_SETCOLORADJUSTMENT | Este registro define los valores de ajuste de color para el contexto del dispositivo de reproducción utilizando los valores especificados. |
| EMR_SETCOLORSPACE | Este registro define el objeto de espacio de color lógico actual para operaciones gráficas. |
| EMR_SETDIBITSTODEVICE | Este registro especifica una transferencia de bloque de píxeles desde líneas de escaneo especificadas de un mapa de bits de origen<br/>             a un rectángulo de destino. |
| EMR_SETICMMODE | Este registro especifica el modo de Gestión de Color de Imagen (ICM) para operaciones gráficas. |
| EMR_SETICMPROFILEA | Este registro especifica un perfil de color en un archivo con un nombre compuesto por caracteres ASCII,<br/>             para la salida gráfica. |
| EMR_SETICMPROFILEW | Este registro especifica un perfil de color en un archivo con un nombre compuesto por caracteres Unicode,<br/>             para la salida gráfica |
| EMR_SETLAYOUT | Este registro especifica el orden en que se dibujan el texto y los gráficos |
| EMR_SETLINKEDUFIS | Este registro establece los UniversalFontIds de fuentes vinculadas para usar durante la búsqueda de caracteres. |
| EMR_SETMAPMODE | Este registro define el modo de mapeo del contexto del dispositivo de reproducción. El modo de mapeo<br/>             define la unidad de medida utilizada para transformar unidades del espacio de página en unidades del espacio del dispositivo,<br/>             y también define la orientación del eje x y del eje y del dispositivo. |
| EMR_SETMAPPERFLAGS | Este registro especifica los parámetros del proceso de emparejamiento de fuentes lógicas con fuentes físicas <br/>            , que es realizado por el asignador de fuentes. |
| EMR_SETMETARGN | Este registro intersecta la región de recorte actual del contexto del dispositivo de reproducción con la <br/>            región meta actual y guarda la región combinada como la nueva región meta. La región de recorte se restablece a una región nula. |
| EMR_SETMITERLIMIT | Este registro define el límite para la longitud de las uniones de inglete para la reproducción <br/>            contexto de dispositivo. |
| EMR_SETPALETTEENTRIES | Este registro define los valores de color RGB (rojo-verde-azul) en un rango de entradas <br/>            en un objeto LogPalette. |
| EMR_SETPIXELV | Este registro define el color del píxel en las coordenadas lógicas especificadas. |
| EMR_SETPOLYFILLMODE | Este registro define el modo de relleno del polígono. |
| EMR_SETROP2 | Este registro define el modo de operación raster binaria. |
| EMR_SETSTRETCHBLTMODE | Este registro define el modo de estiramiento del mapa de bits. |
| EMR_SETTEXTALIGN | Este registro define la alineación del texto. |
| EMR_SETTEXTCOLOR | Este registro define el color actual del texto. |
| EMR_SETTEXTJUSTIFICATION | Este registro especifica la cantidad de espacio adicional que se debe agregar a los caracteres de salto para la justificación <br/>             propósitos. |
| EMR_SETVIEWPORTEXTEX | Este registro define la extensión de la ventana de vista. |
| EMR_SETVIEWPORTORGEX | Este registro define el origen de la ventana de vista. |
| EMR_SETWINDOWEXTEX | Este registro define la extensión de la ventana. |
| EMR_SETWINDOWORGEX | Este registro define el origen de la ventana. |
| EMR_SETWORLDTRANSFORM | Este registro define una transformación lineal bidimensional entre el espacio mundial y <br/>            el espacio de página (para más información, consulte [MSDN-WRLDPGSPC]) para el contexto del dispositivo de reproducción. <br/>            Esta transformación puede usarse para escalar, rotar, sesgar o trasladar la salida gráfica. |
| EMR_SMALLTEXTOUT | Este registro genera una cadena. |
| EMR_STRETCHBLT | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits fuente a un <br/>             rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster<br/>             especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario. |
| EMR_STRETCHDIBITS | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits fuente a un <br/>            rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación raster <br/>            especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario. |
| EMR_STROKEANDFILLPATH | Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta usando <br/>            la pluma actual, y rellena su interior usando el pincel actual. |
| EMR_STROKEPATH | Este registro renderiza la ruta especificada usando la pluma actual. |
| EMR_TRANSPARENTBLT | Este registro especifica una transferencia de bloque de píxeles desde un mapa de bits fuente a un rectángulo de destino,<br/>             tratando un color especificado como transparente, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario. |
| EMR_WIDENPATH | Este registro redefine la ruta actual como el área que se pintaría si la ruta <br/>            se trazara usando la pluma actualmente seleccionada en el contexto del dispositivo de reproducción. |
