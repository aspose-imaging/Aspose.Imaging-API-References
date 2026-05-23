---
title: "IntRange-Klasse"
type: docs
weight: 5810
url: /de/python-net/aspose.imaging/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IntRange

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | Initialisiert eine neue Instanz der [IntRange](/imaging/python-net/aspose.imaging/intrange/)-Klasse. |
| [IntRange(start, count)](#IntRange_start_count_2) | Initialisiert eine neue Instanz der [IntRange](/imaging/python-net/aspose.imaging/intrange/)-Klasse. |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | Initialisiert eine neue Instanz der [IntRange](/imaging/python-net/aspose.imaging/intrange/)-Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Bereich | int[] | r/w | Liest oder setzt den Bereich. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | Gibt ein Ein-Element-Array vom angegebenen Index zurück |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | Liest den Zählerbereich von int-Elementen, beginnend bei start |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

Initialisiert eine neue Instanz der [IntRange](/imaging/python-net/aspose.imaging/intrange/)-Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bereich | int[] | Der Bereich. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

Initialisiert eine neue Instanz der [IntRange](/imaging/python-net/aspose.imaging/intrange/)-Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Start | int | Der Start. |
| count | int | Die Anzahl. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

Initialisiert eine neue Instanz der [IntRange](/imaging/python-net/aspose.imaging/intrange/)-Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Start | int | Der Start. |
| count | int | Die Anzahl. |
| Delta | int | Das Delta. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

Gibt ein Ein-Element-Array vom angegebenen Index zurück

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Bereichsindex. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Array von Zeichenketten |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

Liest den Zählerbereich von int-Elementen, beginnend bei start

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Start | int | Der Start. |
| count | int | Die Anzahl. |
| Delta | int | Das Delta. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[System.Int32]] | Array von Elementen |


