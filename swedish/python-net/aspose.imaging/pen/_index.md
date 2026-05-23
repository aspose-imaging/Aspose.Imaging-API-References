---
title: "Pen Class"
type: docs
weight: 6890
url: /sv/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [Pen(color)](#Pen_color_3) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna färgen. |
| [Pen(color, width)](#Pen_color_width_4) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med de angivna egenskaperna [Pen.color](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Hämtar eller anger justeringen för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Hämtar eller anger [Pen.brush](/imaging/python-net/aspose.imaging/pen/) som bestämmer attributen för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger färgen på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | Hämtar eller anger en array av värden som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Hämtar eller anger en anpassad spets att använda i slutet av linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Hämtar eller anger en anpassad spets att använda i början av linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Hämtar eller anger spetsstilen som används i slutet av strecken som utgör streckade linjer ritat med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Hämtar eller anger avståndet från början av en linje till början av ett streckmönster. |
| dash_pattern | float[] | r/w | Hämtar eller anger en array av anpassade streck och mellanslag. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Hämtar eller anger stilen som används för streckade linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Hämtar eller anger kapstil som används i slutet av linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Hämtar eller anger sammanfogningsstil för ändarna på två på varandra följande linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Hämtar eller anger gränsen för tjockleken på sammanfogningen i ett fasat hörn. |
| opacity | float | r/w | Hämtar eller anger objektets opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att objektet är helt synligt, värdet 1 betyder att objektet är helt ogenomskinligt. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Hämtar stilen på linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Hämtar eller anger kapstil som används i början av linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger en kopia av den geometriska transformationen för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | Hämtar eller anger bredden på denna [Pen](/imaging/python-net/aspose.imaging/pen/), i enheter av Graphics-objektet som används för ritning. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_color(color)](#create_with_color_color_3) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna färgen. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med de angivna egenskaperna [Pen.color](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Multiplicerar transformationsmatrisen för denna [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Multiplicerar transformationsmatrisen för denna [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer den geometriska transformationsmatrisen för denna [Pen](/imaging/python-net/aspose.imaging/pen/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger rotationen före transformationen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger skalningsmatrisen före transformationen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Anger värdena som bestämmer kapstilen som används för att avsluta linjer ritade av denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger översättningen före transformationen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Pen.brush](/imaging/python-net/aspose.imaging/pen/) som bestämmer fyllningsegenskaperna för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Pen.brush](/imaging/python-net/aspose.imaging/pen/) som bestämmer egenskaperna för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Bredden på den nya [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | En [Pen.color](/imaging/python-net/aspose.imaging/pen/) struktur som anger färgen på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med de angivna egenskaperna [Pen.color](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | En [Pen.color](/imaging/python-net/aspose.imaging/pen/) struktur som anger färgen på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Ett värde som anger bredden på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Pen.brush](/imaging/python-net/aspose.imaging/pen/) som bestämmer fyllningsegenskaperna för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Pen.brush](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Pen.brush](/imaging/python-net/aspose.imaging/pen/) som bestämmer egenskaperna för denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Bredden på den nya [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | En [Pen.color](/imaging/python-net/aspose.imaging/pen/) struktur som anger färgen på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Initierar en ny instans av klassen [Pen](/imaging/python-net/aspose.imaging/pen/) med de angivna egenskaperna [Pen.color](/imaging/python-net/aspose.imaging/pen/) och [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | En [Pen.color](/imaging/python-net/aspose.imaging/pen/) struktur som anger färgen på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Ett värde som anger bredden på denna [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Multiplicerar transformationsmatrisen för denna [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Det [Matrix](/imaging/python-net/aspose.imaging/matrix/)‑objektet som ska multipliceras med transformationsmatrisen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Multiplicerar transformationsmatrisen för denna [Pen](/imaging/python-net/aspose.imaging/pen/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med transformationsmatrisen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Den ordning i vilken multiplikationsoperationen ska utföras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger rotationen före transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger skalningsmatrisen före transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Faktorn som ska skalas transformationen i x‑axelns riktning. |
| sy | float | Faktorn som ska skalas transformationen i y‑axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Faktorn som ska skalas transformationen i x‑axelns riktning. |
| sy | float | Faktorn som ska skalas transformationen i y‑axelns riktning. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som anger om skalningsmatrisen ska läggas till eller föregås. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Anger värdena som bestämmer kapstilen som används för att avsluta linjer ritade av denna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | En [LineCap](/imaging/python-net/aspose.imaging/linecap/) som representerar kapstilen att använda i början av linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | En [LineCap](/imaging/python-net/aspose.imaging/linecap/) som representerar kapstilen att använda i slutet av linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | En [LineCap](/imaging/python-net/aspose.imaging/linecap/) som representerar kapstilen att använda i början eller slutet av streckade linjer som ritas med denna [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger översättningen före transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen (före eller efter) i vilken translationen ska tillämpas. |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Skapa en instans av BmpOptions och sätt dess olika egenskaper
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
# Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Skapa en instans av Image på angiven sökväg
with Image.create(bmpOptions, 500, 500) as image:
	# Skapa en instans av Graphics och initiera den med Image‑objektet
	graphics = Graphics(image)
	# Rensa Graphics‑ytan med vit färg
	graphics.clear(Color.white)
	#Skapa en instans av Pen med färgen röd och bredd 5
	pen = Pen(Color.red, 5.0);
	# Skapa en instans av HatchBrush och sätt dess egenskaper
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Skapa en instans av Pen
	# initiera den med HatchBrush-objekt och bredd
	brusedpen = Pen(brush, 5.0)
	# Rita rektanglar genom att ange Pen-objekt
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Rita rektanglar genom att ange Pen-objekt
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# spara alla ändringar.
	image.save()


```

