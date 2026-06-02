---
title: "EpsImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para el soporte del formato de archivo de imagen Encapsulated PostScript EPS ofrece capacidades robustas para manipular composiciones que incluyen texto, gráficos e imágenes."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

La API para el soporte del formato de archivo de imagen Encapsulated PostScript (EPS) ofrece capacidades robustas para manipular composiciones que incluyen texto, gráficos e imágenes. Con funciones como el manejo de imágenes de vista previa bitmap, volteo de orientación, recuperación de la caja delimitadora para los límites de la ilustración, redimensionado, rotación de imágenes y adición de imágenes de vista previa. Esta API garantiza un procesamiento e integración sin problemas de los archivos EPS en diversas aplicaciones con precisión y versatilidad.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Acceda al número de imágenes de vista previa disponibles con facilidad. |
| [getPreviewImages()](#getPreviewImages--) | Recupere las imágenes de vista previa asociadas a su archivo. |
| [getFileFormat()](#getFileFormat--) | Acceda al formato de archivo de su imagen con esta propiedad. |
| [getEpsType()](#getEpsType--) | Acceda e interprete el valor del subtipo de su imagen EPS, optimizando su flujo de trabajo y mejorando la compatibilidad entre plataformas. |
| [hasRasterPreview()](#hasRasterPreview--) | Descubra la presencia de una vista previa raster de forma sencilla con esta propiedad. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Acceda a la profundidad de bits precisa de la imagen de forma sencilla con esta propiedad. |
| [getWidthF()](#getWidthF--) | Recupere el ancho de la imagen con esta práctica propiedad. |
| [getHeightF()](#getHeightF--) | Acceda a la altura de la imagen usando esta propiedad. |
| [isCached()](#isCached--) | Esta propiedad ofrece una forma práctica de comprobar si los datos del objeto están actualmente en caché, eliminando la necesidad de lecturas de datos adicionales. |
| [getPsStream()](#getPsStream--) | Obtiene el flujo que contiene el PostScript a ejecutar. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Esta propiedad recupera la versión de PostScript asociada a la instancia de [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getTitle()](#getTitle--) | Esta propiedad recupera el título extraído de los comentarios de las Convenciones de Estructuración de Documentos EPS (DSC) incrustados en el archivo EPS. |
| [getCreator()](#getCreator--) | Esta propiedad ofrece acceso a la información del creador obtenida de los comentarios de las Convenciones de Estructuración de Documentos EPS (DSC) presentes en el archivo EPS. |
| [getCreationDate()](#getCreationDate--) | Al recuperar la fecha de creación de los comentarios de las Convenciones de Estructuración de Documentos EPS (DSC), esta propiedad proporciona metadatos esenciales que indican el origen del archivo EPS. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Al recuperar la fecha de creación de los comentarios de las Convenciones de Estructuración de Documentos EPS (DSC), esta propiedad proporciona metadatos esenciales que indican el origen del archivo EPS. |
| [getBoundingBox()](#getBoundingBox--) | Al acceder a la caja delimitadora original en puntos independientes del dispositivo, esta propiedad brinda información geométrica crucial sobre las dimensiones del [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Esta propiedad devuelve la caja delimitadora original de la instancia de [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en píxeles, proporcionando datos geométricos esenciales para una renderización y manipulación precisas. |
| [cacheData()](#cacheData--) | Esta propiedad devuelve la caja delimitadora original de la instancia de [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en píxeles, proporcionando datos geométricos esenciales para una renderización y manipulación precisas. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Accede a las imágenes de vista previa vinculadas a la instancia de [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), permitiendo una recuperación sin problemas para inspección o uso en aplicaciones. |
| [getPreviewImage()](#getPreviewImage--) | Recupera la imagen de vista previa existente en el `format` especificado o devuelve `` si no se encuentra ninguna. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Recupera la imagen de vista previa existente en el `format` especificado o devuelve `` si no se encuentra ninguna. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personalice las paletas de imágenes para lograr esquemas de color únicos y mejorar el atractivo visual. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// Cargar imagen EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Redimensiona la imagen usando el método de interpolación cúbica Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // Exportar imagen al formato PNG
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// Cargar imagen EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Establecer el modo de interpolación
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Establecer el tipo de filtro
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Establece el método de comparación de color
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Establecer el método de cuantización de color
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Redimensionar la imagen usando configuraciones avanzadas de redimensionado
    image.resize(400, 400, resizeSettings);

    // Exportar imagen al formato PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Acceda al número de imágenes de vista previa disponibles con facilidad. Esta propiedad le permite recuperar sin esfuerzo el recuento de imágenes de vista previa asociadas a su archivo, facilitando la gestión y navegación eficientes de sus vistas previas de imágenes. Ideal para optimizar su flujo de trabajo y organizar sus recursos de imágenes de manera efectiva.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Recupere las imágenes de vista previa asociadas a su archivo. Esta propiedad brinda acceso sin problemas a la colección de imágenes de vista previa, permitiéndole explorar y gestionarlas de manera eficiente según sea necesario. Ideal para previsualizar rápidamente y seleccionar la imagen adecuada para su proyecto.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Acceda al formato de archivo de su imagen con esta propiedad. Recupere información esencial sobre el formato de su archivo de imagen, facilitando la compatibilidad y el procesamiento eficiente. Ideal para identificar el formato de sus archivos de imagen e integrarlos sin problemas en sus proyectos.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Acceda e interprete el valor del subtipo de su imagen EPS, simplificando su flujo de trabajo y mejorando la compatibilidad entre plataformas. Ideal para optimizar la recuperación del subtipo EPS en sus proyectos con precisión y eficiencia.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Descubra la presencia de una vista previa rasterizada sin esfuerzo con esta propiedad. Acceda al valor booleano que indica si la instancia [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) incluye una vista previa raster, potenciando sus tareas de procesamiento de imágenes con claridad y eficiencia. Ideal para simplificar decisiones de flujo de trabajo basadas en la presencia o ausencia de vistas previas raster en imágenes EPS.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Acceda al preciso nivel de bits de la imagen sin esfuerzo con esta propiedad. Recupere el recuento de bits por píxel, proporcionando información crucial sobre la profundidad de color de la imagen y ayudando a optimizar tareas de procesamiento. Ideal para aplicaciones que requieren un control detallado sobre la manipulación y análisis de imágenes.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Recupere el ancho de la imagen con esta práctica propiedad. Obtenga el ancho de la imagen sin esfuerzo, facilitando cálculos precisos de diseño, operaciones de escalado y tareas relacionadas con dimensiones dentro de su aplicación. Ideal para garantizar una representación y visualización precisas de imágenes en diversas plataformas y dispositivos.

**Returns:**
float - El ancho de la imagen en píxeles.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Acceda a la altura de la imagen usando esta propiedad. Obtenga la altura de la imagen con facilidad, permitiendo ajustes de diseño sin interrupciones, cálculos de proporción y una representación precisa en diferentes resoluciones de pantalla y entornos de visualización.

**Returns:**
float - La altura de la imagen en píxeles.
### isCached() {#isCached--}
```
public boolean isCached()
```


Esta propiedad ofrece una forma práctica de comprobar si los datos del objeto están actualmente en caché, eliminando la necesidad de lecturas de datos adicionales. Proporciona un método rápido y eficiente para determinar si la información requerida está disponible, optimizando el rendimiento y reduciendo la sobrecarga de recursos en operaciones intensivas en datos.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Obtiene el flujo que contiene el PostScript a ejecutar.

**Returns:**
java.io.InputStream - el flujo que contiene el PostScript a ejecutar.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Esta propiedad recupera la versión de PostScript asociada a la instancia [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Proporciona información sobre la versión específica del lenguaje PostScript utilizada en el archivo EPS, ayudando en la evaluación de compatibilidad y facilitando una integración sin problemas con entornos compatibles con PostScript.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Esta propiedad recupera el título extraído de los comentarios de las Convenciones de Estructuración de Documentos (DSC) del EPS incrustados en el archivo EPS. Proporciona metadatos valiosos sobre el contenido del archivo EPS, ayudando en la organización e identificación de documentos dentro de aplicaciones de software compatibles.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Esta propiedad ofrece acceso a la información del creador obtenida de los comentarios de las Convenciones de Estructuración de Documentos (DSC) del EPS encontrados en el archivo EPS. Comprender los detalles del creador brinda información sobre el software o herramienta utilizada para generar el archivo EPS, facilitando la evaluación de compatibilidad en diversas plataformas y aplicaciones.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Al recuperar la fecha de creación de los comentarios de las Convenciones de Estructuración de Documentos (DSC) del EPS, esta propiedad proporciona metadatos esenciales que indican el inicio del archivo EPS. Al acceder a esta información, los usuarios obtienen información sobre el origen y la cronología del archivo, mejorando la gestión y organización de los mismos.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Al recuperar la fecha de creación de los comentarios de las Convenciones de Estructuración de Documentos (DSC) del EPS, esta propiedad proporciona metadatos esenciales que indican el inicio del archivo EPS. Al acceder a esta información, los usuarios obtienen información sobre el origen y la cronología del archivo, mejorando la gestión y organización de los mismos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Al acceder al cuadro delimitador original en puntos independientes del dispositivo, esta propiedad brinda información geométrica crucial sobre las dimensiones del [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Al recuperar estos datos, los usuarios pueden evaluar con precisión el tamaño y la proporción de la imagen, facilitando un diseño y posicionamiento exactos en diversas aplicaciones.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Esta propiedad devuelve el cuadro delimitador original de la instancia [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en píxeles, proporcionando datos geométricos esenciales para una representación y manipulación precisas. Con esta información, los usuarios pueden garantizar una colocación y dimensionado exactos de las imágenes EPS en sus proyectos, mejorando la presentación visual general y la calidad.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Esta propiedad devuelve el cuadro delimitador original de la instancia [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en píxeles, proporcionando datos geométricos esenciales para una representación y manipulación precisas. Con esta información, los usuarios pueden garantizar una colocación y dimensionado exactos de las imágenes EPS en sus proyectos, mejorando la presentación visual general y la calidad.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Accede a las imágenes de vista previa vinculadas a la instancia [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), permitiendo una recuperación sin problemas para inspección o uso en aplicaciones. Este método brinda acceso conveniente a las imágenes de vista previa, mejorando la interacción del usuario con los datos de la imagen.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - Las imágenes de vista previa.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Recupera la imagen de vista previa existente en el `format` especificado o devuelve `` si no se encuentra ninguna. Este método ofrece flexibilidad al acceder a imágenes de vista previa adaptadas a formatos específicos, optimizando la compatibilidad y la gestión de recursos dentro de las aplicaciones.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Recupera la imagen de vista previa existente en el `format` especificado o devuelve `` si no se encuentra ninguna. Este método ofrece flexibilidad al acceder a imágenes de vista previa adaptadas a formatos específicos, optimizando la compatibilidad y la gestión de recursos dentro de las aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formato | long | El formato de imagen de vista previa EPS. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Personalice las paletas de imágenes para lograr esquemas de color únicos y mejorar el atractivo visual. Ajuste los colores para efectos específicos y optimice la calidad de la imagen en diferentes plataformas y dispositivos con facilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

