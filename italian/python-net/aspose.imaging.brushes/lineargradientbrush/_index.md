---
title: "Classe LinearGradientBrush"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con parametri predefiniti.<br/>            Il colore iniziale è nero, il colore finale è bianco, l'angolo è di 45 gradi e il rettangolo si trova in (0,0) con dimensioni (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| angle | float | r/w | Ottiene o imposta l'angolo del gradiente. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Ottiene o imposta un [Blend](/imaging/python-net/aspose.imaging/blend/) che specifica posizioni e fattori che definiscono un decadimento personalizzato per il gradiente. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore finale del gradiente. |
| gamma_correction | bool | r/w | Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Ottiene o imposta un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) che definisce un gradiente lineare multicolore. |
| is_angle_scalable | bool | r/w | Ottiene o imposta un valore che indica se [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) viene modificato durante le trasformazioni con questo [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta i colori iniziale e finale del gradiente. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta una regione rettangolare che definisce i punti iniziale e finale del gradiente. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore iniziale del gradiente. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta una copia di [Matrix](/imaging/python-net/aspose.imaging/matrix/) che definisce una trasformazione geometrica locale per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Ottiene o imposta un'enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che indica la modalità di avvolgimento per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con i punti e i colori specificati. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con i punti e i colori specificati. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [deep_clone()](#deep_clone__7) | Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato. |
| reset_transform() | Reimposta la proprietà [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a identità. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Crea un decadimento del gradiente basato su una curva a forma di campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Crea un decadimento del gradiente basato su una curva a forma di campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con parametri predefiniti.<br/>            Il colore iniziale è nero, il colore finale è bianco, l'angolo è di 45 gradi e il rettangolo si trova in (0,0) con dimensioni (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il punto1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il punto2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Il punto1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Il punto2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore2. |
| angle | float | L'angolo. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore2. |
| angle | float | L'angolo. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore2. |
| angle | float | L'angolo. |
| is_angle_scalable | bool | se impostato su <c>true</c> [è scalabile l'angolo]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore2. |
| angle | float | L'angolo. |
| is_angle_scalable | bool | se impostato su <c>true</c> [è scalabile l'angolo]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con i punti e i colori specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Una struttura [Point](/imaging/python-net/aspose.imaging/point/) che rappresenta il punto di partenza del gradiente lineare. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Una struttura [Point](/imaging/python-net/aspose.imaging/point/) che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore finale del gradiente lineare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con i punti e i colori specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Una struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto di partenza del gradiente lineare. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Una struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore finale del gradiente lineare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore iniziale del gradiente. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore finale del gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore iniziale del gradiente. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore finale del gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| is_angle_scalable | bool | se impostato su <c>true</c> l'angolo viene modificato durante le trasformazioni con questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore iniziale del gradiente. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore finale del gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore iniziale del gradiente. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Color](/imaging/python-net/aspose.imaging/color/) che rappresenta il colore finale del gradiente. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| is_angle_scalable | bool | se impostato su <c>true</c> l'angolo viene modificato durante le trasformazioni con questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuovo [Brush](/imaging/python-net/aspose.imaging/brush/) che è la copia profonda di questa istanza [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o pre-pendere la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o anteporre la matrice di scaling. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scala | float | Un valore da 0 a 1 che specifica la velocità con cui i colori sfumano dal colore iniziale al _fuoco_ (colore finale) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Crea un decadimento del gradiente basato su una curva a forma di campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il colore iniziale e il colore finale sono mescolati in modo uguale). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea un decadimento del gradiente basato su una curva a forma di campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scala | float | Un valore da 0 a 1 che specifica la velocità con cui i colori sfumano dal _fuoco_. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


```
 translate_transform(dx, dy, order) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

