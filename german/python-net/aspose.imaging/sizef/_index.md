---
title: "SizeF Klasse"
type: docs
weight: 7290
url: /de/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initialisiert eine neue Instanz der SizeF Klasse |
| [SizeF(point)](#SizeF_point_2) | Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus den angegebenen Abmessungen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Gibt eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur zurück, deren [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) und [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) Werte auf Null gesetzt sind. |
| height | float | r/w | Liest oder setzt die vertikale Komponente dieses [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [SizeF](/imaging/python-net/aspose.imaging/sizef/) eine Breite und Höhe von Null hat. |
| width | float | r/w | Liest oder setzt die horizontale Komponente dieses [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Addiert die Breite und Höhe einer [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur zur Breite und Höhe einer anderen [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur. |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtrahiert die Breite und Höhe einer [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur von der Breite und Höhe einer anderen [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur. |
| [to_point_f()](#to_point_f__5) | Konvertiert ein [SizeF](/imaging/python-net/aspose.imaging/sizef/) zu einem [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Konvertiert ein [SizeF](/imaging/python-net/aspose.imaging/sizef/) zu einer [Size](/imaging/python-net/aspose.imaging/size/) Struktur mit abgeschnittenen Größenwerten. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initialisiert eine neue Instanz der SizeF Klasse

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/), aus dem diese [SizeF](/imaging/python-net/aspose.imaging/sizef/) initialisiert wird. |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Das [SizeF](/imaging/python-net/aspose.imaging/sizef/), aus dem das neue [SizeF](/imaging/python-net/aspose.imaging/sizef/) erstellt wird. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus den angegebenen Abmessungen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | float | Die Breitenkomponente des neuen [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | Die Höhenkomponente des neuen [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Addiert die Breite und Höhe einer [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur zur Breite und Höhe einer anderen [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Das erste [SizeF](/imaging/python-net/aspose.imaging/sizef/) zum Hinzufügen. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Das zweite [SizeF](/imaging/python-net/aspose.imaging/sizef/) zum Hinzufügen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Eine [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur, die das Ergebnis der Additionsoperation ist. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der [PointF](/imaging/python-net/aspose.imaging/pointf/), aus dem diese [SizeF](/imaging/python-net/aspose.imaging/sizef/) initialisiert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Initialisiert eine neue Instanz der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur aus dem angegebenen [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Das [SizeF](/imaging/python-net/aspose.imaging/sizef/), aus dem das neue [SizeF](/imaging/python-net/aspose.imaging/sizef/) erstellt wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtrahiert die Breite und Höhe einer [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur von der Breite und Höhe einer anderen [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Die [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Die [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Das [SizeF](/imaging/python-net/aspose.imaging/sizef/), das das Ergebnis der Subtraktionsoperation ist. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Konvertiert ein [SizeF](/imaging/python-net/aspose.imaging/sizef/) zu einem [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Gibt eine [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur zurück. |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Konvertiert ein [SizeF](/imaging/python-net/aspose.imaging/sizef/) zu einer [Size](/imaging/python-net/aspose.imaging/size/) Struktur mit abgeschnittenen Größenwerten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Gibt eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur zurück. |


