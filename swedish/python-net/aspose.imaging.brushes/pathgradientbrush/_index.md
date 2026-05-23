---
title: "PathGradientBrush klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Initierar en ny instans av PathGradientBrush-klassen |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_2) | Initierar en ny instans av PathGradientBrush-klassen |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_3) | Initierar en ny instans av PathGradientBrush-klassen |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_4) | Initierar en ny instans av PathGradientBrush-klassen |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_5) | Initierar en ny instans av PathGradientBrush-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Hämtar eller anger en [Blend](/imaging/python-net/aspose.imaging/blend/) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| center_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger färgen i mitten av path gradienten. |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger mittpunkten för bangradienten. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger fokuspunkten för gradientens avtagande. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Hämtar grafikvägen som denna pensel byggdes på. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Hämtar eller anger en [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) som definierar en flerfärgs linjär gradient. |
| is_transform_changed | bool | r | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller<br/>            anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| opacity | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att penseln är helt synlig, ett värde på 1 betyder att penseln är helt ogenomskinlig. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar banpunkterna som denna pensel byggdes på. |
| surround_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger en array av färger som motsvarar punkterna i banan som denna [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) fyller. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger en kopia av [Matrix](/imaging/python-net/aspose.imaging/matrix/) som definierar en lokal geometrisk transformation för denna [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Hämtar eller anger en [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration som indikerar omslagsläget för detta [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med den angivna banan. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna och omslagsläget. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna och omslagsläget. |
| [deep_clone()](#deep_clone__6) | Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_13) | Skapar en gradient med en mittfärg och ett linjärt avtagande till en omgivande färg. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_14) | Skapar en gradient med en mittfärg och ett linjärt avtagande till varje omgivande färg. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_15) | Skapar en gradientpensel som ändrar färg med början från mitten av banan och utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_16) | Skapar en gradientpensel som ändrar färg med början från mitten av banan och utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_17) | Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_18) | Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Initierar en ny instans av PathGradientBrush-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_2}


```
 PathGradientBrush(path_points) 
```

Initierar en ny instans av PathGradientBrush-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_3}


```
 PathGradientBrush(path_points) 
```

Initierar en ny instans av PathGradientBrush-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_4}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Initierar en ny instans av PathGradientBrush-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_5}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Initierar en ny instans av PathGradientBrush-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med den angivna banan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Den [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) som definierar området som fylls av detta [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som bildar banans hörn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som bildar banans hörn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna och omslagsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som bildar banans hörn. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ett [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) som specificerar hur fyllningar som ritas med detta [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) kaklas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Initierar en ny instans av [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) klassen med de angivna punkterna och omslagsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | En array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar de punkter som bildar banans hörn. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ett [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) som specificerar hur fyllningar som ritas med detta [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) kaklas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | En ny [Brush](/imaging/python-net/aspose.imaging/brush/) som är den djupa klonen av detta [Brush](/imaging/python-net/aspose.imaging/brush/)-instans. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_13}


```
 set_blend_triangular_shape(focus) 
```

Skapar en gradient med en mittfärg och ett linjärt avtagande till en omgivande färg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_14}


```
 set_blend_triangular_shape(focus, scale) 
```

Skapar en gradient med en mittfärg och ett linjärt avtagande till varje omgivande färg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |
| skala | float | Ett värde från 0 till 1 som specificerar den maximala intensiteten för centrumfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för centrumfärgen, och det är standardvärdet. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_15}


```
 set_sigma_bell_shape(focus) 
```

Skapar en gradientpensel som ändrar färg med början från mitten av banan och utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_16}


```
 set_sigma_bell_shape(focus, scale) 
```

Skapar en gradientpensel som ändrar färg med början från mitten av banan och utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |
| skala | float | Ett värde från 0 till 1 som specificerar den maximala intensiteten för centrumfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för centrumfärgen, och det är standardvärdet. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_17}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_18}


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

