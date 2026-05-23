---
title: "GraphicsPath Klasse"
type: docs
weight: 5040
url: /de/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest oder setzt die Begrenzungen des Objekts. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Liefert die Pfadfiguren. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Liefert oder setzt eine [FillMode](/imaging/python-net/aspose.imaging/fillmode/)-Aufzählung, die bestimmt, wie die Innenbereiche von Formen in diesem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) gefüllt werden. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Fügt eine neue Figur hinzu. |
| [add_figures(figures)](#add_figures_figures_2) | Fügt neue Figuren hinzu. |
| [add_path(adding_path)](#add_path_adding_path_3) | Hängt den angegebenen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an diesen Pfad an. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Hängt den angegebenen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an diesen Pfad an. |
| [deep_clone()](#deep_clone__5) | Führt eine tiefe Kopie dieses Grafikpfads aus. |
| flatten() | Konvertiert jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente. |
| [flatten(matrix)](#flatten_matrix_6) | Wendet die angegebene Transformation an und konvertiert dann jede Kurve in diesem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in eine Sequenz verbundener Liniensegmente. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Konvertiert jede Kurve in diesem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in eine Sequenz verbundener Liniensegmente. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Liest die Begrenzungen des Objekts. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird. |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_visible(point)](#is_visible_point_26) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible(point)](#is_visible_point_27) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible(x, y)](#is_visible_x_y_30) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible(x, y)](#is_visible_x_y_31) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/imaging/python-net/aspose.imaging/graphics/) liegt. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/imaging/python-net/aspose.imaging/graphics/) liegt. |
| [is_visible_point(point)](#is_visible_point_point_34) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wobei das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird. |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt. |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/imaging/python-net/aspose.imaging/graphics/) liegt. |
| [remove_figure(figure)](#remove_figure_figure_42) | Entfernt eine Figur. |
| [remove_figures(figures)](#remove_figures_figures_43) | Entfernt Figuren. |
| reset() | Leert den Grafikpfad und setzt das [FillMode](/imaging/python-net/aspose.imaging/fillmode/) auf [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) um. |
| [transform(transform)](#transform_transform_44) | Wendet die angegebene Transformation auf die Form an. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an. |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an. |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an. |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an. |
| [widen(pen)](#widen_pen_49) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Fügt dem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) eine zusätzliche Kontur hinzu. |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Ersetzt diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Die Figuren, von denen initialisiert werden soll. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Die Figuren, von denen initialisiert werden soll. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Der Füllmodus. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Der Füllmodus. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Fügt eine neue Figur hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Die hinzuzufügende Figur. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Fügt neue Figuren hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Die hinzuzufügenden Figuren. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Hängt den angegebenen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an diesen Pfad an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der hinzuzufügende [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Hängt den angegebenen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an diesen Pfad an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der hinzuzufügende [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| verbinden | bool | Ein boolescher Wert, der angibt, ob die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert true gibt an, dass die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert false gibt an, dass die erste Figur im hinzugefügten Pfad von der letzten Figur in diesem Pfad getrennt ist. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Führt eine tiefe Kopie dieses Grafikpfads aus.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Eine tiefe Kopie des Grafikpfads. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Wendet die angegebene Transformation an und konvertiert dann jede Kurve in diesem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in eine Sequenz verbundener Liniensegmente.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der dieser [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) vor dem Abflachen transformiert wird. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Konvertiert jede Kurve in diesem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in eine Sequenz verbundener Liniensegmente.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der dieser [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) vor dem Abflachen transformiert wird. |
| Flachheit | float | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an. Der Standardwert ist 0,25. Eine Verringerung des Flachheitswertes erhöht die Anzahl der Liniensegmente in der Annäherung. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Begrenzungen des Objekts beeinflussen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [Point](/imaging/python-net/aspose.imaging/point/), der den zu testenden Ort angibt. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird und das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der zu testende [Pen](/imaging/python-net/aspose.imaging/pen/). |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/imaging/python-net/aspose.imaging/pen/) gezeichnet wird; andernfalls false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses Objekts enthalten ist; andernfalls false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses Objekts enthalten ist; andernfalls false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/imaging/python-net/aspose.imaging/graphics/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/imaging/python-net/aspose.imaging/graphics/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) , der den zu testenden Punkt darstellt. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses Objekts enthalten ist; andernfalls false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [Point](/imaging/python-net/aspose.imaging/point/) , der den zu testenden Punkt darstellt. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt, wobei das angegebene [Graphics](/imaging/python-net/aspose.imaging/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/imaging/python-net/aspose.imaging/graphics/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Das [Graphics](/imaging/python-net/aspose.imaging/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) enthalten ist; andernfalls false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Entfernt eine Figur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Die zu entfernende Figur. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Entfernt Figuren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Die zu entfernenden Figuren. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die anzuwendende Transformation. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das durch _srcRect_ definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , der das Rechteck darstellt, das in das durch _destPoints_ definierte Parallelogramm transformiert wird. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das durch _srcRect_ definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , der das Rechteck darstellt, das in das durch _destPoints_ definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/) , die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, das ein Parallelogramm definiert, zu dem das durch _srcRect_ definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , der das Rechteck darstellt, das in das durch _destPoints_ definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/) , die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Eine [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) Aufzählung, die angibt, ob diese Verzerrungsoperation den Perspektiv- oder den bilinearen Modus verwendet. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das durch _srcRect_ definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) , der das Rechteck darstellt, das in das durch _destPoints_ definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/) , die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Eine [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) Aufzählung, die angibt, ob diese Verzerrungsoperation den Perspektiv- oder den bilinearen Modus verwendet. |
| flatness | float | Ein Wert von 0 bis 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie in den [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/) Methoden. |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Fügt dem Pfad eine zusätzliche Kontur hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) , der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Fügt dem [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) eine zusätzliche Kontur hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) , der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/) , die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Ersetzt diesen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) , der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine [Matrix](/imaging/python-net/aspose.imaging/matrix/) , die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |
| Flachheit | float | Ein Wert, der die Flachheit für Kurven angibt. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Erstelle eine Instanz eines Dateistreams
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Legen Sie die Quelle für die Instanz von ImageOptions fest
	tiffOptions.source = StreamSource(stream)
	# Erstellen Sie eine Instanz von Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		# Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		# Erstellen Sie eine Instanz der Klasse GraphicsPath
		graphics_path = GraphicsPath()
		# Erstellen Sie eine Instanz der Klasse Figure
		figure = Figure()
		# Fügen Sie dem Figure-Objekt Formen hinzu
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Fügen Sie das Figure-Objekt zu GraphicsPath hinzu
		graphics_path.add_figure(figure)
		# Zeichnen Sie den Pfad mit dem Pen-Objekt in der Farbe Schwarz
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Alle Änderungen speichern.
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

#Erstellt eine Instanz von BmpOptions und setzt deren verschiedene Eigenschaften
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Quelle für die Instanz von BmpOptions zu
	#Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Erstelle eine Instanz von Image.
	with Image.create(bmpOptions, 500, 500) as image:
		# Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		# Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat)
		# Erstellen Sie eine Instanz der Klasse GraphicsPath
		graphicspath = GraphicsPath()
		#Erstellen Sie eine Instanz der Klasse Figure
		figure1 = Figure()
		# Fügen Sie dem Figure-Objekt eine Form hinzu
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Erstellen Sie eine Instanz der Klasse Figure
		figure2 = Figure()
		# Fügen Sie dem Figure-Objekt eine Form hinzu
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Fügen Sie das Figure-Objekt zu GraphicsPath hinzu
		graphicspath.add_figures([figure1, figure2])
		# Zeichnen Sie den Pfad mit dem Pen-Objekt in der Farbe Schwarz
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# Alle Änderungen speichern.
		image.save()


```

