---
title: "SizeF-klass"
type: docs
weight: 7290
url: /sv/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initierar en ny instans av SizeF-klassen |
| [SizeF(point)](#SizeF_point_2) | Initierar en ny instans av [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen från den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initierar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) från den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initierar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) från de angivna dimensionerna. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Hämtar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) som har värdena [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) och [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) satta till noll. |
| height | float | r/w | Hämtar eller anger den vertikala komponenten för denna [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Hämtar ett värde som indikerar om denna [SizeF](/imaging/python-net/aspose.imaging/sizef/) har noll bredd och höjd. |
| width | float | r/w | Hämtar eller anger den horisontella komponenten för denna [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Lägger till bredden och höjden för en [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur till bredden och höjden för en annan [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur. |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Initierar en ny instans av [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen från den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Initierar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) från den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtraherar bredden och höjden för en [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur från bredden och höjden för en annan [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur. |
| [to_point_f()](#to_point_f__5) | Konverterar en [SizeF](/imaging/python-net/aspose.imaging/sizef/) till en [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Konverterar en [SizeF](/imaging/python-net/aspose.imaging/sizef/) till en [Size](/imaging/python-net/aspose.imaging/size/) struktur med trunkerade storleksvärden. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initierar en ny instans av SizeF-klassen

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initierar en ny instans av [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen från den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) från vilken man initierar denna [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initierar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) från den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den [SizeF](/imaging/python-net/aspose.imaging/sizef/) från vilken den nya [SizeF](/imaging/python-net/aspose.imaging/sizef/) skapas. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initierar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) från de angivna dimensionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | float | Breddkomponenten för den nya [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | Höjskomponenten för den nya [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Lägger till bredden och höjden för en [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur till bredden och höjden för en annan [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den första [SizeF](/imaging/python-net/aspose.imaging/sizef/) att lägga till. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den andra [SizeF](/imaging/python-net/aspose.imaging/sizef/) att lägga till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | En [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur som är resultatet av additionsoperationen. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Initierar en ny instans av [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen från den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) från vilken man initierar denna [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Initierar en ny instans av strukturen [SizeF](/imaging/python-net/aspose.imaging/sizef/) från den angivna [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den [SizeF](/imaging/python-net/aspose.imaging/sizef/) från vilken den nya [SizeF](/imaging/python-net/aspose.imaging/sizef/) skapas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtraherar bredden och höjden för en [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur från bredden och höjden för en annan [SizeF](/imaging/python-net/aspose.imaging/sizef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen på vänster sida av subtraktionsoperatorn. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den [SizeF](/imaging/python-net/aspose.imaging/sizef/) strukturen på höger sida av subtraktionsoperatorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Den [SizeF](/imaging/python-net/aspose.imaging/sizef/) som är resultatet av subtraktionsoperationen. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Konverterar en [SizeF](/imaging/python-net/aspose.imaging/sizef/) till en [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Returnerar en [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur. |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Konverterar en [SizeF](/imaging/python-net/aspose.imaging/sizef/) till en [Size](/imaging/python-net/aspose.imaging/size/) struktur med trunkerade storleksvärden.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Returnerar en [Size](/imaging/python-net/aspose.imaging/size/) struktur. |


