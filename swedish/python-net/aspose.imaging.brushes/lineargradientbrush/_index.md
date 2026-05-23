---
title: "LinearGradientBrush-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med standardparametrar.<br/>            Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| vinkel | float | r/w | Hämtar eller anger gradientvinkeln. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Hämtar eller anger en [Blend](/imaging/python-net/aspose.imaging/blend/) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger den avslutande gradientfärgen. |
| gamma_correction | bool | r/w | Hämtar eller anger ett värde som indikerar om gamma‑korrektion är aktiverad för denna [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Hämtar eller anger en [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) som definierar en flerfärgs linjär gradient. |
| is_angle_scalable | bool | r/w | Hämtar eller anger ett värde som indikerar om [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) ändras under transformationer med denna [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller<br/>            anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger de start- och slutfärgerna för gradienten. |
| opacity | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att penseln är helt synlig, ett värde på 1 betyder att penseln är helt ogenomskinlig. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger startgradientfärgen. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger en kopia av [Matrix](/imaging/python-net/aspose.imaging/matrix/) som definierar en lokal geometrisk transformation för denna [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Hämtar eller anger en [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration som indikerar omslagsläget för detta [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med de angivna punkterna och färgerna. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med de angivna punkterna och färgerna. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [deep_clone()](#deep_clone__7) | Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med standardparametrar.<br/>            Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Punkt1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Punkt2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Punkt1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Punkt2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangeln. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg2. |
| vinkel | float | Vinkeln. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg2. |
| vinkel | float | Vinkeln. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangeln. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg2. |
| vinkel | float | Vinkeln. |
| is_angle_scalable | bool | om den är satt till <c>true</c> [is angle scalable]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Färg2. |
| vinkel | float | Vinkeln. |
| is_angle_scalable | bool | om den är satt till <c>true</c> [is angle scalable]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med de angivna punkterna och färgerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | En [Point](/imaging/python-net/aspose.imaging/point/) struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | En [Point](/imaging/python-net/aspose.imaging/point/) struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar slutfärgen för den linjära gradienten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med de angivna punkterna och färgerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar slutfärgen för den linjära gradienten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| is_angle_scalable | bool | om den är satt till <c>true</c> ändras vinkeln under transformationer med denna [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | En [Color](/imaging/python-net/aspose.imaging/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| is_angle_scalable | bool | om den är satt till <c>true</c> ändras vinkeln under transformationer med denna [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | En ny [Brush](/imaging/python-net/aspose.imaging/brush/) som är den djupa klonen av detta [Brush](/imaging/python-net/aspose.imaging/brush/)-instans. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som anger om skalningsmatrisen ska läggas till eller föregås. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar mitten av gradienten (punkten där gradienten endast består av slutfärgen). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar mitten av gradienten (punkten där gradienten endast består av slutfärgen). |
| skala | float | Ett värde från 0 till 1 som specificerar hur snabbt färgerna avtar från startfärgen till _focus_ (slutfärg). |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar mitten av gradienten (punkten där startfärgen och slutfärgen blandas lika). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar mitten av gradienten (punkten där gradienten endast består av slutfärgen). |
| skala | float | Ett värde från 0 till 1 som specificerar hur snabbt färgerna avtar från _focus_. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen (före eller efter) i vilken translationen ska tillämpas. |

