---
title: "ImageExtensions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller utökningsmetoder för konverteringar baserade på System.Drawing.Image och Image."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Innehåller utökningsmetoder för konverteringar baserade på `System.Drawing.Image` och `Image`.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Konverterar `BufferedImage` till `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Konverterar `BufferedImage` till `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Konverterar `Image` till `BufferedImage` med TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Konverterar `Image` till `BufferedImage` med bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Tar subbilden från `Image` och konverterar till `BufferedImage` med BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Skapa en wrapper över BufferedImage utan att kopiera pixeldata. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Tar subbilden från `Image` och konverterar till `BufferedImage` med bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | Tar subbilden från `Image` och konverterar till `BufferedImage` med bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Konverterar `BufferedImage` till `PngImage`.

Varning: GDI‑bilden kan få lägre gränser än `image`. För att få alla delar av bilden, använd den säkrare utökningsmetoden ToGdiImageFull.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Den `BufferedImage` som ska konverteras. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den nödvändiga rektangeln. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Konverterar `BufferedImage` till `PngImage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Den `BufferedImage` som ska konverteras. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Konverterar `Image` till `BufferedImage` med TYPE\_INT\_ARGB.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Den `Image` som ska konverteras. |

**Returns:**
java.awt.image.BufferedImage - Den konverterade `BufferedImage`.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Konverterar `Image` till `BufferedImage` med bufferedImageType. Vänligen välj `bufferedImageType` från java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Den `Image` som ska konverteras. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Den konverterade `BufferedImage`.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Tar subbilden från `Image` och konverterar till `BufferedImage` med BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Den `Image` som ska konverteras. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för delbilden som ska konverteras. |

**Returns:**
java.awt.image.BufferedImage - Den konverterade `BufferedImage` innehåller delbild hämtad från `Image`.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Skapa ett omslag runt BufferedImage utan att kopiera pixeldata. Det använder käll-`image` under huven men tillåter manipulation med den som med en [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Källbilden. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Tar delbilden från `Image` och konverterar till `BufferedImage` med bufferedImageType. Vänligen välj `bufferedImageType` från java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Den `Image` som ska konverteras. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för delbilden som ska konverteras. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Den konverterade `BufferedImage` innehåller delbild hämtad från `Image`.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


Tar delbilden från `Image` och konverterar till `BufferedImage` med bufferedImageType. Vänligen välj `bufferedImageType` från java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Den `Image` som ska konverteras. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för delbilden som ska konverteras. Om `subImageRect.isEmpty()` tas hela bilden. |
| dstImage | java.awt.image.BufferedImage | Målbilden. |

**Returns:**
java.awt.image.BufferedImage - Den konverterade `BufferedImage` innehåller delbild hämtad från `Image`.
