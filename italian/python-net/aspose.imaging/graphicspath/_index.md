---
title: "Classe GraphicsPath"
type: docs
weight: 5040
url: /it/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene o imposta i limiti dell'oggetto. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Ottiene le figure del percorso. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Ottiene o imposta un'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come vengono riempiti gli interni delle forme in questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Aggiunge una nuova figura. |
| [add_figures(figures)](#add_figures_figures_2) | Aggiunge nuove figure. |
| [add_path(adding_path)](#add_path_adding_path_3) | Aggiunge alla fine il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato a questo percorso. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Aggiunge alla fine il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato a questo percorso. |
| [deep_clone()](#deep_clone__5) | Esegue una clonazione profonda di questo percorso grafico. |
| flatten() | Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati. |
| [flatten(matrix)](#flatten_matrix_6) | Applica la trasformazione specificata e poi converte ogni curva in questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in una sequenza di segmenti di linea collegati. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Converte ogni curva in questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in una sequenza di segmenti di linea collegati. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Ottiene i limiti dell'oggetto. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata. |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_visible(point)](#is_visible_point_26) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nella regione di ritaglio visibile della [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nella regione di ritaglio visibile della [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_visible_point(point)](#is_visible_point_point_34) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nella regione di ritaglio visibile della [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata. |
| [remove_figure(figure)](#remove_figure_figure_42) | Rimuove una figura. |
| [remove_figures(figures)](#remove_figures_figures_43) | Rimuove le figure. |
| reset() | Svuota il percorso grafico e imposta il [FillMode](/imaging/python-net/aspose.imaging/fillmode/) su [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Inverte l'ordine delle figure, delle forme e dei punti in ogni forma di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | Applica la trasformazione specificata alla forma. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | Aggiunge un contorno aggiuntivo al percorso. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Aggiunge un contorno aggiuntivo al [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Sostituisce questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) con curve che racchiudono l'area riempita quando questo percorso è disegnato con la penna specificata. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Le figure da cui inizializzare. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Le figure da cui inizializzare. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | La modalità di riempimento. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Inizializza una nuova istanza della classe [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | La modalità di riempimento. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Aggiunge una nuova figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | La figura da aggiungere. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Aggiunge nuove figure.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Le figure da aggiungere. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Aggiunge alla fine il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato a questo percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da aggiungere. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Aggiunge alla fine il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato a questo percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da aggiungere. |
| connetti | bool | Un valore booleano che specifica se la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore true specifica che la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore false specifica che la prima figura nel percorso aggiunto è separata dall'ultima figura in questo percorso. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Esegue una clonazione profonda di questo percorso grafico.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Una copia profonda del percorso grafico. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Applica la trasformazione specificata e poi converte ogni curva in questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in una sequenza di segmenti di linea collegati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui trasformare questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) prima di appiattire. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Converte ogni curva in questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in una sequenza di segmenti di linea collegati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui trasformare questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) prima di appiattire. |
| planarità | float | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita. Un valore di 0.25 è quello predefinito. Ridurre il valore di planarità aumenterà il numero di segmenti lineari nell'approssimazione. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | I limiti stimati dell'oggetto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna da usare per l'oggetto. Questo può influenzare la dimensione dei limiti dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | I limiti stimati dell'oggetto. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) che specifica la posizione da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) quando disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/) specificata e utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La [Pen](/imaging/python-net/aspose.imaging/pen/) da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) così disegnato con la [Pen](/imaging/python-net/aspose.imaging/pen/); altrimenti, false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nella regione di ritaglio visibile della [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nella regione di ritaglio visibile della [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) che rappresenta il punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), utilizzando la [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nella regione di ritaglio visibile della [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Il [Graphics](/imaging/python-net/aspose.imaging/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); altrimenti, false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Rimuove una figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | La figura da rimuovere. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Rimuove le figure.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Le figure da rimuovere. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La trasformazione da applicare. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono un parallelogramma al quale viene trasformato il rettangolo definito da _srcRect_. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da _destPoints_. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono un parallelogramma al quale viene trasformato il rettangolo definito da _srcRect_. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) che specifica una trasformazione geometrica da applicare al percorso. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono un parallelogramma al quale viene trasformato il rettangolo definito da _srcRect_. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) che specifica una trasformazione geometrica da applicare al percorso. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Una enumerazione [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono un parallelogramma al quale viene trasformato il rettangolo definito da _srcRect_. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) che specifica una trasformazione geometrica da applicare al percorso. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Una enumerazione [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |
| flatness | float | Un valore da 0 a 1 che specifica quanto è piatta la traiettoria risultante. Per maggiori informazioni, vedere i metodi [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Aggiunge un contorno aggiuntivo al percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Pen](/imaging/python-net/aspose.imaging/pen/) che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Aggiunge un contorno aggiuntivo al [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Pen](/imaging/python-net/aspose.imaging/pen/) che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) che specifica una trasformazione da applicare al percorso prima dell'allargamento. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Sostituisce questo [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) con curve che racchiudono l'area riempita quando questo percorso è disegnato con la penna specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Pen](/imaging/python-net/aspose.imaging/pen/) che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una [Matrix](/imaging/python-net/aspose.imaging/matrix/) che specifica una trasformazione da applicare al percorso prima dell'allargamento. |
| planarità | float | Un valore che specifica la piattezza per le curve. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Crea un'istanza di un flusso di file
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Crea un'istanza di TiffOptions e imposta le sue varie proprietà
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Imposta la sorgente per l'istanza di ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Crea un'istanza di Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		# Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		# Crea un'istanza della classe GraphicsPath
		graphics_path = GraphicsPath()
		# Crea un'istanza della classe Figure
		figure = Figure()
		# Aggiungi forme all'oggetto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Aggiungi l'oggetto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Disegna il percorso con l'oggetto Pen di colore Nero
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# salva tutte le modifiche.
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

#Crea un'istanza di BmpOptions e imposta le sue varie proprietà
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Crea un'istanza di FileCreateSource e assegnala come sorgente per l'istanza di BmpOptions
	#Il secondo parametro Booleano determina se il file da creare è temporaneo o meno
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Crea un'istanza di Image 
	with Image.create(bmpOptions, 500, 500) as image:
		# Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		# Cancella la superficie Graphics
		graphics.clear(Color.wheat)
		# Crea un'istanza della classe GraphicsPath
		graphicspath = GraphicsPath()
		#Crea un'istanza della classe Figure
		figure1 = Figure()
		# Aggiungi forma all'oggetto Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Crea un'istanza della classe Figure
		figure2 = Figure()
		# Aggiungi forma all'oggetto Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Aggiungi l'oggetto Figure a GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Disegna il percorso con l'oggetto Pen di colore Nero
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# salva tutte le modifiche.
		image.save()


```

