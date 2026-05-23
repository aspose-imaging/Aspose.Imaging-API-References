---
title: "Classe CurveShape"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0,5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0,5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il centro della forma. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene il punto finale della forma. |
| has_segments | bool | r | Restituisce un valore che indica se la forma ha segmenti. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se la forma è chiusa. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i punti della curva. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Restituisce i segmenti della forma. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene il punto iniziale della forma. |
| tensione | float | r/w | Ottiene o imposta la tensione della curva. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0,5. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Ottiene i limiti dell'oggetto. |
| reverse() | Inverte l'ordine dei punti per questa forma. |
| [transform(transform)](#transform_transform_5) | Applica la trasformazione specificata alla forma. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |
| is_closed | bool | Se impostato su <c>true</c> la curva è chiusa. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |
| tensione | float | La tensione della curva. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |
| tensione | float | La tensione della curva. |
| is_closed | bool | Se impostato su <c>true</c> la curva è chiusa. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |
| is_closed | bool | Se impostato su <c>true</c> la curva è chiusa. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Inizializza una nuova istanza della classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |
| tensione | float | La tensione della curva. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La trasformazione da applicare. |

