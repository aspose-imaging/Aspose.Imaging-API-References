---
title: "TgaImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule archivos de imagen raster TGA con nuestra API adaptada al formato TARGA Truevision Advanced Raster Adapter, permitiendo una carga y personalización sin problemas."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Manipule archivos de imagen raster TGA con nuestra API, adaptada al formato TARGA (Truevision Advanced Raster Adapter), que permite una carga y personalización sin problemas. Actualice fácilmente propiedades públicas como autor, marca de tiempo, ID de imagen y versión del software, mientras utiliza diversas configuraciones de bits por píxel, canal alfa y transparencia de color. Además, puede exportar imágenes TGA a otros formatos raster populares, garantizando la compatibilidad para sus proyectos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Inicializa un nuevo objeto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) usando la ruta de archivo proporcionada para cargar el contenido de la imagen. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Crea una nueva instancia de la clase [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) proporcionando un objeto de imagen raster. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Inicializa una nueva instancia de la clase [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) usando un flujo para cargar la imagen. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene el valor de bits por píxel, proporcionando información esencial sobre la profundidad de color de la imagen. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Obtiene el valor de bytes por píxel, que indica la cantidad de memoria ocupada por cada píxel en la imagen. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor booleano que indica si el [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) incluye un canal alfa, facilitando efectos de transparencia. |
| [isGrayScale()](#isGrayScale--) | Obtiene un valor booleano que indica si el [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) representa una imagen en escala de grises. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen representada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen encapsulada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getFileFormat()](#getFileFormat--) | Obtiene información crucial sobre el formato de archivo de la imagen representada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | Obtiene si esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) contiene un mapa de colores. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Obtiene la parte del numerador del valor gamma, que es esencial para una representación precisa del color en imágenes. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Obtiene la parte del denominador del valor gamma, un factor integral para determinar la representación del color en imágenes. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Obtiene el componente numerador de la Relación de Aspecto de Píxel, que influye en el aspecto visual de los píxeles dentro de la imagen. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Obtiene la parte del denominador de la Relación de Aspecto de Píxel, un factor crucial para determinar el aspecto visual de los píxeles dentro de la imagen. |
| [getXOrigin()](#getXOrigin--) | Obtiene la coordenada horizontal absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA). |
| [setXOrigin(int value)](#setXOrigin-int-) | Establece la coordenada horizontal absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA). |
| [getYOrigin()](#getYOrigin--) | Obtiene la coordenada vertical absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA). |
| [setYOrigin(int value)](#setYOrigin-int-) | Establece la coordenada vertical absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA). |
| [getImageId()](#getImageId--) | Obtiene el identificador único asociado a la imagen. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Establece el identificador único asociado a la imagen. |
| [getAuthorComments()](#getAuthorComments--) | Obtiene o establece los comentarios proporcionados por el autor de la imagen. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Obtiene o establece los comentarios proporcionados por el autor de la imagen. |
| [getAuthorName()](#getAuthorName--) | Obtiene o establece el nombre del autor asociado a la imagen. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Obtiene o establece el nombre del autor asociado a la imagen. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Obtiene la marca de fecha/hora. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Establece la marca de fecha/hora. |
| [getJobNameOrId()](#getJobNameOrId--) | Obtiene o establece el nombre o ID del trabajo asociado a la imagen. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Obtiene o establece el nombre o ID del trabajo asociado a la imagen. |
| [getJobTime()](#getJobTime--) | Obtiene o establece la marca de tiempo que indica la hora del trabajo asociada a la imagen. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Obtiene o establece la marca de tiempo que indica la hora del trabajo asociada a la imagen. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene o establece el color clave asociado a la imagen. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Obtiene o establece el color clave asociado a la imagen. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene o establece un valor booleano que indica si la imagen contiene un color transparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtiene o establece un valor booleano que indica si la imagen contiene un color transparente. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene o establece el color de fondo de la imagen. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Obtiene o establece el color de fondo de la imagen. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtiene o establece un valor que indica si la imagen contiene un color de fondo. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtiene o establece un valor que indica si la imagen contiene un color de fondo. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Obtiene o establece la versión del software asociada a la imagen. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Obtiene o establece la versión del software asociada a la imagen. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Obtiene o establece el componente de letra de la versión del software asociada a la imagen. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Obtiene o establece el componente de letra de la versión del software asociada a la imagen. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Obtiene o establece el componente numérico de la versión del software asociada a la imagen. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Obtiene o establece el componente numérico de la versión del software asociada a la imagen. |
| [getSoftwareId()](#getSoftwareId--) | Gestiona la identificación (ID) del software asociada a la imagen, permitiendo hasta 40 caracteres ASCII. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Gestiona la identificación (ID) del software asociada a la imagen, permitiendo hasta 40 caracteres ASCII. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Realiza una comparación de igualdad entre dos imágenes TGA, considerando tanto la primera como la segunda imagen involucradas en el proceso de comparación. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Realiza una comparación de desigualdad entre dos imágenes TGA, evaluando tanto la primera como la segunda imagen involucrada en la comparación. |
| [deepClone()](#deepClone--) | Produce un duplicado de la instancia actual, generando un nuevo objeto que clona todos los atributos y propiedades del original. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Replica las propiedades de otro objeto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), creando una nueva instancia con atributos idénticos. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | En una comparación de igualdad, el método evalúa si la instancia actual de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) es igual a la segunda imagen proporcionada como parámetro. |
| [equals(Object other)](#equals-java.lang.Object-) | El método realiza una comparación de igualdad entre la instancia actual de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) y otro objeto proporcionado como parámetro. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | El método "rotateFlip" permite operaciones de rotación y volteo en la imagen. |
| [hashCode()](#hashCode--) | Obtiene el código hash de la instancia actual. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la imagen a una región especificada. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recorta la imagen especificando desplazamientos para los bordes izquierdo, derecho, superior e inferior. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen aplicando configuraciones específicas para mantener las dimensiones y la relación de aspecto deseadas. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ajusta el tamaño de la imagen usando un tipo de redimensionamiento especificado, que determina cómo se realiza la operación de redimensionado. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rota la imagen alrededor de su centro mediante un ángulo especificado mientras mantiene la proporcionalidad del redimensionado y preserva el color de fondo. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Inicializa un nuevo objeto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) utilizando la ruta de archivo proporcionada para cargar el contenido de la imagen. Este constructor inicializa eficientemente la instancia de la imagen, permitiendo un acceso sin problemas a los archivos de imagen TGA, simplificando la integración en el flujo de trabajo de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta para cargar una imagen. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Cree una nueva instancia de la clase [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) proporcionando un objeto de imagen raster. Este constructor facilita la integración directa de imágenes raster existentes en el formato de imagen TGA, optimizando el proceso de conversión para una mayor compatibilidad dentro de sus sistemas de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Inicialice una nueva instancia de la clase [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) usando un flujo para cargar la imagen. Este constructor permite una integración sin problemas de datos de imagen desde flujos, facilitando el manejo y procesamiento eficiente de imágenes TGA dentro de sus aplicaciones de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupere el valor de bits por píxel, proporcionando información esencial sobre la profundidad de color de la imagen. Esta propiedad sirve como una métrica crucial para comprender el nivel de detalle y la riqueza de color presente en la imagen, ayudando a los desarrolladores a optimizar los algoritmos de procesamiento y la asignación de recursos para una manipulación y renderizado de imágenes eficientes.

**Returns:**
int - bits por píxel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Obtenga el valor de bytes por píxel, que indica la cantidad de memoria ocupada por cada píxel en la imagen. Esta propiedad sirve como una métrica crucial para la gestión y optimización de la memoria, ayudando a los desarrolladores a asignar recursos y procesar datos de imagen de manera eficiente.

**Returns:**
int - bytes por píxel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Recupere un valor booleano que indique si el [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) incluye un canal alfa, facilitando efectos de transparencia. Esta propiedad proporciona información esencial para el manejo de la composición y renderizado de imágenes, asistiendo a los desarrolladores en la implementación de diversos efectos visuales y operaciones de composición.

**Returns:**
boolean - un valor que indica si este [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) tiene un canal alfa.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Obtenga un valor booleano que indique si el [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) representa una imagen en escala de grises. Esta propiedad es crucial para distinguir entre imágenes en color y en escala de grises, ayudando a los desarrolladores a aplicar técnicas de procesamiento y renderizado apropiadas según las características de color de la imagen.

**Returns:**
boolean - un valor que indica si este [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) está en escala de grises.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Recupere el ancho de la imagen representada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Esta propiedad brinda a los desarrolladores información esencial sobre las dimensiones de la imagen, facilitando diversas tareas de manipulación y procesamiento de imágenes dentro de sus aplicaciones de software.

**Returns:**
int - el ancho de esta imagen en píxeles.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtenga la altura de la imagen encapsulada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Esta propiedad proporciona a los desarrolladores detalles críticos sobre las dimensiones verticales de la imagen, permitiendo una integración y manipulación sin problemas de las imágenes dentro de sus soluciones de software.

**Returns:**
int - la altura de esta imagen en píxeles.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtener información crucial sobre el formato de archivo de la imagen representada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Comprender el formato de archivo es esencial para verificaciones de compatibilidad y para garantizar una integración fluida dentro de los sistemas de software, permitiendo un procesamiento y manipulación eficientes de las imágenes.

**Returns:**
long - información crucial sobre el formato de archivo de la imagen representada por esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Recuperar si esta instancia de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) contiene un mapa de colores. Comprender la presencia de un mapa de colores es crucial para una interpretación y manipulación precisas de los datos de color de la imagen.

**Returns:**
boolean - un valor que indica si esta imagen tiene mapa de colores.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Obtiene la parte numeradora del valor gamma, que es esencial para una representación de color precisa en las imágenes. En imágenes sin corrección gamma, este valor debe ser 1.0. Comprender y utilizar este valor es crucial para mantener la fidelidad del color y garantizar una renderización de imagen precisa.

**Returns:**
int - la parte numeradora del valor gamma, que es esencial para una representación de color precisa en las imágenes.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Recupera la parte denominadora del valor gamma, un factor integral para determinar la representación del color dentro de las imágenes. Para imágenes sin corrección gamma, este valor debe ser 1.0, garantizando una renderización de color precisa. Apreciar y aprovechar este parámetro es fundamental para mantener la fidelidad del color y lograr una visualización de imagen precisa.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Recupera el componente numerador de la Relación de Aspecto de Píxel, que influye en el aspecto visual de los píxeles dentro de la imagen. Comprender y manipular este valor es esencial para lograr una representación precisa de los píxeles y relaciones de aspecto en la renderización y procesamiento de imágenes.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Recupera la parte denominadora de la Relación de Aspecto de Píxel, un factor crucial para determinar el aspecto visual de los píxeles dentro de la imagen. Este valor es esencial para preservar una representación precisa de los píxeles y relaciones de aspecto a lo largo de diversas operaciones de renderizado y procesamiento de imágenes, garantizando una salida visual de alta calidad.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Obtiene la coordenada horizontal absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA).

**Returns:**
int - coordenada horizontal absoluta para la esquina inferior izquierda de la imagen tal como se posiciona en un dispositivo de visualización que tiene su origen en la esquina inferior izquierda de la pantalla.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Establece la coordenada horizontal absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | coordenada horizontal absoluta para la esquina inferior izquierda de la imagen tal como se posiciona en un dispositivo de visualización que tiene su origen en la esquina inferior izquierda de la pantalla. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Obtiene la coordenada vertical absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA).

**Returns:**
int - coordenada vertical absoluta para la esquina inferior izquierda de la imagen tal como se posiciona en un dispositivo de visualización que tiene su origen en la esquina inferior izquierda de la pantalla.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Establece la coordenada vertical absoluta de la esquina inferior izquierda de la imagen según se posiciona en un dispositivo de visualización que tiene el origen en la esquina inferior izquierda de la pantalla (p. ej., la serie TARGA).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | coordenada vertical absoluta para la esquina inferior izquierda de la imagen tal como se posiciona en un dispositivo de visualización que tiene su origen en la esquina inferior izquierda de la pantalla. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Obtiene el identificador único asociado con la imagen. Este ID sirve como punto de referencia para identificar y distinguir la imagen de otras dentro de un sistema o aplicación. Al establecer o recuperar el ID de Imagen, puedes gestionar y rastrear imágenes de manera eficaz, facilitando procesos organizados de gestión y recuperación de imágenes.

Este campo opcional contiene información de identificación sobre la imagen. La longitud máxima para este campo es de 255 bytes.

**Returns:**
java.lang.String - el identificador único asociado con la imagen.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Establece el identificador único asociado con la imagen. Este ID sirve como punto de referencia para identificar y distinguir la imagen de otras dentro de un sistema o aplicación. Al establecer o recuperar el ID de Imagen, puedes gestionar y rastrear imágenes de manera eficaz, facilitando procesos organizados de gestión y recuperación de imágenes.

Este campo opcional contiene información de identificación sobre la imagen. La longitud máxima para este campo es de 255 bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el identificador único asociado con la imagen. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Recupera o establece los comentarios proporcionados por el autor de la imagen. Estos comentarios a menudo contienen información valiosa, como descripciones, anotaciones o contexto adicional sobre la imagen. Al acceder o modificar la propiedad Comentarios del Autor, los desarrolladores pueden mejorar los metadatos asociados con la imagen, proporcionando a los usuarios información y contexto valiosos sobre su contenido o creación. Este es un campo ASCII de 324 bytes que se organiza en cuatro líneas de 80 caracteres, cada una seguida de un terminador nulo.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Recupera o establece los comentarios proporcionados por el autor de la imagen. Estos comentarios a menudo contienen información valiosa, como descripciones, anotaciones o contexto adicional sobre la imagen. Al acceder o modificar la propiedad Comentarios del Autor, los desarrolladores pueden mejorar los metadatos asociados con la imagen, proporcionando a los usuarios información y contexto valiosos sobre su contenido o creación. Este es un campo ASCII de 324 bytes que se organiza en cuatro líneas de 80 caracteres, cada una seguida de un terminador nulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Recupera o establece el nombre del autor asociado con la imagen. Esta propiedad permite a los desarrolladores acceder o modificar los metadatos del nombre del autor, proporcionando información valiosa sobre el creador de la imagen. Al utilizar la propiedad Nombre del Autor, los usuarios pueden identificar fácilmente a la persona responsable de crear o contribuir a la imagen, mejorando sus metadatos generales y proporcionando contexto valioso para los espectadores. Este campo tiene un total de 40 caracteres ASCII para el nombre. Si se usa el campo, debe contener el nombre de la persona que creó la imagen (autor).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Recupera o establece el nombre del autor asociado con la imagen. Esta propiedad permite a los desarrolladores acceder o modificar los metadatos del nombre del autor, proporcionando información valiosa sobre el creador de la imagen. Al utilizar la propiedad Nombre del Autor, los usuarios pueden identificar fácilmente a la persona responsable de crear o contribuir a la imagen, mejorando sus metadatos generales y proporcionando contexto valioso para los espectadores. Este campo tiene un total de 40 caracteres ASCII para el nombre. Si se usa el campo, debe contener el nombre de la persona que creó la imagen (autor).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nombre del Autor. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Obtiene la Marca de Fecha/Hora. Este campo define el valor para la fecha y hora en que la imagen fue guardada. Aunque los sistemas operativos normalmente marcan con fecha y hora los archivos, esta característica se proporciona porque el sistema operativo puede cambiar la marca de fecha y hora si el archivo se copia. Al usar esta área, se garantiza una región no modificada para el registro de fecha y hora.

**Returns:**
java.util.Date - Marca de Fecha/Hora.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Establece la marca de fecha/hora. Este campo define el valor para la fecha y hora en que se guardó la imagen. Aunque los sistemas operativos suelen marcar los archivos con fecha y hora, esta característica se proporciona porque el sistema operativo puede cambiar la marca de fecha y hora si el archivo se copia. Al usar esta área, se garantiza una región no modificada para el registro de fecha y hora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date | Marca de fecha/hora. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Recupera o establece el nombre o ID del trabajo asociado con la imagen. Esta propiedad le permite acceder o modificar los metadatos relacionados con el trabajo o proyecto específico asociado con la imagen. Al utilizar la propiedad Job Name/ID, los usuarios pueden identificar fácilmente el proyecto o tarea al que pertenece la imagen, facilitando la organización y gestión de los recursos de imagen dentro de flujos de trabajo o proyectos más amplios.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Recupera o establece el nombre o ID del trabajo asociado con la imagen. Esta propiedad le permite acceder o modificar los metadatos relacionados con el trabajo o proyecto específico asociado con la imagen. Al utilizar la propiedad Job Name/ID, los usuarios pueden identificar fácilmente el proyecto o tarea al que pertenece la imagen, facilitando la organización y gestión de los recursos de imagen dentro de flujos de trabajo o proyectos más amplios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Recupera o establece la marca de tiempo que indica la hora del trabajo asociada con la imagen. Esta propiedad permite a los desarrolladores acceder o modificar los metadatos de tiempo relacionados con el trabajo o proyecto específico asociado con la imagen.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Recupera o establece la marca de tiempo que indica la hora del trabajo asociada con la imagen. Esta propiedad permite a los desarrolladores acceder o modificar los metadatos de tiempo relacionados con el trabajo o proyecto específico asociado con la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Recupera o establece el color clave asociado con la imagen. Esta propiedad le permite acceder o modificar el color designado como color clave para tareas o efectos específicos de procesamiento de imágenes. Utilizar la propiedad Key Color permite a los usuarios aplicar operaciones basadas en color, como croma o sustitución de color, mejorando las capacidades de manipulación de imágenes y las posibilidades creativas.

El Color Clave puede considerarse como el \\u2018color de fondo\\u2019 o \\u2018color transparente\\u2019. Este es el color del área \\u2018non image\\u2019 de la pantalla, y el mismo color al que se borraría la pantalla si se elimina en la aplicación.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Recupera o establece el color clave asociado con la imagen. Esta propiedad le permite acceder o modificar el color designado como color clave para tareas o efectos específicos de procesamiento de imágenes. Utilizar la propiedad Key Color permite a los usuarios aplicar operaciones basadas en color, como croma o sustitución de color, mejorando las capacidades de manipulación de imágenes y las posibilidades creativas.

El Color Clave puede considerarse como el \\u2018color de fondo\\u2019 o \\u2018color transparente\\u2019. Este es el color del área \\u2018non image\\u2019 de la pantalla, y el mismo color al que se borraría la pantalla si se elimina en la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Recupera o establece un valor booleano que indica si la imagen contiene un color transparente. Esta propiedad es esencial para identificar si la imagen admite transparencia, ayudándole a implementar el manejo adecuado de operaciones relacionadas con la transparencia, como mezcla, composición o enmascarado.

**Returns:**
boolean - un valor que indica si la imagen tiene color transparente.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Recupera o establece un valor booleano que indica si la imagen contiene un color transparente. Esta propiedad es esencial para identificar si la imagen admite transparencia, ayudándole a implementar el manejo adecuado de operaciones relacionadas con la transparencia, como mezcla, composición o enmascarado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si la imagen tiene color transparente. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Recupera o establece el color de fondo de la imagen. Esta propiedad le permite especificar el color utilizado para el fondo de la imagen, asegurando consistencia y mejorando la presentación visual. Es particularmente útil para escenarios donde la imagen se muestra sobre un fondo de color diferente o al renderizar la imagen en otro lienzo.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Recupera o establece el color de fondo de la imagen. Esta propiedad le permite especificar el color utilizado para el fondo de la imagen, asegurando consistencia y mejorando la presentación visual. Es particularmente útil para escenarios donde la imagen se muestra sobre un fondo de color diferente o al renderizar la imagen en otro lienzo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | el color de fondo. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Recupera o establece un valor que indica si la imagen contiene un color de fondo. Esta propiedad es útil para determinar si la imagen incluye un color de fondo distinto del contenido principal. Le permite personalizar el procesamiento o renderizado de la imagen según la presencia o ausencia de un color de fondo.

**Returns:**
boolean - un valor que indica si la imagen tiene color de fondo.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Recupera o establece un valor que indica si la imagen contiene un color de fondo. Esta propiedad es útil para determinar si la imagen incluye un color de fondo distinto del contenido principal. Le permite personalizar el procesamiento o renderizado de la imagen según la presencia o ausencia de un color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si la imagen tiene color de fondo. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Recupera o establece la versión del software asociada con la imagen. La longitud aceptada para la cadena de versión es típicamente de 3 a 4 caracteres. Esta propiedad es útil para rastrear el software utilizado para crear o manipular la imagen y puede proporcionar un contexto valioso para el procesamiento de imágenes y verificaciones de compatibilidad.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Recupera o establece la versión del software asociada con la imagen. La longitud aceptada para la cadena de versión es típicamente de 3 a 4 caracteres. Esta propiedad es útil para rastrear el software utilizado para crear o manipular la imagen y puede proporcionar un contexto valioso para el procesamiento de imágenes y verificaciones de compatibilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Versión del software. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Recupera o establece el componente de letra de la versión del software asociada con la imagen. Esta propiedad representa un detalle adicional dentro de la cadena de versión del software y puede ser útil para una diferenciación de versiones más fina.

**Returns:**
char - Parte de letra de la versión del software.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Recupera o establece el componente de letra de la versión del software asociada con la imagen. Esta propiedad representa un detalle adicional dentro de la cadena de versión del software y puede ser útil para una diferenciación de versiones más fina.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char | Parte de letra de la versión del software. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Obtiene o establece el componente numérico de la versión del software asociada con la imagen. Esta propiedad representa la parte numérica de la cadena de versión del software, proporcionando información importante sobre la versión del software utilizada para crear o modificar la imagen.

**Returns:**
int - Parte numérica de la versión del software.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Obtiene o establece el componente numérico de la versión del software asociada con la imagen. Esta propiedad representa la parte numérica de la cadena de versión del software, proporcionando información importante sobre la versión del software utilizada para crear o modificar la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Parte numérica de la versión del software. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Gestiona la identificación del software (ID) asociada con la imagen, permitiendo hasta 40 caracteres ASCII. Esta propiedad sirve como medio para identificar de forma única el software utilizado en la creación o procesamiento de la imagen, proporcionando metadatos valiosos para fines organizativos e informativos.

**Returns:**
java.lang.String - ID del software.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Gestiona la identificación del software (ID) asociada con la imagen, permitiendo hasta 40 caracteres ASCII. Esta propiedad sirve como medio para identificar de forma única el software utilizado en la creación o procesamiento de la imagen, proporcionando metadatos valiosos para fines organizativos e informativos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | ID del software. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Realiza una comparación de igualdad entre dos imágenes TGA, considerando tanto la primera como la segunda imagen involucradas en el proceso de comparación. Este método facilita una evaluación directa de la igualdad de imágenes, garantizando un análisis preciso y una toma de decisiones adecuada dentro de los flujos de trabajo de procesamiento de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Primera [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) que participa en la comparación. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Segunda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) que participa en la comparación. |

**Returns:**
boolean - Resultados de la comparación.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Realiza una comparación de desigualdad entre dos imágenes TGA, evaluando tanto la primera como la segunda imagen involucradas en la comparación. Este método ayuda a identificar discrepancias o diferencias entre imágenes, permitiendo un análisis preciso y una toma de decisiones en tareas de procesamiento de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Primera [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) que participa en la comparación. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Segunda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) que participa en la comparación. |

**Returns:**
boolean - Resultados de la comparación.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Produce un duplicado de la instancia actual, generando un nuevo objeto que clona todos los atributos y propiedades del original. Este método facilita la creación de copias idénticas, garantizando la integridad de los datos y preservando el estado de la instancia actual sin afectar al objeto original.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Replica las propiedades de otro objeto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), creando una nueva instancia con atributos idénticos. Esta operación asegura la preservación de la integridad de los datos y facilita la duplicación de las propiedades de la imagen sin alterar el objeto fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Otro [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


En una comparación de igualdad, el método evalúa si la instancia actual de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) es igual a la segunda imagen proporcionada como parámetro. Esta operación facilita determinar si dos imágenes TGA son idénticas, ayudando en tareas de procesamiento y comparación de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Segunda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) que participa en la comparación. |

**Returns:**
boolean - Resultados de la comparación.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


El método realiza una comparación de igualdad entre la instancia actual de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) y otro objeto proporcionado como parámetro. Específicamente, evalúa si las propiedades de la imagen actual coinciden con las del segundo objeto, ayudando a determinar su equivalencia para propósitos de comparación dentro de los flujos de trabajo de procesamiento de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | java.lang.Object | Segunda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) que participa en la comparación. |

**Returns:**
boolean - Resultados de la comparación.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


El método "rotateFlip" permite operaciones de rotación y volteo en la imagen. Ofrece una funcionalidad versátil para manipular la orientación de la imagen, permitiendo a los usuarios realizar rotaciones y volteos según sus requisitos, facilitando tareas eficientes de procesamiento de imágenes dentro de aplicaciones de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtenga el código hash de la instancia actual. Sin embargo, es importante notar que este código hash puede no ser adecuado para usar como clave, particularmente porque las instancias de la clase TgaImage no son inmutables.

**Returns:**
int - Código hash de esta instancia.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorte la imagen a una región especificada. Este método le permite definir un área rectangular dentro de la imagen para conservar, descartando el resto. Esta operación es útil para enfocarse en contenido específico dentro de la imagen o eliminar porciones no deseadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recorte la imagen especificando desplazamientos para los límites izquierdo, derecho, superior e inferior. Este método le permite recortar la imagen moviendo sus límites de forma independiente a lo largo de los ejes horizontal y vertical. Al ajustar estos desplazamientos, puede controlar con precisión qué porciones de la imagen conservar, recortándola efectivamente a las dimensiones deseadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento derecho. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensione la imagen aplicando configuraciones específicas para mantener las dimensiones y la relación de aspecto deseadas. Al personalizar la configuración de la imagen, puede redimensionar la imagen de manera eficaz asegurando una calidad visual óptima y compatibilidad con diferentes dispositivos de visualización o aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ajusta el tamaño de la imagen usando un tipo de redimensionado especificado, que determina cómo se realiza la operación de redimensionado. Este método brinda flexibilidad para redimensionar imágenes según diferentes algoritmos o técnicas. Al elegir el tipo de redimensionado apropiado, puede lograr el equilibrio deseado entre la calidad de la imagen y la eficiencia computacional según requisitos o preferencias específicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Gira la imagen alrededor de su centro mediante un ángulo especificado mientras mantiene la proporcionalidad del redimensionado y preserva el color de fondo. Este método permite una manipulación precisa de la imagen, asegurando que la rotación mantenga el equilibrio visual y la consistencia con el color de fondo especificado. Es ideal para tareas donde se requiere una rotación exacta alrededor del centro, como la corrección de orientación o ajustes artísticos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); de lo contrario, se dejarán las dimensiones sin cambios y solo `` el contenido de la imagen será rotado. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

