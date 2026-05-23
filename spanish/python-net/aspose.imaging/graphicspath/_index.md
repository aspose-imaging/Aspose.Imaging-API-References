---
title: "Clase GraphicsPath"
type: docs
weight: 5040
url: /es/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene o establece los límites del objeto. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Obtiene las figuras de la ruta. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Obtiene o establece una enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellenan los interiores de las formas en este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Agrega una nueva figura. |
| [add_figures(figures)](#add_figures_figures_2) | Agrega nuevas figuras. |
| [add_path(adding_path)](#add_path_adding_path_3) | Añade el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado a esta ruta. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Añade el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado a esta ruta. |
| [deep_clone()](#deep_clone__5) | Realiza una clonación profunda de esta ruta gráfica. |
| flatten() | Convierte cada curva en esta ruta en una secuencia de segmentos de línea conectados. |
| [flatten(matrix)](#flatten_matrix_6) | Aplica la transformación especificada y luego convierte cada curva en este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en una secuencia de segmentos de línea conectados. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Convierte cada curva en este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en una secuencia de segmentos de línea conectados. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Obtiene los límites del objeto. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada. |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(point)](#is_visible_point_26) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en la región de recorte visible del [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en la región de recorte visible del [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_point(point)](#is_visible_point_point_34) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en la región de recorte visible del [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [remove_figure(figure)](#remove_figure_figure_42) | Elimina una figura. |
| [remove_figures(figures)](#remove_figures_figures_43) | Elimina figuras. |
| reset() | Vacía la ruta gráfica y establece el [FillMode](/imaging/python-net/aspose.imaging/fillmode/) a [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Invierte el orden de figuras, formas y puntos en cada forma de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | Aplica la transformación especificada a la forma. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | Agrega un contorno adicional a la ruta. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Agrega un contorno adicional al [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Reemplaza este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) con curvas que encierran el área que se rellena cuando esta ruta se dibuja con la pluma especificada. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Las figuras desde las que inicializar. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Las figuras desde las que inicializar. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | El modo de relleno. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | El modo de relleno. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Agrega una nueva figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | La figura a agregar. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Agrega nuevas figuras.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Las figuras a agregar. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Añade el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado a esta ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) a agregar. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Añade el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado a esta ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) a agregar. |
| conectar | bool | Un valor booleano que especifica si la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor true especifica que la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor false especifica que la primera figura en la ruta añadida está separada de la última figura en esta ruta. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Realiza una clonación profunda de esta ruta gráfica.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Una clonación profunda de la ruta gráfica. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Aplica la transformación especificada y luego convierte cada curva en este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en una secuencia de segmentos de línea conectados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) mediante la cual transformar este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) antes de aplanar. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Convierte cada curva en este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en una secuencia de segmentos de línea conectados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) mediante la cual transformar este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) antes de aplanar. |
| planitud | float | Especifica el error máximo permitido entre la curva y su aproximación aplanada. Un valor de 0.25 es el predeterminado. Reducir el valor de planitud aumentará el número de segmentos de línea en la aproximación. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz a aplicar antes de que se calculen los límites. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Los límites estimados del objeto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Los límites estimados del objeto. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) que especifica la ubicación a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) cuando se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/) especificada y usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) tal como se dibuja con la [Pen](/imaging/python-net/aspose.imaging/pen/); de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este; de lo contrario, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este; de lo contrario, false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en la región de recorte visible del [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en la región de recorte visible del [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este; de lo contrario, false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) que representa el punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en la región de recorte visible del [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | El [Graphics](/imaging/python-net/aspose.imaging/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); de lo contrario, false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Elimina una figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | La figura a eliminar. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Elimina figuras.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Las figuras a eliminar. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformación a aplicar. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por _srcRect_. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por _destPoints_. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por _srcRect_. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) que especifica una transformación geométrica para aplicar a la ruta. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que define un paralelogramo al que se transforma el rectángulo definido por _srcRect_. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) que especifica una transformación geométrica para aplicar a la ruta. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Una enumeración [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) que especifica si esta operación de deformación usa modo perspectiva o bilineal. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por _srcRect_. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) que especifica una transformación geométrica para aplicar a la ruta. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Una enumeración [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) que especifica si esta operación de deformación usa modo perspectiva o bilineal. |
| flatness | float | Un valor de 0 a 1 que especifica cuán plana es la ruta resultante. Para más información, consulte los métodos [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Agrega un contorno adicional a la ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Agrega un contorno adicional al [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) que especifica una transformación para aplicar a la ruta antes de ensancharla. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Reemplaza este [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) con curvas que encierran el área que se rellena cuando esta ruta se dibuja con la pluma especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) que especifica una transformación para aplicar a la ruta antes de ensancharla. |
| planitud | float | Un valor que especifica la planitud para curvas. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Crea una instancia de un flujo de archivo
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Cree una instancia de TiffOptions y establezca sus diversas propiedades
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Establezca la fuente para la instancia de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Cree una instancia de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		# Limpia la superficie Graphics
		graphics.clear(Color.wheat);
		# Cree una instancia de la clase GraphicsPath
		graphics_path = GraphicsPath()
		# Cree una instancia de la clase Figure
		figure = Figure()
		# Agregue Shapes al objeto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Agregue el objeto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Dibuje la ruta con el objeto Pen de color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# guarde todos los cambios.
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

#Crea una instancia de BmpOptions y establezca sus diversas propiedades            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Cree una instancia de FileCreateSource y asígnela como Source para la instancia de BmpOptions
	#El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Crea una instancia de Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		# Limpia la superficie Graphics
		graphics.clear(Color.wheat)
		# Cree una instancia de la clase GraphicsPath
		graphicspath = GraphicsPath()
		#Cree una instancia de la clase Figure
		figure1 = Figure()
		# Agregue Shape al objeto Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Cree una instancia de la clase Figure
		figure2 = Figure()
		# Agregue Shape al objeto Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Agregue el objeto Figure a GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Dibuje la ruta con el objeto Pen de color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# guarde todos los cambios.
		image.save()


```

