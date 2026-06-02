---
title: "RectangleExtensions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "包含 Rectangle 的扩展方法。"
type: docs
weight: 21
url: /zh/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

包含 `Rectangle` 的扩展方法。
## 方法

| 方法 | 描述 |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | 将 `Rectangle` 转换为 `System.Drawing.Rectangle`。 |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | 将 `RectangleF` 转换为 `System.Drawing.Rectangle`。 |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | 合并两个矩形。 |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


将 `Rectangle` 转换为 `System.Drawing.Rectangle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要转换的矩形。 |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


将 `RectangleF` 转换为 `System.Drawing.Rectangle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 要转换的矩形。 |

**Returns:**
java.awt.geom.Rectangle2D.Float - 已转换的 `System.Drawing.RectangleF`。
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


合并两个矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 第一个矩形。 |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 第二个矩形。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
