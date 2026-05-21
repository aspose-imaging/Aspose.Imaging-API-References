---
title: "IntRange"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase para representar una secuencia de elementos"
type: docs
weight: 64
url: /es/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Clase para representar una secuencia de elementos
## Constructores

| Constructor | Descripción |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Inicializa una nueva instancia de la clase `IntRange`. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Inicializa una nueva instancia de la clase `IntRange`. |
| [IntRange(int[] range)](#IntRange-int---) | Inicializa una nueva instancia de la clase `IntRange`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRange()](#getRange--) | Obtiene el rango. |
| [setRange(int[] value)](#setRange-int---) | Establece el rango. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Devuelve una matriz de un elemento desde el índice especificado |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Obtiene el rango de conteo de elementos int que comienza en start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Inicializa una nueva instancia de la clase `IntRange`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | int | El start. |
| count | int | El count. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Inicializa una nueva instancia de la clase `IntRange`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | int | El start. |
| count | int | El count. |
| delta | int | El delta. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Inicializa una nueva instancia de la clase `IntRange`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| range | int[] | El range. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Obtiene el rango.

**Returns:**
int[] - El rango.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Establece el rango.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El range. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Devuelve una matriz de un elemento desde el índice especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice del rango. |

**Returns:**
int[] - La matriz de `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Obtiene el rango de conteo de elementos int que comienza en start

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | int | El start. |
| count | int | El count. |
| delta | int | El delta. |

**Returns:**
int[] - Matriz de elementos
