---
title: "Classe PolygonShape"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initialise une nouvelle instance de la classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Initialise une nouvelle instance de la classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initialise une nouvelle instance de la classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient les limites de l'objet. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le centre de la forme. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point final de la forme. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si la forme est fermée. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les points de la courbe. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtient les segments de la forme. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point de départ de la forme. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| reverse() | Inverse l'ordre des points pour cette forme. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initialise une nouvelle instance de la classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initialise une nouvelle instance de la classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initialise une nouvelle instance de la classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| is_closed | bool | Si défini sur <c>true</c> le polygone est fermé. |

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

## **Examples**
### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#Crée une instance de BmpOptions et définissez ses différentes propriétés
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de BmpOptions
	#Le deuxième paramètre booléen détermine si le fichier à créer est temporaire ou non
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Créez une instance de Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		# Efface la surface Graphics
		graphics.clear(Color.wheat)
		# Créez une instance de la classe GraphicsPath
		graphicspath = GraphicsPath()
		#Créez une instance de la classe Figure
		figure1 = Figure()
		# Ajoutez une forme à l'objet Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Créez une instance de la classe Figure
		figure2 = Figure()
		# Ajoutez une forme à l'objet Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Ajoutez l'objet Figure à GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Dessinez le chemin avec l'objet Pen de couleur Noir
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# enregistrez toutes les modifications.
		image.save()


```

