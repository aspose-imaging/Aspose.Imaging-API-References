---
title: "TextShape-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initierar en ny instans av klassen [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initierar en ny instans av klassen [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar objektets gränser. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar figurens centrum. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Hämtar eller anger teckensnittet som används för att rita texten. |
| has_segments | bool | r | Hämtar ett värde som indikerar om figuren har segment. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den vänstra nedre rektangelpunkten. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den vänstra övre rektangelpunkten. |
| rectangle_height | float | r | Hämtar rektangelns höjd. |
| rectangle_width | float | r | Hämtar rektangelns bredd. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den högra nedre rektangelpunkten. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den högra övre rektangelpunkten. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Hämtar figurens segment. |
| text | string | r/w | Hämtar eller anger den ritade texten. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Hämtar eller anger textformatet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initierar en ny instans av klassen [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initierar en ny instans av klassen [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | Texten att rita. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Textrutan. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Teckensnittet att använda. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Strängformatet. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Transformationen att tillämpa. |

