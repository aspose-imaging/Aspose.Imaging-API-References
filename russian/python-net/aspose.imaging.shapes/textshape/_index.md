---
title: "Класс TextShape"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextShape()](#TextShape__1) | Инициализирует новый экземпляр класса [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Инициализирует новый экземпляр класса [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает границы объекта. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает центр фигуры. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Получает или задает шрифт, используемый для отрисовки текста. |
| has_segments | bool | r | Возвращает значение, указывающее, имеет ли фигура сегменты. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает левую нижнюю точку прямоугольника. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает левую верхнюю точку прямоугольника. |
| rectangle_height | float | r | Возвращает высоту прямоугольника. |
| rectangle_width | float | r | Возвращает ширину прямоугольника. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает правую нижнюю точку прямоугольника. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает правую верхнюю точку прямоугольника. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Возвращает сегменты фигуры. |
| text | string | r/w | Получает или задает отрисованный текст. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Получает или задает формат текста. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к форме. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Инициализирует новый экземпляр класса [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Инициализирует новый экземпляр класса [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Текст для отрисовки. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник текста. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Шрифт для использования. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Формат строки. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка, используемая для объекта. Это может влиять на размер границ объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Применяет указанное преобразование к форме.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Преобразование для применения. |

