---
title: "Clase SizeF"
type: docs
weight: 7290
url: /es/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SizeF()](#SizeF__1) | Inicializa una nueva instancia de la clase SizeF |
| [SizeF(point)](#SizeF_point_2) | Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado. |
| [SizeF(size)](#SizeF_size_3) | Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificado. |
| [SizeF(width, height)](#SizeF_width_height_4) | Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir de las dimensiones especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Obtiene una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) que tiene los valores [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) y [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) establecidos en cero. |
| height | float | r/w | Obtiene o establece el componente vertical de este [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Obtiene un valor que indica si este [SizeF](/imaging/python-net/aspose.imaging/sizef/) tiene ancho y alto cero. |
| width | float | r/w | Obtiene o establece el componente horizontal de este [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Añade el ancho y alto de una estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al ancho y alto de otra estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado. |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificado. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Resta el ancho y alto de una estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) del ancho y alto de otra estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [to_point_f()](#to_point_f__5) | Convierte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) a un [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Convierte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) a una estructura [Size](/imaging/python-net/aspose.imaging/size/) con valores de tamaño truncados. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Inicializa una nueva instancia de la clase SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) desde el cual inicializar este [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | El [SizeF](/imaging/python-net/aspose.imaging/sizef/) desde el cual crear el nuevo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir de las dimensiones especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | float | El componente de ancho del nuevo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | El componente de alto del nuevo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Añade el ancho y alto de una estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al ancho y alto de otra estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | El primer [SizeF](/imaging/python-net/aspose.imaging/sizef/) a añadir. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | El segundo [SizeF](/imaging/python-net/aspose.imaging/sizef/) a añadir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Una estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) que es el resultado de la operación de suma. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [PointF](/imaging/python-net/aspose.imaging/pointf/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) desde el cual inicializar este [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Inicializa una nueva instancia de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a partir del [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | El [SizeF](/imaging/python-net/aspose.imaging/sizef/) desde el cual crear el nuevo [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Resta el ancho y alto de una estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) del ancho y alto de otra estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) en el lado izquierdo del operador de resta. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) en el lado derecho del operador de resta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | El [SizeF](/imaging/python-net/aspose.imaging/sizef/) que es el resultado de la operación de resta. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Convierte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) a un [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Devuelve una estructura [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Convierte un [SizeF](/imaging/python-net/aspose.imaging/sizef/) a una estructura [Size](/imaging/python-net/aspose.imaging/size/) con valores de tamaño truncados.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Devuelve una estructura [Size](/imaging/python-net/aspose.imaging/size/). |


