---
title: "RectangleExtensions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит методы-расширения для Rectangle."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Содержит методы-расширения для `Rectangle`.
## Методы

| Метод | Описание |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | Преобразует `Rectangle` в `System.Drawing.Rectangle`. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | Преобразует `RectangleF` в `System.Drawing.Rectangle`. |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Объединяет два прямоугольника. |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


Преобразует `Rectangle` в `System.Drawing.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник для преобразования. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Преобразует `RectangleF` в `System.Drawing.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник для преобразования. |

**Returns:**
java.awt.geom.Rectangle2D.Float - преобразованный `System.Drawing.RectangleF`.
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


Объединяет два прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Первый прямоугольник. |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Второй прямоугольник. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
