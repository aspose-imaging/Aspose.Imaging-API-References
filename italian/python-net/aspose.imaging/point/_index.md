---
title: "Classe Point"
type: docs
weight: 6960
url: /it/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Point()](#Point__1) | Inizializza una nuova istanza della classe Point |
| [Point(dw)](#Point_dw_2) | Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) utilizzando coordinate specificate da un valore intero. |
| [Point(size)](#Point_size_3) | Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) dalla struttura [Size](/imaging/python-net/aspose.imaging/size/). |
| [Point(x, y)](#Point_x_y_4) | Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) con le coordinate specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Ottiene una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) che ha i valori [Point.x](/imaging/python-net/aspose.imaging/point/) e [Point.y](/imaging/python-net/aspose.imaging/point/) impostati a zero. |
| is_empty | bool | r | Ottiene un valore che indica se questo [Point](/imaging/python-net/aspose.imaging/point/) è vuoto. |
| x | int | r/w | Ottiene o imposta la coordinata x di questo [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Ottiene o imposta la coordinata y di questo [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Aggiunge il [Size](/imaging/python-net/aspose.imaging/size/) specificato al [Point](/imaging/python-net/aspose.imaging/point/) specificato. |
| [ceiling(point)](#ceiling_point_2) | Converte il [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato in un [Point](/imaging/python-net/aspose.imaging/point/) arrotondando i valori del [PointF](/imaging/python-net/aspose.imaging/pointf/) al prossimo valore intero più alto. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) utilizzando coordinate specificate da un valore intero. |
| [create_from_size(size)](#create_from_size_size_4) | Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) dalla struttura [Size](/imaging/python-net/aspose.imaging/size/). |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Decompone un oggetto Point inserito in un oggetto long per separare i valori interi X e Y. |
| [offset(dx, dy)](#offset_dx_dy_6) | Trasla questo [Point](/imaging/python-net/aspose.imaging/point/) dell'importo specificato. |
| [offset(point)](#offset_point_7) | Trasla questo [Point](/imaging/python-net/aspose.imaging/point/) del [Point](/imaging/python-net/aspose.imaging/point/) specificato. |
| [round(point)](#round_point_8) | Converte il [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato in un oggetto [Point](/imaging/python-net/aspose.imaging/point/) arrotondando i valori del [Point](/imaging/python-net/aspose.imaging/point/) all'intero più vicino. |
| [subtract(point, size)](#subtract_point_size_9) | Restituisce il risultato della sottrazione del [Size](/imaging/python-net/aspose.imaging/size/) specificato dal [Point](/imaging/python-net/aspose.imaging/point/) specificato. |
| [to_long()](#to_long__10) | Converti questo Point in un unico valore long, contenente le coordinate X e Y nei bit più alti e più bassi. |
| [truncate(point)](#truncate_point_11) | Converte il [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato in un [Point](/imaging/python-net/aspose.imaging/point/) troncando i valori del [Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Inizializza una nuova istanza della classe Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) utilizzando coordinate specificate da un valore intero.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dw | int | Un intero a 32 bit che specifica le coordinate per il nuovo punto. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) dalla struttura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contiene le coordinate del nuovo punto. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) con le coordinate specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La posizione orizzontale del punto. |
| y | int | La posizione verticale del punto. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Aggiunge il [Size](/imaging/python-net/aspose.imaging/size/) specificato al [Point](/imaging/python-net/aspose.imaging/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) a cui aggiungere. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Il [Size](/imaging/python-net/aspose.imaging/size/) da aggiungere al _punto_. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) che è il risultato dell'operazione di addizione. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Converte il [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato in un [Point](/imaging/python-net/aspose.imaging/point/) arrotondando i valori del [PointF](/imaging/python-net/aspose.imaging/pointf/) al prossimo valore intero più alto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) a cui questo metodo converte. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) utilizzando coordinate specificate da un valore intero.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dw | int | Un intero a 32 bit che specifica le coordinate per il nuovo punto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Inizializza una nuova istanza della struttura [Point](/imaging/python-net/aspose.imaging/point/) dalla struttura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contiene le coordinate del nuovo punto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Decompone un oggetto Point inserito in un oggetto long per separare i valori interi X e Y.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| packed_point | int | L'oggetto Point impacchettato in un valore long. |
| x | int[] | Il valore X estratto dal Point impacchettato. |
| y | int[] | Il valore Y estratto dal Point impacchettato. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Trasla questo [Point](/imaging/python-net/aspose.imaging/point/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | int | La quantità da offsettare la coordinata x. |
| dy | int | La quantità da offsettare la coordinata y. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Trasla questo [Point](/imaging/python-net/aspose.imaging/point/) del [Point](/imaging/python-net/aspose.imaging/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) usato per offsettare questo [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Converte il [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato in un oggetto [Point](/imaging/python-net/aspose.imaging/point/) arrotondando i valori del [Point](/imaging/python-net/aspose.imaging/point/) all'intero più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) a cui questo metodo converte. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Restituisce il risultato della sottrazione del [Size](/imaging/python-net/aspose.imaging/size/) specificato dal [Point](/imaging/python-net/aspose.imaging/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) da cui sottrarre. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Il [Size](/imaging/python-net/aspose.imaging/size/) da sottrarre dal _point_. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) che è il risultato dell'operazione di sottrazione. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Converti questo Point in un unico valore long, contenente le coordinate X e Y nei bit più alti e più bassi.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'oggetto Point impacchettato in un valore long. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Converte il [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato in un [Point](/imaging/python-net/aspose.imaging/point/) troncando i valori del [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) a cui questo metodo converte. |


