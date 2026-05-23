---
title: "Clase Size"
type: docs
weight: 7280
url: /es/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Size()](#Size__1) | Inicializa una nueva instancia de la clase Size |
| [Size(point)](#Size_point_2) | Inicializa una nueva instancia de la estructura [Size](/imaging/python-net/aspose.imaging/size/) a partir del [Point](/imaging/python-net/aspose.imaging/point/) especificado. |
| [Size(width, height)](#Size_width_height_3) | Inicializa una nueva instancia de la estructura [Size](/imaging/python-net/aspose.imaging/size/) a partir de las dimensiones especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtiene una nueva instancia de la estructura [Size](/imaging/python-net/aspose.imaging/size/) que tiene los valores [Size.width](/imaging/python-net/aspose.imaging/size/) y [Size.height](/imaging/python-net/aspose.imaging/size/) establecidos en cero. |
| height | int | r/w | Obtiene o establece el componente vertical de este [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | Obtiene un valor que indica si este [Size](/imaging/python-net/aspose.imaging/size/) tiene ancho y alto de 0. |
| width | int | r/w | Obtiene o establece el componente horizontal de este [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Añade el ancho y alto de una estructura [Size](/imaging/python-net/aspose.imaging/size/) al ancho y alto de otra estructura [Size](/imaging/python-net/aspose.imaging/size/). |
| [ceiling(size)](#ceiling_size_2) | Convierte la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificada a una estructura [Size](/imaging/python-net/aspose.imaging/size/) redondeando los valores de la estructura [Size](/imaging/python-net/aspose.imaging/size/) al siguiente entero superior. |
| [round(size)](#round_size_3) | Convierte la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificada a una estructura [Size](/imaging/python-net/aspose.imaging/size/) redondeando los valores de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al entero más cercano. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Resta el ancho y alto de una estructura [Size](/imaging/python-net/aspose.imaging/size/) del ancho y alto de otra estructura [Size](/imaging/python-net/aspose.imaging/size/). |
| [truncate(size)](#truncate_size_5) | Convierte la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificada a una estructura [Size](/imaging/python-net/aspose.imaging/size/) truncando los valores de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al siguiente entero inferior. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Inicializa una nueva instancia de la clase Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Inicializa una nueva instancia de la estructura [Size](/imaging/python-net/aspose.imaging/size/) a partir del [Point](/imaging/python-net/aspose.imaging/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) desde el cual inicializar este [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Inicializa una nueva instancia de la estructura [Size](/imaging/python-net/aspose.imaging/size/) a partir de las dimensiones especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El componente de ancho del nuevo [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | El componente de alto del nuevo [Size](/imaging/python-net/aspose.imaging/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Añade el ancho y alto de una estructura [Size](/imaging/python-net/aspose.imaging/size/) al ancho y alto de otra estructura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | El primer [Size](/imaging/python-net/aspose.imaging/size/) a añadir. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | El segundo [Size](/imaging/python-net/aspose.imaging/size/) a añadir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Una estructura [Size](/imaging/python-net/aspose.imaging/size/) que es el resultado de la operación de suma. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Convierte la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificada a una estructura [Size](/imaging/python-net/aspose.imaging/size/) redondeando los valores de la estructura [Size](/imaging/python-net/aspose.imaging/size/) al siguiente entero superior.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La estructura [Size](/imaging/python-net/aspose.imaging/size/) a la que este método convierte. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Convierte la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificada a una estructura [Size](/imaging/python-net/aspose.imaging/size/) redondeando los valores de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al entero más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La estructura [Size](/imaging/python-net/aspose.imaging/size/) a la que este método convierte. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Resta el ancho y alto de una estructura [Size](/imaging/python-net/aspose.imaging/size/) del ancho y alto de otra estructura [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | La estructura [Size](/imaging/python-net/aspose.imaging/size/) en el lado izquierdo del operador de sustracción. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | La estructura [Size](/imaging/python-net/aspose.imaging/size/) en el lado derecho del operador de sustracción. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | El [Size](/imaging/python-net/aspose.imaging/size/) que es el resultado de la operación de sustracción. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Convierte la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) especificada a una estructura [Size](/imaging/python-net/aspose.imaging/size/) truncando los valores de la estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) al siguiente entero inferior.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La estructura [SizeF](/imaging/python-net/aspose.imaging/sizef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La estructura [Size](/imaging/python-net/aspose.imaging/size/) a la que este método convierte. |


