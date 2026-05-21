---
title: "RectangleMask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Описывает прямоугольную маску."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Описывает прямоугольную маску.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Инициализирует новый экземпляр класса [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) с указанной точкой верхнего‑левого угла, шириной и высотой. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) с указанным прямоугольником. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Возвращает границы выбранной части маски в пикселях. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Получает непрозрачность указанного пикселя. |
| [inflate(int size)](#inflate-int-) | Увеличивает эту маску на указанное значение. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает маску указанным прямоугольником. |
| [deepClone()](#deepClone--) | Создаёт новый объект, являющийся копией текущего экземпляра. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Создайте новую маску с помощью инструмента magic wand, основанную на тоне и цвете пикселя (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Объедините существующую маску с указанной, созданной инструментом magic wand.
            .union(new MagicWandSettings(416, 387))
            // Инвертируйте существующую маску
            .invert()
            // Вычтите указанную маску, созданную инструментом magic wand с заданным порогом, из существующей.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Вычтите четыре указанных прямоугольных маски из существующей маски одну за другой.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Смягчите маску с указанными настройками.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Примените маску к изображению
            .apply();

    // Сохранить изображение
    image.save(outputFilePath);
}

```

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Инициализирует новый экземпляр класса [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) с указанной точкой верхнего‑левого угла, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата X верхнего‑левого пункта выбранной области. |
| y | int | Координата Y верхнего‑левого пункта выбранной области. |
| width | int | Ширина выбранной области. |
| height | int | Высота выбранной области. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Инициализирует новый экземпляр класса [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) с указанным прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Выбранная область, заданная как прямоугольник. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns:**
java.lang.Object — Новый объект, являющийся копией этого экземпляра.
