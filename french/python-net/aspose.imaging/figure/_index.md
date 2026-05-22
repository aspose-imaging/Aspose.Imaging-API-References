---
title: "Classe Figure"
type: docs
weight: 4770
url: /fr/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Initialise une nouvelle instance de [Figure](/imaging/python-net/aspose.imaging/figure/).<br/>            Un constructeur requis pour la désérialisation JSON. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient ou définit les limites de l'objet. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où<br/>            les formes de la première et de la dernière figure sont continues. Dans ce cas, le premier point de la première forme sera<br/>            relié par une ligne droite au dernier point de la dernière forme. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtient tous les segments de la figure. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Obtient les formes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Ajoute une forme à la figure. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Ajoute une plage de formes à la figure. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Obtient les limites de l'objet. |
| [remove_shape(shape)](#remove_shape_shape_5) | Supprime une forme de la figure. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Supprime une plage de formes de la figure. |
| reverse() | Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes. |
| [transform(transform)](#transform_transform_7) | Applique la transformation spécifiée à la forme. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initialise une nouvelle instance de [Figure](/imaging/python-net/aspose.imaging/figure/).<br/>            Un constructeur requis pour la désérialisation JSON.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Ajoute une forme à la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | La forme à ajouter. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Ajoute une plage de formes à la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Les formes à ajouter. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Supprime une forme de la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | La forme à supprimer. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Supprime une plage de formes de la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | La plage de formes à supprimer. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformation à appliquer. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Créez une instance d'un flux de fichier
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Créez une instance de TiffOptions et définissez ses différentes propriétés
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Définissez la source pour l'instance de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Créez une instance de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		# Efface la surface Graphics
		graphics.clear(Color.wheat);
		# Créez une instance de la classe GraphicsPath
		graphics_path = GraphicsPath()
		# Créez une instance de la classe Figure
		figure = Figure()
		# Ajoutez des formes à l'objet Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Ajoutez l'objet Figure à GraphicsPath
		graphics_path.add_figure(figure)
		# Dessinez le chemin avec l'objet Pen de couleur Noir
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# enregistrez toutes les modifications.
		image.save()


```

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

