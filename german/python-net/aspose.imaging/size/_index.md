---
title: "Size-Klasse"
type: docs
weight: 7280
url: /de/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Size()](#Size__1) | Initialisiert eine neue Instanz der Size-Klasse |
| [Size(point)](#Size_point_2) | Initialisiert eine neue Instanz der [Size](/imaging/python-net/aspose.imaging/size/) Struktur aus dem angegebenen [Point](/imaging/python-net/aspose.imaging/point/). |
| [Size(width, height)](#Size_width_height_3) | Initialisiert eine neue Instanz der [Size](/imaging/python-net/aspose.imaging/size/) Struktur aus den angegebenen Abmessungen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | Gibt eine neue Instanz der [Size](/imaging/python-net/aspose.imaging/size/) Struktur zurück, bei der die Werte von [Size.width](/imaging/python-net/aspose.imaging/size/) und [Size.height](/imaging/python-net/aspose.imaging/size/) auf Null gesetzt sind. |
| height | int | r/w | Liest oder setzt die vertikale Komponente dieses [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Size](/imaging/python-net/aspose.imaging/size/) eine Breite und Höhe von 0 hat. |
| width | int | r/w | Liest oder setzt die horizontale Komponente dieses [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Addiert die Breite und Höhe einer [Size](/imaging/python-net/aspose.imaging/size/) Struktur zur Breite und Höhe einer anderen [Size](/imaging/python-net/aspose.imaging/size/) Struktur. |
| [ceiling(size)](#ceiling_size_2) | Konvertiert die angegebene [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur in eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, indem die Werte der [Size](/imaging/python-net/aspose.imaging/size/) Struktur auf die nächsthöheren Ganzzahlen gerundet werden. |
| [round(size)](#round_size_3) | Konvertiert die angegebene [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur in eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, indem die Werte der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur auf die nächsten Ganzzahlen gerundet werden. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtrahiert die Breite und Höhe einer [Size](/imaging/python-net/aspose.imaging/size/) Struktur von der Breite und Höhe einer anderen [Size](/imaging/python-net/aspose.imaging/size/) Struktur. |
| [truncate(size)](#truncate_size_5) | Konvertiert die angegebene [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur in eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, indem die Werte der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initialisiert eine neue Instanz der Size-Klasse

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initialisiert eine neue Instanz der [Size](/imaging/python-net/aspose.imaging/size/) Struktur aus dem angegebenen [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Der [Point](/imaging/python-net/aspose.imaging/point/), aus dem diese [Size](/imaging/python-net/aspose.imaging/size/) initialisiert wird. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initialisiert eine neue Instanz der [Size](/imaging/python-net/aspose.imaging/size/) Struktur aus den angegebenen Abmessungen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breitenkomponente des neuen [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | Die Höhenkomponente des neuen [Size](/imaging/python-net/aspose.imaging/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Addiert die Breite und Höhe einer [Size](/imaging/python-net/aspose.imaging/size/) Struktur zur Breite und Höhe einer anderen [Size](/imaging/python-net/aspose.imaging/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Das erste [Size](/imaging/python-net/aspose.imaging/size/) zum Hinzufügen. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Das zweite [Size](/imaging/python-net/aspose.imaging/size/) zum Hinzufügen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, die das Ergebnis der Additionsoperation ist. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Konvertiert die angegebene [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur in eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, indem die Werte der [Size](/imaging/python-net/aspose.imaging/size/) Struktur auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Die zu konvertierende [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) Struktur, in die diese Methode konvertiert. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Konvertiert die angegebene [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur in eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, indem die Werte der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Die zu konvertierende [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) Struktur, in die diese Methode konvertiert. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtrahiert die Breite und Höhe einer [Size](/imaging/python-net/aspose.imaging/size/) Struktur von der Breite und Höhe einer anderen [Size](/imaging/python-net/aspose.imaging/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/), die das Ergebnis der Subtraktionsoperation ist. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Konvertiert die angegebene [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur in eine [Size](/imaging/python-net/aspose.imaging/size/) Struktur, indem die Werte der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Die zu konvertierende [SizeF](/imaging/python-net/aspose.imaging/sizef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Die [Size](/imaging/python-net/aspose.imaging/size/) Struktur, in die diese Methode konvertiert. |


