---
title: "Classe Rectangle"
type: docs
weight: 7120
url: /it/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Inizializza una nuova istanza della classe Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Inizializza una nuova istanza della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la posizione e la dimensione specificate. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Inizializza una nuova istanza della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la posizione e la dimensione specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bottom | int | r/w | Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) e [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ottiene una nuova istanza della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con i valori [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) e [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) impostati a zero. |
| height | int | r/w | Ottiene o imposta l'altezza di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| is_empty | bool | r | Ottiene un valore che indica se tutte le proprietà numeriche di questa [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) hanno valore zero. |
| left | int | r/w | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | r/w | Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) e [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Ottiene o imposta la dimensione di questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Ottiene o imposta la coordinata y del bordo superiore di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| width | int | r/w | Ottiene o imposta la larghezza di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| x | int | r/w | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | r/w | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Converte la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata in una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) arrotondando i valori di [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al prossimo intero superiore. |
| [contains(point)](#contains_point_2) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(rect)](#contains_rect_3) | Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_point(point)](#contains_point_point_5) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_rect(rect)](#contains_rect_rect_6) | Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Crea una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con le posizioni dei bordi specificate. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Crea un nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a partire da due punti specificati. Due verticali del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creato saranno uguali ai punti _point1_ e _point2_ passati. Questi sono tipicamente i vertici opposti. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Crea e restituisce una copia ingrandita della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificata. La copia è ingrandita dell'importo specificato. La struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale rimane invariata. |
| [inflate(size)](#inflate_size_10) | Ingrandisce questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dell'importo specificato. |
| [inflate(width, height)](#inflate_width_height_11) | Ingrandisce questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dell'importo specificato. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Crea e restituisce una copia ingrandita della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificata. La copia è ingrandita dell'importo specificato. La struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale rimane invariata. |
| [intersect(a, b)](#intersect_a_b_13) | Restituisce una terza struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta l'intersezione di due altre strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Se non esiste alcuna intersezione, viene restituito un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vuoto. |
| [intersect(rect)](#intersect_rect_14) | Sostituisce questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con l'intersezione di sé stesso e del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificato. |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Restituisce una terza struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta l'intersezione di due altre strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Se non esiste alcuna intersezione, viene restituito un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vuoto. |
| [intersects_with(rect)](#intersects_with_rect_16) | Determina se questo rettangolo interseca _rect_. |
| normalize() | Normalizza il rettangolo rendendo la larghezza e l'altezza positive, sinistra minore di destra e superiore minore di inferiore. |
| [offset(pos)](#offset_pos_17) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(x, y)](#offset_x_y_18) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [round(value)](#round_value_19) | Converte il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato in un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) arrotondando i valori di [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al valore intero più vicino. |
| [truncate(value)](#truncate_value_20) | Converte il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato in un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) troncando i valori di [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(a, b)](#union_a_b_21) | Ottiene una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che contiene l'unione di due strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Inizializza una nuova istanza della classe Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Inizializza una nuova istanza della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la posizione e la dimensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) che rappresenta l'angolo in alto a sinistra della regione rettangolare. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Una [Size](/imaging/python-net/aspose.imaging/size/) che rappresenta la larghezza e l'altezza della regione rettangolare. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Inizializza una nuova istanza della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la posizione e la dimensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | int | La larghezza del rettangolo. |
| height | int | L'altezza del rettangolo. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Converte la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata in una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) arrotondando i valori di [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al prossimo intero superiore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Restituisce un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto rappresentato da _point_ è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); altrimenti false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); altrimenti false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto definito da _x_ e _y_ è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); altrimenti false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto rappresentato da _point_ è contenuto all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); altrimenti false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); altrimenti false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con le posizioni dei bordi specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left | int | La coordinata x dell'angolo in alto a sinistra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | La coordinata y dell'angolo in alto a sinistra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | La coordinata x dell'angolo in basso a destra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| bottom | int | La coordinata y dell'angolo in basso a destra di questa struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che questo metodo crea. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Crea un nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a partire da due punti specificati. Due verticali del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creato saranno uguali ai punti _point1_ e _point2_ passati. Questi sono tipicamente i vertici opposti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Il primo [Point](/imaging/python-net/aspose.imaging/point/) per il nuovo rettangolo. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Il secondo [Point](/imaging/python-net/aspose.imaging/point/) per il nuovo rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) appena creato. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Crea e restituisce una copia ingrandita della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificata. La copia è ingrandita dell'importo specificato. La struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale rimane invariata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con cui iniziare. Questo rettangolo non viene modificato. |
| x | int | La quantità con cui gonfiare orizzontalmente questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | La quantità con cui gonfiare verticalmente questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) gonfiato. |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Ingrandisce questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La quantità con cui gonfiare questo rettangolo. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Ingrandisce questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La quantità con cui gonfiare orizzontalmente questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| height | int | La quantità con cui gonfiare verticalmente questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Crea e restituisce una copia ingrandita della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificata. La copia è ingrandita dell'importo specificato. La struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale rimane invariata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con cui iniziare. Questo rettangolo non viene modificato. |
| x | int | La quantità con cui gonfiare orizzontalmente questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | La quantità con cui gonfiare verticalmente questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) gonfiato. |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Restituisce una terza struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta l'intersezione di due altre strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Se non esiste alcuna intersezione, viene restituito un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vuoto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un primo rettangolo da intersecare. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un secondo rettangolo da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta l'intersezione di _a_ e _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Sostituisce questo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con l'intersezione di sé stesso e del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con cui intersecare. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Restituisce una terza struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta l'intersezione di due altre strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Se non esiste alcuna intersezione, viene restituito un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vuoto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un primo rettangolo da intersecare. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un secondo rettangolo da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta l'intersezione di _a_ e _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Determina se questo rettangolo interseca _rect_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se esiste qualche intersezione, altrimenti false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Quantità per spostare la posizione. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | Lo spostamento orizzontale. |
| y | int | Lo spostamento verticale. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Converte il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato in un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) arrotondando i valori di [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al valore intero più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Converte il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato in un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) troncando i valori di [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Ottiene una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che contiene l'unione di due strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un primo rettangolo da unire. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un secondo rettangolo da unire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che delimita l'unione delle due strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


