---
title: "LoadOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa las opciones de carga."
type: docs
weight: 70
url: /es/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Representa las opciones de carga.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Obtiene el modo de recuperación de datos. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Establece el modo de recuperación de datos. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Obtiene el `Color` de fondo de la `Image`. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | Establece el `Color` de fondo de la `Image`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Obtiene un valor que indica si se debe aplicar la conversión del perfil ICC. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Establece un valor que indica si se debe aplicar la conversión del perfil ICC. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Agrega la fuente de fuentes personalizada para suministrar fuentes específicas de la imagen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Obtiene un valor que indica si [procesamiento de imágenes concurrente]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Establece un valor que indica si [procesamiento de imágenes concurrente]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Obtiene el controlador del evento de progreso. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Establece el controlador del evento de progreso. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Obtiene el modo de recuperación de datos.

**Returns:**
int - El modo de recuperación de datos.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Establece el modo de recuperación de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de recuperación de datos. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Obtiene el `Color` de fondo de la `Image`.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Normalmente el color de fondo se establece siempre que el valor del píxel no pueda recuperarse debido a corrupción de datos.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


Establece el `Color` de fondo de la `Image`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | El color de fondo. |

Normalmente el color de fondo se establece siempre que el valor del píxel no pueda recuperarse debido a corrupción de datos. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Obtiene un valor que indica si se debe aplicar la conversión del perfil ICC.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Establece un valor que indica si se debe aplicar la conversión del perfil ICC.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Agrega la fuente de fuentes personalizada para suministrar fuentes específicas de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | La función del proveedor de la fuente de fuentes personalizada. |
| args | java.lang.Object[] | Los argumentos. |

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


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
El siguiente ejemplo muestra cómo establecer un límite de memoria al cargar una imagen JPEG. El límite de memoria es el tamaño máximo permitido (en megabytes) para todos los búferes internos.
``` java
String workDir = "c:\\temp\\";
// Estableciendo un límite de memoria de 50 megabytes para la imagen cargada objetivo
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


Obtiene un valor que indica si [procesamiento de imágenes concurrente].

Valor: `true` si [procesamiento de imágenes concurrente]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [procesamiento de imágenes concurrente].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Establece un valor que indica si [procesamiento de imágenes concurrente].

Valor: `true` si [procesamiento de imágenes concurrente]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


Obtiene el controlador del evento de progreso.

Valor: El controlador de evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


Establece el controlador del evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | el controlador de evento de progreso. |

