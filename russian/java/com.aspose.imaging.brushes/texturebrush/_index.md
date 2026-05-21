---
title: "TextureBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Каждое свойство класса Aspose.Imaging.Brushes.TextureBrush представляет объект Aspose.Imaging.Brush, который использует изображение для заполнения внутренней части фигуры."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Каждое свойство класса `Aspose.Imaging.Brushes.TextureBrush` представляет объект `Aspose.Imaging.Brush`, который использует изображение для заполнения внутренней части фигуры. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение и режим обтекания. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
## Методы

| Метод | Описание |
| --- | --- |
| [getImage()](#getImage--) | Получает объект `com.aspose.imaging.Image`, связанный с этим объектом `com.aspose.imaging.brushes.TextureBrush`. |
| [getImageAttributes()](#getImageAttributes--) | Получает `ImageAttributes`, связанные с этим `TextureBrush`. |
| [getImageRectangle()](#getImageRectangle--) | Получает `Rectangle`, связанный с этим `TextureBrush`. |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект `Aspose.Imaging.Image`, с помощью которого этот объект `Aspose.Imaging.Brushes.TextureBrush` заполняет внутренние области. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение и режим обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект `Aspose.Imaging.Image`, с помощью которого этот объект `Aspose.Imaging.Brushes.TextureBrush` заполняет внутренние области. |
| wrapMode | int | Перечисление `Aspose.Imaging.WrapMode`, которое указывает, как будет тайлироваться объект `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект [Image](../../com.aspose.imaging/image), с помощью которого объект [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) заполняет внутренние области. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Структура [Rectangle](../../com.aspose.imaging/rectangle), представляющая ограничивающий прямоугольник для объекта [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Объект [ImageAttributes](../../com.aspose.imaging/imageattributes), содержащий дополнительную информацию об изображении, используемом объектом [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект [Image](../../com.aspose.imaging/image), с помощью которого объект [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) заполняет внутренние области. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Структура [Rectangle](../../com.aspose.imaging/rectangle), представляющая ограничивающий прямоугольник для объекта [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект [Image](../../com.aspose.imaging/image), с помощью которого объект [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) заполняет внутренние области. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура [RectangleF](../../com.aspose.imaging/rectanglef), представляющая ограничивающий прямоугольник для объекта [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.imaging.brushes/texturebrush), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект [Image](../../com.aspose.imaging/image), с помощью которого объект [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) заполняет внутренние области. |
| wrapMode | int | Перечисление [WrapMode](../../com.aspose.imaging/wrapmode), которое указывает, как будет тайлироваться объект [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Структура [Rectangle](../../com.aspose.imaging/rectangle), представляющая ограничивающий прямоугольник для объекта [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект `Aspose.Imaging.Image`, с помощью которого этот объект `Aspose.Imaging.Brushes.TextureBrush` заполняет внутренние области. |
| wrapMode | int | Перечисление `Aspose.Imaging.WrapMode`, которое указывает, как будет тайлироваться объект `Aspose.Imaging.Brushes.TextureBrush`. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `Aspose.Imaging.RectangleF`, представляющая ограничивающий прямоугольник для объекта `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Инициализирует новый экземпляр класса `Aspose.Imaging.Brushes.TextureBrush`, использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Объект `Aspose.Imaging.Image`, с помощью которого этот объект `Aspose.Imaging.Brushes.TextureBrush` заполняет внутренние области. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `Aspose.Imaging.RectangleF`, представляющая ограничивающий прямоугольник для объекта `Aspose.Imaging.Brushes.TextureBrush`. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Объект `com.aspose.imaging.ImageAttributes`, содержащий дополнительную информацию об изображении, используемом объектом `Aspose.Imaging.Brushes.TextureBrush`. |

### getImage() {#getImage--}
```
public Image getImage()
```


Получает объект `com.aspose.imaging.Image`, связанный с этим объектом `com.aspose.imaging.brushes.TextureBrush`.

Значение: Объект `com.aspose.imaging.Image`, представляющий изображение, с помощью которого объект `com.aspose.imaging.brushes.TextureBrush` заполняет формы.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Получает `ImageAttributes`, связанные с этим `TextureBrush`.

Значение: `ImageAttributes`.

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Получает `Rectangle`, связанный с этим `TextureBrush`.

Значение: `Rectangle`.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
