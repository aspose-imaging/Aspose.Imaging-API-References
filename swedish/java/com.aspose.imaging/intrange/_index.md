---
title: "IntRange"
second_title: "Aspose.Imaging för Java API-referens"
description: "Klass för att representera en sekvens av element"
type: docs
weight: 64
url: /sv/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Klass för att representera en sekvens av element
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Initierar en ny instans av klassen `IntRange`. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Initierar en ny instans av klassen `IntRange`. |
| [IntRange(int[] range)](#IntRange-int---) | Initierar en ny instans av klassen `IntRange`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRange()](#getRange--) | Hämtar intervallet. |
| [setRange(int[] value)](#setRange-int---) | Ställer in intervallet. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Returnerar en array med ett objekt från angivet index |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Hämtar räkningsintervallet för int‑element som startar vid start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Initierar en ny instans av klassen `IntRange`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int | Starten. |
| antal | int | Antalet. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Initierar en ny instans av klassen `IntRange`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int | Starten. |
| antal | int | Antalet. |
| delta | int | Delta. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Initierar en ny instans av klassen `IntRange`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| intervall | int[] | Intervallet. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Hämtar intervallet.

**Returns:**
int[] - intervallet.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Ställer in intervallet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Intervallet. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Returnerar en array med ett objekt från angivet index

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Intervallets index. |

**Returns:**
int[] - arrayen av `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Hämtar räkningsintervallet för int‑element som startar vid start

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int | Starten. |
| antal | int | Antalet. |
| delta | int | Delta. |

**Returns:**
int[] - array av objekt
