---
title: "LoadOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Ladeoptionen dar."
type: docs
weight: 70
url: /de/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Stellt die Ladeoptionen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Ruft den Datenwiederherstellungsmodus ab. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Setzt den Datenwiederherstellungsmodus. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Ruft die Hintergrund-`Color` des `Image` ab. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | Setzt die Hintergrund-`Color` des `Image`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Ruft einen Wert ab, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Setzt einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Fügt die benutzerdefinierte Schriftquelle hinzu, um bildspezifische Schriften bereitzustellen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Ruft einen Wert ab, der angibt, ob [concurrent image processing]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Setzt einen Wert, der angibt, ob [concurrent image processing]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Ruft den Fortschritts-Event-Handler ab. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Setzt den Fortschritts-Event-Handler. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Ruft den Datenwiederherstellungsmodus ab.

**Returns:**
int - Der Datenwiederherstellungsmodus.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Setzt den Datenwiederherstellungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Datenwiederherstellungsmodus. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Ruft die Hintergrund-`Color` des `Image` ab.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Typischerweise wird die Hintergrundfarbe gesetzt, wenn ein Pixelwert aufgrund von Datenkorruption nicht wiederhergestellt werden kann.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


Setzt die Hintergrund-`Color` des `Image`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | Die Hintergrundfarbe. |

Typischerweise wird die Hintergrundfarbe gesetzt, wenn ein Pixelwert aufgrund von Datenkorruption nicht wiederhergestellt werden kann. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Ruft einen Wert ab, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Setzt einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Fügt die benutzerdefinierte Schriftquelle hinzu, um bildspezifische Schriften bereitzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | Die benutzerdefinierte Schriftquellen-Provider-Funktion. |
| args | java.lang.Object[] | Die Argumente. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße in Megabyte. Ein nicht‑positiver Wert bedeutet keine Speicherbeschränkung für interne Puffer.

**Returns:**
int - der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße in Megabyte. Ein nicht‑positiver Wert bedeutet keine Speicherbeschränkung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
Das folgende Beispiel zeigt, wie man ein Speicherlimit beim Laden eines JPEG-Bildes festlegt. Das Speicherlimit ist die maximal zulässige Größe (in Megabyte) für alle internen Puffer.
``` java
String workDir = "c:\\temp\\";
// Festlegen eines Speicherlimits von 50 Megabyte für das zu ladende Bild.
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


Ruft einen Wert ab, der angibt, ob [concurrent image processing].

Wert: `true`, wenn [concurrent image processing]; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob [concurrent image processing].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Setzt einen Wert, der angibt, ob [concurrent image processing].

Wert: `true`, wenn [concurrent image processing]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


Ruft den Fortschritts-Event-Handler ab.

Wert: Der Fortschritts-Ereignishandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


Setzt den Fortschritts-Event-Handler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | der Fortschritts-Ereignishandler. |

