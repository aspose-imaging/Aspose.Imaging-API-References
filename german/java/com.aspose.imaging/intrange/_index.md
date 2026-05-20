---
title: "IntRange"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Klasse zur Darstellung einer Sequenz von Elementen"
type: docs
weight: 64
url: /de/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Klasse zur Darstellung einer Sequenz von Elementen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Initialisiert eine neue Instanz der `IntRange`-Klasse. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Initialisiert eine neue Instanz der `IntRange`-Klasse. |
| [IntRange(int[] range)](#IntRange-int---) | Initialisiert eine neue Instanz der `IntRange`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRange()](#getRange--) | Liest den Bereich. |
| [setRange(int[] value)](#setRange-int---) | Setzt den Bereich. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Gibt ein Array mit einem Element vom angegebenen Index zurück. |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Liest den Zählbereich von int-Elementen, beginnend bei start. |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Initialisiert eine neue Instanz der `IntRange`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | int | Der start. |
| count | int | Der count. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Initialisiert eine neue Instanz der `IntRange`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | int | Der start. |
| count | int | Der count. |
| delta | int | Der delta. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Initialisiert eine neue Instanz der `IntRange`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| range | int[] | Der range. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Liest den Bereich.

**Returns:**
int[] - Der range.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Setzt den Bereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Der range. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Gibt ein Array mit einem Element vom angegebenen Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der range-Index. |

**Returns:**
int[] - Das Array von `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Liest den Zählbereich von int-Elementen, beginnend bei start.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | int | Der start. |
| count | int | Der count. |
| delta | int | Der delta. |

**Returns:**
int[] - Array von Elementen
