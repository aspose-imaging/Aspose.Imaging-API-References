---
title: "RectangleF-Klasse"
type: docs
weight: 7130
url: /de/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initialisiert eine neue Instanz der RectangleF-Klasse |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initialisiert eine neue Instanz der [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur mit dem angegebenen Ort und der Größe. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initialisiert eine neue Instanz der [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur mit dem angegebenen Ort und der Größe. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bottom | float | r/w | Liest oder setzt die y-Koordinate, die die Summe von [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) und [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur ist. |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest eine neue Instanz der [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, bei der die Werte von [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) und [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) auf Null gesetzt sind. |
| height | float | r/w | Liest oder setzt die Höhe dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| is_empty | bool | r | Liest einen Wert, der angibt, ob die Eigenschaft [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) oder [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) den Wert Null hat. |
| left | float | r/w | Liest oder setzt die x-Koordinate der linken Kante dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Koordinaten der oberen linken Ecke dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| right | float | r/w | Liest oder setzt die x-Koordinate, die die Summe von [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) und [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur ist. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Liest oder setzt die Größe dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Liest oder setzt die y-Koordinate der oberen Kante dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| width | float | r/w | Liest oder setzt die Breite dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| x | float | r/w | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| y | float | r/w | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [contains(point)](#contains_point_1) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist. |
| [contains(rect)](#contains_rect_2) | Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist. |
| [contains(x, y)](#contains_x_y_3) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist. |
| [contains_point_f(point)](#contains_point_f_point_4) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist. |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Erstellt eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Erstellt ein neues [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) aus zwei angegebenen Punkten. Die beiden Eckpunkte des erstellten [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) entsprechen den übergebenen _point1_ und _point2_. Diese sind typischerweise die gegenüberliegenden Eckpunkte. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Das ursprüngliche Rechteck bleibt unverändert. |
| [inflate(size)](#inflate_size_9) | Vergrößert dieses [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) um den angegebenen Betrag. |
| [inflate(x, y)](#inflate_x_y_10) | Vergrößert diese [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur um den angegebenen Betrag. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Das ursprüngliche Rechteck bleibt unverändert. |
| [intersect(a, b)](#intersect_a_b_12) | Gibt eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) zurückgegeben. |
| [intersect(rect)](#intersect_rect_13) | Ersetzt diese [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur durch die Schnittmenge von ihr selbst und der angegebenen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Gibt eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) zurückgegeben. |
| [intersects_with(rect)](#intersects_with_rect_15) | Bestimmt, ob dieses Rechteck mit _rect_ schneidet. |
| normalize() | Normalisiert das Rechteck, indem seine Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [offset(pos)](#offset_pos_16) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [offset(x, y)](#offset_x_y_17) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [union(a, b)](#union_a_b_18) | Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initialisiert eine neue Instanz der RectangleF-Klasse

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initialisiert eine neue Instanz der [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Ein [PointF](/imaging/python-net/aspose.imaging/pointf/) das die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Ein [SizeF](/imaging/python-net/aspose.imaging/sizef/) das die Breite und Höhe des rechteckigen Bereichs darstellt. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initialisiert eine neue Instanz der [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate der oberen linken Ecke des Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des Rechtecks. |
| width | float | Die Breite des Rechtecks. |
| height | float | Die Höhe des Rechtecks. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch den Parameter _point_ dargestellte Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist; andernfalls false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb des durch dieses [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) dargestellten rechteckigen Bereichs liegt; andernfalls false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _x_ und _y_ definierte Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur liegt; andernfalls false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch den Parameter _point_ dargestellte Punkt innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist; andernfalls false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Bestimmt, ob der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb dieser [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur enthalten ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch _rect_ dargestellte rechteckige Bereich vollständig innerhalb des durch dieses [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) dargestellten rechteckigen Bereichs liegt; andernfalls false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Erstellt eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| links | float | Die x-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| oben | float | Die y-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| rechts | float | Die x-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |
| unten | float | Die y-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das neue [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), das diese Methode erstellt. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Erstellt ein neues [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) aus zwei angegebenen Punkten. Die beiden Eckpunkte des erstellten [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) entsprechen den übergebenen _point1_ und _point2_. Diese sind typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der erste [Point](/imaging/python-net/aspose.imaging/point/) für das neue Rechteck. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der zweite [Point](/imaging/python-net/aspose.imaging/point/) für das neue Rechteck. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein neu erstelltes [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Das ursprüngliche Rechteck bleibt unverändert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das zu kopierende [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Dieses Rechteck wird nicht verändert. |
| x | float | Der Betrag, um den die Kopie des Rechtecks horizontal vergrößert wird. |
| y | float | Der Betrag, um den die Kopie des Rechtecks vertikal vergrößert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das aufgeblähte [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Vergrößert dieses [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Der Betrag, um den dieses Rechteck vergrößert wird. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Vergrößert diese [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Der Betrag, um den diese [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur horizontal vergrößert wird. |
| y | float | Der Betrag, um den diese [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur vertikal vergrößert wird. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Das ursprüngliche Rechteck bleibt unverändert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das zu kopierende [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Dieses Rechteck wird nicht verändert. |
| x | float | Der Betrag, um den die Kopie des Rechtecks horizontal vergrößert wird. |
| y | float | Der Betrag, um den die Kopie des Rechtecks vertikal vergrößert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das aufgeblähte [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Gibt eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein erstes Rechteck zum Überschneiden. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein zweites Rechteck zum Überschneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine dritte [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, deren Größe den überlappenden Bereich der beiden angegebenen Rechtecke darstellt. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Ersetzt diese [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur durch die Schnittmenge von ihr selbst und der angegebenen [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck zum Schneiden. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Gibt eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein erstes Rechteck zum Überschneiden. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein zweites Rechteck zum Überschneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine dritte [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, deren Größe den überlappenden Bereich der beiden angegebenen Rechtecke darstellt. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Bestimmt, ob dieses Rechteck mit _rect_ schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn irgendeine Schnittmenge besteht. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Betrag, um den Standort zu verschieben. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Der Betrag, um den Standort horizontal zu verschieben. |
| y | float | Der Betrag, um den Standort vertikal zu verschieben. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein erstes Rechteck zum Vereinigen. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Ein zweites Rechteck zum Vereinigen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine dritte [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die beide Rechtecke enthält, die die Vereinigung bilden. |


