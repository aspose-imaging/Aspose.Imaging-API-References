---
title: "Classe Pen"
type: docs
weight: 6890
url: /fr/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [Pen(brush, width)](#Pen_brush_width_2) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) et le [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiés. |
| [Pen(color)](#Pen_color_3) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec la couleur spécifiée. |
| [Pen(color, width)](#Pen_color_width_4) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec les propriétés [Pen.color](/imaging/python-net/aspose.imaging/pen/) et [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Obtient ou définit l'alignement de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Obtient ou définit le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) qui détermine les attributs de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée de lignes parallèles et d'espaces. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Obtient ou définit un cap personnalisé à utiliser à la fin des lignes dessinées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Obtient ou définit un cap personnalisé à utiliser au début des lignes dessinées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Obtient ou définit le style de cap utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Obtient ou définit la distance du début d'une ligne au début d'un motif de tirets. |
| dash_pattern | float[] | r/w | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Obtient ou définit le style utilisé pour les lignes en pointillé tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Obtient ou définit le style de terminaison utilisé à l'extrémité des lignes tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| opacity | float | r/w | Obtient ou définit l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que l'objet est totalement visible, une valeur de 1 signifie que l'objet est totalement opaque. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Obtient le style des lignes tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Obtient ou définit le style de terminaison utilisé au début des lignes tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la transformation géométrique pour ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | Obtient ou définit la largeur de ce [Pen](/imaging/python-net/aspose.imaging/pen/), en unités de l'objet Graphics utilisé pour le dessin. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) et le [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiés. |
| [create_with_color(color)](#create_with_color_color_3) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec la couleur spécifiée. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec les propriétés [Pen.color](/imaging/python-net/aspose.imaging/pen/) et [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiées. |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Multiplie la matrice de transformation pour ce [Pen](/imaging/python-net/aspose.imaging/pen/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Multiplie la matrice de transformation pour ce [Pen](/imaging/python-net/aspose.imaging/pen/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la matrice de transformation géométrique pour ce [Pen](/imaging/python-net/aspose.imaging/pen/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Fait pivoter la transformation géométrique locale de l'angle spécifié. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre indiqué. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Définit les valeurs qui déterminent le style de terminaison utilisé pour terminer les lignes tracées par ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Translater la transformation géométrique locale par les dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre indiqué. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) qui détermine les propriétés de remplissage de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) et le [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) qui détermine les caractéristiques de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | La largeur du nouveau [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec la couleur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Pen.color](/imaging/python-net/aspose.imaging/pen/) qui indique la couleur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec les propriétés [Pen.color](/imaging/python-net/aspose.imaging/pen/) et [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Pen.color](/imaging/python-net/aspose.imaging/pen/) qui indique la couleur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Une valeur indiquant la largeur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) qui détermine les propriétés de remplissage de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec le [Pen.brush](/imaging/python-net/aspose.imaging/pen/) et le [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) qui détermine les caractéristiques de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | La largeur du nouveau [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec la couleur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Pen.color](/imaging/python-net/aspose.imaging/pen/) qui indique la couleur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Initialise une nouvelle instance de la classe [Pen](/imaging/python-net/aspose.imaging/pen/) avec les propriétés [Pen.color](/imaging/python-net/aspose.imaging/pen/) et [Pen.width](/imaging/python-net/aspose.imaging/pen/) spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Pen.color](/imaging/python-net/aspose.imaging/pen/) qui indique la couleur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Une valeur indiquant la largeur de ce [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Multiplie la matrice de transformation pour ce [Pen](/imaging/python-net/aspose.imaging/pen/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | L'objet [Matrix](/imaging/python-net/aspose.imaging/matrix/) par lequel multiplier la matrice de transformation. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Multiplie la matrice de transformation pour ce [Pen](/imaging/python-net/aspose.imaging/pen/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Le [Matrix](/imaging/python-net/aspose.imaging/matrix/) par lequel multiplier la matrice de transformation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre dans lequel effectuer l'opération de multiplication. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de l'angle spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Définit les valeurs qui déterminent le style de terminaison utilisé pour terminer les lignes tracées par ce [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) qui représente le style de terminaison à utiliser au début des lignes tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) qui représente le style de terminaison à utiliser à la fin des lignes tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) qui représente le style de terminaison à utiliser au début ou à la fin des lignes pointillées tracées avec ce [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Translater la transformation géométrique locale par les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Créez une instance de BmpOptions et définissez ses différentes propriétés
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de BmpOptions
# Le deuxième paramètre booléen détermine si le fichier à créer est temporaire ou non
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Créez une instance d'Image au chemin spécifié
with Image.create(bmpOptions, 500, 500) as image:
	# Créez une instance de Graphics et initialisez‑la avec l'objet Image
	graphics = Graphics(image)
	# Effacez la surface Graphics avec la couleur blanche
	graphics.clear(Color.white)
	#Créez une instance de Pen avec la couleur Rouge et une largeur de 5
	pen = Pen(Color.red, 5.0);
	# Créez une instance de HatchBrush et définissez ses propriétés
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Créez une instance de Pen
	# initialisez-le avec l'objet HatchBrush et la largeur
	brusedpen = Pen(brush, 5.0)
	# Dessinez des rectangles en spécifiant l'objet Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Dessinez des rectangles en spécifiant l'objet Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# enregistrez toutes les modifications.
	image.save()


```

