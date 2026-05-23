---
title: "Rectangle Klasse"
type: docs
weight: 7120
url: /de/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initialisiert eine neue Instanz der Rectangle Klasse |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initialisiert eine neue Instanz der [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur mit dem angegebenen Ort und der Größe. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initialisiert eine neue Instanz der [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur mit dem angegebenen Ort und der Größe. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bottom | int | r/w | Liest oder setzt die y-Koordinate, die die Summe der Werte von [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) und [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur ist. |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gibt eine neue Instanz der [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück, bei der die Werte von [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) und [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) auf Null gesetzt sind. |
| height | int | r/w | Liest oder setzt die Höhe dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob alle numerischen Eigenschaften dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) den Wert Null haben. |
| left | int | r/w | Liest oder setzt die x-Koordinate der linken Kante dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt die Koordinaten der oberen linken Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| right | int | r/w | Liest oder setzt die x-Koordinate, die die Summe der Werte von [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) und [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) ist. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Liest oder setzt die Größe dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Liest oder setzt die y-Koordinate der oberen Kante dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| width | int | r/w | Liest oder setzt die Breite dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| x | int | r/w | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| y | int | r/w | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Konvertiert die angegebene [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur in eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, indem die Werte von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) auf die nächsthöhere Ganzzahl gerundet werden. |
| [contains(point)](#contains_point_2) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt. |
| [contains(rect)](#contains_rect_3) | Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt. |
| [contains(x, y)](#contains_x_y_4) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt. |
| [contains_point(point)](#contains_point_point_5) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt. |
| [contains_rect(rect)](#contains_rect_rect_6) | Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Erstellt eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur mit den angegebenen Kantenpositionen. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Erstellt ein neues [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) aus zwei angegebenen Punkten. Zwei Vertikale des erstellten [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) entsprechen den übergebenen _point1_ und _point2_. Diese sind typischerweise die gegenüberliegenden Eckpunkte. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Die ursprüngliche [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur bleibt unverändert. |
| [inflate(size)](#inflate_size_10) | Vergrößert dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) um den angegebenen Betrag. |
| [inflate(width, height)](#inflate_width_height_11) | Vergrößert dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) um den angegebenen Betrag. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Die ursprüngliche [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur bleibt unverändert. |
| [intersect(a, b)](#intersect_a_b_13) | Gibt eine dritte [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) zurückgegeben. |
| [intersect(rect)](#intersect_rect_14) | Ersetzt dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) durch die Schnittmenge von sich selbst und dem angegebenen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Gibt eine dritte [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) zurückgegeben. |
| [intersects_with(rect)](#intersects_with_rect_16) | Bestimmt, ob dieses Rechteck mit _rect_ schneidet. |
| normalize() | Normalisiert das Rechteck, indem seine Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [offset(pos)](#offset_pos_17) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [offset(x, y)](#offset_x_y_18) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [round(value)](#round_value_19) | Konvertiert das angegebene [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) in ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), indem die Werte von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) auf die nächsten Ganzzahlen gerundet werden. |
| [truncate(value)](#truncate_value_20) | Konvertiert das angegebene [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) in ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), indem die Werte von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) abgeschnitten werden. |
| [union(a, b)](#union_a_b_21) | Liest eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die die Vereinigung zweier [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen enthält. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initialisiert eine neue Instanz der Rectangle Klasse

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initialisiert eine neue Instanz der [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Ein [Point](/imaging/python-net/aspose.imaging/point/), der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Ein [Size](/imaging/python-net/aspose.imaging/size/), der die Breite und Höhe des rechteckigen Bereichs darstellt. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initialisiert eine neue Instanz der [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate der oberen linken Ecke des Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des Rechtecks. |
| width | int | Die Breite des Rechtecks. |
| height | int | Die Höhe des Rechtecks. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Konvertiert die angegebene [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur in eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, indem die Werte von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) auf die nächsthöhere Ganzzahl gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die konvertiert werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Gibt ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) zurück. |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _point_ dargestellte Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt; andernfalls false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das zu testende [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt; andernfalls false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _x_ und _y_ definierte Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt; andernfalls false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _point_ dargestellte Punkt innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt; andernfalls false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das zu testende [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur liegt; andernfalls false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Erstellt eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur mit den angegebenen Kantenpositionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left | int | Die x‑Koordinate der oberen linken Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| top | int | Die y‑Koordinate der oberen linken Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| right | int | Die x‑Koordinate der unteren rechten Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| bottom | int | Die y‑Koordinate der unteren rechten Ecke dieser [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das neue [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), das diese Methode erstellt. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Erstellt ein neues [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) aus zwei angegebenen Punkten. Zwei Vertikale des erstellten [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) entsprechen den übergebenen _point1_ und _point2_. Diese sind typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Der erste [Point](/imaging/python-net/aspose.imaging/point/) für das neue Rechteck. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Der zweite [Point](/imaging/python-net/aspose.imaging/point/) für das neue Rechteck. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein neu erstelltes [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Erstellt und gibt eine aufgeblähte Kopie der angegebenen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Die ursprüngliche [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur bleibt unverändert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), mit dem gestartet wird. Dieses Rechteck wird nicht verändert. |
| x | int | Der Betrag, um den dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontal erweitert wird. |
| y | int | Der Betrag, um den dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertikal erweitert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das aufgeblähte [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Vergrößert dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Der Betrag, um den dieses Rechteck vergrößert wird. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Vergrößert dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Der Betrag, um den dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontal erweitert wird. |
| height | int | Der Betrag, um den dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertikal erweitert wird. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Erstellt und gibt eine aufgeblähte Kopie der angegebenen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Die ursprüngliche [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur bleibt unverändert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), mit dem gestartet wird. Dieses Rechteck wird nicht verändert. |
| x | int | Der Betrag, um den dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontal erweitert wird. |
| y | int | Der Betrag, um den dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertikal erweitert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das aufgeblähte [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Gibt eine dritte [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein erstes Rechteck zum Überschneiden. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein zweites Rechteck zum Überschneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), das die Schnittmenge von _a_ und _b_ darstellt. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Ersetzt dieses [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) durch die Schnittmenge von sich selbst und dem angegebenen [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), mit dem geschnitten wird. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Gibt eine dritte [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein erstes Rechteck zum Überschneiden. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein zweites Rechteck zum Überschneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), das die Schnittmenge von _a_ und _b_ darstellt. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Bestimmt, ob dieses Rechteck mit _rect_ schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn irgendeine Schnittmenge besteht, andernfalls false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Betrag, um den die Position verschoben wird. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Der horizontale Versatz. |
| y | int | Der vertikale Versatz. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Konvertiert das angegebene [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) in ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), indem die Werte von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das zu konvertierende [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein neues [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Konvertiert das angegebene [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) in ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), indem die Werte von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) abgeschnitten werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das zu konvertierende [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein neues [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Liest eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die die Vereinigung zweier [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein erstes Rechteck zum Vereinigen. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein zweites Rechteck zum Vereinigen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ein [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die die Vereinigung der beiden [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen umschließt. |


