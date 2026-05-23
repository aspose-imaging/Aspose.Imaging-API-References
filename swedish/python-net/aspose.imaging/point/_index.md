---
title: "Point klass"
type: docs
weight: 6960
url: /sv/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Initierar en ny instans av Point-klassen |
| [Point(dw)](#Point_dw_2) | Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) med koordinater angivna av ett heltalsvärde. |
| [Point(size)](#Point_size_3) | Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) från strukturen [Size](/imaging/python-net/aspose.imaging/size/). |
| [Point(x, y)](#Point_x_y_4) | Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) med de angivna koordinaterna. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Hämtar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) som har värdena [Point.x](/imaging/python-net/aspose.imaging/point/) och [Point.y](/imaging/python-net/aspose.imaging/point/) satta till noll. |
| is_empty | bool | r | Hämtar ett värde som indikerar om denna [Point](/imaging/python-net/aspose.imaging/point/) är tom. |
| x | int | r/w | Hämtar eller anger x-koordinaten för denna [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Hämtar eller anger y-koordinaten för denna [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Lägger till den angivna [Size](/imaging/python-net/aspose.imaging/size/) till den angivna [Point](/imaging/python-net/aspose.imaging/point/). |
| [ceiling(point)](#ceiling_point_2) | Konverterar den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/) till en [Point](/imaging/python-net/aspose.imaging/point/) genom att avrunda värdena i [PointF](/imaging/python-net/aspose.imaging/pointf/) till nästa högre heltalsvärden. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) med koordinater angivna av ett heltalsvärde. |
| [create_from_size(size)](#create_from_size_size_4) | Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) från strukturen [Size](/imaging/python-net/aspose.imaging/size/). |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | De­konstruera ett Point‑objekt packat i ett long‑objekt till separata X‑ och Y‑int‑värden. |
| [offset(dx, dy)](#offset_dx_dy_6) | Översätter denna [Point](/imaging/python-net/aspose.imaging/point/) med den angivna mängden. |
| [offset(point)](#offset_point_7) | Översätter denna [Point](/imaging/python-net/aspose.imaging/point/) med den angivna [Point](/imaging/python-net/aspose.imaging/point/). |
| [round(point)](#round_point_8) | Konverterar den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/) till ett [Point](/imaging/python-net/aspose.imaging/point/) objekt genom att avrunda [Point](/imaging/python-net/aspose.imaging/point/) värdena till närmaste heltal. |
| [subtract(point, size)](#subtract_point_size_9) | Returnerar resultatet av att subtrahera den angivna [Size](/imaging/python-net/aspose.imaging/size/) från den angivna [Point](/imaging/python-net/aspose.imaging/point/). |
| [to_long()](#to_long__10) | Konvertera denna Point till ett enda long‑värde som innehåller X‑ och Y‑koordinater i hög‑ respektive lågbit. |
| [truncate(point)](#truncate_point_11) | Konverterar den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/) till en [Point](/imaging/python-net/aspose.imaging/point/) genom att trunkera värdena i [Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initierar en ny instans av Point-klassen

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) med koordinater angivna av ett heltalsvärde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dw | int | Ett 32‑bitars heltal som anger koordinaterna för den nya punkten. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) från strukturen [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Innehåller de nya punktkoordinaterna. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) med de angivna koordinaterna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Den horisontella positionen för punkten. |
| y | int | Den vertikala positionen för punkten. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Lägger till den angivna [Size](/imaging/python-net/aspose.imaging/size/) till den angivna [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) att lägga till i. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Den [Size](/imaging/python-net/aspose.imaging/size/) att lägga till i _point_. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som är resultatet av additionsoperationen. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Konverterar den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/) till en [Point](/imaging/python-net/aspose.imaging/point/) genom att avrunda värdena i [PointF](/imaging/python-net/aspose.imaging/pointf/) till nästa högre heltalsvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som den här metoden konverterar till. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) med koordinater angivna av ett heltalsvärde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dw | int | Ett 32‑bitars heltal som anger koordinaterna för den nya punkten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Initierar en ny instans av strukturen [Point](/imaging/python-net/aspose.imaging/point/) från strukturen [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Innehåller de nya punktkoordinaterna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

De­konstruera ett Point‑objekt packat i ett long‑objekt till separata X‑ och Y‑int‑värden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| packed_point | int | Point-objektet packat i ett långt värde. |
| x | int[] | Det extraherade X‑värdet från den packade Point. |
| y | int[] | Det extraherade Y‑värdet från den packade Point. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Översätter denna [Point](/imaging/python-net/aspose.imaging/point/) med den angivna mängden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | int | Mängden för att förskjuta x‑koordinaten. |
| dy | int | Mängden för att förskjuta y‑koordinaten. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Översätter denna [Point](/imaging/python-net/aspose.imaging/point/) med den angivna [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som används för att förskjuta denna [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Konverterar den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/) till ett [Point](/imaging/python-net/aspose.imaging/point/) objekt genom att avrunda [Point](/imaging/python-net/aspose.imaging/point/) värdena till närmaste heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som den här metoden konverterar till. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Returnerar resultatet av att subtrahera den angivna [Size](/imaging/python-net/aspose.imaging/size/) från den angivna [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som ska subtraheras från. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Den [Size](/imaging/python-net/aspose.imaging/size/) som ska subtraheras från _point_. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som är resultatet av subtraktionsoperationen. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Konvertera denna Point till ett enda long‑värde som innehåller X‑ och Y‑koordinater i hög‑ respektive lågbit.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Point-objektet packat i ett långt värde. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Konverterar den angivna [PointF](/imaging/python-net/aspose.imaging/pointf/) till en [Point](/imaging/python-net/aspose.imaging/point/) genom att trunkera värdena i [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Den [PointF](/imaging/python-net/aspose.imaging/pointf/) att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Den [Point](/imaging/python-net/aspose.imaging/point/) som den här metoden konverterar till. |


