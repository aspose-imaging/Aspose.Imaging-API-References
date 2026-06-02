---
title: "Classe SizeF"
type: docs
weight: 7290
url: /it/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [SizeF()](#SizeF__1) | Inizializza una nuova istanza della classe SizeF |
| [SizeF(point)](#SizeF_point_2) | Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato. |
| [SizeF(size)](#SizeF_size_3) | Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificato. |
| [SizeF(width, height)](#SizeF_width_height_4) | Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dalle dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Ottiene una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) con i valori [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) e [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) impostati a zero. |
| height | float | r/w | Ottiene o imposta la componente verticale di questo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Ottiene un valore che indica se questo [SizeF](/imaging/python-net/aspose.imaging/sizef/) ha larghezza e altezza pari a zero. |
| width | float | r/w | Ottiene o imposta la componente orizzontale di questo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Aggiunge la larghezza e l'altezza di una struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) alla larghezza e all'altezza di un'altra struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato. |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificato. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Sottrae la larghezza e l'altezza di una struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) dalla larghezza e dall'altezza di un'altra struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [to_point_f()](#to_point_f__5) | Converte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) in un [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Converte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) in una struttura [Size](/imaging/python-net/aspose.imaging/size/) con valori di dimensione troncati. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Inizializza una nuova istanza della classe SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da cui inizializzare questo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Il [SizeF](/imaging/python-net/aspose.imaging/sizef/) da cui creare il nuovo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dalle dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | float | La componente di larghezza del nuovo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | La componente di altezza del nuovo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Aggiunge la larghezza e l'altezza di una struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) alla larghezza e all'altezza di un'altra struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Il primo [SizeF](/imaging/python-net/aspose.imaging/sizef/) da aggiungere. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Il secondo [SizeF](/imaging/python-net/aspose.imaging/sizef/) da aggiungere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Una struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) che è il risultato dell'operazione di aggiunta. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [PointF](/imaging/python-net/aspose.imaging/pointf/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il [PointF](/imaging/python-net/aspose.imaging/pointf/) da cui inizializzare questo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Inizializza una nuova istanza della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partire dal [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Il [SizeF](/imaging/python-net/aspose.imaging/sizef/) da cui creare il nuovo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Sottrae la larghezza e l'altezza di una struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) dalla larghezza e dall'altezza di un'altra struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) sul lato sinistro dell'operatore di sottrazione. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) sul lato destro dell'operatore di sottrazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Il [SizeF](/imaging/python-net/aspose.imaging/sizef/) che è il risultato dell'operazione di sottrazione. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Converte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) in un [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Restituisce una struttura [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Converte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) in una struttura [Size](/imaging/python-net/aspose.imaging/size/) con valori di dimensione troncati.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Restituisce una struttura [Size](/imaging/python-net/aspose.imaging/size/). |


