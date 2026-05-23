---
title: "Класс TextureBrush"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и режим обтекания. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает объект [Image](/imaging/python-net/aspose.imaging/image/), связанный с этим объектом [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Получает [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/), связанные с этим [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , связанный с этим [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| opacity | float | r/w | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает копию [Matrix](/imaging/python-net/aspose.imaging/matrix/), определяющую локальное геометрическое преобразование для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Получает или задает перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), которое указывает режим обтекания для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и режим обтекания. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [deep_clone()](#deep_clone__8) | Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Объект [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) , содержащий дополнительную информацию об изображении, используемом этим [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объектом. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Объект [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) , содержащий дополнительную информацию об изображении, используемом этим [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объектом. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и режим обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) , определяющее, как этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объект заполняется плиткой. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) , определяющее, как этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объект заполняется плиткой. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) , определяющее, как этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объект заполняется плиткой. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Объект [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) , содержащий дополнительную информацию об изображении, используемом этим [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объектом. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Объект [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) , содержащий дополнительную информацию об изображении, используемом этим [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объектом. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение и режим обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) , определяющее, как этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объект заполняется плиткой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) , определяющее, как этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объект заполняется плиткой. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Объект [Image](/imaging/python-net/aspose.imaging/image/) , с помощью которого этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) , определяющее, как этот [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объект заполняется плиткой. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , представляющая ограничивающий прямоугольник для этого [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Новый [Brush](/imaging/python-net/aspose.imaging/brush/), который является глубоким клоном этого экземпляра [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Вращает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая, следует ли добавить в конец или в начало матрицу вращения. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Тип [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) который указывает, добавлять или предварять матрицу масштабирования. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


```
 translate_transform(dx, dy, order) 
```

Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок (предварительно или последовательно), в котором применяется трансляция. |

