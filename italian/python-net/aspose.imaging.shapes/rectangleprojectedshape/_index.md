---
title: "Classe RectangleProjectedShape"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.RectangleProjectedShape

**Inheritance:** Shape

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il centro della forma. |
| has_segments | bool | r | Restituisce un valore che indica se la forma ha segmenti. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in basso a sinistra del rettangolo. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in alto a sinistra del rettangolo. |
| rectangle_height | float | r | Restituisce l'altezza del rettangolo. |
| rectangle_width | float | r | Restituisce la larghezza del rettangolo. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in basso a destra del rettangolo. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in alto a destra del rettangolo. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Restituisce i segmenti della forma. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


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

