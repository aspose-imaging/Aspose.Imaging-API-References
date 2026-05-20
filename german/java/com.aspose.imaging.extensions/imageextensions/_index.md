---
title: "ImageExtensions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält Erweiterungsmethoden für Konvertierungen basierend auf System.Drawing.Image und Image."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Enthält Erweiterungsmethoden für Konvertierungen basierend auf `System.Drawing.Image` und `Image`.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Konvertiert das `BufferedImage` in das `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Konvertiert das `BufferedImage` in das `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Konvertiert das `Image` in das `BufferedImage` mit TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Konvertiert das `Image` in das `BufferedImage` mit bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Nimmt das Teilbild von `Image` und konvertiert es in das `BufferedImage` mit BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Erstellt einen Wrapper über das BufferedImage, ohne die Pixeldaten zu kopieren. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Nimmt das Teilbild von `Image` und konvertiert es in das `BufferedImage` mit bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | Nimmt das Teilbild von `Image` und konvertiert es in das `BufferedImage` mit bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Konvertiert das `BufferedImage` in das `PngImage`.

Warnung, das GDI-Bild kann niedrigere Grenzen haben als `image`. Um alle Teile des Bildes zu erhalten, verwenden Sie die sicherere Erweiterungsmethode ToGdiImageFull.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Das `BufferedImage` zum Konvertieren. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das erforderliche Rechteck. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Konvertiert das `BufferedImage` in das `PngImage`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Das `BufferedImage` zum Konvertieren. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Konvertiert das `Image` in das `BufferedImage` mit TYPE\_INT\_ARGB.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das `Image` zum Konvertieren. |

**Returns:**
java.awt.image.BufferedImage - Das konvertierte `BufferedImage`.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Konvertiert das `Image` in das `BufferedImage` mit bufferedImageType. Bitte wählen Sie `bufferedImageType` aus java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das `Image` zum Konvertieren. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Das konvertierte `BufferedImage`.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Nimmt das Teilbild von `Image` und konvertiert es in das `BufferedImage` mit BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das `Image` zum Konvertieren. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck des Teilbildes zum Konvertieren. |

**Returns:**
java.awt.image.BufferedImage - Das konvertierte `BufferedImage` enthält ein Teilbild, das aus `Image` entnommen wurde.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Erstellen Sie einen Wrapper über das BufferedImage, ohne die Pixeldaten zu kopieren. Er verwendet das Quell-`image` im Hintergrund, ermöglicht jedoch die Manipulation wie bei einem [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Das Quellbild. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Nimmt das Teilbild von `Image` und konvertiert es in das `BufferedImage` mit bufferedImageType. Bitte wählen Sie `bufferedImageType` aus java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das `Image` zum Konvertieren. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck des Teilbildes zum Konvertieren. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Das konvertierte `BufferedImage` enthält ein Teilbild, das aus `Image` entnommen wurde.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


Nimmt das Teilbild von `Image` und konvertiert es in das `BufferedImage` mit bufferedImageType. Bitte wählen Sie `bufferedImageType` aus java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das `Image` zum Konvertieren. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck des Teilbildes zum Konvertieren. Wenn `subImageRect.isEmpty()` ist, wird das gesamte Bild genommen. |
| dstImage | java.awt.image.BufferedImage | Das Zielbild. |

**Returns:**
java.awt.image.BufferedImage - Das konvertierte `BufferedImage` enthält ein Teilbild, das aus `Image` entnommen wurde.
