---
title: "TiffOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones del formato de archivo TIFF."
type: docs
weight: 48
url: /es/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Las opciones del formato de archivo TIFF. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán al crear la imagen mediante los parámetros de ancho y alto, por lo que no es necesario especificarlas directamente. Observe que muchas opciones devuelven un valor predeterminado, pero eso no significa que esta opción esté establecida explícitamente como valor de etiqueta. Para verificar que la etiqueta está presente, use la propiedad Tags o el método correspondiente IsTagPresent.

` ADVERTENCIA! nunca modifique las opciones tiff durante el guardado ya que esto puede causar efectos secundarios y errores difíciles de encontrar. La siguiente línea se dejó especialmente comentada porque provocó una determinación incorrecta del inicio de los datos. Las opciones pasadas no contenían spp (aunque las opciones no son correctas en tal caso, este escenario aún causa errores) y la siguiente línea provocó la adición de la etiqueta +spp y la etiqueta +bpp y cuando las opciones se escribieron después de que los datos se escribieron completamente, sobrescribieron el inicio de los datos para el códec sin comprimir!!! Ver TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Inicializa una nueva instancia de la clase `TiffOptions`. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Inicializa una nueva instancia de la clase `TiffOptions`. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Inicializa una nueva instancia de la clase `TiffOptions`. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase `TiffOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtiene el recuento de etiquetas válidas. |
| [getTagCount()](#getTagCount--) | Obtiene el recuento de etiquetas. |
| [getFileStandard()](#getFileStandard--) | Obtiene o establece el estándar de archivo TIFF. |
| [setFileStandard(int value)](#setFileStandard-int-) | Obtiene o establece el estándar de archivo TIFF. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtiene o establece el límite predeterminado de asignación de memoria. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Obtiene o establece el límite predeterminado de asignación de memoria. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtiene o establece un valor que indica si los componentes deben estar premultiplicados. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtiene o establece un valor que indica si los componentes deben estar premultiplicados. |
| [isValid()](#isValid--) | Obtiene un valor que indica si el `TiffOptions` ha sido configurado correctamente. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Obtiene o establece los factores de submuestreo para la fotometría YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Obtiene o establece los factores de submuestreo para la fotometría YCbCr. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtiene o establece los YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece los YCbCrCoefficients. |
| [isTiled()](#isTiled--) | Obtiene un valor que indica si la imagen está en mosaico. |
| [getArtist()](#getArtist--) | Obtiene o establece el artista. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtiene o establece el artista. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Determina si la etiqueta está presente en las opciones o no. |
| [getByteOrder()](#getByteOrder--) | Obtiene o establece un valor que indica el orden de bytes del TIFF. |
| [setByteOrder(int value)](#setByteOrder-int-) | Obtiene o establece un valor que indica el orden de bytes del TIFF. |
| [getIccProfile()](#getIccProfile--) | Obtiene el flujo del perfil ICC. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Establece el flujo del perfil ICC. |
| [isDisableIccExport()](#isDisableIccExport--) | Obtiene un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen previamente). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Establece un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen previamente). |
| [getBitsPerSample()](#getBitsPerSample--) | Obtiene los bits por muestra. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Establece los bits por muestra. |
| [getExtraSamples()](#getExtraSamples--) | Obtiene los valores de muestras adicionales. |
| [getCompression()](#getCompression--) | Obtiene la compresión. |
| [setCompression(int value)](#setCompression-int-) | Establece la compresión. |
| [getCompressedQuality()](#getCompressedQuality--) | Obtiene la calidad de la imagen comprimida. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Establece la calidad de la imagen comprimida. |
| [getCopyright()](#getCopyright--) | Obtiene el copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Establece el copyright. |
| [getColorMap()](#getColorMap--) | Obtiene o establece el mapa de colores. |
| [setColorMap(int[] value)](#setColorMap-int---) | Obtiene o establece el mapa de colores. |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Obtiene o establece la paleta de colores. |
| [getDateTime()](#getDateTime--) | Obtiene o establece la fecha y hora. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtiene o establece la fecha y hora. |
| [getDocumentName()](#getDocumentName--) | Obtiene o establece el nombre del documento. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Obtiene o establece el nombre del documento. |
| [getAlphaStorage()](#getAlphaStorage--) | Obtiene o establece la opción de almacenamiento alfa. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Obtiene o establece la opción de almacenamiento alfa. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Obtiene un valor que indica si las muestras extra están presentes. |
| [getFillOrder()](#getFillOrder--) | Obtiene o establece el orden de relleno de bits de byte. |
| [setFillOrder(int value)](#setFillOrder-int-) | Obtiene o establece el orden de relleno de bits de byte. |
| [getHalfToneHints()](#getHalfToneHints--) | Obtiene o establece las sugerencias de semitono. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Obtiene o establece las sugerencias de semitono. |
| [getImageDescription()](#getImageDescription--) | Obtiene o establece la descripción de la imagen. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtiene o establece la descripción de la imagen. |
| [getInkNames()](#getInkNames--) | Obtiene o establece los nombres de tinta. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Obtiene o establece los nombres de tinta. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Obtiene o establece el fabricante del escáner. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Obtiene o establece el fabricante del escáner. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Obtiene o establece el valor máximo de muestra. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Obtiene o establece el valor máximo de muestra. |
| [getMinSampleValue()](#getMinSampleValue--) | Obtiene o establece el valor mínimo de muestra. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Obtiene o establece el valor mínimo de muestra. |
| [getScannerModel()](#getScannerModel--) | Obtiene o establece el modelo del escáner. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Obtiene o establece el modelo del escáner. |
| [getOrientation()](#getOrientation--) | Obtiene o establece la orientación. |
| [setOrientation(int value)](#setOrientation-int-) | Obtiene o establece la orientación. |
| [getPageName()](#getPageName--) | Obtiene o establece el nombre de página. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Obtiene o establece el nombre de página. |
| [getPageNumber()](#getPageNumber--) | Obtiene o establece la etiqueta de número de página. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Obtiene o establece la etiqueta de número de página. |
| [getPhotometric()](#getPhotometric--) | Obtiene o establece el fotométrico. |
| [setPhotometric(int value)](#setPhotometric-int-) | Obtiene o establece el fotométrico. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtiene o establece la configuración planar. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtiene o establece la configuración planar. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtiene o establece la unidad de resolución. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtiene o establece la unidad de resolución. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Obtiene o establece las filas por tira. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Obtiene o establece las filas por tira. |
| [getTileWidth()](#getTileWidth--) | Obtiene o establece el ancho del mosaico. |
| [setTileWidth(long value)](#setTileWidth-long-) | Obtiene o establece el ancho del mosaico. |
| [getTileLength()](#getTileLength--) | Obtiene o establece la longitud del mosaico. |
| [setTileLength(long value)](#setTileLength-long-) | Obtiene o establece la longitud del mosaico. |
| [getSampleFormat()](#getSampleFormat--) | Obtiene o establece el formato de muestra. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Obtiene o establece el formato de muestra. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtiene las muestras por píxel. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Obtiene o establece el valor máximo de muestra. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Obtiene o establece el valor máximo de muestra. |
| [getSminSampleValue()](#getSminSampleValue--) | Obtiene o establece el valor mínimo de muestra. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Obtiene o establece el valor mínimo de muestra. |
| [getSoftwareType()](#getSoftwareType--) | Obtiene o establece el tipo de software. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Obtiene o establece el tipo de software. |
| [getStripByteCounts()](#getStripByteCounts--) | Obtiene o establece los recuentos de bytes de tira. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Obtiene o establece los recuentos de bytes de tira. |
| [getStripOffsets()](#getStripOffsets--) | Obtiene o establece los desplazamientos de la tira. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Obtiene o establece los desplazamientos de la tira. |
| [getTileByteCounts()](#getTileByteCounts--) | Obtiene o establece los recuentos de bytes de los mosaicos. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Obtiene o establece los recuentos de bytes de los mosaicos. |
| [getTileOffsets()](#getTileOffsets--) | Obtiene o establece los desplazamientos de los mosaicos. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Obtiene o establece los desplazamientos de los mosaicos. |
| [getSubFileType()](#getSubFileType--) | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| [setSubFileType(long value)](#setSubFileType-long-) | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| [getTargetPrinter()](#getTargetPrinter--) | Obtiene o establece la impresora de destino. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Obtiene o establece la impresora de destino. |
| [getThreshholding()](#getThreshholding--) | Obtiene o establece el umbral. |
| [setThreshholding(int value)](#setThreshholding-int-) | Obtiene o establece el umbral. |
| [getTotalPages()](#getTotalPages--) | Obtiene el total de páginas. |
| [getXposition()](#getXposition--) | Obtiene o establece la posición x. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la posición x. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene o establece la configuración de resolución. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Obtiene o establece la configuración de resolución. |
| [getXresolution()](#getXresolution--) | Obtiene o establece la resolución x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución x. |
| [getYposition()](#getYposition--) | Obtiene o establece la posición y. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la posición y. |
| [getYresolution()](#getYresolution--) | Obtiene o establece la resolución y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución y. |
| [getFaxT4Options()](#getFaxT4Options--) | Obtiene o establece las opciones de fax t4. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Obtiene o establece las opciones de fax t4. |
| [getPredictor()](#getPredictor--) | Obtiene o establece el predictor para la compresión LZW. |
| [setPredictor(int value)](#setPredictor-int-) | Obtiene o establece el predictor para la compresión LZW. |
| [getImageLength()](#getImageLength--) | Obtiene o establece la longitud de la imagen. |
| [setImageLength(long value)](#setImageLength-long-) | Obtiene o establece la longitud de la imagen. |
| [getImageWidth()](#getImageWidth--) | Obtiene o establece el ancho de la imagen. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtiene o establece el ancho de la imagen. |
| [getExifIfd()](#getExifIfd--) | Obtiene o establece el puntero al IFD EXIF. |
| [getTags()](#getTags--) | Obtiene o establece las etiquetas. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtiene o establece las etiquetas. |
| [getValidTagCount()](#getValidTagCount--) | Obtiene el recuento de etiquetas válidas. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene los bits por píxel. |
| [getXPTitle()](#getXPTitle--) | Obtiene información sobre la imagen, que es utilizada por el Explorador de Windows. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Establece información sobre la imagen, que es utilizada por el Explorador de Windows. |
| [getXPComment()](#getXPComment--) | Obtiene el comentario de la imagen, que es utilizado por el Explorador de Windows. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Establece el comentario de la imagen, que es utilizado por el Explorador de Windows. |
| [getXPAuthor()](#getXPAuthor--) | Obtiene el autor de la imagen, que es utilizado por el Explorador de Windows. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Establece el autor de la imagen, que es utilizado por el Explorador de Windows. |
| [getXPKeywords()](#getXPKeywords--) | Obtiene la imagen de asunto, que es utilizada por el Explorador de Windows. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Establece la imagen del sujeto, que es utilizada por Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Obtiene información sobre la imagen, que es utilizada por el Explorador de Windows. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Establece información sobre la imagen, que es utilizada por el Explorador de Windows. |
| [getExifData()](#getExifData--) | Obtiene los datos Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Establece los datos Exif. |
| [removeTag(int tag)](#removeTag-int-) | Elimina la etiqueta. |
| [removeTags(int[] tags)](#removeTags-int...-) | Elimina las etiquetas. |
| [validate()](#validate--) | Valida si las opciones tienen una combinación válida de etiquetas. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Agrega las etiquetas. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Agrega una nueva etiqueta. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Obtiene la instancia de la etiqueta por tipo. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Este ejemplo muestra el uso de diferentes clases del espacio de nombres SaveOptions para propósitos de exportación. Se carga una imagen de tipo Gif en una instancia de Image y luego se exporta a varios formatos.
``` java
String dir = "c:\\temp\\";

//Cargar una imagen existente (de tipo Gif) en una instancia de la clase Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportar al formato de archivo BMP usando las opciones predeterminadas
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportar al formato de archivo JPEG usando las opciones predeterminadas
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportar al formato de archivo PNG usando las opciones predeterminadas
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportar al formato de archivo TIFF usando las opciones predeterminadas
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. Estas páginas se presentarán como fotogramas en el TIFF de salida.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Inicializa una nueva instancia de la clase `TiffOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expectedFormat | int | El formato de archivo TIFF esperado. |
| byteOrder | int | El orden de bytes del formato de archivo TIFF. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Inicializa una nueva instancia de la clase `TiffOptions`. Por defecto, se utiliza la convención little endian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expectedFormat | int | El formato de archivo TIFF esperado. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Inicializa una nueva instancia de la clase `TiffOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Las opciones de las que copiar. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Inicializa una nueva instancia de la clase `TiffOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas con las que inicializar las opciones. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Obtiene el recuento de etiquetas válidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas a validar. |

**Returns:**
int - El recuento de etiquetas válidas.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Obtiene el recuento de etiquetas.

**Returns:**
int - el recuento de etiquetas.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Obtiene o establece el estándar de archivo TIFF.

**Returns:**
int - El estándar de archivo TIFF.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Obtiene o establece el estándar de archivo TIFF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El estándar de archivo TIFF. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtiene o establece el límite predeterminado de asignación de memoria.

**Returns:**
int - El límite de asignación de memoria predeterminado.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Obtiene o establece el límite predeterminado de asignación de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El límite de asignación de memoria predeterminado. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtiene o establece un valor que indica si los componentes deben estar premultiplicados.

**Returns:**
boolean - `true` si los componentes deben estar premultiplicados; de lo contrario, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtiene o establece un valor que indica si los componentes deben estar premultiplicados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si los componentes deben estar premultiplicados; de lo contrario, `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Obtiene un valor que indica si `TiffOptions` ha sido configurado correctamente. Use el método Validate para encontrar la razón del fallo.

**Returns:**
boolean - `true` si TiffOptions está configurado correctamente; de lo contrario, `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Obtiene o establece los factores de submuestreo para la fotometría YCbCr.

**Returns:**
int[] - Los factores de submuestreo para la fotométrica YCbCr.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Obtiene o establece los factores de submuestreo para la fotometría YCbCr.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | Los factores de submuestreo para la fotométrica YCbCr. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 8 bits para cada componente de color.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Establece el orden de bytes Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Establece la compresión LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Permite reducir el tamaño de imágenes de tono continuo.
// Actualmente este campo se usa solo con codificación LZW porque LZW es probablemente el único esquema de codificación TIFF.
// que se beneficia significativamente de un paso predictor.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Establece el modelo de color RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Para YCbCr, puedes usar una de las siguientes opciones:
// Campo YCbCrSubSampling   Factores de muestreo JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valor predeterminado)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Todos los componentes de color se almacenarán en un solo plano.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un Frame TIFF de 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtiene o establece los YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Los YCbCrCoefficients.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtiene o establece los YCbCrCoefficients.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Los YCbCrCoefficients. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Obtiene un valor que indica si la imagen está en mosaico.

**Returns:**
boolean - `true` si la imagen está en mosaico; de lo contrario, `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtiene o establece el artista.

**Returns:**
java.lang.String - El artista.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtiene o establece el artista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El artista. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Determina si la etiqueta está presente en las opciones o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiqueta | int | El id de la etiqueta a comprobar. |

**Returns:**
boolean - `true` si la etiqueta está presente; de lo contrario, `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Obtiene o establece un valor que indica el orden de bytes del TIFF.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Obtiene o establece un valor que indica el orden de bytes del TIFF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 8 bits para cada componente de color.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Establece el orden de bytes Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Establece la compresión LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Permite reducir el tamaño de imágenes de tono continuo.
// Actualmente este campo se usa solo con codificación LZW porque LZW es probablemente el único esquema de codificación TIFF.
// que se beneficia significativamente de un paso predictor.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Establece el modelo de color RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Para YCbCr, puedes usar una de las siguientes opciones:
// Campo YCbCrSubSampling   Factores de muestreo JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valor predeterminado)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Todos los componentes de color se almacenarán en un solo plano.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un Frame TIFF de 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Obtiene el flujo del perfil ICC.

**Returns:**
byte[] - El perfil icc.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Establece el flujo del perfil ICC.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | El perfil icc. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Obtiene un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen previamente).

**Returns:**
boolean - un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen previamente).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Establece un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen previamente).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen previamente). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtiene los bits por muestra.

**Returns:**
int[] - El valor de bits por muestra.

Al establecer este valor, ten en cuenta que también establecerá el valor SamplesPerPixel a la longitud del arreglo. Estas 2 propiedades están muy estrechamente acopladas, por lo que solo pueden establecerse juntas.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Establece los bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | El valor de bits por muestra. |

Al establecer este valor, ten en cuenta que también establecerá el valor SamplesPerPixel a la longitud del arreglo. Estas 2 propiedades están muy estrechamente acopladas, por lo que solo pueden establecerse juntas. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Crear una fuente de archivo permanente, no temporal.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // El degradado lineal desde la esquina superior izquierda a la esquina inferior derecha de la imagen.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Rellenar el fotograma activo con un pincel de degradado lineal.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Opciones de escala de grises
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Crear una copia en escala de grises del fotograma activo.
    // Los datos de píxeles se conservan pero se convierten al formato deseado.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Agregar el fotograma recién creado a la imagen TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


Obtiene los valores de muestras adicionales.

Valor: El valor de muestras extra.

**Returns:**
int[] - los valores de muestras extra.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtiene la compresión.

**Returns:**
int - La compresión.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Establece la compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La compresión. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Opciones para el primer fotograma
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 8 bits para cada componente de color.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Establece el orden de bytes Big Endian (Motorola)
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Establece la compresión LZW.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Establece el modelo de color RGB.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Todos los componentes de color se almacenarán en un solo plano.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea el primer fotograma TIFF de 100x100 px.
// Ten en cuenta que no tienes que liberar los fotogramas explícitamente si están incluidos en TiffImage.
// Cuando el contenedor se libera, todos los frames se liberarán automáticamente.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Rellena el primer fotograma con el degradado azul-amarillo.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Opciones para el primer fotograma
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 1 bit por píxel para una imagen B/W.
createOptions2.setBitsPerSample(new int[]{1});

// Establece el orden de bytes Little Endian (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Establece la compresión CCITT Group 3 Fax.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Establece el modelo de color B/W donde 0 es negro, 1 es blanco.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Crea el segundo fotograma TIFF de 200x200px.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Rellena el segundo fotograma con el degradado azul-amarillo.
// Se convertirá automáticamente al formato B/W debido a la configuración correspondiente del fotograma.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Crea una imagen TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Obtiene la calidad de imagen comprimida. Se usa con la compresión Jpeg.

**Returns:**
int - calidad de imagen comprimida.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Establece la calidad de imagen comprimida. Se usa con la compresión Jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | calidad de imagen comprimida. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Establece el modelo de color RGB.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Establece la compresión Jpeg.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Establece 8 bits para cada componente de color.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtiene el copyright.

**Returns:**
java.lang.String - El copyright.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Establece el copyright.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El copyright. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Obtiene o establece el mapa de colores.

**Returns:**
int[] - El mapa de colores.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Obtiene o establece el mapa de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El mapa de colores. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtiene o establece la paleta de colores.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtiene o establece la paleta de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtiene o establece la fecha y hora.

**Returns:**
java.lang.String - La fecha y hora.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtiene o establece la fecha y hora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La fecha y hora. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Obtiene o establece el nombre del documento.

**Returns:**
java.lang.String - El nombre del documento.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Obtiene o establece el nombre del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre del documento. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Obtiene o establece la opción de almacenamiento alfa. Las opciones distintas de `TiffAlphaStorage.Unspecified` se usan cuando hay más de 3 `SamplesPerPixel` definidos.

**Returns:**
int - La opción de almacenamiento alfa.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Obtiene o establece la opción de almacenamiento alfa. Las opciones distintas de `TiffAlphaStorage.Unspecified` se usan cuando hay más de 3 `SamplesPerPixel` definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La opción de almacenamiento alfa. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Obtiene un valor que indica si las muestras extra están presentes.

**Returns:**
boolean - `true` si la muestra extra está presente; de lo contrario, `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Obtiene o establece el orden de relleno de bits de byte.

**Returns:**
int - El orden de relleno de bits de byte.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Obtiene o establece el orden de relleno de bits de byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El orden de relleno de bits de byte. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Obtiene o establece las sugerencias de semitono.

**Returns:**
int[] - Las sugerencias de semitono.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Obtiene o establece las sugerencias de semitono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | Las sugerencias de semitono. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtiene o establece la descripción de la imagen.

**Returns:**
java.lang.String - La descripción de la imagen.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtiene o establece la descripción de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La descripción de la imagen. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Obtiene o establece los nombres de tinta.

**Returns:**
java.lang.String - Los nombres de tinta.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Obtiene o establece los nombres de tinta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Los nombres de tinta. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Obtiene o establece el fabricante del escáner.

**Returns:**
java.lang.String - El fabricante del escáner.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Obtiene o establece el fabricante del escáner.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El fabricante del escáner. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Obtiene o establece el valor máximo de muestra.

**Returns:**
int[] - El valor máximo de muestra.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Obtiene o establece el valor máximo de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El valor máximo de muestra. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Obtiene o establece el valor mínimo de muestra.

**Returns:**
int[] - El valor mínimo de muestra.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Obtiene o establece el valor mínimo de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El valor mínimo de muestra. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Obtiene o establece el modelo del escáner.

**Returns:**
java.lang.String - El modelo del escáner.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Obtiene o establece el modelo del escáner.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El modelo del escáner. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtiene o establece la orientación.

**Returns:**
int - La orientación [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtiene o establece la orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | La orientación [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Obtiene o establece el nombre de página.

**Returns:**
java.lang.String - El nombre de la página.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Obtiene o establece el nombre de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre de la página. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Obtiene o establece la etiqueta de número de página.

**Returns:**
int[] - La etiqueta de número de página.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Obtiene o establece la etiqueta de número de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | La etiqueta de número de página. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Obtiene o establece el fotométrico.

**Returns:**
int - El fotométrico.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Obtiene o establece el fotométrico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El fotométrico. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Crear una fuente de archivo permanente, no temporal.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // El degradado lineal desde la esquina superior izquierda a la esquina inferior derecha de la imagen.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Rellenar el fotograma activo con un pincel de degradado lineal.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Opciones de escala de grises
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Crear una copia en escala de grises del fotograma activo.
    // Los datos de píxeles se conservan pero se convierten al formato deseado.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Agregar el fotograma recién creado a la imagen TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtiene o establece la configuración planar.

**Returns:**
int - La configuración planar.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtiene o establece la configuración planar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La configuración planar. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 8 bits para cada componente de color.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Establece el orden de bytes Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Establece la compresión LZW.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Establece el modelo de color RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Todos los componentes de color se almacenarán en un solo plano.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un Frame TIFF de 100x100 px.
// Ten en cuenta que no tienes que liberar un frame explícitamente si está incluido en TiffImage.
// Cuando el contenedor se libera, todos los frames se liberarán automáticamente.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Rellena todo el frame con el degradado azul-amarillo.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Crea una imagen TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtiene o establece la unidad de resolución.

**Returns:**
int - La unidad de resolución.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtiene o establece la unidad de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La unidad de resolución. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Obtiene o establece las filas por tira.

**Returns:**
long - Las filas por tira.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Obtiene o establece las filas por tira.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | Las filas por tira. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Obtiene o establece el ancho del mosaico.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Obtiene o establece el ancho del mosaico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Obtiene o establece la longitud del mosaico.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Obtiene o establece la longitud del mosaico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Obtiene o establece el formato de muestra.

**Returns:**
int[] - El formato de muestra.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Obtiene o establece el formato de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El formato de muestra. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad use el setter de la propiedad `BitsPerSample`.

**Returns:**
int - Las muestras por píxel.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Obtiene o establece el valor máximo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (tipo Byte, Short o Long).

**Returns:**
long[] - El valor máximo de muestra.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Obtiene o establece el valor máximo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (tipo Byte, Short o Long).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | El valor máximo de muestra. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Obtiene o establece el valor mínimo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (tipo Byte, Short o Long).

**Returns:**
long[] - El valor mínimo de muestra.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Obtiene o establece el valor mínimo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (tipo Byte, Short o Long).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | El valor mínimo de muestra. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Obtiene o establece el tipo de software.

**Returns:**
java.lang.String - El tipo de software.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Obtiene o establece el tipo de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El tipo de software. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Obtiene o establece los recuentos de bytes de tira.

**Returns:**
long[] - Los recuentos de bytes de la tira.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Obtiene o establece los recuentos de bytes de tira.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | Los recuentos de bytes de la tira. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Obtiene o establece los desplazamientos de la tira.

**Returns:**
long[] - Los desplazamientos de la tira.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Obtiene o establece los desplazamientos de la tira.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | Los desplazamientos de la tira. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Obtiene o establece los recuentos de bytes de los mosaicos.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Obtiene o establece los recuentos de bytes de los mosaicos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Obtiene o establece los desplazamientos de los mosaicos.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Obtiene o establece los desplazamientos de los mosaicos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo.

**Returns:**
long - La indicación general del tipo de datos contenidos en este subarchivo.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La indicación general del tipo de datos contenidos en este subarchivo. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Obtiene o establece la impresora de destino.

**Returns:**
java.lang.String - La impresora objetivo.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Obtiene o establece la impresora de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La impresora de destino. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Obtiene o establece el umbral.

**Returns:**
int - El umbral.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Obtiene o establece el umbral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El umbral. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Obtiene el total de páginas.

**Returns:**
int - El total de páginas.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Obtiene o establece la posición x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Obtiene o establece la posición x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La posición x. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtiene o establece la configuración de resolución.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtiene o establece la configuración de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Obtiene o establece la resolución x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Obtiene o establece la resolución x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La resolución x. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Obtiene o establece la posición y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Obtiene o establece la posición y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La posición y. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Obtiene o establece la resolución y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Obtiene o establece la resolución y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La resolución y. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Obtiene o establece las opciones de fax t4.

**Returns:**
long - Las opciones de fax t4.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Obtiene o establece las opciones de fax t4.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | Las opciones de fax t4. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Obtiene o establece el predictor para la compresión LZW.

**Returns:**
int - El tipo de predictor.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Obtiene o establece el predictor para la compresión LZW.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tipo de predictor. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 8 bits para cada componente de color.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Establece el orden de bytes Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Establece la compresión LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Permite reducir el tamaño de imágenes de tono continuo.
// Actualmente este campo se usa solo con codificación LZW porque LZW es probablemente el único esquema de codificación TIFF.
// que se beneficia significativamente de un paso predictor.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Establece el modelo de color RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Para YCbCr, puedes usar una de las siguientes opciones:
// Campo YCbCrSubSampling   Factores de muestreo JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valor predeterminado)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Todos los componentes de color se almacenarán en un solo plano.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un Frame TIFF de 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtiene o establece la longitud de la imagen.

**Returns:**
long - La longitud de la imagen.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtiene o establece la longitud de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La longitud de la imagen. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtiene o establece el ancho de la imagen.

**Returns:**
long - El ancho de la imagen.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtiene o establece el ancho de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El ancho de la imagen. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Obtiene o establece el puntero al IFD EXIF.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Obtiene o establece las etiquetas.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - Las etiquetas.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Obtiene o establece las etiquetas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Obtiene el recuento de etiquetas válidas. No es el recuento total de etiquetas, sino el número de etiquetas que pueden preservarse.

**Returns:**
int - El recuento de etiquetas válidas.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene los bits por píxel.

**Returns:**
int - Los bits por píxel.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Obtiene información sobre la imagen, que es utilizada por el Explorador de Windows.

Valor: Información sobre la imagen, utilizada por Windows Explorer. El `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) es ignorado por Windows Explorer si la etiqueta `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) existe.

**Returns:**
java.lang.String - información sobre la imagen, que se usa en Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Establece información sobre la imagen, que es utilizada por el Explorador de Windows.

Valor: Información sobre la imagen, utilizada por Windows Explorer. El `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) es ignorado por Windows Explorer si la etiqueta `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) existe.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | información sobre la imagen, que se usa en Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Obtiene el comentario de la imagen, que es utilizado por el Explorador de Windows.

Valor: Comentario sobre la imagen, utilizado por Windows Explorer.

**Returns:**
java.lang.String - comentario sobre la imagen, que se usa en Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Establece el comentario de la imagen, que es utilizado por el Explorador de Windows.

Valor: Comentario sobre la imagen, utilizado por Windows Explorer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | comentario en la imagen, que se usa en Windows Explorer. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Obtiene el autor de la imagen, que es utilizado por el Explorador de Windows.

Valor: Autor de la imagen, usado por Windows Explorer. El `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) es ignorado por Windows Explorer si la etiqueta `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) existe.

**Returns:**
java.lang.String - autor de la imagen, que se usa en Windows Explorer.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Establece el autor de la imagen, que es utilizado por el Explorador de Windows.

Valor: Autor de la imagen, usado por Windows Explorer. El `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) es ignorado por Windows Explorer si la etiqueta `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) existe.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | autor de la imagen, que se usa en Windows Explorer. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Obtiene la imagen de asunto, que es utilizada por el Explorador de Windows.

Valor: Imagen del sujeto, usado por Windows Explorer.

**Returns:**
java.lang.String - imagen del sujeto, que se usa en Windows Explorer.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Establece la imagen del sujeto, que es utilizada por Windows Explorer.

Valor: Imagen del sujeto, usado por Windows Explorer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | imagen del sujeto, que se usa en Windows Explorer. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Obtiene información sobre la imagen, que es utilizada por el Explorador de Windows.

Valor: Información sobre la imagen, usado por Windows Explorer.

**Returns:**
java.lang.String - información sobre la imagen, que se usa en Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Establece información sobre la imagen, que es utilizada por el Explorador de Windows.

Valor: Información sobre la imagen, usado por Windows Explorer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | información sobre la imagen, que se usa en Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtiene los datos Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Establece los datos Exif.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Datos Exif. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Elimina la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiqueta | int | La etiqueta a eliminar. |

**Returns:**
boolean - verdadero si se eliminó con éxito
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Elimina las etiquetas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiquetas | int[] | Las etiquetas a eliminar. |

**Returns:**
boolean - `` si el tamaño de la colección de etiquetas cambió.
### validate() {#validate--}
```
public void validate()
```


Valida si las opciones tienen una combinación válida de etiquetas.

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Agrega las etiquetas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas a agregar. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Agrega una nueva etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | La etiqueta a agregar. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Obtiene la instancia de la etiqueta por tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagKey | int | La clave de la etiqueta. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
