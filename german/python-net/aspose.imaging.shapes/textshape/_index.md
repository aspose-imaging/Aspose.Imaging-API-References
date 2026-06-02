---
title: "TextShape Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initialisiert eine neue Instanz der Klasse [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initialisiert eine neue Instanz der Klasse [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt das Zentrum der Form zurück. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Liest oder setzt die zum Zeichnen des Textes verwendete Schriftart. |
| has_segments | bool | r | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den linken unteren Rechteckpunkt. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den linken oberen Rechteckpunkt. |
| rectangle_height | float | r | Liefert die Rechteckhöhe. |
| rectangle_width | float | r | Liefert die Rechteckbreite. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den rechten unteren Rechteckpunkt. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den rechten oberen Rechteckpunkt. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gibt die Formsegmente zurück. |
| text | string | r/w | Liest oder setzt den gezeichneten Text. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Liest oder setzt das Textformat. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initialisiert eine neue Instanz der Klasse [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initialisiert eine neue Instanz der Klasse [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | string | Der zu zeichnende Text. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Textrechteck. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Die zu verwendende Schriftart. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Das Zeichenkettenformat. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Begrenzungen des Objekts beeinflussen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die anzuwendende Transformation. |

