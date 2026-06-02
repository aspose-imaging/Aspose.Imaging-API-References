---
title: "IntRange"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe per rappresentare la sequenza di elementi"
type: docs
weight: 64
url: /it/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Classe per rappresentare la sequenza di elementi
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Inizializza una nuova istanza della classe `IntRange`. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Inizializza una nuova istanza della classe `IntRange`. |
| [IntRange(int[] range)](#IntRange-int---) | Inizializza una nuova istanza della classe `IntRange`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRange()](#getRange--) | Ottiene l'intervallo. |
| [setRange(int[] value)](#setRange-int---) | Imposta l'intervallo. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Restituisce un array di un elemento dall'indice specificato |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Ottiene l'intervallo di conteggio degli elementi int a partire da start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Inizializza una nuova istanza della classe `IntRange`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | int | L'inizio. |
| count | int | Il conteggio. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Inizializza una nuova istanza della classe `IntRange`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | int | L'inizio. |
| count | int | Il conteggio. |
| delta | int | Il delta. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Inizializza una nuova istanza della classe `IntRange`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| range | int[] | L'intervallo. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Ottiene l'intervallo.

**Returns:**
int[] - L'intervallo.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Imposta l'intervallo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | L'intervallo. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Restituisce un array di un elemento dall'indice specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice dell'intervallo. |

**Returns:**
int[] - L'array di `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Ottiene l'intervallo di conteggio degli elementi int a partire da start

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | int | L'inizio. |
| count | int | Il conteggio. |
| delta | int | Il delta. |

**Returns:**
int[] - Array di elementi
