---
title: "Classe GraphicsPath"
type: docs
weight: 5040
url: /fr/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient ou définit les limites de l'objet. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Obtient les figures du chemin. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Obtient ou définit une énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment les intérieurs des formes dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) sont remplis. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Ajoute une nouvelle figure. |
| [add_figures(figures)](#add_figures_figures_2) | Ajoute de nouvelles figures. |
| [add_path(adding_path)](#add_path_adding_path_3) | Ajoute le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié à ce chemin. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Ajoute le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié à ce chemin. |
| [deep_clone()](#deep_clone__5) | Effectue un clonage profond de ce chemin graphique. |
| flatten() | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [flatten(matrix)](#flatten_matrix_6) | Applique la transformation spécifiée puis convertit chaque courbe de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en une séquence de segments de ligne connectés. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Convertit chaque courbe de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en une séquence de segments de ligne connectés. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Obtient les limites de l'objet. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié. |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(point)](#is_visible_point_26) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dans la région de découpage visible du [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dans la région de découpage visible du [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_point(point)](#is_visible_point_point_34) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dans la région de découpage visible du [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [remove_figure(figure)](#remove_figure_figure_42) | Supprime une figure. |
| [remove_figures(figures)](#remove_figures_figures_43) | Supprime les figures. |
| reset() | Vide le chemin graphique et définit le [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sur [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Inverse l'ordre des figures, formes et points dans chaque forme de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | Applique la transformation spécifiée à la forme. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | Ajoute un contour supplémentaire au chemin. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Ajoute un contour supplémentaire au [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Remplace ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le stylo spécifié. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Les figures à initialiser. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Les figures à initialiser. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Le mode de remplissage. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Le mode de remplissage. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Ajoute une nouvelle figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | La figure à ajouter. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Ajoute de nouvelles figures.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Les figures à ajouter. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Ajoute le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié à ce chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à ajouter. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Ajoute le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié à ce chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à ajouter. |
| connecter | bool | Une valeur booléenne qui indique si la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur true indique que la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur false indique que la première figure du chemin ajouté est distincte de la dernière figure de ce chemin. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Effectue un clonage profond de ce chemin graphique.

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Une copie profonde du chemin graphique. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Applique la transformation spécifiée puis convertit chaque courbe de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en une séquence de segments de ligne connectés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) permettant de transformer ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) avant l'aplatissement. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Convertit chaque courbe de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en une séquence de segments de ligne connectés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) permettant de transformer ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) avant l'aplatissement. |
| planéité | float | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie. Une valeur de 0,25 est la valeur par défaut. Réduire la valeur de planéité augmentera le nombre de segments de ligne dans l'approximation. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


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


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur (ou sous) du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur (ou sous) du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur (ou sous) du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur (ou sous) du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur (ou sous) du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) qui indique l'emplacement à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Indique si le point spécifié est contenu (ou se trouve sous) le contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) lorsqu'il est dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié et en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le [Pen](/imaging/python-net/aspose.imaging/pen/) à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié se trouve à l'intérieur (ou sous) du contour de ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tel que dessiné avec le [Pen](/imaging/python-net/aspose.imaging/pen/) spécifié ; sinon, false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans cet objet; sinon, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans cet objet; sinon, false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dans la région de découpage visible du [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dans la région de découpage visible du [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans cet objet; sinon, false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), en utilisant le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Indique si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) dans la région de découpage visible du [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Le [Graphics](/imaging/python-net/aspose.imaging/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); sinon, false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Supprime une figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | La figure à supprimer. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Supprime les figures.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Les figures à supprimer. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformation à appliquer. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par _srcRect_ est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle qui est transformé en parallélogramme défini par _destPoints_. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par _srcRect_ est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle qui est transformé en parallélogramme défini par _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par _srcRect_ est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle qui est transformé en parallélogramme défini par _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Une énumération [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par _srcRect_ est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle qui est transformé en parallélogramme défini par _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Une énumération [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |
| flatness | float | Une valeur comprise entre 0 et 1 qui spécifie la planéité du chemin résultant. Pour plus d'informations, consultez les méthodes [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Ajoute un contour supplémentaire au chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Ajoute un contour supplémentaire au [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui spécifie une transformation à appliquer au chemin avant l'élargissement. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Remplace ce [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le stylo spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui spécifie une transformation à appliquer au chemin avant l'élargissement. |
| planéité | float | Une valeur qui spécifie la planéité des courbes. |

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

