---
title: "JpegExifData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contenedor de datos EXIF para archivos jpeg."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Contenedor de datos EXIF para archivos jpeg.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Inicializa una nueva instancia de la clase `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase `JpegExifData` con datos de una matriz. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase `JpegExifData` con datos de una matriz. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Inicializa una nueva instancia de la clase [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) con datos de una matriz. |
## Campos

| Campo | Descripción |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | El tamaño máximo del segmento EXIF permitido en bytes. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getArtist()](#getArtist--) | Obtiene o establece el artista. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtiene o establece el artista. |
| [getBitsPerSample()](#getBitsPerSample--) | Obtiene o establece los bits por muestra. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Obtiene o establece los bits por muestra. |
| [getCompression()](#getCompression--) | Obtiene o establece la compresión. |
| [setCompression(int value)](#setCompression-int-) | Obtiene o establece la compresión. |
| [getCopyright()](#getCopyright--) | Obtiene o establece los derechos de autor. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Obtiene o establece los derechos de autor. |
| [getDateTime()](#getDateTime--) | Obtiene o establece la fecha y hora. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtiene o establece la fecha y hora. |
| [getImageDescription()](#getImageDescription--) | Obtiene o establece la descripción de la imagen. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtiene o establece la descripción de la imagen. |
| [getImageLength()](#getImageLength--) | Obtiene o establece la longitud de la imagen. |
| [setImageLength(long value)](#setImageLength-long-) | Obtiene o establece la longitud de la imagen. |
| [getImageWidth()](#getImageWidth--) | Obtiene o establece el ancho de la imagen. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtiene o establece el ancho de la imagen. |
| [getModel()](#getModel--) | Obtiene o establece el modelo. |
| [setModel(String value)](#setModel-java.lang.String-) | Obtiene o establece el modelo. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Obtiene o establece la interpretación fotométrica. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Obtiene o establece la interpretación fotométrica. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtiene o establece la configuración planar. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtiene o establece la configuración planar. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Obtiene o establece la cromaticidad de los tres colores primarios de la imagen. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la cromaticidad de los tres colores primarios de la imagen. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Obtiene o establece la referencia de negro y blanco. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la referencia de negro y blanco. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtiene o establece la unidad de resolución. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtiene o establece la unidad de resolución. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtiene o establece las muestras por píxel. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Obtiene o establece las muestras por píxel. |
| [getSoftware()](#getSoftware--) | Obtiene o establece el software. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Obtiene o establece el software. |
| [getTransferFunction()](#getTransferFunction--) | Obtiene o establece la función de transferencia. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Obtiene o establece la función de transferencia. |
| [getXResolution()](#getXResolution--) | Obtiene o establece la resolución x. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtiene o establece los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Obtiene o establece la posición de los componentes de crominancia en relación con el componente de luminancia. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Obtiene o establece la posición de los componentes de crominancia en relación con el componente de luminancia. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Obtiene o establece la proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Obtiene o establece la proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| [getYResolution()](#getYResolution--) | Obtiene o establece la resolución y. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución y. |
| [serializeExifData()](#serializeExifData--) | Serializa los datos EXIF. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Inicializa una nueva instancia de la clase `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Inicializa una nueva instancia de la clase `JpegExifData` con datos de una matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Matriz de etiquetas EXIF junto con etiquetas comunes y GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Inicializa una nueva instancia de la clase `JpegExifData` con datos de una matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas comunes. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas GPS. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Inicializa una nueva instancia de la clase [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) con datos de una matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Matriz de etiquetas EXIF junto con etiquetas comunes y GPS. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


El tamaño máximo del segmento EXIF permitido en bytes.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtiene o establece el artista.

Valor: El artista.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtiene o establece el artista.

Valor: El artista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtiene o establece los bits por muestra.

Valor: Los bits por muestra.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Obtiene o establece los bits por muestra.

Valor: Los bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtiene o establece la compresión.

Valor: La compresión.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Obtiene o establece la compresión.

Valor: La compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtiene o establece los derechos de autor.

Valor: Los derechos de autor.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Obtiene o establece los derechos de autor.

Valor: Los derechos de autor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtiene o establece la fecha y hora.

Valor: La fecha y hora.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtiene o establece la fecha y hora.

Valor: La fecha y hora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtiene o establece la descripción de la imagen.

Valor: La descripción de la imagen.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtiene o establece la descripción de la imagen.

Valor: La descripción de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtiene o establece la longitud de la imagen.

Valor: La longitud de la imagen.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtiene o establece la longitud de la imagen.

Valor: La longitud de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtiene o establece el ancho de la imagen.

Valor: El ancho de la imagen.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtiene o establece el ancho de la imagen.

Valor: El ancho de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Obtiene o establece el modelo.

Valor: El modelo.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Obtiene o establece el modelo.

Valor: El modelo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Obtiene o establece la interpretación fotométrica.

Valor: La interpretación fotométrica.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Obtiene o establece la interpretación fotométrica.

Valor: La interpretación fotométrica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtiene o establece la configuración planar.

Valor: La configuración planar.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtiene o establece la configuración planar.

Valor: La configuración planar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Obtiene o establece la cromaticidad de los tres colores primarios de la imagen.

Valor: La cromaticidad de los tres colores primarios de la imagen.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Obtiene o establece la cromaticidad de los tres colores primarios de la imagen.

Valor: La cromaticidad de los tres colores primarios de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Obtiene o establece la referencia de negro y blanco.

Valor: La referencia negro blanco.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Obtiene o establece la referencia de negro y blanco.

Valor: La referencia negro blanco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtiene o establece la unidad de resolución.

Valor: La unidad de resolución.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtiene o establece la unidad de resolución.

Valor: La unidad de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtiene o establece las muestras por píxel.

Valor: Las muestras por píxel.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Obtiene o establece las muestras por píxel.

Valor: Las muestras por píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Obtiene o establece el software.

Valor: El software.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Obtiene o establece el software.

Valor: El software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Obtiene o establece la función de transferencia.

Valor: La función de transferencia.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Obtiene o establece la función de transferencia.

Valor: La función de transferencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Obtiene o establece la resolución x.

Valor: La resolución x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Obtiene o establece la resolución x.

Valor: La resolución x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtiene o establece los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr.

Valor: Los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtiene o establece los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr.

Valor: Los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Obtiene o establece la posición de los componentes de crominancia en relación con el componente de luminancia.

Valor: La posición de los componentes de crominancia en relación con el componente de luminancia.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Obtiene o establece la posición de los componentes de crominancia en relación con el componente de luminancia.

Valor: La posición de los componentes de crominancia en relación con el componente de luminancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Obtiene o establece la proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia.

Valor: La proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Obtiene o establece la proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia.

Valor: La proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Obtiene o establece la resolución y.

Valor: La resolución y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Obtiene o establece la resolución y.

Valor: La resolución y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño más influyente es el contenido de la etiqueta Miniatura.

**Returns:**
byte[] - Los datos EXIF serializados.

El tamaño total del segmento debe ser menor o igual a MaxExifSegmentSize bytes para producir una imagen jpeg correcta. Sugerencia: intenta reducir el tamaño de la miniatura o cambiar su compresión en caso de que la sección EXIF sea demasiado grande.
