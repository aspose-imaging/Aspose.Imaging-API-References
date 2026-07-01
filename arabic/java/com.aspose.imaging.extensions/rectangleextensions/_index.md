---
title: "RectangleExtensions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على أساليب توسيع لـ Rectangle."
type: docs
weight: 21
url: /ar/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

يحتوي على طرق امتداد لـ `Rectangle`.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | يقوم بتحويل `Rectangle` إلى `System.Drawing.Rectangle`. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | يقوم بتحويل `RectangleF` إلى `System.Drawing.Rectangle`. |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | يجمع مستطيلين. |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


يقوم بتحويل `Rectangle` إلى `System.Drawing.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المراد تحويله. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


يقوم بتحويل `RectangleF` إلى `System.Drawing.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل المراد تحويله. |

**Returns:**
java.awt.geom.Rectangle2D.Float - الـ `System.Drawing.RectangleF` المحول.
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


يجمع مستطيلين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل الأول. |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل الثاني. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
