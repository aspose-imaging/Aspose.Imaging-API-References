---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El espacio de nombres contiene tipos MS-EMF Formato de metarchivo mejorado. 2.3 Registros EMF
type: docs
weight: 360
url: /es/aspose.imaging.fileformats.emf.emf.records/
---
El espacio de nombres contiene tipos [MS-EMF]: Formato de metarchivo mejorado. 2.3 Registros EMF

## Clases

| Clase | Descripción |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | Este registro aborta un corchete de ruta o descarta la ruta de un corchete de ruta cerrado. |
| [EmfAlphaBlend](./emfalphablend) | El registro EMR_ALPHABLEND especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , incluidos los datos de transparencia alfa, de acuerdo con una operación de fusión especificada. |
| [EmfAngleArc](./emfanglearc) | El registro EMR_ANGLEARC especifica un segmento de línea de un arco. El segmento de línea se dibuja desde la posición actual hasta el comienzo del arco. El arco se dibuja a lo largo del perímetro de un círculo con el radio y el centro dados . La longitud del arco está definida por los ángulos de inicio y barrido dados |
| [EmfArc](./emfarc) | El registro EMR_ARC especifica un arco elíptico. |
| [EmfArcTo](./emfarcto) | El registro EMR_ARCTO especifica un arco elíptico. Restablece la posición actual al punto final del arco. |
| [EmfBeginPath](./emfbeginpath) | Este registro abre un corchete de ruta en el contexto del dispositivo de reproducción actual. Después de abrir un corchete de ruta, una aplicación puede comenzar a procesar registros para definir los puntos que se encuentran en la ruta. Una aplicación DEBE cerrar un corchete de ruta abierto procesando EMR_ENDPATH record. Cuando una aplicación procesa el registro EMR_BEGINPATH, todas las rutas anteriores DEBEN descartarse del contexto del dispositivo de reproducción. |
| [EmfBitBlt](./emfbitblt) | El registro EMR_BITBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, según una operación de trama especificada. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | Los tipos de registro de mapa de bits realizan transferencias en bloque de imágenes de mapa de bits. |
| [EmfChord](./emfchord) | El registro EMR_CHORD especifica una cuerda, que es una región delimitada por la intersección de una elipse y un segmento de línea, llamado secante. El acorde se delinea con el lápiz actual y se rellena con el pincel actual. |
| [EmfClippingRecordType](./emfclippingrecordtype) | Los tipos de registro de recorte especifican y administran regiones de recorte. Nota El registro EMR_SETMETARGN no especifica parámetros. |
| [EmfCloseFigure](./emfclosefigure) | Este registro cierra una figura abierta en una ruta. El procesamiento del registro EMR_CLOSEFIGURE DEBE cerrar la figura dibujando una línea desde la posición actual hasta el primer punto de la figura, y luego DEBE conectar las líneas usando el estilo de unión de líneas. Si una figura se cierra al procesar el registro EMR_LINETO en lugar del registro EMR_CLOSEFIGURE, las tapas finales se usan para crear la esquina en lugar de una unión. EMR_LINETO se especifica en la sección 2.3.5.13. El registro EMR_CLOSEFIGURE solo DEBE usarse si hay un ruta abierta corchete en el contexto del dispositivo de reproducción. Una figura en una ruta está abierta a menos que se cierre explícitamente al procesar este registro. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | El registro EMR_COLORCORRECTPALETTE especifica cómo corregir las entradas de un objeto lógico palette usando valores WCS 1.0. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | El registro EMR_COLORMATCHTOTargetW especifica si se realiza la coincidencia de color con un perfil de color que se especifica en un archivo con un nombre que consta de caracteres Unicode. |
| [EmfComment](./emfcomment) | El registro EMR_COMMENT contiene datos privados arbitrarios. Nota Los campos que no se describen en esta sección se especifican en la sección 2.3.3. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | El registro EMR_COMMENT_BEGINGROUP especifica el comienzo de un grupo de registros de dibujo. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | El registro EMR_COMMENT_EMFPLUS contiene registros EMF+ incrustados. Nota Los campos que no se describen en esta sección se especifican en la sección 2.3.3. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | El registro EMR_COMMENT_EMFSPOOL contiene registros EMFSPOOL incrustados. Nota Los campos que no se describen en esta sección se especifican en la sección 2.3.3. |
| [EmfCommentEndGroup](./emfcommentendgroup) | El registro EMR_COMMENT_ENDGROUP especifica el final de un grupo de registros de dibujo. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | El registro EMR_COMMENT_MULTIFORMATS especifica una imagen en varios formatos gráficos. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | Los tipos de registro EMR_COMMENT_PUBLIC especifican extensiones para el procesamiento de EMF. |
| [EmfCommentRecordType](./emfcommentrecordtype) | Los tipos de registro de comentarios definen formatos para especificar datos privados arbitrarios, incrustar registros en otros formatos de metarchivo y agregar comandos nuevos o de propósito especial. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | El registro EMR_COMMENT_WINDOWS_METAFILE especifica una imagen en un metarchivo WMF incrustado. |
| [EmfControlRecordType](./emfcontrolrecordtype) | Los tipos de registros de control definen el inicio y el final de un metarchivo EMF y las propiedades del metarchivo. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | El registro EMR_CREATEBRUSHINDIRECT define un pincel lógico para operaciones gráficas. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | El registro EMR_CREATECOLORSPACE crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre que consta de caracteres ASCII. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | El registro EMR_CREATECOLORSPACEW crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres Unicode. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | El registro EMR_CREATEDIBPATTERNBRUSHPT define un pincel de motivo para operaciones gráficas. El patrón está especificado por un DIB. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | El registro EMR_CREATEMONOBRUSH define un pincel de motivo monocromático para operaciones gráficas. El motivo se especifica mediante un DIB monocromático. |
| [EmfCreatePalette](./emfcreatepalette) | El registro EMR_CREATEPALETTE define una paleta lógica para operaciones gráficas. |
| [EmfCreatePen](./emfcreatepen) | El registro EMR_CREATEPEN define una pluma lógica para operaciones gráficas. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | El registro EMR_DELETECOLORSPACE elimina un objeto de espacio de color lógico. |
| [EmfDeleteObject](./emfdeleteobject) | El registro EMR_DELETEOBJECT elimina un objeto gráfico, que se especifica por su índice en la tabla de objetos EMF (sección 3.1.1.1). |
| [EmfDrawEscape](./emfdrawescape) | El registro EMR_DRAWESCAPE pasa información arbitraria a un controlador de impresora. La intención es que la información dé como resultado que se realice el dibujo. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | Los tipos de registro de dibujo realizan dibujo de gráficos. |
| [EmfEllipse](./emfellipse) | El registro EMR_ELLIPSE especifica una elipse. El centro de la elipse es el centro del rectángulo delimitador especificado. La elipse se perfila con el lápiz actual y se rellena con el pincel actual. |
| [EmfEndPath](./emfendpath) | Este registro cierra un corchete de ruta y selecciona la ruta definida por el corchete en el contexto del dispositivo de reproducción. |
| [EmfEof](./emfeof) | El registro EMR_EOF indica el final del metarchivo y especifica una paleta. |
| [EmfEscapeRecordType](./emfescaperecordtype) | Los tipos de registro de escape ejecutan funciones del controlador de impresora. |
| [EmfExcludeClipRect](./emfexcludecliprect) | El registro EMR_EXCLUDECLIPRECT especifica una nueva región de recorte que consta de la región de recorte existente menos el rectángulo especificado. Nota Los campos que no se describen en esta sección se especifican en la sección 2.3.2. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | El registro EMR_EXTCREATEFONTINDIRECTW define una fuente lógica para operaciones gráficas. |
| [EmfExtCreatePen](./emfextcreatepen) | El registro EMR_EXTCREATEPEN define una pluma lógica extendida para operaciones gráficas. Se puede especificar un DIB opcional para usar como estilo de línea. |
| [EmfExtEscape](./emfextescape) | El registro EMR_EXTESCAPE pasa información arbitraria a un controlador de impresora. La intención es que la información no resulte en que se realice el dibujo. |
| [EmfExtFloodFill](./emfextfloodfill) | El registro EMR_EXTFLOODFILL llena un área de la superficie de visualización con el pincel actual |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | El registro EMR_EXTSELECTCLIPRGN combina la región especificada con la región de clip actual usando el modo especificado. Nota Los campos que no se describen en esta sección se especifican en la sección 2.3.2. |
| [EmfExtTextOutA](./emfexttextouta) | El registro EMR_EXTTEXTOUTA dibuja una cadena de texto ASCII utilizando la fuente y los colores de texto actuales. |
| [EmfExtTextOutW](./emfexttextoutw) | El registro EMR_EXTTEXTOUTW dibuja una cadena de texto ASCII utilizando la fuente y los colores de texto actuales. |
| [EmfFillPath](./emffillpath) | El registro EMR_FILLPATH cierra cualquier figura abierta en la ruta actual y llena el interior de la ruta por usando el pincel actual y el modo de relleno de polígonos. |
| [EmfFillRgn](./emffillrgn) | El registro EMR_FILLRGN llena la región especificada usando el pincel especificado. |
| [EmfFlatternPath](./emfflatternpath) | Este registro transforma cualquier curva en la ruta seleccionada en el contexto del dispositivo de reproducción ; cada curva DEBE convertirse en una secuencia de líneas. |
| [EmfForceUfiMapping](./emfforceufimapping) | El registro EMR_FORCEUFIMAPPING obliga al mapeador de fuentes a hacer coincidir las fuentes en función de su UniversalFontId con preferencia a su información LogFont (sección 2.2.13). |
| [EmfFrameRgn](./emfframergn) | El registro EMR_FRAMERGN dibuja un borde alrededor de la región especificada usando el pincel especificado. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | El registro EMR_GLSBOUNDEDRECORD especifica una función OpenGL con un rectángulo delimitador para la salida. |
| [EmfGlsRecord](./emfglsrecord) | El registro EMR_GLSRECORD especifica una función OpenGL. |
| [EmfGradientFill](./emfgradientfill) | El registro EMR_GRADIENTFILL especifica el relleno de rectángulos o triángulos con degradados de color. |
| [EmfIntersectClipRect](./emfintersectcliprect) | El registro EMR_INTERSECTCLIPRECT especifica una nueva región de recorte desde la intersección de la región de recorte actual y el rectángulo especificado. Nota Los campos que no se describen en esta sección se especifican en la sección 2.3.2. |
| [EmfInvertRgn](./emfinvertrgn) | El registro EMR_INVERTRGN invierte los colores en la región especificada. |
| [EmfLineTo](./emflineto) | El registro EMR_LINETO especifica una línea desde la posición actual hasta, pero sin incluir, el punto especificado . Restablece la posición actual al punto especificado. |
| [EmfMaskBlt](./emfmaskblt) | El registro EMR_MASKBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel y con la aplicación de un mapa de bits de máscara de color , de acuerdo con las operaciones de trama de fondo y primer plano especificadas. |
| [EmfMetafileHeader](./emfmetafileheader) | Los tipos de registro EMR_HEADER definen los puntos de partida de los metarchivos EMF y especifican las propiedades del dispositivo en el que se creó la imagen en el metarchivo . La información en el registro de encabezado hace posible que los metarchivos EMF sean independientes de cualquier dispositivo de salida específico. El valor del campo Tamaño se puede usar para distinguir entre los diferentes tipos de registro EMR_HEADER enumerados anteriormente en esta sección. Hay tres posibles headers: El encabezado base, que es el registro EmfMetafileHeader. La parte de tamaño fijo de este encabezado es de 88 bytes y contiene un objeto Header. El primer encabezado de extensión, que es el registro EmfMetafileHeaderExtension1. El tamaño fijo parte de este encabezado tiene 100 bytes y contiene un objeto Header y un objeto HeaderExtension1 (sección 2.2.10). El segundo encabezado de extensión, que es el registro EmfMetafileHeaderExtension2. La parte de tamaño fijo de este encabezado es de 108 bytes, y contiene un objeto Header, un objeto HeaderExtension1 y un objeto HeaderExtension2 (sección 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | El registro EmfMetafileHeaderExtension1 es el registro de encabezado utilizado en la primera extensión de los metarchivos EMF. Después del campo EmfHeaderExtension1, los campos restantes son opcionales y pueden estar presentes en cualquier orden. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | El registro EmfMetafileHeaderExtension2 es el registro de encabezado utilizado en la segunda extensión de los metarchivos EMF . Después del campo EmfHeaderExtension2, los campos restantes son opcionales y pueden estar presentes en cualquier orden. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | El registro EMR_MODIFYWORLDTRANSFORM modifica el espacio mundial actual a la transformación page-space en el contexto del dispositivo de reproducción. |
| [EmfMoveToEx](./emfmovetoex) | El registro EMR_MOVETOEX especifica las coordenadas de la nueva posición actual, en unidades lógicas. |
| [EmfNamedEscape](./emfnamedescape) | El registro MR_NAMEDESCAPE pasa información arbitraria a un controlador de impresora especificado. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | Los tipos de registros de creación de objetos crean objetos gráficos. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | Los tipos de registro de manipulación de objetos gestionan y modifican objetos gráficos. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | El registro EMR_OFFSETCLIPRGN mueve la región de recorte actual en el contexto del dispositivo de reproducción según los desplazamientos especificados. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | Los tipos de registro de OpenGL especifican funciones de OpenGL. |
| [EmfPaintRgn](./emfpaintrgn) | El registro EMR_PAINTRGN pinta la región especificada utilizando el pincel actualmente seleccionado en el contexto del dispositivo de reproducción . |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | Los tipos de registro de corchete de ruta especifican y manipulan rutas en corchetes de ruta. Nota: Ninguno de los registros de corchete de ruta especifica parámetros. |
| [EmfPie](./emfpie) | El registro EMR_PIE especifica una cuña en forma de pastel delimitada por la intersección de una elipse y dos radiales . El gráfico circular se delinea con el lápiz actual y se rellena con el pincel actual. |
| [EmfPixelFormat](./emfpixelformat) | El registro EMR_PIXELFORMAT especifica el formato de píxel que se utilizará para las operaciones gráficas. |
| [EmfPlgBlt](./emfplgblt) | El registro EMR_PLGBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un paralelogramo de destino, con la aplicación de un mapa de bits de máscara de color. |
| [EmfPolyBezier](./emfpolybezier) | El registro EMR_POLYBEZIER especifica una o más curvas Bezier. |
| [EmfPolyBezier16](./emfpolybezier16) | El registro EMR_POLYBEZIER16 especifica una o más curvas Bezier. Las curvas se dibujan usando la pluma actual. |
| [EmfPolyBezierTo](./emfpolybezierto) | El registro EMR_POLYBEZIERTO especifica una o más curvas Bezier en función de la posición actual. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | El registro EMR_POLYBEZIERTO16 especifica una o más curvas Bezier en función de la posición actual. |
| [EmfPolyDraw](./emfpolydraw) | El registro EMR_POLYDRAW especifica un conjunto de segmentos de línea y curvas Bezier. |
| [EmfPolyDraw16](./emfpolydraw16) | El registro EMR_POLYDRAW16 especifica un conjunto de segmentos de línea y curvas Bezier. |
| [EmfPolygon](./emfpolygon) | El registro EMR_POLYGON especifica un polígono que consta de dos o más vértices conectados por líneas rectas. |
| [EmfPolygon16](./emfpolygon16) | El registro EMR_POLYGON16 especifica un polígono que consta de dos o más vértices conectados por líneas rectas. El polígono se delinea con el lápiz actual y se rellena con el pincel actual y el modo de relleno de polígono. El polígono se cierra automáticamente dibujando una línea desde el último vértice hasta el primero. |
| [EmfPolyline](./emfpolyline) | El registro EMR_POLYLINE especifica una serie de segmentos de línea conectando los puntos en la matriz especificada. |
| [EmfPolyline16](./emfpolyline16) | El registro EMR_POLYLINE16 especifica una serie de segmentos de línea conectando los puntos en la matriz especificada . |
| [EmfPolylineTo](./emfpolylineto) | El registro EMR_POLYLINETO especifica una o más líneas rectas según la posición actual. |
| [EmfPolylineTo16](./emfpolylineto16) | El registro EMR_POLYLINETO16 especifica una o más líneas rectas según la posición actual. Se dibuja una línea desde la posición actual hasta el primer punto especificado por el campo aPoints utilizando el lápiz actual . Para cada línea adicional, el dibujo se realiza desde el punto final de la línea anterior hasta el siguiente punto especificado por aPoints. |
| [EmfPolyPolygon](./emfpolypolygon) | El registro EMR_POLYPOLYGON especifica una serie de polígonos cerrados. |
| [EmfPolyPolygon16](./emfpolypolygon16) | El registro EMR_POLYPOLYGON16 especifica una serie de polígonos cerrados. Cada polígono se delinea con la pluma actual y se rellena con el pincel actual y el modo de relleno de polígono. Los polígonos dibujados por este registro pueden superponerse. |
| [EmfPolyPolyline](./emfpolypolyline) | El registro EMR_POLYPOLYLINE especifica varias series de segmentos de línea conectados. |
| [EmfPolyPolyline16](./emfpolypolyline16) | El registro EMR_POLYPOLYLINE16 especifica varias series de segmentos de línea conectados. |
| [EmfPolyTextOutA](./emfpolytextouta) | El registro EMR_POLYTEXTOUTA dibuja una o más cadenas de texto ASCII utilizando la fuente y los colores de texto actuales. |
| [EmfPolyTextOutW](./emfpolytextoutw) | El registro EMR_POLYTEXTOUTW dibuja una o más cadenas de texto Unicode utilizando la fuente y los colores de texto actuales. |
| [EmfRealizePalette](./emfrealizepalette) | Este registro asigna entradas de paleta del objeto LogPalette actual (sección 2.2.17) a system_palette. Este registro EMF no especifica parámetros. |
| [EmfRecord](./emfrecord) | Clase base para registros EMF Todos los registros EMF DEBEN tener una longitud que sea un múltiplo de 4 bytes. Esto se representa en las estructuras genéricas de los tipos de registros EMF anteriores al incluir campos AlignmentPadding cuando corresponda en los extremos de estas estructuras. El contenido de AlignmentPadding fields siempre DEBE ignorarse. Para abreviar, estos campos no se muestran en cada definición de registro EMF individual. |
| [EmfRectangle](./emfrectangle) | El registro EMR_RECTANGLE dibuja un rectángulo. El rectángulo se perfila con el lápiz actual y se rellena con el pincel actual. |
| [EmfResizePalette](./emfresizepalette) | El registro EMR_RESIZEPALETTE aumenta o disminuye el tamaño de un objeto LogPalette existente (sección 2.2.17). |
| [EmfRestoreDc](./emfrestoredc) | El registro EMR_RESTOREDC restaura el contexto del dispositivo de reproducción al estado especificado. El contexto del dispositivo de reproducción se restaura extrayendo información de estado de una pila creada por registros EMR_SAVEDC anteriores (sección 2.3.11). |
| [EmfRop4](./emfrop4) | Una operación de trama cuaternaria, que especifica operaciones de trama ternaria para los colores frontal y de fondo de un mapa de bits. Estos valores definen cómo se combinarán los datos de color de el rectángulo de origen con los datos de color del rectángulo de destino. |
| [EmfRoundRect](./emfroundrect) | El registro EMR_ROUNDRECT especifica un rectángulo con esquinas redondeadas. El rectángulo se delinea con el lápiz actual y se rellena con el pincel actual. |
| [EmfSaveDc](./emfsavedc) | Guarda el estado actual del contexto del dispositivo de reproducción en una pila de estados guardados por registros EMR_SAVEDC anteriores, si los hay. El estado consta de propiedades gráficas y objetos, incluidos el mapa de bits, el pincel , la paleta, la fuente, la pluma y la región seleccionados actualmente. Se utiliza un registro EMR_RESTOREDC para restaurar el estado. Este registro EMF no especifica parámetros. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | El registro EMR_SCALEVIEWPORTEXTEX vuelve a especificar la ventana gráfica para un contexto de dispositivo usando las relaciones formadas por los multiplicandos y divisores especificados. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | El registro EMR_SCALEWINDOWEXTEX vuelve a especificar la ventana para un contexto de dispositivo de reproducción por utilizando las proporciones formadas por los multiplicandos y divisores especificados. |
| [EmfSelectClipPath](./emfselectclippath) | El registro EMR_SELECTCLIPPATH especifica la ruta actual como una región de recorte para un contexto de dispositivo de reproducción , combinando la nueva región con cualquier región de recorte existente utilizando el modo especificado. |
| [EmfSelectObject](./emfselectobject) | El registro EMR_SELECTOBJECT agrega un objeto de gráficos al contexto actual del dispositivo de reproducción del metarchivo . El objeto se especifica por su índice en la tabla de objetos EMF (sección 3.1.1.1) o por su valor de la enumeración StockObject (sección 2.1.31). |
| [EmfSelectPalette](./emfselectpalette) | El registro EMR_SELECTPALETTE especifica una paleta lógica para el contexto del dispositivo de reproducción. |
| [EmfSetArcDirection](./emfsetarcdirection) | El registro EMR_SETARCDIRECTION especifica la dirección de dibujo que se usará para la salida de arco y rectángulo. |
| [EmfSetBkColor](./emfsetbkcolor) | El registro EMR_SETBKCOLOR especifica el color de fondo. |
| [EmfSetBkMode](./emfsetbkmode) | El registro EMR_SETBKMODE especifica el modo de mezcla de fondo del contexto del dispositivo de reproducción. El modo de mezcla de fondo se usa con texto, pinceles sombreados y estilos de pluma que no son líneas continuas. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | El registro EMR_SETBRUSHORGEX especifica el origen del pincel actual. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | El registro EMR_SETCOLORADJUSTMENT especifica las propiedades de ajuste de color en el contexto del dispositivo playback . |
| [EmfSetColorSpace](./emfsetcolorspace) | El registro EMR_SETCOLORSPACE define el objeto de espacio de color lógico actual para operaciones gráficas. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | El registro EMR_SETDIBITSTODEVICE especifica una transferencia en bloque de píxeles desde líneas de exploración especificadas de un mapa de bits de origen a un rectángulo de destino. |
| [EmfSetIcmMode](./emfseticmmode) | El registro EMR_SETICMMODE especifica el modo de administración de color de imagen (ICM) para operaciones gráficas. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | El registro EMR_SETICMPROFILEA especifica un perfil de color en un archivo con un nombre que consta de caracteres ASCII , para la salida de gráficos. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | El registro EMR_SETICMPROFILEW especifica un perfil de color en un archivo con un nombre que consta de caracteres Unicode, para la salida de gráficos. |
| [EmfSetLayout](./emfsetlayout) | El registro EMR_SETLAYOUT especifica el orden en que se dibujan el texto y los gráficos. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | El registro EMR_SETLINKEDUFIS establece los UniversalFontIds (sección 2.2.27) de las fuentes vinculadas para usar durante la búsqueda de caracteres. |
| [EmfSetMapMode](./emfsetmapmode) | El registro EMR_SETMAPMODE especifica el modo de asignación del contexto del dispositivo de reproducción. El modo de asignación especifica la unidad de medida utilizada para transformar las unidades de espacio de página en unidades de espacio de dispositivo, y también especifica la orientación del eje x y el eje y del dispositivo. |
| [EmfSetMapperFlags](./emfsetmapperflags) | El registro EMR_SETMAPPERFLAGS especifica los parámetros del proceso de coincidencia de fuentes lógicas con fuentes físicas, que realiza el mapeador de fuentes. |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter establece la metaregión actual con la región de recorte actual para formar una nueva metaregión para el contexto del dispositivo de reproducción. La región de recorte actual DEBERÍA restablecerse a nulo. Este registro EMF no especifica parámetros. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | El registro EMR_SETMITERLIMIT especifica el límite para la longitud de las uniones en inglete para el contexto del dispositivo de reproducción. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | El registro EMR_SETPALETTEENTRIES define valores de color RGB en un rango de entradas para un objeto LogPalette (sección 2.2.17) existente . |
| [EmfSetPixelV](./emfsetpixelv) | El registro EMR_SETPIXELV define el color del píxel en las coordenadas lógicas especificadas. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | El registro EMR_SETPOLYFILLMODE define el modo de relleno de polígonos. |
| [EmfSetRop2](./emfsetrop2) | El registro EMR_SETROP2 define un modo de operación raster binario. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | El registro EMR_SETSTRETCHBLTMODE especifica el modo de extensión de mapa de bits. |
| [EmfSetTextAlign](./emfsettextalign) | El registro EMR_SETTEXTALIGN especifica la alineación del texto. |
| [EmfSetTextColor](./emfsettextcolor) | El registro EMR_SETTEXTCOLOR define el color del texto actual. |
| [EmfSetTextJustification](./emfsettextjustification) | El registro EMR_SETTEXTJUSTIFICATION especifica la cantidad de espacio adicional para agregar a break caracteres para la justificación del texto. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | El registro EMR_SETVIEWPORTEXTEX define la extensión de la ventana gráfica. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | El registro EMR_SETVIEWPORTORGEX define el origen de la ventana gráfica. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | El registro EMR_SETWINDOWEXTEX define la extensión de la ventana. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | El registro EMR_SETWINDOWORGEX define el origen de la ventana. |
| [EmfSetWorldTransform](./emfsetworldtransform) | El registro EMR_SETWORLDTRANSFORM especifica una transformación para la transformación del espacio mundial actual al espacio de la página en el contexto del dispositivo de reproducción. |
| [EmfSmallTextOut](./emfsmalltextout) | El registro EMR_SMALLTEXTOUT genera una cadena. |
| [EmfStateRecordType](./emfstaterecordtype) | Los tipos de registro de estado especifican y administran las propiedades gráficas que definen el estado del contexto del dispositivo de reproducción. |
| [EmfStretchBlt](./emfstretchblt) | El registro EMR_STRETCHBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario . |
| [EmfStretchDiBits](./emfstretchdibits) | El registro EMR_STRETCHDIBITS especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, según una operación de ráster especificada, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si necesario. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | El registro EMR_STROKEANDFILLPATH cierra las figuras abiertas en un trazado, traza el contorno del trazado con el lápiz actual y rellena su interior con el pincel actual. |
| [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH clase |
| [EmfTransformRecordType](./emftransformrecordtype) | Los tipos de registro de transformación especifican y modifican transformaciones de espacio mundial a espacio de página. |
| [EmfTransparentBlt](./emftransparentblt) | El registro EMR_TRANSPARENTBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , tratando un color específico como transparente, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario |
| [EmfVertexData](./emfvertexdata) | Objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden. |
| [EmfWidenPath](./emfwidenpath) | Este registro redefine la ruta actual como el área que se pintaría si la ruta se dibujara utilizando el lápiz actualmente seleccionado en el contexto del dispositivo de reproducción. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
