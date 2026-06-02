---
title: "DicomImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Esta Clase implementa el soporte del formato de imagen raster DICOM (Digital Imaging and Communications in Medicine) y ofrece una solución integral para procesar imágenes DICOM con precisión y flexibilidad."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Esta Clase implementa el soporte del formato de imagen raster DICOM (Digital Imaging and Communications in Medicine) y ofrece una solución integral para procesar imágenes DICOM con precisión y flexibilidad. Puedes manipular sin problemas las páginas de la imagen, incluyendo operaciones para obtener, añadir o eliminar páginas, y controlar las páginas predeterminadas y activas. Con capacidades para trabajar con canales alfa, incrustar metadatos XMP, redimensionar, rotar, recortar, binarizar, ajustar, aplicar filtros y convertir a otros formatos raster. Esta API permite a los desarrolladores manejar imágenes DICOM de manera eficaz mientras satisfacen diversos requisitos de aplicación en contextos de imágenes médicas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Inicializa una nueva instancia de la clase DicomImage sin esfuerzo con este constructor, utilizando los parámetros dicomOptions. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Inicie una nueva instancia de la clase DicomImage de forma fluida empleando los parámetros stream y loadOptions en este constructor. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Cree una nueva instancia de la clase DicomImage utilizando un parámetro stream en este constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageCount()](#getPageCount--) | Recupere el recuento total de páginas de la imagen con esta propiedad intuitiva. |
| [getPages()](#getPages--) | Acceda a las páginas de la imagen con esta propiedad intuitiva. |
| [getFileInfo()](#getFileInfo--) | Recupere información valiosa del encabezado del archivo DICOM sin esfuerzo con esta propiedad intuitiva. |
| [getDicomPages()](#getDicomPages--) | Acceda a las páginas de la imagen con esta propiedad intuitiva. |
| [getActivePage()](#getActivePage--) | Acceda a la página activa de la imagen con esta propiedad intuitiva. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Administre la página activa de la imagen con esta propiedad intuitiva. |
| [getActivePageIndex()](#getActivePageIndex--) | Recupere el índice de la página activa sin esfuerzo con esta propiedad intuitiva. |
| [getFileFormat()](#getFileFormat--) | Recupere el valor del formato de archivo sin esfuerzo con esta propiedad intuitiva. |
| [hasAlpha()](#hasAlpha--) | Recupere si la imagen tiene un canal alfa sin esfuerzo con esta propiedad intuitiva. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Amplíe su colección de imágenes añadiendo una nueva página con este método intuitivo. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Conserve los datos del objeto guardándolos en el archivo designado (indexer + filename) junto con el formato de archivo y las opciones especificados. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ajuste la resolución de este [RasterImage](../../com.aspose.imaging/rasterimage) con precisión usando este método sencillo. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Redimensione la imagen manteniendo su relación de aspecto con este método conveniente. |
| [addPage()](#addPage--) | Agregue una nueva página al final de la lista de páginas de la imagen con este método sencillo. |
| [insertPage(int pageIndex)](#insertPage-int-) | Inserte una nueva página en la lista de páginas de la imagen en un índice especificado con este método intuitivo. |
| [removePage(int pageIndex)](#removePage-int-) | Elimine la página en el índice especificado de la lista de páginas con este método conveniente. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Gire la imagen alrededor de su centro con este método conveniente. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ajuste el tamaño de la imagen con este método sencillo. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ajuste el ancho de la imagen manteniendo su relación de aspecto con este método conveniente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ajuste la altura de la imagen manteniendo su relación de aspecto con este método fácil de usar. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Manipule fácilmente el fotograma activo rotando, volteando o realizando ambas acciones simultáneamente con este método sencillo. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mejore la imagen actual aplicando efectos de tramado con este método sencillo. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorte la imagen para eliminar áreas no deseadas y centrarse en el contenido esencial con este método simple. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Ajuste el área de recorte de la imagen aplicando desplazamientos con este método versátil. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Convierta fácilmente la imagen a un formato binario usando un umbral predefinido con este método sencillo. |
| [binarizeOtsu()](#binarizeOtsu--) | Aplicar el umbralizado Otsu para binarizar la imagen, determinando automáticamente el valor de umbral óptimo basado en el histograma de la imagen. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarizar imágenes con el algoritmo de umbralizado adaptativo de Bradley, aprovechando el umbralizado de imagen integral para mejorar el rendimiento. |
| [grayscale()](#grayscale--) | Transformar fácilmente las imágenes a su representación en escala de grises, simplificando las tareas de análisis visual y procesamiento. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Mejorar la calidad de la imagen y ajustarla con corrección gamma, una técnica poderosa para afinar la apariencia visual. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Lograr ajustes de color precisos aplicando corrección gamma de forma independiente a los componentes rojo, verde y azul de una imagen. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Mejorar la luminancia de la imagen con el ajuste de `brightness`, un método parametrizado que permite a los desarrolladores afinar la luminosidad de las imágenes. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Mejorar el contraste de [Image](../../com.aspose.imaging/image) con este método fácil de usar, que ajusta la disparidad entre áreas claras y oscuras. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Mejorar sin esfuerzo áreas específicas de tu imagen aplicando filtros a rectángulos designados. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ajustar el tamaño de tu imagen con este sencillo método de redimensionado. |
| [cacheData()](#cacheData--) | Este método almacena en caché los datos de manera eficiente, optimizando el rendimiento y garantizando un acceso rápido cuando sea necesario. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Cargar una imagen
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Dibuja algo usando gráficos vectoriales
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Guarda los píxeles de la imagen dibujada. Ahora están en la primera página de la imagen Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Añade algunas páginas después, oscureciéndolas
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Añade algunas páginas antes de la página principal, iluminándolas
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Guarda la imagen multipágina creada en el archivo de salida
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Inicializar una nueva instancia de la clase DicomImage sin esfuerzo con este constructor, utilizando los parámetros dicomOptions. Perfecto para desarrolladores que desean sumergirse rápidamente y de manera eficiente en objetos [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Las opciones dicom (ignorando por ahora). |
| width | int | El ancho. |
| height | int | La altura. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Iniciar una nueva instancia de la clase DicomImage de forma fluida empleando un stream y los parámetros loadOptions en este constructor. Ideal para desarrolladores ansiosos por comenzar a trabajar con objetos [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) de manera rápida y eficaz en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Crear una nueva instancia de la clase DicomImage utilizando un parámetro stream en este constructor. Perfecto para desarrolladores que buscan una forma simplificada de inicializar objetos [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) a partir de flujos de datos existentes en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Obtener el recuento total de páginas de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceso rápido al número de páginas dentro de una imagen, garantizando una navegación y gestión eficientes.

**Returns:**
int - el recuento de páginas.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Acceder a las páginas de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que desean interactuar con páginas individuales dentro de la imagen, asegurando una navegación y manipulación fluidas.

**Returns:**
com.aspose.imaging.Image[] - las páginas.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Obtener información valiosa del encabezado del archivo DICOM sin esfuerzo con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceso rápido a los detalles esenciales encapsulados en el archivo DICOM, garantizando una extracción y análisis de datos eficientes.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Acceder a las páginas de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que desean interactuar con páginas individuales dentro de la imagen, asegurando una navegación y manipulación fluidas.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - las páginas.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Acceder a la página activa de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan cambiar dinámicamente entre páginas dentro de imágenes multipágina, garantizando una navegación y procesamiento eficientes.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Gestionar la página activa de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan cambiar dinámicamente entre páginas dentro de imágenes multipágina, garantizando una navegación y procesamiento eficientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | la página activa. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Obtener el índice de la página activa sin esfuerzo con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceso rápido al índice de la página actual dentro de imágenes multipágina, garantizando una navegación y procesamiento eficientes.

**Returns:**
int - el índice de la página activa.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtener el valor del formato de archivo sin esfuerzo con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceso rápido al formato del archivo de imagen, garantizando un manejo y procesamiento eficientes según el tipo de archivo.

**Returns:**
long - un valor del formato de archivo [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtenga de forma sencilla si la imagen tiene un canal alfa con esta propiedad intuitiva. Ideal para desarrolladores que buscan determinar si la imagen contiene información de transparencia, garantizando un manejo preciso de los datos del canal alfa en tareas de procesamiento de imágenes.

**Returns:**
boolean - verdadero si la imagen tiene canal alfa.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Amplíe su colección de imágenes añadiendo una nueva página con este método intuitivo. Ideal para desarrolladores que buscan agregar páginas de forma dinámica a imágenes multipágina, asegurando una expansión y organización sin problemas del contenido de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La página a agregar. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Conserve los datos del objeto guardándolos en la ubicación del archivo designado (indexador + nombre de archivo) junto con el formato de archivo y las opciones especificadas. Ideal para desarrolladores que buscan almacenar datos de forma segura en varios formatos mientras mantienen flexibilidad y control sobre los parámetros de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Ajuste la resolución de este [RasterImage](../../com.aspose.imaging/rasterimage) con precisión usando este método sencillo. Ideal para desarrolladores que desean adaptar la resolución de la imagen a requisitos específicos, garantizando una calidad de visualización óptima y una gestión adecuada del tamaño de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpiX | double | La resolución horizontal, en puntos por pulgada, del [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La resolución vertical, en puntos por pulgada, del [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Redimensione la imagen manteniendo su relación de aspecto con este método conveniente. Ideal para desarrolladores que buscan ajustar las dimensiones de la imagen de forma proporcional, asegurando consistencia y preservando las proporciones del contenido original. El redimensionado proporcional cambiará el tamaño de cada fotograma según la relación de `newWidth`/width y `newHeight`/height.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Agregue una nueva página al final de la lista de páginas de la imagen con este método sencillo. Ideal para desarrolladores que buscan expandir dinámicamente imágenes multipágina, asegurando una integración y organización sin problemas del contenido de la imagen.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Inserte una nueva página en la lista de páginas de la imagen en un índice especificado con este método intuitivo. Ideal para desarrolladores que buscan un control preciso sobre la disposición de las páginas en imágenes multipágina, asegurando una organización y personalización sin problemas del contenido de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageIndex | int | Índice de la página. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Dibuja algo usando gráficos vectoriales
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Guarda los píxeles de la imagen dibujada. Ahora están en la primera página de la imagen Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Añade algunas páginas después, oscureciéndolas
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Añade algunas páginas antes de la página principal, iluminándolas
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Guarda la imagen multipágina creada en el archivo de salida
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Elimine la página en el índice especificado de la lista de páginas con este método conveniente. Ideal para desarrolladores que buscan un control preciso sobre la gestión de imágenes multipágina, asegurando una organización y personalización sin problemas del contenido de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageIndex | int | Índice de la página. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Gire la imagen alrededor de su centro con este método conveniente. Ideal para desarrolladores que buscan ajustar la orientación de la imagen de forma dinámica, garantizando una presentación y alineación óptimas dentro de sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); de lo contrario, se dejarán las dimensiones sin cambios y solo `` el contenido de la imagen será rotado. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Cargue una imagen DICOM desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Gire la imagen alrededor del centro 60 grados en sentido horario.
        // Use gris como color de fondo.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Tenga en cuenta que si la imagen es colorida, se convertirá automáticamente al formato en escala de grises según las opciones a continuación.
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // Cree una matriz de fotogramas TIFF.
        // El número de fotogramas es igual al número de páginas DJVU.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Guarde cada página como un fotograma TIFF individual.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // Cree un fotograma TIFF basado en la página DICOM.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Componga una imagen TIFF a partir de los fotogramas.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // Guardar en un archivo.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ajuste el tamaño de la imagen con este método sencillo. Ideal para desarrolladores que buscan redimensionar imágenes de forma dinámica, asegurando que se adapten sin problemas a varios contextos y diseños dentro de sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ajuste el ancho de la imagen manteniendo su relación de aspecto con este método conveniente. Ideal para desarrolladores que buscan redimensionar imágenes de forma proporcional, garantizando resultados consistentes y visualmente atractivos en diferentes entornos de visualización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| resizeType | int | Tipo de redimensionado. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Este ejemplo carga una imagen DICOM y la redimensiona proporcionalmente usando varios métodos de redimensionado. Solo se especifica el ancho, la altura se calcula automáticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ajuste la altura de la imagen manteniendo su relación de aspecto con este método fácil de usar. Perfecto para desarrolladores que buscan redimensionar imágenes dinámicamente mientras preservan sus proporciones, garantizando una visualización óptima y usabilidad en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| resizeType | int | Tipo de redimensionado. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Este ejemplo carga una imagen DICOM y la redimensiona proporcionalmente usando varios métodos de redimensionado. Solo se especifica la altura, el ancho se calcula automáticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Manipule fácilmente el fotograma activo rotándolo, volteándolo o realizando ambas acciones simultáneamente con este método sencillo. Ideal para desarrolladores que necesitan ajustar dinámicamente la orientación de fotogramas específicos dentro de sus secuencias de imágenes, garantizando una presentación y alineación óptimas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de volteo rotativo. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotar, voltear y guardar en el archivo de salida.
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mejore la imagen actual aplicando efectos de dithering con este método sencillo. Perfecto para desarrolladores que buscan añadir textura y profundidad a las imágenes, mejorando su calidad visual y atractivo general.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Realizar dithering por umbral usando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Realizar dithering Floyd usando una paleta de colores de 1 bit que contiene solo 2 colores: negro y blanco.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorte la imagen para eliminar áreas no deseadas y centrarse en el contenido esencial con este método simple. Ideal para desarrolladores que desean personalizar la composición visual de las imágenes, asegurando que transmitan el mensaje deseado de manera eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |


**Example: The following example crops a DICOM image.**
El siguiente ejemplo recorta una imagen DICOM. El área de recorte se especifica mediante Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Recorte la imagen. El área de recorte es la zona rectangular central de la imagen.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Guarde la imagen recortada en PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Ajuste el área de recorte de la imagen aplicando desplazamientos con este método versátil. Perfecto para desarrolladores que necesitan un control preciso sobre el proceso de recorte, garantizando que se conserven los detalles importantes mientras se eliminan los elementos innecesarios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento derecho. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |


**Example: The following example crops a DICOM image.**
El siguiente ejemplo recorta una imagen DICOM. El área de recorte se especifica mediante los márgenes Izquierda, Superior, Derecha, Inferior.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Recorte nuevamente. Establezca un margen del 10 % del tamaño de la imagen.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Guarde la imagen recortada en PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Convierta fácilmente la imagen a un formato binario usando un umbral predefinido con este método sencillo. Ideal para desarrolladores que buscan simplificar tareas de procesamiento de imágenes segmentando la imagen en componentes de primer plano y fondo basados en niveles de intensidad especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
El siguiente ejemplo binariza una imagen DICOM con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binariza la imagen con un valor de umbral de 127.
    // Si el valor gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Aplique el umbral de Otsu para binarizar la imagen, determinando automáticamente el valor óptimo del umbral basado en el histograma de la imagen. Perfecto para desarrolladores que buscan un método fiable para segmentar imágenes en regiones de primer plano y fondo con mínima intervención manual.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
El siguiente ejemplo binariza una imagen DICOM con umbral de Otsu. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binariza la imagen con umbralización de Otsu.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarice imágenes con el algoritmo de umbral adaptativo de Bradley, aprovechando el umbral de imagen integral para mejorar el rendimiento. Ideal para desarrolladores que buscan segmentar automáticamente imágenes basándose en variaciones locales de brillo, garantizando una detección y extracción precisas de objetos en condiciones de iluminación variables.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| windowSize | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
El siguiente ejemplo binariza una imagen DICOM con el algoritmo de umbral adaptativo de Bradley con el tamaño de ventana especificado. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binariza la imagen con una diferencia de brillo de 5. El brillo es la diferencia entre un píxel y el promedio de una ventana de 10 x 10 píxeles centrada en ese píxel.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transforme fácilmente las imágenes a su representación en escala de grises, simplificando el análisis visual y las tareas de procesamiento. Perfecto para desarrolladores que buscan mejorar la claridad de la imagen, reducir la complejidad y facilitar algoritmos eficientes basados en escala de grises para diversas aplicaciones.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
El siguiente ejemplo transforma una imagen DICOM a color a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente por tonos de gris y solo contienen información de intensidad.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Mejore la calidad de la imagen y ajústela con corrección gamma, una técnica poderosa para afinar la apariencia visual. Perfecto para desarrolladores que buscan optimizar la presentación de la imagen, ajustar el balance de color y garantizar una renderización consistente en diferentes dispositivos y entornos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Logre ajustes de color precisos aplicando corrección gamma de forma independiente a los componentes rojo, verde y azul de una imagen. Este método garantiza un balance de color exacto y una salida visual óptima, atendiendo a desarrolladores que buscan un control granular sobre la renderización de la imagen y la precisión del color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Gamma para el coeficiente del canal rojo |
| gammaGreen | float | Gamma para el coeficiente del canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Mejore la luminancia de la imagen con el ajuste de `brightness`, un método parametrizado que permite a los desarrolladores afinar la luminosidad de las imágenes. Esta función fácil de usar permite a los desarrolladores manipular sin problemas el brillo de la imagen, ofreciendo flexibilidad y control sobre la estética visual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Establece el valor de brillo. Los valores aceptados de brillo están en el rango [-255, 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Mejore el contraste de [Image](../../com.aspose.imaging/image) con este método fácil de usar, que ajusta la disparidad entre áreas claras y oscuras. Mejore la claridad y definición visual sin esfuerzo, proporcionando a los desarrolladores un control intuitivo sobre el contraste de la imagen para una renderización óptima.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Establece el valor de contraste. Los valores aceptados de contraste están en el rango [-100f, 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Mejore sin esfuerzo áreas específicas de su imagen aplicando filtros a rectángulos designados. Este método brinda a los desarrolladores un control preciso sobre la manipulación de la imagen, permitiendo ajustes dirigidos para lograr los efectos visuales deseados con facilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Las opciones. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ajuste el tamaño de su imagen con este método simple de redimensionado. Ya sea que necesite reducir o ampliar su imagen, esta función garantiza que sus necesidades de redimensionado se cumplan de manera eficiente y precisa, lo que la hace perfecta para desarrolladores que buscan ajustes de tamaño de imagen rápidos y fáciles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// El algoritmo adaptativo basado en una función racional ponderada y combinada y en la interpolación lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// El pequeño filtro rectangular
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// El número de colores en la paleta.
resizeSettings.setEntriesCount(256);

// La cuantización de color no se usa
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// El método euclidiano
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Reducir a la mitad usando remuestreo adaptativo.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Guardar como PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Este método almacena en caché datos de manera eficiente, optimizando el rendimiento y garantizando un acceso rápido cuando sea necesario. Ideal para desarrolladores que buscan mejorar la velocidad y eficiencia de sus aplicaciones gestionando inteligentemente los recursos de datos.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Cargue una imagen desde un archivo DICOM.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Esta llamada almacena en caché todas las páginas para que no se realice una carga adicional de datos desde el flujo de datos subyacente.
    image.cacheData();

    // O puedes almacenar en caché las páginas individualmente.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

