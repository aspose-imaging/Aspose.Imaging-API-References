---
title: "CircleMask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Описывает круглую маску."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Описывает круглую маску.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Инициализирует новый экземпляр класса [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) с указанной центральной точкой и радиусом. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Инициализирует новый экземпляр класса [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) с указанной центральной точкой и радиусом. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Возвращает границы этой маски в пикселях. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Получает непрозрачность указанного пикселя. |
| [inflate(int size)](#inflate-int-) | Увеличивает эту маску на указанное значение. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает маску указанным прямоугольником. |
| [deepClone()](#deepClone--) | Создаёт новый объект, являющийся копией текущего экземпляра. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Инициализирует новый экземпляр класса [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) с указанной центральной точкой и радиусом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x центральной точки выбранной области. |
| y | int | Координата y центральной точки выбранной области. |
| radius | int | Радиус выбранной области. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Инициализирует новый экземпляр класса [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) с указанной центральной точкой и радиусом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | Центральная точка выбранной области. |
| radius | int | Радиус выбранной области. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Возвращает границы этой маски в пикселях.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Получает непрозрачность указанного пикселя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns:**
boolean — true, если указанный пиксель непрозрачный; иначе false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Увеличивает эту маску на указанное значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Величина для расширения этой маски. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Обрезает маску указанным прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Указанный прямоугольник. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns:**
java.lang.Object — Новый объект, являющийся копией этого экземпляра.
