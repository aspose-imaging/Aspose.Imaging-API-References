---
title: "Classe PathGradientBrush"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Inizializza una nuova istanza della classe PathGradientBrush |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_2) | Inizializza una nuova istanza della classe PathGradientBrush |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_3) | Inizializza una nuova istanza della classe PathGradientBrush |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_4) | Inizializza una nuova istanza della classe PathGradientBrush |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_5) | Inizializza una nuova istanza della classe PathGradientBrush |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Ottiene o imposta un [Blend](/imaging/python-net/aspose.imaging/blend/) che specifica posizioni e fattori che definiscono un decadimento personalizzato per il gradiente. |
| center_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore al centro del gradiente del percorso. |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta il punto centrale del gradiente del percorso. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta il punto focale per la caduta del gradiente. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Ottiene il percorso grafico su cui è stato costruito questo pennello. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Ottiene o imposta un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) che definisce un gradiente lineare multicolore. |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
| surround_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un array di colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) riempie. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta una copia di [Matrix](/imaging/python-net/aspose.imaging/matrix/) che definisce una trasformazione geometrica locale per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Ottiene o imposta un'enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che indica la modalità di avvolgimento per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con il percorso specificato. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento. |
| [deep_clone()](#deep_clone__6) | Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato. |
| reset_transform() | Reimposta la proprietà [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a identità. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_13) | Crea un gradiente con un colore centrale e una sfumatura lineare verso un colore circostante. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_14) | Crea un gradiente con un colore centrale e una sfumatura lineare verso ciascun colore circostante. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_15) | Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_16) | Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_17) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_18) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Inizializza una nuova istanza della classe PathGradientBrush

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_2}


```
 PathGradientBrush(path_points) 
```

Inizializza una nuova istanza della classe PathGradientBrush

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_3}


```
 PathGradientBrush(path_points) 
```

Inizializza una nuova istanza della classe PathGradientBrush

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_4}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Inizializza una nuova istanza della classe PathGradientBrush

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_5}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Inizializza una nuova istanza della classe PathGradientBrush

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con il percorso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce l'area riempita da questo [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta i punti che costituiscono i vertici del percorso. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta i punti che costituiscono i vertici del percorso. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta i punti che costituiscono i vertici del percorso. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come i riempimenti disegnati con questo [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) vengono affiancati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che rappresenta i punti che costituiscono i vertici del percorso. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come i riempimenti disegnati con questo [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) vengono affiancati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuovo [Brush](/imaging/python-net/aspose.imaging/brush/) che è la copia profonda di questa istanza [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o pre-pendere la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_13}


```
 set_blend_triangular_shape(focus) 
```

Crea un gradiente con un colore centrale e una sfumatura lineare verso un colore circostante.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_14}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea un gradiente con un colore centrale e una sfumatura lineare verso ciascun colore circostante.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |
| scala | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore del bordo. Un valore di 1 provoca l'intensità più alta possibile del colore centrale, ed è il valore predefinito. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_15}


```
 set_sigma_bell_shape(focus) 
```

Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_16}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fuoco | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |
| scala | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore del bordo. Un valore di 1 provoca l'intensità più alta possibile del colore centrale, ed è il valore predefinito. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_17}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_18}


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

