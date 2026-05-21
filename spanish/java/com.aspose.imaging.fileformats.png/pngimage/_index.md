---
title: "PngImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule imágenes rasterizadas Portable Network Graphics PNG con nuestra versátil API que ofrece soporte para niveles de compresión y diversas profundidades de color, incluyendo escala de grises, color indexado, TrueColor y canales alfa."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Manipule imágenes rasterizadas Portable Network Graphics (PNG) con nuestra versátil API, que ofrece soporte para niveles de compresión y diversas profundidades de color, incluyendo escala de grises, color indexado, TrueColor y canales alfa. Procese sin problemas los metadatos XMP, lo que permite una gestión integral de los metadatos de la imagen, mientras carga fácilmente imágenes PNG, realiza diversas manipulaciones, aplica filtros y convierte imágenes a otros formatos de archivo para una versatilidad y personalización óptimas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Inicialice un nuevo objeto de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) proporcionando los parámetros de ancho y alto. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Construye una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) usando el parámetro de ruta para especificar la ubicación del archivo de imagen a cargar. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Crea una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) proporcionando una imagen raster como parámetro. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Inicializa una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) especificando la ruta al archivo de imagen y el tipo de color. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Crea una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) especificando una imagen raster y un tipo de color. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Crea una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) inicializándola con un flujo. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Instancie una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), especificando los parámetros deseados de ancho, alto y tipo de color. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Inicialice una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), incorporando opciones PNG junto con los parámetros de ancho y alto. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupere el valor de bits por píxel de la imagen. |
| [getHeight()](#getHeight--) | Obtenga la altura de la imagen en píxeles. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Recupere o modifique la resolución horizontal de la imagen. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Recupere o modifique la resolución horizontal de la imagen. |
| [getFileFormat()](#getFileFormat--) | Recupera el formato del archivo asociado con la instancia de la imagen. |
| [getRawDataFormat()](#getRawDataFormat--) | Accede al formato de datos sin procesar de la imagen. |
| [getVerticalResolution()](#getVerticalResolution--) | Proporciona acceso a la resolución vertical de la imagen. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Proporciona acceso a la resolución vertical de la imagen. |
| [getWidth()](#getWidth--) | Permite obtener el ancho de la imagen en píxeles, proporcionando información esencial sobre sus dimensiones. |
| [hasTransparentColor()](#hasTransparentColor--) | Proporciona un valor booleano que indica si la imagen contiene un color transparente. |
| [hasAlpha()](#hasAlpha--) | Devuelve un valor booleano que indica si la imagen tiene un canal alfa, lo que determina su transparencia. |
| [getTransparentColor()](#getTransparentColor--) | Recupera el color transparente de la imagen, si existe. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Proporciona un valor booleano que indica si la imagen contiene un color transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Modifica el color transparente de la imagen, si existe. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Recupera un valor booleano que indica si la imagen tiene un color de fondo. |
| [getBackgroundColor()](#getBackgroundColor--) | Recupera el color de fondo de la imagen, si se ha especificado. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Recupera un valor booleano que indica si la imagen tiene un color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Recupera el color de fondo de la imagen, si se ha especificado. |
| [getInterlaced()](#getInterlaced--) | Recupera un valor booleano que indica si el [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) está entrelazado, lo que determina si los datos de la imagen se almacenan de manera progresiva para una carga o transmisión más rápida. |
| [isInterlaced()](#isInterlaced--) | Obtiene un valor que indica si esta instancia de imagen está entrelazada. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtiene las opciones predeterminadas. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones basadas en la configuración original del archivo. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Cargar una imagen PNG desde un archivo.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Transforma la imagen a una representación en escala de grises
    pngImage.grayscale();

    // Guardar en un archivo.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Inicializa un nuevo objeto de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) proporcionando los parámetros de ancho y alto. Este constructor simplifica la creación de imágenes PNG al permitir a los desarrolladores especificar las dimensiones directamente, facilitando la gestión eficiente de los datos de imágenes PNG dentro de sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho. |
| height | int | La altura. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Construye una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) usando el parámetro de ruta para especificar la ubicación del archivo de imagen a cargar. Este constructor permite a los desarrolladores crear imágenes PNG de forma conveniente cargándolas desde un archivo, simplificando el proceso de trabajo con imágenes PNG en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta para cargar una imagen. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Crea una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) proporcionando una imagen raster como parámetro. Este constructor permite a los desarrolladores inicializar directamente un objeto de imagen PNG usando una imagen raster existente, agilizando el proceso de trabajo con imágenes PNG en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Inicializa una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) especificando la ruta al archivo de imagen y el tipo de color. Este constructor permite la creación conveniente de imágenes PNG a partir de archivos con diferentes tipos de color, proporcionando flexibilidad en el manejo de varios formatos de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta para cargar una imagen. |
| colorType | int | El tipo de color. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Crea una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) especificando una imagen raster y un tipo de color. Este constructor permite a los desarrolladores convertir directamente imágenes raster al formato PNG mientras especifican el tipo de color deseado, ofreciendo flexibilidad en la representación de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| colorType | int | El tipo de color. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Crea una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) inicializándola con un flujo. Este constructor permite a los desarrolladores cargar imágenes PNG directamente desde un flujo, proporcionando flexibilidad en la obtención de imágenes desde diferentes fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Instancia una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), especificando los parámetros de ancho, alto y tipo de color deseados. Este constructor permite una creación rápida de imágenes PNG con dimensiones y configuraciones de color personalizadas, facilitando la generación de imágenes optimizada para diversas aplicaciones y flujos de trabajo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho. |
| height | int | La altura. |
| colorType | int | El tipo de color. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Inicializa una nueva instancia de la clase [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), incorporando opciones PNG junto con los parámetros de ancho y alto. Este constructor permite a los desarrolladores crear imágenes PNG con configuraciones y dimensiones personalizables, ofreciendo flexibilidad en la generación de imágenes para diversos casos de uso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Las opciones PNG. |
| width | int | El ancho. |
| height | int | La altura. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtén el valor de bits por píxel de la imagen. Esta propiedad proporciona información crucial sobre la profundidad de color de la imagen, permitiendo a los desarrolladores comprender el nivel de detalle y precisión de color presente en los datos de la imagen.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtén la altura de la imagen en píxeles. Esta propiedad devuelve la dimensión vertical de la imagen, permitiendo a los desarrolladores determinar su tamaño en píxeles a lo largo del eje vertical.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtén o modifica la resolución horizontal de la imagen. Esta propiedad representa el número de píxeles por pulgada a lo largo del eje horizontal de la imagen. Ajustar esta resolución puede afectar el tamaño físico de la imagen al imprimirse o mostrarse.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Obtén la resolución horizontal y vertical del PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//La resolución horizontal, en píxeles por pulgada: 96.0
//La resolución vertical, en píxeles por pulgada: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Obtén o modifica la resolución horizontal de la imagen. Esta propiedad representa el número de píxeles por pulgada a lo largo del eje horizontal de la imagen. Ajustar esta resolución puede afectar el tamaño físico de la imagen al imprimirse o mostrarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera el formato del archivo asociado a la instancia de imagen. Esta propiedad proporciona información esencial sobre el tipo de archivo, permitiendo un manejo y procesamiento eficientes según los requisitos específicos del formato.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Accede al formato de datos sin procesar de la imagen. Esta propiedad brinda información sobre cómo se estructuran internamente los datos de la imagen, lo que puede ser útil para tareas avanzadas de procesamiento de imágenes o conversión de formatos.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// Las imágenes PNG a cargar.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// La salida puede verse así:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Proporciona acceso a la resolución vertical de la imagen. Los desarrolladores pueden usar esta propiedad para obtener o modificar la configuración de resolución, que indica el número de píxeles por pulgada (PPI) a lo largo del eje vertical de la imagen.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Obtén la resolución horizontal y vertical del PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//La resolución horizontal, en píxeles por pulgada: 96.0
//La resolución vertical, en píxeles por pulgada: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Proporciona acceso a la resolución vertical de la imagen. Los desarrolladores pueden usar esta propiedad para obtener o modificar la configuración de resolución, que indica el número de píxeles por pulgada (PPI) a lo largo del eje vertical de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Permite la obtención del ancho de la imagen en píxeles, proporcionando información esencial sobre sus dimensiones. Esta propiedad es utilizada frecuentemente por los desarrolladores para determinar el ancho de la imagen, lo que les permite realizar diversas operaciones basadas en su tamaño

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Proporciona un valor booleano que indica si la imagen contiene un color transparente. Esta propiedad es crucial para aplicaciones que necesitan manejar la transparencia, permitiendo a los desarrolladores determinar si se requiere procesamiento adicional para gestionar regiones transparentes en la imagen.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Devuelve un valor booleano que indica si la imagen tiene un canal alfa, lo que determina su transparencia. Esta propiedad es útil para aplicaciones que necesitan manejar la transparencia, permitiendo a los desarrolladores determinar si se requiere procesamiento adicional para gestionar áreas transparentes en la imagen.

**Returns:**
boolean - `true` si esta instancia tiene alfa; de lo contrario, `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Clase auxiliar
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Aquí está el ejemplo principal
Utils utils = new Utils();

// Obtenga todos los tipos de color PNG compatibles.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// La salida se ve así:
// Una imagen PNG en escala de grises no admite canal alfa
// Una imagen PNG Truecolor no admite canal alfa
// Una imagen PNG IndexedColor no admite canal alfa
// Una imagen PNG GrayscaleWithAlpha admite canal alfa
// Una imagen PNG TruecolorWithAlpha admite canal alfa
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtiene el color transparente de la imagen, si existe. Esta propiedad es valiosa para aplicaciones que requieren un manejo preciso de áreas transparentes dentro de las imágenes, permitiendo a los desarrolladores acceder y manipular el color transparente específico utilizado.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Proporciona un valor booleano que indica si la imagen contiene un color transparente. Esta propiedad es crucial para aplicaciones que necesitan manejar la transparencia, permitiendo a los desarrolladores determinar si se requiere procesamiento adicional para gestionar regiones transparentes en la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Cree una imagen PNG TrueColor de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Todos los píxeles rojos se considerarán completamente transparentes.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Todos los píxeles transparentes tendrán un color de fondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Rellene toda la imagen con color blanco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Rellene el cuarto superior izquierdo de la imagen con el color transparente.
    // Esto hace que el cuarto superior izquierdo se coloree con el color de fondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Modifica el color transparente de la imagen, si existe. Esta propiedad es valiosa para aplicaciones que requieren un manejo preciso de áreas transparentes dentro de las imágenes, permitiendo a los desarrolladores acceder y manipular el color transparente específico utilizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Cree una imagen PNG TrueColor de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Todos los píxeles rojos se considerarán completamente transparentes.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Todos los píxeles transparentes tendrán un color de fondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Rellene toda la imagen con color blanco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Rellene el cuarto superior izquierdo de la imagen con el color transparente.
    // Esto hace que el cuarto superior izquierdo se coloree con el color de fondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtiene un valor booleano que indica si la imagen tiene un color de fondo. Esta propiedad es útil para aplicaciones que necesitan determinar si una imagen incluye un color de fondo, lo que puede ser importante para diversas tareas de procesamiento como composición, renderizado o exportación.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color de fondo de la imagen, si se ha especificado uno. Esta propiedad es útil para aplicaciones que necesitan identificar y potencialmente manipular el color de fondo de una imagen.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Obtiene un valor booleano que indica si la imagen tiene un color de fondo. Esta propiedad es útil para aplicaciones que necesitan determinar si una imagen incluye un color de fondo, lo que puede ser importante para diversas tareas de procesamiento como composición, renderizado o exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Cree una imagen PNG TrueColor de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Todos los píxeles rojos se considerarán completamente transparentes.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Todos los píxeles transparentes tendrán un color de fondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Rellene toda la imagen con color blanco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Rellene el cuarto superior izquierdo de la imagen con el color transparente.
    // Esto hace que el cuarto superior izquierdo se coloree con el color de fondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Obtiene el color de fondo de la imagen, si se ha especificado uno. Esta propiedad es útil para aplicaciones que necesitan identificar y potencialmente manipular el color de fondo de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Cree una imagen PNG TrueColor de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Todos los píxeles rojos se considerarán completamente transparentes.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Todos los píxeles transparentes tendrán un color de fondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Rellene toda la imagen con color blanco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Rellene el cuarto superior izquierdo de la imagen con el color transparente.
    // Esto hace que el cuarto superior izquierdo se coloree con el color de fondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Recupera un valor booleano que indica si el [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) está entrelazado, lo que determina si los datos de la imagen se almacenan de manera progresiva para una carga o transmisión más rápida.

**Returns:**
boolean - `true` si está entrelazado; de lo contrario, `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Obtiene un valor que indica si esta instancia de imagen está entrelazada.

Valor: `true` si esta instancia de imagen está entrelazada; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta instancia de imagen está entrelazada.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtiene las opciones predeterminadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | java.lang.Object[] | Los argumentos. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método `DataStreamSupporter.Save(string)`, se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método `Image.Save(string, ImageOptionsBase)` como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
