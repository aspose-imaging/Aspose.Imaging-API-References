---
title: "Classe Size"
type: docs
weight: 7280
url: /it/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Size()](#Size__1) | Inizializza una nuova istanza della classe Size |
| [Size(point)](#Size_point_2) | Inizializza una nuova istanza della struttura [Size](/imaging/python-net/aspose.imaging/size/) dal [Point](/imaging/python-net/aspose.imaging/point/) specificato. |
| [Size(width, height)](#Size_width_height_3) | Inizializza una nuova istanza della struttura [Size](/imaging/python-net/aspose.imaging/size/) dalle dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | Ottiene una nuova istanza della struttura [Size](/imaging/python-net/aspose.imaging/size/) con i valori [Size.width](/imaging/python-net/aspose.imaging/size/) e [Size.height](/imaging/python-net/aspose.imaging/size/) impostati a zero. |
| height | int | r/w | Ottiene o imposta la componente verticale di questo [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | Ottiene un valore che indica se questo [Size](/imaging/python-net/aspose.imaging/size/) ha larghezza e altezza pari a 0. |
| width | int | r/w | Ottiene o imposta la componente orizzontale di questo [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Aggiunge la larghezza e l'altezza di una struttura [Size](/imaging/python-net/aspose.imaging/size/) alla larghezza e all'altezza di un'altra struttura [Size](/imaging/python-net/aspose.imaging/size/). |
| [ceiling(size)](#ceiling_size_2) | Converte la struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificata in una struttura [Size](/imaging/python-net/aspose.imaging/size/) arrotondando i valori della struttura [Size](/imaging/python-net/aspose.imaging/size/) al prossimo intero più alto. |
| [round(size)](#round_size_3) | Converte la struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificata in una struttura [Size](/imaging/python-net/aspose.imaging/size/) arrotondando i valori della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al valore intero più vicino. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Sottrae la larghezza e l'altezza di una struttura [Size](/imaging/python-net/aspose.imaging/size/) dalla larghezza e dall'altezza di un'altra struttura [Size](/imaging/python-net/aspose.imaging/size/). |
| [truncate(size)](#truncate_size_5) | Converte la struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificata in una struttura [Size](/imaging/python-net/aspose.imaging/size/) troncando i valori della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al prossimo intero più basso. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Inizializza una nuova istanza della classe Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Inizializza una nuova istanza della struttura [Size](/imaging/python-net/aspose.imaging/size/) dal [Point](/imaging/python-net/aspose.imaging/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Il [Point](/imaging/python-net/aspose.imaging/point/) da cui inizializzare questo [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Inizializza una nuova istanza della struttura [Size](/imaging/python-net/aspose.imaging/size/) dalle dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La componente di larghezza del nuovo [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | La componente di altezza del nuovo [Size](/imaging/python-net/aspose.imaging/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Aggiunge la larghezza e l'altezza di una struttura [Size](/imaging/python-net/aspose.imaging/size/) alla larghezza e all'altezza di un'altra struttura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Il primo [Size](/imaging/python-net/aspose.imaging/size/) da aggiungere. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Il secondo [Size](/imaging/python-net/aspose.imaging/size/) da aggiungere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Una struttura [Size](/imaging/python-net/aspose.imaging/size/) che è il risultato dell'operazione di addizione. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Converte la struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificata in una struttura [Size](/imaging/python-net/aspose.imaging/size/) arrotondando i valori della struttura [Size](/imaging/python-net/aspose.imaging/size/) al prossimo intero più alto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La struttura [Size](/imaging/python-net/aspose.imaging/size/) in cui questo metodo converte. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Converte la struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificata in una struttura [Size](/imaging/python-net/aspose.imaging/size/) arrotondando i valori della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al valore intero più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La struttura [Size](/imaging/python-net/aspose.imaging/size/) in cui questo metodo converte. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Sottrae la larghezza e l'altezza di una struttura [Size](/imaging/python-net/aspose.imaging/size/) dalla larghezza e dall'altezza di un'altra struttura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | La struttura [Size](/imaging/python-net/aspose.imaging/size/) sul lato sinistro dell'operatore di sottrazione. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | La struttura [Size](/imaging/python-net/aspose.imaging/size/) sul lato destro dell'operatore di sottrazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La [Size](/imaging/python-net/aspose.imaging/size/) che è il risultato dell'operazione di sottrazione. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Converte la struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) specificata in una struttura [Size](/imaging/python-net/aspose.imaging/size/) troncando i valori della struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al prossimo intero più basso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La struttura [SizeF](/imaging/python-net/aspose.imaging/sizef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La struttura [Size](/imaging/python-net/aspose.imaging/size/) in cui questo metodo converte. |


