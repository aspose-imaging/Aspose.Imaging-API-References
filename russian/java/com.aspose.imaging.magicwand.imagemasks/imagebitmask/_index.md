---
title: "ImageBitMask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Описывает бинарную маску изображения."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

Описывает бинарную маску изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | Инициализирует новый экземпляр класса [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) с указанной шириной и высотой. |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | Инициализирует новый экземпляр класса [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) с размером указанного существующего [RasterImage](../../com.aspose.imaging/rasterimage). |
## Методы

| Метод | Описание |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Возвращает границы выбранной части маски в пикселях. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Получает непрозрачность указанного пикселя. |
| [inflate(int size)](#inflate-int-) | Увеличивает эту маску на указанное значение. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает маску указанным прямоугольником. |
| [deepClone()](#deepClone--) | Создаёт новый объект, являющийся копией текущего экземпляра. |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | Устанавливает непрозрачность указанному пикселю. |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Инвертирует маску. |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Объединение двух масок. |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Вычесть вторую маску из первой. |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Пересечение двух масок. |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Исключающая дизъюнкция двух масок. |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


Инициализирует новый экземпляр класса [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) с указанной шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина маски. |
| height | int | Высота маски. |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


Инициализирует новый экземпляр класса [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) с размером указанного существующего [RasterImage](../../com.aspose.imaging/rasterimage). Указанный [RasterImage](../../com.aspose.imaging/rasterimage) будет сохранён как исходное изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Исходное изображение. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Возвращает границы выбранной части маски в пикселях.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Получает непрозрачность указанного пикселя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. Значение: true, если указанный пиксель непрозрачный; иначе false. |

**Returns:**
boolean
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns:**
java.lang.Object — Новый объект, являющийся копией этого экземпляра.
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


Устанавливает непрозрачность указанному пикселю.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| value | boolean | true, если указанный пиксель непрозрачный; иначе false. |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


Инвертирует маску.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Маска, которую нужно инвертировать. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


Объединение двух масок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Первая маска. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Вторая маска. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


Вычесть вторую маску из первой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Первая маска. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Вторая маска. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


Пересечение двух масок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Первая маска. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Вторая маска. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


Исключающая дизъюнкция двух масок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Первая маска. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Вторая маска. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
