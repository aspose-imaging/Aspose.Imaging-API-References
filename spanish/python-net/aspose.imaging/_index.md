---
title: "aspose.imaging"
type: docs
weight: 10
url: /es/python-net/aspose.imaging/
---


El módulo es el núcleo para módulos anidados y los objetos más básicos utilizados para el procesamiento de Aspose.Imaging.

## **Classes**
| **Clase** | **Descripción** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Define un patrón de mezcla. Esta clase no puede heredarse. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | La clase base de pincel. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Contiene la información de la versión de compilación actual. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Contiene la configuración de caché. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | El color CMYK del píxel. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Métodos auxiliares para trabajar con el color CMYK presentado como un valor entero de 32 bits con signo.<br/>            Proporciona una API similar a la estructura [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/).<br/>            Es más ligera porque el color CMYK se presenta simplemente como Int32 en lugar de una estructura con campos internos.<br/>            Por favor, prefiera usar los métodos estáticos de esta clase cuando sea posible en lugar de la estructura obsoleta<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |
| [Color](/imaging/python-net/aspose.imaging/color/) | El color del píxel. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Define matrices de colores y posiciones usadas para interpolar la mezcla de colores en un degradado multicolor. Esta clase no puede heredarse. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Define un mapa para convertir colores. Varios métodos de la clase [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) ajustan los colores de la imagen usando una tabla de reasignación de colores, que es una matriz de estructuras [ColorMap](/imaging/python-net/aspose.imaging/colormap/). No heredable. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Define una matriz de 5 x 5 que contiene las coordenadas del espacio RGBA. Varios métodos de la clase [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) ajustan los colores de la imagen usando una matriz de colores. Esta clase no puede heredarse. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Define una matriz de colores que forman una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Clase auxiliar para la manipulación de paletas de colores. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Traduce colores a y desde estructuras GDI+ Color. Esta clase no puede heredarse. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Encapsula un extremo de línea personalizado definido por el usuario. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | El contenedor de flujo de datos. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Representa un objeto desechable. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | La clase de imagen incrustada |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | La figura. Un contenedor para formas. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Auxiliar para el procesamiento de flujos de archivo. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Define un formato particular para texto, incluyendo la familia tipográfica, el tamaño y los atributos de estilo. Esta clase no puede heredarse. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | Configuración de fuentes del renderizador de formatos vectoriales de imágenes generales. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Representa los gráficos según el motor gráfico usado en el ensamblado actual. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Representa una serie de líneas y curvas conectadas. Esta clase no puede heredarse. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | El procesador avanzado de búfer. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | El fotograma de animación |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | El procesador de búfer. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | El convertidor de color. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La interfaz de paleta de colores. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Interfaz de metadatos de imagen. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | El creador de imágenes. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | El descriptor del creador de imágenes que especifica las propiedades del creador. El descriptor del creador se usa para superar<br/>            la necesidad de contener cada instancia del creador de imágenes en memoria y los problemas de multihilo. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | El descriptor de imagen. Contiene propiedades y métodos base para todos los demás tipos de descriptor de imagen. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | El exportador de imagen. Puede exportar datos del formato interno `aspose.imaging` a un formato de datos especificado. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Representa el descriptor del exportador de imagen. El descriptor del exportador se utiliza para superar la necesidad de contener cada instancia del exportador<br/>            en memoria y los problemas de multihilo. |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | El cargador de imagen. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El descriptor del cargador de imagen que especifica las propiedades del cargador. El descriptor del cargador se utiliza para superar<br/>            la necesidad de contener cada instancia del cargador de imagen en memoria y los problemas de multihilo. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | El convertidor de color para formatos de imagen indexados. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Interfaz del contenedor de metadatos de imagen. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | La interfaz de imagen multipágina |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | La interfaz de imagen multipágina extendida |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Representa un objeto con límites. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Representa una forma ordenada. Una forma ordenada es un conjunto continuo de puntos que tiene un punto de inicio y un punto final.<br/>            El conjunto continuo de puntos conectado mediante una regla específica. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Cumple con los píxeles ARGB de 32 bits cargados parcialmente. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Cumple con los píxeles cargados parcialmente. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | El cargador de datos parciales. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | El cargador de píxeles ARGB de 32 bits de imagen raster. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits de imagen raster. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | El cargador de píxeles de imagen raster. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | El cargador de datos sin procesar de imagen raster. |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen es la clase base para todo tipo de imágenes. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) contiene información sobre cómo se manipulan los colores de mapas de bits y metafiles durante el renderizado. Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) mantiene varios ajustes de color, incluyendo matrices de ajuste de color, matrices de ajuste en escala de grises, valores de corrección gamma, tablas de mapas de color y valores de umbral de color. Durante el renderizado, los colores pueden ser corregidos, oscurecidos, aclarados y eliminados. Para aplicar dichas manipulaciones, inicialice un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) y pase la ruta de ese objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) (junto con la ruta de una [Image](/imaging/python-net/aspose.imaging/image/)) al método DrawImage. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Representa el registro de creadores de imágenes. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Representa el registro de exportadores de imágenes. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Representa el registro de cargadores de imágenes. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones base de la imagen. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Clase de configuración de cambio de tamaño de imagen |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Clase para representar una secuencia de elementos |
| [License](/imaging/python-net/aspose.imaging/license/) | Proporciona métodos para licenciar el componente. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Representa las opciones de carga. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Reemplaza la matriz GDI+. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Proporciona métodos medidos para la integración |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Representa un diccionario no genérico. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Lista no genérica de objetos |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | El objeto que tiene límites. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Caché para fuentes OpenType instaladas en el sistema. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Define un objeto usado para dibujar líneas, curvas y figuras. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | El formato de datos de píxeles. Este es un objeto inmutable. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Representa un par ordenado de coordenadas x e y de punto flotante que define un punto en un plano bidimensional. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Representa una imagen raster que soporta operaciones gráficas raster. Esta imagen almacena en caché los datos de píxeles cuando es necesario. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | La imagen raster multipágina |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Representa una imagen raster que soporta operaciones gráficas raster. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | La configuración de datos sin procesar |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Describe el interior de una forma gráfica compuesta de rectángulos y rutas. Esta clase no puede heredarse. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | La configuración de eliminación de fondo |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | La configuración de resolución para las opciones de guardado de imagen. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | La forma. Un conjunto continuo de puntos conectados mediante una regla específica. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Representa un segmento de forma. Un segmento es una línea o curva que conecta dos puntos. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Representa el tamaño. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo. |
| [Source](/imaging/python-net/aspose.imaging/source/) | El origen se utiliza para contener toda la información relevante para una tubería de objetos. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Encapsula información de diseño de texto (como alineación, orientación y tabulaciones) manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | El objeto que soporta transparencia. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | La imagen vectorial es la clase base para todo tipo de imágenes vectoriales. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | La imagen multipágina Vector |
## **Enumerations**
| **Enumeración** | **Descripción** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Indica la forma en que se debe tratar el gráfico después de ser mostrado. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Especifica el tipo de caché a usar. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Representa el conjunto de caracteres utilizado. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Especifica qué objetos usan información de ajuste de color. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Especifica canales individuales en el espacio de color CMYK (cian, magenta, amarillo, negro). Esta enumeración es usada por los métodos SetOutputChannel. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Método de comparación de color para ajustar al vecino más cercano |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Especifica los tipos de imágenes y colores que se verán afectados por la configuración de ajuste de color y escala de grises de un [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Métodos de cuantización de colores |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Especifica el nivel de calidad a usar durante la composición. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Especifica el tipo de forma gráfica a usar en ambos extremos de cada guión en una línea discontinua. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Especifica el estilo de líneas discontinuas dibujadas con un objeto [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | El modo de recuperación de datos. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Método de tramado. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | Los métodos de tramado usados para controlar la conversión de color. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Uno de los formatos de archivo de imagen compatibles. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Especifica cómo se rellena el interior de una ruta cerrada. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Especifica la información de estilo aplicada al texto. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Especifica la unidad de medida para los datos proporcionados. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Especifica los diferentes patrones disponibles para los objetos [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/). |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Especifica el tipo de visualización para los prefijos de teclas rápidas que se relacionan con el texto. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Filtros de imagen a usar |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | La enumeración [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Especifica los colores del sistema conocidos. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Especifica los estilos de punta disponibles con los que un objeto [Pen](/imaging/python-net/aspose.imaging/pen/) puede terminar una línea. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Especifica cómo unir segmentos consecutivos de línea o curva en una figura (subruta) contenida en un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Especifica el orden de las operaciones de transformación de matrices. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | El método de extracción de paleta de imagen |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Especifica el nivel de cumplimiento PDF para el archivo de salida. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Especifica la alineación de un objeto [Pen](/imaging/python-net/aspose.imaging/pen/) en relación con la línea teórica de ancho cero. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Especifica el tipo de relleno que un objeto [Pen](/imaging/python-net/aspose.imaging/pen/) utiliza para rellenar líneas. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | El significado real del formato de datos de píxel. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | El tipo de procesamiento. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Especifica el tipo de redimensionamiento. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Enumeración de unidad de resolución. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Especifica cuánto se rota una imagen y el eje utilizado para voltear la imagen. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Proporciona los campos que representan puntos de referencia en [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) para la búsqueda. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Especifica si se aplica suavizado (antialiasing) a líneas y curvas y a los bordes de áreas rellenas. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Especifica la alineación de una cadena de texto respecto a su rectángulo de diseño. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | La enumeración especifica cómo sustituir dígitos en una cadena según la configuración regional o el idioma del usuario. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Especifica la información de visualización y diseño para cadenas de texto. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Especifica cómo recortar caracteres de una cadena que no cabe completamente en una forma de diseño. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Especifica la calidad del renderizado de texto. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Especifica el tipo de transformación de deformación aplicada. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Especifica cómo se repite una textura o degradado cuando es más pequeña que el área a rellenar. |
