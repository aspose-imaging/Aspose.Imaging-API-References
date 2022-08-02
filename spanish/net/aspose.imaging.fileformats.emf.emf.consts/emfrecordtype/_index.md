---
title: EmfRecordType
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración RecordType define valores que identifican de forma exclusiva los registros EMF. Estos valores se proporcionan en el campo Tipo de cada registro.
type: docs
weight: 2820
url: /es/net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

La enumeración RecordType define valores que identifican de forma exclusiva los registros EMF. Estos valores se proporcionan en el campo Tipo de cada registro.

```csharp
public enum EmfRecordType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| EMR_HEADER | `1` | Este registro define el inicio del metarchivo y especifica sus características; su contenido, incluidas las dimensiones de la imagen incrustada; el número de registros en el metarchivo; y la resolución del dispositivo en el que se creó la imagen incrustada. Estos valores hacen posible que el metarchivo sea independiente del dispositivo. |
| EMR_POLYBEZIER | `2` | Este registro define una o más curvas Bezier. Las curvas de Bézier cúbicas se definen utilizando puntos finales y puntos de control especificados, y se trazan con la pluma actual. |
| EMR_POLYGON | `3` | Este registro define un polígono que consta de dos o más vértices conectados por líneas rectas . El polígono se delinea con el lápiz actual y se rellena con el pincel actual y el modo de relleno de polígono. El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero. |
| EMR_POLYLINE | `4` | Este registro define una serie de segmentos de línea al conectar los puntos en la matriz especificada. |
| EMR_POLYBEZIERTO | `5` | Este registro define una o más curvas Bezier basadas en la posición actual. |
| EMR_POLYLINETO | `6` | Este registro define una o más líneas rectas según la posición actual. Se dibuja una línea desde la posición actual hasta el primer punto especificado por el campo de puntos usando la pluma actual. Para cada línea adicional, el dibujo se realiza desde el punto final de la línea anterior hasta el siguiente punto especificado por puntos. |
| EMR_POLYPOLYLINE | `7` | Este registro define varias series de segmentos de línea conectados. Los segmentos de línea se dibujan con la pluma actual. Las figuras formadas por los segmentos no se rellenan. T Este registro no utiliza ni actualiza la posición actual. |
| EMR_POLYPOLYGON | `8` | Este registro define una serie de polígonos cerrados. Cada polígono se delinea con el lápiz actual y se rellena con el pincel actual y el modo de relleno de polígonos. Los polígonos definidos por este registro pueden superponerse. |
| EMR_SETWINDOWEXTEX | `9` | Este registro define la extensión de la ventana. |
| EMR_SETWINDOWORGEX | `10` | Este registro define el origen de la ventana. |
| EMR_SETVIEWPORTEXTEX | `11` | Este registro define la extensión de la ventana gráfica. |
| EMR_SETVIEWPORTORGEX | `12` | Este registro define el origen de la vista. |
| EMR_SETBRUSHORGEX | `13` | Este registro define el origen del pincel actual. |
| EMR_EOF | `14` | Este registro indica el final del metarchivo. |
| EMR_SETPIXELV | `15` | Este registro define el color del píxel en las coordenadas lógicas especificadas. |
| EMR_SETMAPPERFLAGS | `16` | Este registro especifica los parámetros del proceso de coincidencia de fuentes lógicas con fuentes físicas , que realiza el mapeador de fuentes. |
| EMR_SETMAPMODE | `17` | Este registro define el modo de mapeo del contexto del dispositivo de reproducción. El modo de mapeo define la unidad de medida utilizada para transformar unidades de espacio de página en unidades de espacio de dispositivo, y también define la orientación del eje x y el eje y del dispositivo. |
| EMR_SETBKMODE | `18` | Este registro define el modo de mezcla de fondo del contexto del dispositivo de reproducción. El modo background mix se usa con texto, pinceles sombreados y estilos de pluma que no son líneas sólidas. |
| EMR_SETPOLYFILLMODE | `19` | Este registro define el modo de relleno de polígonos. |
| EMR_SETROP2 | `20` | Este registro define el modo de operación de ráster binario. |
| EMR_SETSTRETCHBLTMODE | `21` | Este registro define el modo de extensión de mapa de bits. |
| EMR_SETTEXTALIGN | `22` | Este registro define la alineación del texto. |
| EMR_SETCOLORADJUSTMENT | `23` | Este registro define los valores de ajuste de color para el contexto del dispositivo de reproducción utilizando los valores especificados. |
| EMR_SETTEXTCOLOR | `24` | Este registro define el color del texto actual. |
| EMR_SETBKCOLOR | `25` | Este registro define el color de fondo. |
| EMR_OFFSETCLIPRGN | `26` | Este registro redefine la región de recorte del contexto del dispositivo de reproducción por los desplazamientos especificados. |
| EMR_MOVETOEX | `27` | Este registro define las coordenadas de la nueva posición actual, en unidades lógicas. |
| EMR_SETMETARGN | `28` | Este registro cruza la región de recorte actual para el contexto del dispositivo de reproducción con la metaregión actual y guarda la región combinada como la nueva metaregión. La región de recorte se restablece a una región nula. |
| EMR_EXCLUDECLIPRECT | `29` | Este registro define una nueva región de recorte que consta de la región de recorte existente menos el rectángulo especificado. |
| EMR_INTERSECTCLIPRECT | `30` | Este registro define una nueva región de recorte desde la intersección de la región de recorte actual y el rectángulo especificado. |
| EMR_SCALEVIEWPORTEXTEX | `31` | Este registro redefine la ventana gráfica para el contexto del dispositivo de reproducción utilizando las proporciones formadas por los multiplicandos y divisores especificados. |
| EMR_SCALEWINDOWEXTEX | `32` | Este registro redefine la ventana para el contexto del dispositivo de reproducción utilizando las proporciones formadas por los multiplicandos y divisores especificados. |
| EMR_SAVEDC | `33` | Este registro guarda el estado actual del contexto del dispositivo de reproducción copiando los datos que describen los objetos seleccionados y los modos gráficos (incluidos el mapa de bits, el pincel, la paleta, la fuente , la pluma, la región, el modo de dibujo y el modo de asignación) en una pila de archivos guardados. contextos del dispositivo. |
| EMR_RESTOREDC | `34` | Este registro restaura el contexto del dispositivo de reproducción al estado guardado especificado. El contexto del dispositivo de reproducción se restaura extrayendo información de estado de una pila de contextos de dispositivo guardados creados por registros EMR_SAVEDC anteriores (sección 2.3.11). |
| EMR_SETWORLDTRANSFORM | `35` | Este registro define una transformación lineal bidimensional entre el espacio mundial y el espacio de página (para obtener más información, consulte [MSDN-WRLDPGSPC]) para el contexto del dispositivo de reproducción. Esta transformación se puede usar para escalar, rotar, distorsionar o traducir la salida de gráficos. |
| EMR_MODIFYWORLDTRANSFORM | `36` | Este registro redefine la transformación mundial para el contexto del dispositivo de reproducción usando el modo especificado. |
| EMR_SELECTOBJECT | `37` | Este registro agrega un objeto al contexto del dispositivo de reproducción, identificándolo por su índice en la Tabla de Objetos EMF (sección 3.1.1.1). |
| EMR_CREATEPEN | `38` | Este registro define una pluma lógica que tiene el estilo, el ancho y el color especificados. El lápiz puede seleccionarse posteriormente en el contexto del dispositivo de reproducción y utilizarse para dibujar líneas y curvas. |
| EMR_CREATEBRUSHINDIRECT | `39` | Este registro define un pincel lógico para el relleno de figuras en operaciones gráficas. |
| EMR_DELETEOBJECT | `40` | Este registro elimina un objeto gráfico, borrando su índice en la tabla de objetos EMF. Si el objeto eliminado se selecciona en el contexto del dispositivo de reproducción, DEBE restaurarse el objeto predeterminado para esa propiedad de contexto. |
| EMR_ANGLEARC | `41` | Este registro define un segmento de línea de un arco. El segmento de línea se dibuja desde la posición actual hasta el comienzo del arco. El arco se dibuja a lo largo del perímetro de un círculo con el radio y el centro dados. La longitud del arco está definida por los ángulos de inicio y barrido dados. |
| EMR_ELLIPSE | `42` | Este registro define una elipse. El centro de la elipse es el centro del rectángulo delimitador especificado . La elipse se perfila con el lápiz actual y se rellena con el pincel actual. |
| EMR_RECTANGLE | `43` | Este registro define un rectángulo. El rectángulo se delinea con el bolígrafo actual y se rellena con el pincel actual. |
| EMR_ROUNDRECT | `44` | Este registro define un rectángulo con esquinas redondeadas. El rectángulo se delinea con el lápiz actual y se rellena con el pincel actual. |
| EMR_ARC | `45` | Este registro define un arco elíptico. |
| EMR_CHORD | `46` | Este registro define una cuerda (una región limitada por la intersección de una elipse y un segmento de línea, llamado secante). El acorde se delinea con el bolígrafo actual y se rellena con el pincel actual. |
| EMR_PIE | `47` | Este registro define una cuña en forma de pastel delimitada por la intersección de una elipse y dos radiales. El gráfico circular se delinea con el lápiz actual y se rellena con el pincel actual. |
| EMR_SELECTPALETTE | `48` | Este registro agrega un objeto LogPalette (sección 2.2.17) al contexto del dispositivo de reproducción , identificándolo por su índice en la tabla de objetos EMF. |
| EMR_CREATEPALETTE | `49` | Este registro define un objeto LogPalette. |
| EMR_SETPALETTEENTRIES | `50` | Este registro define valores de color RGB (rojo-verde-azul) en un rango de entradas en un objeto LogPalette. |
| EMR_RESIZEPALETTE | `51` | Este registro aumenta o disminuye el tamaño de una paleta lógica. |
| EMR_REALIZEPALETTE | `52` | Este registro asigna entradas de la paleta lógica actual a la paleta del sistema. |
| EMR_EXTFLOODFILL | `53` | Este registro llena un área de la superficie de visualización con el pincel actual. |
| EMR_LINETO | `54` | Este registro define una línea desde la posición actual hasta, pero sin incluir, el punto especificado. Restablece la posición actual al punto especificado. |
| EMR_ARCTO | `55` | Este registro define un arco elíptico. Restablece la posición actual al punto final del arco. |
| EMR_POLYDRAW | `56` | Este registro define un conjunto de segmentos de línea y curvas Bezier. |
| EMR_SETARCDIRECTION | `57` | Este registro define la dirección de dibujo que se utilizará para las operaciones de arco y rectángulo . |
| EMR_SETMITERLIMIT | `58` | Este registro define el límite para la longitud de las uniones en inglete para el contexto del dispositivo de reproducción . |
| EMR_BEGINPATH | `59` | Este registro abre un corchete de ruta en el contexto del dispositivo de reproducción. |
| EMR_ENDPATH | `60` | Este registro cierra un corchete de ruta y selecciona la ruta definida por el corchete en el contexto del dispositivo de reproducción. |
| EMR_CLOSEFIGURE | `61` | Este registro cierra una figura abierta en un camino. |
| EMR_FILLPATH | `62` | Este registro cierra cualquier figura abierta en la ruta actual y rellena el interior de la ruta utilizando el pincel actual y el modo de relleno de polígonos. |
| EMR_STROKEANDFILLPATH | `63` | Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta por con el lápiz actual y rellena su interior con el pincel actual. |
| EMR_STROKEPATH | `64` | Este registro representa la ruta especificada usando la pluma actual. |
| EMR_FLATTENPATH | `65` | Este registro transforma cualquier curva de la ruta seleccionada en el contexto del dispositivo de reproducción , convirtiendo cada curva en una secuencia de líneas. |
| EMR_WIDENPATH | `66` | Este registro redefine la ruta actual como el área que se pintaría si la ruta se trazara con el lápiz actualmente seleccionado en el contexto del dispositivo de reproducción. |
| EMR_SELECTCLIPPATH | `67` | Este registro define la ruta actual como una región de recorte para el contexto del dispositivo de reproducción , combinando la nueva región con cualquier región de recorte existente utilizando el modo especificado. |
| EMR_ABORTPATH | `68` | Este registro aborta un corchete de ruta o descarta la ruta de un corchete de ruta cerrado. |
| EMR_COMMENT | `70` | Este registro especifica datos privados arbitrarios. |
| EMR_FILLRGN | `71` | Este registro llena la región especificada usando el pincel especificado. |
| EMR_FRAMERGN | `72` | Este registro dibuja un borde alrededor de la región especificada usando el pincel especificado. |
| EMR_INVERTRGN | `73` | Este registro invierte los colores en la región especificada. |
| EMR_PAINTRGN | `74` | Este registro pinta la región especificada utilizando el pincel actualmente seleccionado en el contexto del dispositivo de reproducción. |
| EMR_EXTSELECTCLIPRGN | `75` | Este registro combina la región especificada con la región de clip actual usando el modo especificado. |
| EMR_BITBLT | `76` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, según una operación de trama específica. |
| EMR_STRETCHBLT | `77` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario. |
| EMR_MASKBLT | `78` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel y con la aplicación de un mapa de bits de máscara de color , según las operaciones de trama de primer plano y de fondo especificadas. |
| EMR_PLGBLT | `79` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un paralelogramo de destino, con la aplicación de un mapa de bits de máscara de color. |
| EMR_SETDIBITSTODEVICE | `80` | Este registro especifica una transferencia en bloque de píxeles desde líneas de escaneo especificadas de un mapa de bits source a un rectángulo de destino. |
| EMR_STRETCHDIBITS | `81` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, según una operación de trama específica, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario . |
| EMR_EXTCREATEFONTINDIRECTW | `82` | Este registro define una fuente lógica que tiene las características especificadas. La fuente se puede seleccionar posteriormente como la fuente actual para el contexto del dispositivo de reproducción. |
| EMR_EXTTEXTOUTA | `83` | Este registro dibuja una cadena de texto ASCII utilizando la fuente y los colores de texto actuales. Nota EMR_EXTTEXTOUTA DEBE emularse con un registro EMR_EXTTEXTOUTW (sección 2.3.5.8). Esto requiere que la cadena de texto ASCII en el objeto EmrText se convierta a la codificación Unicode UTF16-LE. |
| EMR_EXTTEXTOUTW | `84` | Este registro dibuja una cadena de texto Unicode utilizando la fuente y los colores de texto actuales. |
| EMR_POLYBEZIER16 | `85` | Este registro define una o más curvas Bezier. Las curvas se dibujan con el lápiz actual. |
| EMR_POLYGON16 | `86` | Este registro define un polígono que consta de dos o más vértices conectados por líneas rectas. El polígono se delinea con el lápiz actual y se rellena con el pincel actual y el modo de relleno del polígono . El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero. |
| EMR_POLYLINE16 | `87` | Este registro define una serie de segmentos de línea conectando los puntos en la matriz especificada. |
| EMR_POLYBEZIERTO16 | `88` | Este registro define una o más curvas Bezier basadas en la posición actual. |
| EMR_POLYLINETO16 | `89` | Este registro define una o más líneas rectas basadas en la posición actual. Se dibuja una línea desde la posición actual hasta el primer punto especificado por el campo Puntos usando la pluma actual. Para cada línea adicional, el dibujo se realiza desde el punto final de la línea anterior hasta el siguiente punto especificado por Puntos. |
| EMR_POLYPOLYLINE16 | `90` | Este registro define varias series de segmentos de línea conectados. |
| EMR_POLYPOLYGON16 | `91` | Este registro define una serie de polígonos cerrados. Cada polígono se delinea usando la pluma actual y se rellena usando el pincel actual y el modo de relleno de polígono. Los polígonos especificados por este registro pueden superponerse. |
| EMR_POLYDRAW16 | `92` | Este registro define un conjunto de segmentos de línea y curvas Bezier. |
| EMR_CREATEMONOBRUSH | `93` | Este registro define un pincel lógico con el patrón de mapa de bits especificado. El mapa de bits puede ser un mapa de bits de sección de mapa de bits independiente del dispositivo (DIB) o puede ser un mapa de bits dependiente del dispositivo. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | Este registro define un pincel lógico que tiene el patrón especificado por el DIB. |
| EMR_EXTCREATEPEN | `95` | Este registro define una pluma cosmética o geométrica lógica que tiene el estilo especificado, ancho y atributos de pincel. |
| EMR_POLYTEXTOUTA | `96` | Este registro dibuja una o más cadenas de texto ASCII utilizando la fuente y los colores de texto actuales. Nota EMR_POLYTEXTOUTA DEBE emularse con una serie de registros EMR_EXTTEXTOUTW, uno por cadena |
| EMR_POLYTEXTOUTW | `97` | Este registro dibuja una o más cadenas de texto Unicode utilizando la fuente y los colores de texto actuales. Nota EMR_POLYTEXTOUTW DEBE emularse con una serie de registros EMR_EXTTEXTOUTW, uno por cadena |
| EMR_SETICMMODE | `98` | Este registro especifica el modo de gestión del color de la imagen (ICM) para operaciones gráficas. |
| EMR_CREATECOLORSPACE | `99` | Este registro crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre que consta de caracteres ASCII |
| EMR_SETCOLORSPACE | `100` | Este registro define el objeto de espacio de color lógico actual para operaciones gráficas. |
| EMR_DELETECOLORSPACE | `101` | Este registro elimina un objeto de espacio de color lógico. Nota Un registro EMR_DELETEOBJECT DEBE usarse en lugar de EMR_DELETECOLORSPACE para eliminar un objeto de espacio de color lógico |
| EMR_GLSRECORD | `102` | Este registro especifica una función OpenGL. |
| EMR_GLSBOUNDEDRECORD | `103` | Este registro especifica una función OpenGL con un rectángulo delimitador para la salida. |
| EMR_PIXELFORMAT | `104` | Este registro especifica el formato de píxel que se utilizará para operaciones gráficas |
| EMR_DRAWESCAPE | `105` | Este registro pasa información arbitraria al controlador. La intención es que la información dé como resultado que se realice el dibujo. |
| EMR_EXTESCAPE | `106` | Este registro pasa información arbitraria al controlador. La intención es que la información no resulte en que se realice el dibujo. |
| EMR_SMALLTEXTOUT | `108` | Este registro genera una cadena. |
| EMR_FORCEUFIMAPPING | `109` | Este registro obliga al mapeador de fuentes a hacer coincidir las fuentes en función de su UniversalFontId en preferencia a su información LogFont. |
| EMR_NAMEDESCAPE | `110` | Este registro pasa información arbitraria al controlador con nombre dado. |
| EMR_COLORCORRECTPALETTE | `111` | Este registro especifica cómo corregir las entradas de un objeto de paleta lógica usando Windows Sistema de color (WCS) 1.0 valores |
| EMR_SETICMPROFILEA | `112` | Este registro especifica un perfil de color en un archivo con un nombre que consta de caracteres ASCII, para salida de gráficos. |
| EMR_SETICMPROFILEW | `113` | Este registro especifica un perfil de color en un archivo con un nombre que consta de caracteres Unicode, para salida de gráficos |
| EMR_ALPHABLEND | `114` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, incluidos los datos de transparencia alfa, de acuerdo con una operación de fusión especificada. |
| EMR_SETLAYOUT | `115` | Este registro especifica el orden en que se dibujan el texto y los gráficos |
| EMR_TRANSPARENTBLT | `116` | Este registro especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, tratando un color específico como transparente, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario |
| EMR_GRADIENTFILL | `118` | Este registro especifica el relleno de rectángulos o triángulos con degradados de color |
| EMR_SETLINKEDUFIS | `119` | Este registro establece los UniversalFontIds de las fuentes vinculadas para usar durante la búsqueda de caracteres. |
| EMR_SETTEXTJUSTIFICATION | `120` | Este registro especifica la cantidad de espacio adicional que se agregará a los caracteres de separación para fines de justificación . |
| EMR_COLORMATCHTOTARGETW | `121` | Este registro especifica si se realiza la coincidencia de color con un perfil de color que se especifica en un archivo con un nombre que consta de caracteres Unicode. |
| EMR_CREATECOLORSPACEW | `122` | Este registro crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre que consta de caracteres Unicode |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
