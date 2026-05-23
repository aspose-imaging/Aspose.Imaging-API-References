---
title: "Clase Point"
type: docs
weight: 6960
url: /es/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Point()](#Point__1) | Inicializa una nueva instancia de la clase Point |
| [Point(dw)](#Point_dw_2) | Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) usando coordenadas especificadas por un valor entero. |
| [Point(size)](#Point_size_3) | Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) a partir de la estructura [Size](/imaging/python-net/aspose.imaging/size/). |
| [Point(x, y)](#Point_x_y_4) | Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) con las coordenadas especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Obtiene una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) que tiene los valores [Point.x](/imaging/python-net/aspose.imaging/point/) y [Point.y](/imaging/python-net/aspose.imaging/point/) establecidos en cero. |
| is_empty | bool | r | Obtiene un valor que indica si este [Point](/imaging/python-net/aspose.imaging/point/) está vacío. |
| x | int | r/w | Obtiene o establece la coordenada x de este [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Obtiene o establece la coordenada y de este [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Añade el [Size](/imaging/python-net/aspose.imaging/size/) especificado al [Point](/imaging/python-net/aspose.imaging/point/) especificado. |
| [ceiling(point)](#ceiling_point_2) | Convierte el [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado a un [Point](/imaging/python-net/aspose.imaging/point/) redondeando los valores del [PointF](/imaging/python-net/aspose.imaging/pointf/) al siguiente entero superior. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) usando coordenadas especificadas por un valor entero. |
| [create_from_size(size)](#create_from_size_size_4) | Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) a partir de la estructura [Size](/imaging/python-net/aspose.imaging/size/). |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Descompone un objeto Point empaquetado en un objeto long para obtener valores int separados de X y Y. |
| [offset(dx, dy)](#offset_dx_dy_6) | Traslada este [Point](/imaging/python-net/aspose.imaging/point/) por la cantidad especificada. |
| [offset(point)](#offset_point_7) | Traslada este [Point](/imaging/python-net/aspose.imaging/point/) por el [Point](/imaging/python-net/aspose.imaging/point/) especificado. |
| [round(point)](#round_point_8) | Convierte el [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado a un objeto [Point](/imaging/python-net/aspose.imaging/point/) redondeando los valores del [Point](/imaging/python-net/aspose.imaging/point/) al entero más cercano. |
| [subtract(point, size)](#subtract_point_size_9) | Devuelve el resultado de restar el [Size](/imaging/python-net/aspose.imaging/size/) especificado del [Point](/imaging/python-net/aspose.imaging/point/) especificado. |
| [to_long()](#to_long__10) | Convierte este Point a un único valor long, que contiene las coordenadas X e Y en los bits altos y bajos. |
| [truncate(point)](#truncate_point_11) | Convierte el [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado a un [Point](/imaging/python-net/aspose.imaging/point/) truncando los valores del [Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Inicializa una nueva instancia de la clase Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) usando coordenadas especificadas por un valor entero.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dw | int | Un entero de 32 bits que especifica las coordenadas del nuevo punto. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) a partir de la estructura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contiene las coordenadas del nuevo punto. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) con las coordenadas especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La posición horizontal del punto. |
| y | int | La posición vertical del punto. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Añade el [Size](/imaging/python-net/aspose.imaging/size/) especificado al [Point](/imaging/python-net/aspose.imaging/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) al que añadir. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | El [Size](/imaging/python-net/aspose.imaging/size/) al que añadir al _point_. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) que es el resultado de la operación de suma. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Convierte el [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado a un [Point](/imaging/python-net/aspose.imaging/point/) redondeando los valores del [PointF](/imaging/python-net/aspose.imaging/pointf/) al siguiente entero superior.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) al que este método convierte. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) usando coordenadas especificadas por un valor entero.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dw | int | Un entero de 32 bits que especifica las coordenadas del nuevo punto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Inicializa una nueva instancia de la estructura [Point](/imaging/python-net/aspose.imaging/point/) a partir de la estructura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contiene las coordenadas del nuevo punto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Descompone un objeto Point empaquetado en un objeto long para obtener valores int separados de X y Y.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| packed_point | int | El objeto Point empaquetado en un valor largo. |
| x | int[] | El extraído del valor X del Point empaquetado. |
| y | int[] | El extraído del valor Y del Point empaquetado. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Traslada este [Point](/imaging/python-net/aspose.imaging/point/) por la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | int | La cantidad para desplazar la coordenada x. |
| dy | int | La cantidad para desplazar la coordenada y. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Traslada este [Point](/imaging/python-net/aspose.imaging/point/) por el [Point](/imaging/python-net/aspose.imaging/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) usado para desplazar este [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Convierte el [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado a un objeto [Point](/imaging/python-net/aspose.imaging/point/) redondeando los valores del [Point](/imaging/python-net/aspose.imaging/point/) al entero más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) al que este método convierte. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Devuelve el resultado de restar el [Size](/imaging/python-net/aspose.imaging/size/) especificado del [Point](/imaging/python-net/aspose.imaging/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) del cual se restará. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | El [Size](/imaging/python-net/aspose.imaging/size/) a restar del _point_. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) que es el resultado de la operación de resta. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Convierte este Point a un único valor long, que contiene las coordenadas X e Y en los bits altos y bajos.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El objeto Point empaquetado en un valor largo. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Convierte el [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado a un [Point](/imaging/python-net/aspose.imaging/point/) truncando los valores del [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) al que este método convierte. |


