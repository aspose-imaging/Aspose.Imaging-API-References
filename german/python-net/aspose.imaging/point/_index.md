---
title: "Point-Klasse"
type: docs
weight: 6960
url: /de/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Point()](#Point__1) | Initialisiert eine neue Instanz der Point-Klasse |
| [Point(dw)](#Point_dw_2) | Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
| [Point(size)](#Point_size_3) | Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur aus der [Size](/imaging/python-net/aspose.imaging/size/) Struktur. |
| [Point(x, y)](#Point_x_y_4) | Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur mit den angegebenen Koordinaten. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Gibt eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur zurück, bei der die Werte von [Point.x](/imaging/python-net/aspose.imaging/point/) und [Point.y](/imaging/python-net/aspose.imaging/point/) auf Null gesetzt sind. |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Point](/imaging/python-net/aspose.imaging/point/) leer ist. |
| x | int | r/w | Liest oder setzt die x-Koordinate dieses [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Liest oder setzt die y-Koordinate dieses [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Addiert die angegebene [Size](/imaging/python-net/aspose.imaging/size/) zu dem angegebenen [Point](/imaging/python-net/aspose.imaging/point/). |
| [ceiling(point)](#ceiling_point_2) | Konvertiert das angegebene [PointF](/imaging/python-net/aspose.imaging/pointf/) in ein [Point](/imaging/python-net/aspose.imaging/point/), indem die Werte des [PointF](/imaging/python-net/aspose.imaging/pointf/) auf die nächsthöheren Ganzzahlen gerundet werden. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
| [create_from_size(size)](#create_from_size_size_4) | Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur aus der [Size](/imaging/python-net/aspose.imaging/size/) Struktur. |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Dekonstruiert ein Point-Objekt, das in ein Long-Objekt verpackt ist, in separate X- und Y‑Int‑Werte. |
| [offset(dx, dy)](#offset_dx_dy_6) | Verschiebt dieses [Point](/imaging/python-net/aspose.imaging/point/) um den angegebenen Betrag. |
| [offset(point)](#offset_point_7) | Verschiebt dieses [Point](/imaging/python-net/aspose.imaging/point/) um das angegebene [Point](/imaging/python-net/aspose.imaging/point/). |
| [round(point)](#round_point_8) | Konvertiert das angegebene [PointF](/imaging/python-net/aspose.imaging/pointf/) in ein [Point](/imaging/python-net/aspose.imaging/point/) Objekt, indem die [Point](/imaging/python-net/aspose.imaging/point/) Werte auf die nächste ganze Zahl gerundet werden. |
| [subtract(point, size)](#subtract_point_size_9) | Gibt das Ergebnis der Subtraktion der angegebenen [Size](/imaging/python-net/aspose.imaging/size/) von dem angegebenen [Point](/imaging/python-net/aspose.imaging/point/) zurück. |
| [to_long()](#to_long__10) | Konvertiert dieses Point in einen einzelnen Long-Wert, der die X- und Y-Koordinaten in hohen und niedrigen Bits enthält. |
| [truncate(point)](#truncate_point_11) | Konvertiert das angegebene [PointF](/imaging/python-net/aspose.imaging/pointf/) in ein [Point](/imaging/python-net/aspose.imaging/point/), indem die Werte des [Point](/imaging/python-net/aspose.imaging/point/) abgeschnitten werden. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initialisiert eine neue Instanz der Point-Klasse

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dw | int | Ein 32‑Bit‑Integer, der die Koordinaten für den neuen Punkt angibt. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur aus der [Size](/imaging/python-net/aspose.imaging/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Enthält die neuen Punktkoordinaten. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur mit den angegebenen Koordinaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die horizontale Position des Punktes. |
| y | int | Die vertikale Position des Punktes. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Addiert die angegebene [Size](/imaging/python-net/aspose.imaging/size/) zu dem angegebenen [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Das [Point](/imaging/python-net/aspose.imaging/point/), zu dem hinzugefügt wird. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) zum Hinzufügen zum _point_. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Das [Point](/imaging/python-net/aspose.imaging/point/), das das Ergebnis der Additionsoperation ist. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Konvertiert das angegebene [PointF](/imaging/python-net/aspose.imaging/pointf/) in ein [Point](/imaging/python-net/aspose.imaging/point/), indem die Werte des [PointF](/imaging/python-net/aspose.imaging/pointf/) auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/) zum Konvertieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) zu dem diese Methode konvertiert. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dw | int | Ein 32‑Bit‑Integer, der die Koordinaten für den neuen Punkt angibt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Initialisiert eine neue Instanz der [Point](/imaging/python-net/aspose.imaging/point/) Struktur aus der [Size](/imaging/python-net/aspose.imaging/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Enthält die neuen Punktkoordinaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Dekonstruiert ein Point-Objekt, das in ein Long-Objekt verpackt ist, in separate X- und Y‑Int‑Werte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| packed_point | int | Das Point-Objekt, das in einen langen Wert gepackt ist. |
| x | int[] | Der aus dem gepackten Point X-Wert extrahierte Wert. |
| y | int[] | Der aus dem gepackten Point Y-Wert extrahierte Wert. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Verschiebt dieses [Point](/imaging/python-net/aspose.imaging/point/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | int | Der Betrag zum Verschieben der x-Koordinate. |
| dy | int | Der Betrag zum Verschieben der y-Koordinate. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Verschiebt dieses [Point](/imaging/python-net/aspose.imaging/point/) um das angegebene [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) wird verwendet, um diesen [Point](/imaging/python-net/aspose.imaging/point/) zu verschieben. |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Konvertiert das angegebene [PointF](/imaging/python-net/aspose.imaging/pointf/) in ein [Point](/imaging/python-net/aspose.imaging/point/) Objekt, indem die [Point](/imaging/python-net/aspose.imaging/point/) Werte auf die nächste ganze Zahl gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/) zum Konvertieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) zu dem diese Methode konvertiert. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Gibt das Ergebnis der Subtraktion der angegebenen [Size](/imaging/python-net/aspose.imaging/size/) von dem angegebenen [Point](/imaging/python-net/aspose.imaging/point/) zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) von dem subtrahiert wird. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) zum Subtrahieren vom _point_. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) ist das Ergebnis der Subtraktionsoperation. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Konvertiert dieses Point in einen einzelnen Long-Wert, der die X- und Y-Koordinaten in hohen und niedrigen Bits enthält.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das Point-Objekt, das in einen langen Wert gepackt ist. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Konvertiert das angegebene [PointF](/imaging/python-net/aspose.imaging/pointf/) in ein [Point](/imaging/python-net/aspose.imaging/point/), indem die Werte des [Point](/imaging/python-net/aspose.imaging/point/) abgeschnitten werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/) zum Konvertieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) zu dem diese Methode konvertiert. |


