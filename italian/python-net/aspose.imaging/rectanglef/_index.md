---
title: "Classe RectangleF"
type: docs
weight: 7130
url: /it/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Inizializza una nuova istanza della classe RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Inizializza una nuova istanza della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la posizione e le dimensioni specificate. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Inizializza una nuova istanza della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la posizione e le dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bottom | float | r/w | Ottiene o imposta la coordinata y che è la somma di [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) e [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene una nuova istanza della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che ha i valori [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) e [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) impostati a zero. |
| height | float | r/w | Ottiene o imposta l'altezza di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| is_empty | bool | r | Ottiene un valore che indica se la proprietà [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) o [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) ha valore zero. |
| left | float | r/w | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| right | float | r/w | Ottiene o imposta la coordinata x che è la somma di [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) e [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Ottiene o imposta le dimensioni di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Ottiene o imposta la coordinata y del bordo superiore di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| width | float | r/w | Ottiene o imposta la larghezza di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| x | float | r/w | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | r/w | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [contains(point)](#contains_point_1) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_point_f(point)](#contains_point_f_point_4) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Crea una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Crea un nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) da due punti specificati. I due vertici del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creato saranno uguali ai valori _point1_ e _point2_ passati. Questi sono tipicamente i vertici opposti. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Crea e restituisce una copia ingrandita del [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato. |
| [inflate(size)](#inflate_size_9) | Ingrandisce questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) dell'importo specificato. |
| [inflate(x, y)](#inflate_x_y_10) | Ingrandisce la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di un valore specificato. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Crea e restituisce una copia ingrandita del [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato. |
| [intersect(a, b)](#intersect_a_b_12) | Restituisce un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta l'intersezione di due rettangoli. Se non vi è alcuna intersezione, viene restituito un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vuoto. |
| [intersect(rect)](#intersect_rect_13) | Sostituisce questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con l'intersezione di sé stesso e del [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Restituisce un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta l'intersezione di due rettangoli. Se non vi è alcuna intersezione, viene restituito un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vuoto. |
| [intersects_with(rect)](#intersects_with_rect_15) | Determina se questo rettangolo interseca _rect_. |
| normalize() | Normalizza il rettangolo rendendo la larghezza e l'altezza positive, sinistra minore di destra e superiore minore di inferiore. |
| [offset(pos)](#offset_pos_16) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(x, y)](#offset_x_y_17) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [union(a, b)](#union_a_b_18) | Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Inizializza una nuova istanza della classe RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Inizializza una nuova istanza della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la posizione e le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Un [SizeF](/imaging/python-net/aspose.imaging/sizef/) che rappresenta la larghezza e l'altezza della regione rettangolare. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Inizializza una nuova istanza della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la posizione e le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | float | La larghezza del rettangolo. |
| height | float | L'altezza del rettangolo. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto rappresentato dal parametro _point_ è contenuto all'interno di questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); altrimenti false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno della regione rettangolare rappresentata da questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); altrimenti false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto definito da _x_ e _y_ è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); altrimenti false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto rappresentato dal parametro _point_ è contenuto all'interno di questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); altrimenti false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Determina se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno di questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se la regione rettangolare rappresentata da _rect_ è interamente contenuta all'interno della regione rettangolare rappresentata da questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); altrimenti false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sinistra | float | La coordinata x dell'angolo in alto a sinistra della regione rettangolare. |
| alto | float | La coordinata y dell'angolo in alto a sinistra della regione rettangolare. |
| destra | float | La coordinata x dell'angolo in basso a destra della regione rettangolare. |
| basso | float | La coordinata y dell'angolo in basso a destra della regione rettangolare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il nuovo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che questo metodo crea. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Crea un nuovo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) da due punti specificati. I due vertici del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creato saranno uguali ai valori _point1_ e _point2_ passati. Questi sono tipicamente i vertici opposti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il primo [Point](/imaging/python-net/aspose.imaging/point/) per il nuovo rettangolo. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il secondo [Point](/imaging/python-net/aspose.imaging/point/) per il nuovo rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) appena creato. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Crea e restituisce una copia ingrandita del [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da copiare. Questo rettangolo non viene modificato. |
| x | float | La quantità con cui gonfiare orizzontalmente la copia del rettangolo. |
| y | float | La quantità con cui gonfiare verticalmente la copia del rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) gonfiato. |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Ingrandisce questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La quantità con cui gonfiare questo rettangolo. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Ingrandisce la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di un valore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La quantità con cui gonfiare orizzontalmente questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | La quantità con cui gonfiare verticalmente questa struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Crea e restituisce una copia ingrandita del [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da copiare. Questo rettangolo non viene modificato. |
| x | float | La quantità con cui gonfiare orizzontalmente la copia del rettangolo. |
| y | float | La quantità con cui gonfiare verticalmente la copia del rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) gonfiato. |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Restituisce un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta l'intersezione di due rettangoli. Se non vi è alcuna intersezione, viene restituito un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vuoto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un primo rettangolo da intersecare. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un secondo rettangolo da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una terza struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) la cui dimensione rappresenta l'area sovrapposta dei due rettangoli specificati. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Sostituisce questo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con l'intersezione di sé stesso e del [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo da intersecare. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Restituisce un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta l'intersezione di due rettangoli. Se non vi è alcuna intersezione, viene restituito un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vuoto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un primo rettangolo da intersecare. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un secondo rettangolo da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una terza struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) la cui dimensione rappresenta l'area sovrapposta dei due rettangoli specificati. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Determina se questo rettangolo interseca _rect_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se esiste qualche intersezione. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La quantità di spostamento della posizione. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La quantità di spostamento della posizione orizzontalmente. |
| y | float | La quantità di spostamento della posizione verticalmente. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un primo rettangolo da unire. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un secondo rettangolo da unire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una terza struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che contiene entrambi i due rettangoli che formano l'unione. |


