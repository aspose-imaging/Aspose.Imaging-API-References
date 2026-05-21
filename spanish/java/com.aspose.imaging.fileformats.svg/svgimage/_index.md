---
title: "SvgImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule archivos de imágenes SVG de Scalar Vector Graphics con nuestra API, utilizando el poder del formato de texto basado en XML para una personalización y escalabilidad sin problemas."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Manipule archivos de imágenes Scalar Vector Graphics (SVG) con nuestra API, utilizando el poder del formato de texto basado en XML para una personalización y escalabilidad sin problemas. Cargue fácilmente imágenes SVG, rasterice elementos vectoriales y conviértalas a otros formatos, mientras controla los niveles de compresión para optimizar el tamaño y la calidad del archivo en sus proyectos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Instancia un nuevo objeto de la clase [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), utilizando la ruta especificada para localizar y cargar la imagen. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Crea una nueva instancia de la clase [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), cargando la imagen desde el flujo proporcionado. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Instancia un nuevo objeto [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con el ancho y alto especificados. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Crea una nueva instancia de la clase [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con opciones SVG especificadas, ancho de imagen y parámetros de altura. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isCached()](#isCached--) | Obtiene un valor booleano que indica si los datos del objeto están actualmente en caché, eliminando la necesidad de operaciones adicionales de lectura de datos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene el recuento de bits por píxel de la imagen. |
| [getFileFormat()](#getFileFormat--) | Obtiene el formato de archivo de la imagen, proporcionando metadatos esenciales para el procesamiento y la verificación de compatibilidad. |
| [cacheData()](#cacheData--) | Cache los datos y garantice que no habrá más cargas de datos desde el `DataStreamSupporter.DataStreamContainer` subyacente ([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensione la imagen para ajustarse a las dimensiones especificadas manteniendo su relación de aspecto. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta el rectángulo especificado. |
| [rotate(float angle)](#rotate-float-) | Rota la imagen alrededor del centro. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Aplica una paleta especificada a la imagen, permitiendo la personalización de esquemas de color con fines estéticos o funcionales. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Cargue una imagen SVG desde un flujo de archivo.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // Para rasterizar SVG necesitamos especificar opciones de rasterización.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
El siguiente ejemplo muestra cómo convertir imágenes comprimidas (*.emz,*.wmz, *.svgz) a formato raster.
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Instancia un nuevo objeto de la clase [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), utilizando la ruta especificada para localizar y cargar la imagen. Este constructor facilita la creación de instancias de imágenes SVG a partir de archivos externos, permitiendo una integración sin problemas en sistemas y flujos de trabajo de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Crea una nueva instancia de la clase [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), cargando la imagen desde el flujo proporcionado. Este constructor permite la carga directa de imágenes SVG desde flujos, mejorando la flexibilidad y eficiencia en el manejo de recursos de imagen dentro de aplicaciones de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Instancia un nuevo objeto [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con el ancho y alto especificados. Este constructor permite a los desarrolladores crear imágenes SVG con dimensiones predefinidas, facilitando un control preciso sobre el tamaño de la imagen durante la inicialización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Crea una nueva instancia de la clase [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con opciones SVG especificadas, ancho de imagen y parámetros de altura. Este constructor permite a los desarrolladores inicializar imágenes SVG con opciones y dimensiones personalizadas, proporcionando flexibilidad en la gestión del contenido y diseño SVG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | Las opciones SVG. |
| width | int | Ancho de imagen. |
| height | int | Altura de la imagen. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor booleano que indica si los datos del objeto están actualmente en caché, eliminando la necesidad de operaciones adicionales de lectura de datos. Esta propiedad brinda información sobre el estado actual de la caché, optimizando la recuperación y el procesamiento de datos para mejorar el rendimiento y la eficiencia.

**Returns:**
boolean - `true` si los datos del objeto están en caché; de lo contrario, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen. Es importante señalar que este parámetro no es aplicable a imágenes vectoriales, ya que no se miden en píxeles. Esta propiedad proporciona información crucial sobre la profundidad de color de la imagen, ayudando en tareas de procesamiento y manipulación.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtiene el formato de archivo de la imagen, proporcionando metadatos esenciales para el procesamiento y la verificación de compatibilidad. Esta propiedad es fundamental para determinar las estrategias de decodificación y codificación apropiadas para manejar los datos de la imagen de manera eficaz en diferentes sistemas y aplicaciones.

**Returns:**
long - formato de archivo
### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos y garantiza que no habrá más cargas de datos desde el `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Esta optimización mejora el rendimiento al eliminar operaciones redundantes de recuperación de datos, siendo especialmente útil en escenarios que requieren acceso frecuente a los datos de la imagen.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona la imagen para ajustarla a las dimensiones especificadas manteniendo su relación de aspecto. Este método ofrece una forma conveniente de ajustar el tamaño de la imagen sin distorsionar sus proporciones, garantizando una visualización o almacenamiento óptimo según las dimensiones deseadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rota la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Aplica una paleta especificada a la imagen, permitiendo la personalización de esquemas de color con fines estéticos o funcionales. Este método brinda flexibilidad en la gestión de paletas de colores para adaptarse a diversos requisitos de diseño o aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

