---
title: "Classe TextShape"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TextShape()](#TextShape__1) | Inizializza una nuova istanza della classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Inizializza una nuova istanza della classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il centro della forma. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Ottiene o imposta il font usato per disegnare il testo. |
| has_segments | bool | r | Restituisce un valore che indica se la forma ha segmenti. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in basso a sinistra del rettangolo. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in alto a sinistra del rettangolo. |
| rectangle_height | float | r | Restituisce l'altezza del rettangolo. |
| rectangle_width | float | r | Restituisce la larghezza del rettangolo. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in basso a destra del rettangolo. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in alto a destra del rettangolo. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Restituisce i segmenti della forma. |
| text | string | r/w | Ottiene o imposta il testo disegnato. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Ottiene o imposta il formato del testo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Inizializza una nuova istanza della classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Inizializza una nuova istanza della classe [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | string | Il testo da disegnare. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo del testo. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Il font da usare. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Il formato stringa. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | I limiti stimati dell'oggetto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna da usare per l'oggetto. Questo può influenzare la dimensione dei limiti dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | I limiti stimati dell'oggetto. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La trasformazione da applicare. |

