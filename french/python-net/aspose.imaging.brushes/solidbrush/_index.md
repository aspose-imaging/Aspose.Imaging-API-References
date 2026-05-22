---
title: "Classe SolidBrush"
type: docs
weight: 80
url: /fr/python-net/aspose.imaging.brushes/solidbrush/
---

**Summary:** Solid brush is intended for drawing continiously with specific color. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.SolidBrush

**Inheritance:** Brush

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SolidBrush()](#SolidBrush__1) | Initialise une nouvelle instance de la classe [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/). |
| [SolidBrush(color)](#SolidBrush_color_2) | Initialise une nouvelle instance de la classe [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [color](#color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur du pinceau. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est totalement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel. |


### Constructor: SolidBrush() {#SolidBrush__1}


```
 SolidBrush() 
```

Initialise une nouvelle instance de la classe [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/).


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Constructor: SolidBrush(color) {#SolidBrush_color_2}


```
 SolidBrush(color) 
```

Initialise une nouvelle instance de la classe [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du pinceau solide. |

### Property: color {#color1}

Obtient ou définit la couleur du pinceau.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel.

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nouveau [Brush](/imaging/python-net/aspose.imaging/brush/) qui est le clone profond de cette instance [Brush](/imaging/python-net/aspose.imaging/brush/). |


## **Examples**
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Crée une instance de flux de fichier
with open(r"C:\temp\output.png", "w+b") as stream:
	#Créez une instance de PngOptions et définissez ses différentes propriétés
	pngOptions = PngOptions()
	#Définissez la source pour PngOptions
	pngOptions.source = StreamSource(stream)
	#Créez une instance de Image
	with Image.create(pngOptions, 500, 500) as image:
		#Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		#Efface la surface Graphics
		graphics.clear(Color.wheat);
		#Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
		#un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Dessinez un Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Dessinez une courbe en spécifiant l'objet Pen ayant la couleur Verte et un tableau de Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Dessinez une ellipse en utilisant l'objet Pen et un rectangle environnant
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Dessinez une ligne
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Dessinez un segment de tarte
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Dessinez un polygone en spécifiant l'objet Pen ayant la couleur Rouge et un tableau de Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Dessinez un rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Créez un objet SolidBrush et définissez ses différentes propriétés
		brush = SolidBrush()
		brush.color = Color.purple
		#Dessinez un String en utilisant l'objet SolidBrush et Font, à un Point spécifique
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# enregistrez toutes les modifications.
		image.save();

```

