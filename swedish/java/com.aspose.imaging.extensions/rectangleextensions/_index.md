---
title: "RectangleExtensions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller förlängningsmetoder för Rectangle."
type: docs
weight: 21
url: /sv/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Innehåller utökningsmetoder för `Rectangle`.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | Konverterar `Rectangle` till `System.Drawing.Rectangle`. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | Konverterar `RectangleF` till `System.Drawing.Rectangle`. |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Förenar två rektanglar. |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


Konverterar `Rectangle` till `System.Drawing.Rectangle`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att konvertera. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Konverterar `RectangleF` till `System.Drawing.Rectangle`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln att konvertera. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Den konverterade `System.Drawing.RectangleF`.
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


Förenar två rektanglar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Den första rektangeln. |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Den andra rektangeln. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
