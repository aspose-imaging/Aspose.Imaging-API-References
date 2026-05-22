---
title: "RectangleExtensions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Rectangle için uzantı yöntemlerini içerir."
type: docs
weight: 21
url: /tr/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

`Rectangle` için uzantı metodlarını içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | `Rectangle` öğesini `System.Drawing.Rectangle`'a dönüştürür. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | `RectangleF` öğesini `System.Drawing.Rectangle`'a dönüştürür. |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | İki dikdörtgeni birleştirir. |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


`Rectangle` öğesini `System.Drawing.Rectangle`'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dönüştürülecek dikdörtgen. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


`RectangleF` öğesini `System.Drawing.Rectangle`'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Dönüştürülecek dikdörtgen. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Dönüştürülmüş `System.Drawing.RectangleF`.
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


İki dikdörtgeni birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | İlk dikdörtgen. |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | İkinci dikdörtgen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
