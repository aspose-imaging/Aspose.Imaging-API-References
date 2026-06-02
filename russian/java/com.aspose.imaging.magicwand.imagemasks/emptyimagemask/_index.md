---
title: "EmptyImageMask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Описывает пустую неабстрактную маску."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Описывает пустую неабстрактную маску.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Инициализирует новый экземпляр класса [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) с указанной шириной и высотой. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Возвращает границы выбранной части маски в пикселях. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Получает непрозрачность указанного пикселя. |
| [inflate(int size)](#inflate-int-) | Увеличивает эту маску на указанное значение. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает маску указанным прямоугольником. |
| [deepClone()](#deepClone--) | Создаёт новый объект, являющийся копией текущего экземпляра. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Инициализирует новый экземпляр класса [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) с указанной шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина маски. |
| height | int | Высота маски. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns:**
java.lang.Object — Новый объект, являющийся копией этого экземпляра.
