---
title: "Classe TextShape"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initialise une nouvelle instance de la classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initialise une nouvelle instance de la classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient les limites de l'objet. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le centre de la forme. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Obtient ou définit la police utilisée pour dessiner le texte. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point inférieur gauche du rectangle. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point supérieur gauche du rectangle. |
| rectangle_height | float | r | Obtient la hauteur du rectangle. |
| rectangle_width | float | r | Obtient la largeur du rectangle. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point inférieur droit du rectangle. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point supérieur droit du rectangle. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtient les segments de la forme. |
| text | string | r/w | Obtient ou définit le texte dessiné. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Obtient ou définit le format du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initialise une nouvelle instance de la classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initialise une nouvelle instance de la classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text | string | Le texte à dessiner. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle du texte. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | La police à utiliser. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Le format de chaîne. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice à appliquer avant que les limites ne soient calculées. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Les limites estimées de l'objet. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice à appliquer avant que les limites ne soient calculées. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Les limites estimées de l'objet. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformation à appliquer. |

