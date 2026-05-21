---
title: "LoadOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar laddningsalternativen."
type: docs
weight: 70
url: /sv/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Representerar laddningsalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Hämtar dataräddningsläget. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Ställer in dataräddningsläget. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Hämtar `Image`-bakgrundens `Color`. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | Ställer in `Image`-bakgrundens `Color`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Hämtar ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Ställer in ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Lägger till den anpassade teckensnittskällan för att tillhandahålla bildspecifika teckensnitt. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Hämtar ett värde som indikerar om [concurrent image processing]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Ställer in ett värde som indikerar om [concurrent image processing]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Hämtar händelsehanteraren för framsteg. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Ställer in händelsehanteraren för framsteg. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Hämtar dataräddningsläget.

**Returns:**
int - Dataräddningsläget.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Ställer in dataräddningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Återställningsläget för data. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Hämtar `Image`-bakgrundens `Color`.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Vanligtvis sätts bakgrundsfärgen när pixelvärdet inte kan återställas på grund av datakorruption.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


Ställer in `Image`-bakgrundens `Color`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | Bakgrundsfärgen. |

Vanligtvis sätts bakgrundsfärgen när pixelvärdet inte kan återställas på grund av datakorruption. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Hämtar ett värde som indikerar om ICC-profilkonvertering ska tillämpas.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Ställer in ett värde som indikerar om ICC-profilkonvertering ska tillämpas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Lägger till den anpassade teckensnittskällan för att tillhandahålla bildspecifika teckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | Den anpassade teckensnittskällans leverantörsfunktion. |
| args | java.lang.Object[] | Argumenten. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Returns:**
int - buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
Följande exempel visar hur man anger en minnesgräns när en JPEG-bild laddas. Minnesgränsen är den maximalt tillåtna storleken (i megabyte) för alla interna buffertar.
``` java
String workDir = "c:\\temp\\";
// Anger en minnesgräns på 50 megabyte för den målbelastade bilden
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


Hämtar ett värde som indikerar om [concurrent image processing].

Värde: `true` om [concurrent image processing]; annars `false`.

**Returns:**
boolean - ett värde som indikerar om [concurrent image processing].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Ställer in ett värde som indikerar om [concurrent image processing].

Värde: `true` om [concurrent image processing]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


Hämtar händelsehanteraren för framsteg.

Värde: Progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


Ställer in händelsehanteraren för framsteg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | progress‑händelsehanteraren. |

