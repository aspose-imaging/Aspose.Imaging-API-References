---
title: "GraphicsPath-klass"
type: docs
weight: 5040
url: /sv/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar eller anger objektets gränser. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Hämtar sökvägsfigurerna. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Hämtar eller anger en [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration som bestämmer hur innanmålen av former i denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) fylls. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Lägger till en ny figur. |
| [add_figures(figures)](#add_figures_figures_2) | Lägger till nya figurer. |
| [add_path(adding_path)](#add_path_adding_path_3) | Lägger till den angivna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till denna sökväg. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Lägger till den angivna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till denna sökväg. |
| [deep_clone()](#deep_clone__5) | Utför en djup kloning av denna grafikväg. |
| flatten() | Konverterar varje kurva i denna sökväg till en sekvens av sammanhängande linjesegment. |
| [flatten(matrix)](#flatten_matrix_6) | Tillämpar den angivna transformationen och konverterar sedan varje kurva i denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till en sekvens av sammanhängande linjesegment. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Konverterar varje kurva i denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till en sekvens av sammanhängande linjesegment. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Hämtar objektets gränser. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point)](#is_visible_point_26) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) i den synliga klipprutan för den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) i den synliga klipprutan för den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point(point)](#is_visible_point_point_34) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) i den synliga klipprutan för den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_42) | Tar bort en figur. |
| [remove_figures(figures)](#remove_figures_figures_43) | Tar bort figurer. |
| reset() | Tömmer grafikvägen och sätter [FillMode](/imaging/python-net/aspose.imaging/fillmode/) till [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Vänder ordningen på figurer, former och punkter i varje form i denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | Tillämpar den angivna transformationen på formen. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | Lägger till en extra kontur till vägen. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Lägger till en extra kontur till [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Ersätter denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) med kurvor som omsluter området som fylls när denna väg ritas med den angivna pennan. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Figurerna att initiera från. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Figurerna att initiera från. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Fyllningsläget. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initierar en ny instans av klassen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Fyllningsläget. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Lägger till en ny figur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Figuren att lägga till. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Lägger till nya figurer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Figurerna att lägga till. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Lägger till den angivna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till denna sökväg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Den [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) att lägga till. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Lägger till den angivna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till denna sökväg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Den [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) att lägga till. |
| anslut | bool | Ett booleskt värde som anger om den första figuren i den tillagda vägen är en del av den sista figuren i denna väg. Ett värde av true anger att den första figuren i den tillagda vägen är en del av den sista figuren i denna väg. Ett värde av false anger att den första figuren i den tillagda vägen är separat från den sista figuren i denna väg. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Utför en djup kloning av denna grafikväg.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | En djup klon av grafikvägen. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Tillämpar den angivna transformationen och konverterar sedan varje kurva i denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till en sekvens av sammanhängande linjesegment.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som används för att transformera denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) innan den plattas ut. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Konverterar varje kurva i denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) till en sekvens av sammanhängande linjesegment.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som används för att transformera denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) innan den plattas ut. |
| platthet | float | Anger det maximalt tillåtna felet mellan kurvan och dess plattade approximation. Ett värde på 0,25 är standard. Att minska platthetsvärdet kommer att öka antalet linjesegment i approximationen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | En [Point](/imaging/python-net/aspose.imaging/point/) som anger platsen att testa. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/) och med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Den [Pen](/imaging/python-net/aspose.imaging/pen/) att testa. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) när den ritas med den angivna [Pen](/imaging/python-net/aspose.imaging/pen/); annars false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom detta; annars false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom detta; annars false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) i den synliga klipprutan för den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) i den synliga klipprutan för den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | En [PointF](/imaging/python-net/aspose.imaging/pointf/) som representerar punkten som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom detta; annars false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | En [Point](/imaging/python-net/aspose.imaging/point/) som representerar punkten som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), med den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för den punkt som ska testas. |
| y | int | Y-koordinaten för den punkt som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) i den synliga klipprutan för den angivna [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för den punkt som ska testas. |
| y | float | Y-koordinaten för den punkt som ska testas. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Den [Graphics](/imaging/python-net/aspose.imaging/graphics/) för vilken synlighet ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); annars false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Tar bort en figur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Figuren som ska tas bort. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Tar bort figurer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Figurerna som ska tas bort. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Transformationen att tillämpa. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar ett parallellogram som rektangeln definierad av _srcRect_ transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av _destPoints_. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar ett parallellogram som rektangeln definierad av _srcRect_ transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som specificerar en geometrisk transformation att tillämpa på sökvägen. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar ett parallellogram som rektangeln definierad av _srcRect_ transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som specificerar en geometrisk transformation att tillämpa på sökvägen. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | En [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilineärt läge. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar ett parallellogram som rektangeln definierad av _srcRect_ transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, är det nedre högra hörnet av parallellogrammet underförstått av de första tre punkterna. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som specificerar en geometrisk transformation att tillämpa på sökvägen. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | En [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilineärt läge. |
| flatness | float | Ett värde från 0 till 1 som specificerar hur platt den resulterande sökvägen är. För mer information, se metoderna [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Lägger till en extra kontur till vägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som specificerar bredden mellan den ursprungliga konturen av sökvägen och den nya kontur som denna metod skapar. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Lägger till en extra kontur till [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som specificerar bredden mellan den ursprungliga konturen av sökvägen och den nya kontur som denna metod skapar. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som specificerar en transformation att tillämpa på sökvägen innan den breddas. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Ersätter denna [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) med kurvor som omsluter området som fylls när denna väg ritas med den angivna pennan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som specificerar bredden mellan den ursprungliga konturen av sökvägen och den nya kontur som denna metod skapar. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En [Matrix](/imaging/python-net/aspose.imaging/matrix/) som specificerar en transformation att tillämpa på sökvägen innan den breddas. |
| platthet | float | Ett värde som specificerar plattheten för kurvor. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Skapa en instans av en filström
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Skapa en instans av TiffOptions och ställ in dess olika egenskaper
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Ange källan för instansen av ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Skapa en instans av Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		# Rensa Graphics-ytan
		graphics.clear(Color.wheat);
		# Skapa en instans av klassen GraphicsPath
		graphics_path = GraphicsPath()
		# Skapa en instans av klassen Figure
		figure = Figure()
		# Lägg till former till Figure-objektet
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Lägg till Figure-objektet till GraphicsPath
		graphics_path.add_figure(figure)
		# Rita bana med Pen-objektet i färgen svart
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# spara alla ändringar.
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

#Skapar en instans av BmpOptions och ställer in dess olika egenskaper            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
	#Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Skapa en instans av Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		# Rensa Graphics-ytan
		graphics.clear(Color.wheat)
		# Skapa en instans av klassen GraphicsPath
		graphicspath = GraphicsPath()
		#Skapa en instans av klassen Figure
		figure1 = Figure()
		# Lägg till form till Figure-objektet
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Skapa en instans av klassen Figure
		figure2 = Figure()
		# Lägg till form till Figure-objektet
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Lägg till Figure-objektet till GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Rita bana med Pen-objektet i färgen svart
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# spara alla ändringar.
		image.save()


```

