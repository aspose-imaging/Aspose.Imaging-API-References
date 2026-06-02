---
title: "ImageOptionsBase"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones base de la imagen."
type: docs
weight: 62
url: /es/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Las opciones base de la imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| [getXmpData()](#getXmpData--) | Obtiene el contenedor de metadatos XMP. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Establece el contenedor de metadatos XMP. |
| [getExifData()](#getExifData--) | Obtiene los datos Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Establece los datos Exif. |
| [getSource()](#getSource--) | Obtiene la fuente donde crear la imagen. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Obtiene o establece la fuente donde crear la imagen. |
| [getPalette()](#getPalette--) | Obtiene la paleta de colores. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Establece la paleta de colores. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene la configuración de resolución. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Establece la configuración de resolución. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtiene las opciones de rasterización vectorial. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Establece las opciones de rasterización vectorial. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Las opciones multipágina |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Las opciones multipágina |
| [getFullFrame()](#getFullFrame--) | Obtiene un valor que indica si [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Establece un valor que indica si [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene el controlador del evento de progreso. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Establece el controlador del evento de progreso. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Intenta establecer una instancia `metadata`, si esta instancia [Image](../../com.aspose.imaging/image) admite e implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar.

**Returns:**
boolean - un valor que indica si mantener los metadatos de imagen originales al exportar.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Un valor que indica si conservar los metadatos originales de la imagen al exportar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si mantener los metadatos de imagen originales al exportar. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtiene el contenedor de metadatos XMP.

Valor: El contenedor de datos XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Establece el contenedor de metadatos XMP.

Valor: El contenedor de datos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | el contenedor de metadatos XMP. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtiene los datos Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Establece los datos Exif.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | los datos Exif. |

### getSource() {#getSource--}
```
public Source getSource()
```


Obtiene la fuente donde crear la imagen.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Obtiene o establece la fuente donde crear la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | La fuente donde crear la imagen. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtiene la paleta de colores.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Establece la paleta de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Crea una imagen BMP de 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // El degradado lineal desde la esquina superior izquierda a la esquina inferior derecha de la imagen.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Rellena toda la imagen con el pincel de degradado lineal.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // La paleta de 8 bits contiene como máximo 256 colores.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// La salida se ve así:
// El tamaño de la imagen paletizada es 11078 bytes.
// El tamaño de la imagen no paletizada es 40054 bytes.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtiene la configuración de resolución.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Establece la configuración de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Realizar algún procesamiento de imagen.

    // Utilice opciones adicionales para especificar los parámetros de imagen deseados.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // El número de bits por canal es 8.
    // Cuando se usa una paleta, el índice de color se almacena en los datos de la imagen en lugar del color mismo.
    saveOptions.setBitsPerChannel((byte) 8);

    // Establezca el tipo progresivo de compresión.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Establezca la calidad de la imagen. Es un valor entre 1 y 100.
    saveOptions.setQuality(100);

    // Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Si la imagen de origen está coloreada, se convertirá a escala de grises.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilice una paleta para reducir el tamaño de salida.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtiene las opciones de rasterización vectorial.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Establece las opciones de rasterización vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Las opciones de rasterización vectorial. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int - la sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos. |

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Las opciones multipágina

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Las opciones multipágina

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtiene un valor que indica si [full frame].

Valor: `true` si [full frame]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Establece un valor que indica si [full frame].

Valor: `true` si [full frame]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Obtiene el controlador del evento de progreso.

Valor: El controlador de evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Establece el controlador del evento de progreso.

Valor: El controlador de evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | el controlador de evento de progreso. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Ejemplo de uso de controladores de eventos de progreso de operación separados para operaciones de carga/exportación
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// El registro STDOUT puede verse así:
//        Evento de carga Inicialización : 1/4
//        Evento de carga Preprocesamiento : 2/4
//        Evento de carga Procesamiento : 3/4
//        Evento de carga Finalización : 4/4
//        Evento de exportación Inicialización : 1/4
//        Evento de exportación Preprocesamiento : 2/4
//        Evento de exportación Procesamiento : 3/4
//        Evento de exportación ProgresoRelativo : 1/1
//        Evento de carga ProgresoRelativo : 1/1
//        Evento de exportación Finalización : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona esta instancia.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Intenta establecer una instancia `metadata`, si esta instancia [Image](../../com.aspose.imaging/image) admite e implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Los metadatos. |

**Returns:**
boolean - Verdadero, si la instancia [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) admite y/o implementa la instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); de lo contrario, falso.
