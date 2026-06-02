---
title: "Pen Classe"
type: docs
weight: 6890
url: /it/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) specificato. |
| [Pen(brush, width)](#Pen_brush_width_2) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) e il [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificati. |
| [Pen(color)](#Pen_color_3) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il colore specificato. |
| [Pen(color, width)](#Pen_color_width_4) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con le proprietà [Pen.color](/imaging/python-net/aspose.imaging/pen/) e [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Ottiene o imposta l'allineamento per questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Ottiene o imposta il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) che determina gli attributi di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | Ottiene o imposta un array di valori che specifica una penna composta. Una penna composta disegna una linea composta da linee parallele e spazi. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Ottiene o imposta un cappuccio personalizzato da utilizzare alla fine delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Ottiene o imposta un cappuccio personalizzato da utilizzare all'inizio delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Ottiene o imposta lo stile del cappuccio usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattini. |
| dash_pattern | float[] | r/w | Ottiene o imposta un array di trattini e spazi personalizzati. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Ottiene o imposta lo stile usato per le linee tratteggiate disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Ottiene o imposta lo stile di estremità usato alla fine delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Ottiene o imposta lo stile di giunzione per le estremità di due linee consecutive disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Ottiene o imposta il limite dello spessore della giunzione su un angolo a spigolo. |
| opacity | float | r/w | Ottiene o imposta l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che l'oggetto è completamente visibile, un valore di 1 indica che l'oggetto è completamente opaco. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Ottiene lo stile delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Ottiene o imposta lo stile di estremità usato all'inizio delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta una copia della trasformazione geometrica per questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | Ottiene o imposta la larghezza di questo [Pen](/imaging/python-net/aspose.imaging/pen/), nelle unità dell'oggetto Graphics usato per il disegno. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) specificato. |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) e il [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificati. |
| [create_with_color(color)](#create_with_color_color_3) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il colore specificato. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con le proprietà [Pen.color](/imaging/python-net/aspose.imaging/pen/) e [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificate. |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Moltiplica la matrice di trasformazione per questo [Pen](/imaging/python-net/aspose.imaging/pen/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Moltiplica la matrice di trasformazione per questo [Pen](/imaging/python-net/aspose.imaging/pen/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata nell'ordine specificato. |
| reset_transform() | Reimposta la matrice di trasformazione geometrica per questo [Pen](/imaging/python-net/aspose.imaging/pen/) all'identità. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Imposta i valori che determinano lo stile di estremità usato per terminare le linee disegnate da questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) che determina le proprietà di riempimento di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) e il [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) che determina le caratteristiche di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | La larghezza del nuovo [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il colore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Pen.color](/imaging/python-net/aspose.imaging/pen/) che indica il colore di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con le proprietà [Pen.color](/imaging/python-net/aspose.imaging/pen/) e [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Pen.color](/imaging/python-net/aspose.imaging/pen/) che indica il colore di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Un valore che indica la larghezza di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) che determina le proprietà di riempimento di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il [Pen.brush](/imaging/python-net/aspose.imaging/pen/) e il [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) che determina le caratteristiche di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | La larghezza del nuovo [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con il colore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Pen.color](/imaging/python-net/aspose.imaging/pen/) che indica il colore di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Inizializza una nuova istanza della classe [Pen](/imaging/python-net/aspose.imaging/pen/) con le proprietà [Pen.color](/imaging/python-net/aspose.imaging/pen/) e [Pen.width](/imaging/python-net/aspose.imaging/pen/) specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una struttura [Pen.color](/imaging/python-net/aspose.imaging/pen/) che indica il colore di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Un valore che indica la larghezza di questo [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Moltiplica la matrice di trasformazione per questo [Pen](/imaging/python-net/aspose.imaging/pen/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | L'oggetto [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la matrice di trasformazione. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Moltiplica la matrice di trasformazione per questo [Pen](/imaging/python-net/aspose.imaging/pen/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la matrice di trasformazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordine in cui eseguire l'operazione di moltiplicazione. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o pre-pendere la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o anteporre la matrice di scaling. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Imposta i valori che determinano lo stile di estremità usato per terminare le linee disegnate da questo [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) che rappresenta lo stile di estremità da usare all'inizio delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) che rappresenta lo stile di estremità da usare alla fine delle linee disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) che rappresenta lo stile di estremità da usare all'inizio o alla fine delle linee tratteggiate disegnate con questo [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Crea un'istanza di BmpOptions e imposta le sue varie proprietà
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Crea un'istanza di FileCreateSource e assegnala come sorgente per l'istanza di BmpOptions
# Il secondo parametro Booleano determina se il file da creare è temporaneo o meno
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Crea un'istanza di Image nel percorso specificato
with Image.create(bmpOptions, 500, 500) as image:
	# Crea un'istanza di Graphics e inizializzala con l'oggetto Image
	graphics = Graphics(image)
	# Cancella la superficie Graphics con colore bianco
	graphics.clear(Color.white)
	#Crea un'istanza di Pen con colore rosso e larghezza 5
	pen = Pen(Color.red, 5.0);
	# Crea un'istanza di HatchBrush e imposta le sue proprietà
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Crea un'istanza di Pen
	# inizializzalo con l'oggetto HatchBrush e la larghezza
	brusedpen = Pen(brush, 5.0)
	# Disegna rettangoli specificando l'oggetto Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Disegna rettangoli specificando l'oggetto Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# salva tutte le modifiche.
	image.save()


```

