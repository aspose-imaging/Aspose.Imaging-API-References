---
title: "Clase IntRange"
type: docs
weight: 5810
url: /es/python-net/aspose.imaging/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IntRange

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | Inicializa una nueva instancia de la clase [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| [IntRange(start, count)](#IntRange_start_count_2) | Inicializa una nueva instancia de la clase [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | Inicializa una nueva instancia de la clase [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| range | int[] | r/w | Obtiene o establece el rango. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | Devuelve una matriz de un elemento del índice especificado |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | Obtiene el rango de recuento de elementos int que comienzan en start |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

Inicializa una nueva instancia de la clase [IntRange](/imaging/python-net/aspose.imaging/intrange/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | int[] | El rango. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

Inicializa una nueva instancia de la clase [IntRange](/imaging/python-net/aspose.imaging/intrange/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start | int | El inicio. |
| count | int | El recuento. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

Inicializa una nueva instancia de la clase [IntRange](/imaging/python-net/aspose.imaging/intrange/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start | int | El inicio. |
| count | int | El recuento. |
| delta | int | El delta. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

Devuelve una matriz de un elemento del índice especificado

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de rango. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de cadenas |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

Obtiene el rango de recuento de elementos int que comienzan en start

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start | int | El inicio. |
| count | int | El recuento. |
| delta | int | El delta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[System.Int32]] | Matriz de elementos |


