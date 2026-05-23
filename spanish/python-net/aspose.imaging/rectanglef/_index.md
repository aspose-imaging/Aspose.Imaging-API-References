---
title: "Clase RectangleF"
type: docs
weight: 7130
url: /es/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Inicializa una nueva instancia de la clase RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Inicializa una nueva instancia de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la ubicación y el tamaño especificados. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Inicializa una nueva instancia de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la ubicación y el tamaño especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bottom | float | r/w | Obtiene o establece la coordenada y que es la suma de [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) y [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene una nueva instancia de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que tiene los valores [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) y [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) establecidos en cero. |
| height | float | r/w | Obtiene o establece la altura de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| is_empty | bool | r | Obtiene un valor que indica si la propiedad [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) o [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) de este [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tiene un valor de cero. |
| left | float | r/w | Obtiene o establece la coordenada x del borde izquierdo de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| right | float | r/w | Obtiene o establece la coordenada x que es la suma de [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) y [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Obtiene o establece el tamaño de esta [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Obtiene o establece la coordenada y del borde superior de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| width | float | r/w | Obtiene o establece el ancho de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| x | float | r/w | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | r/w | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [contains(point)](#contains_point_1) | Determina si el punto especificado se encuentra dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Determina si el punto especificado se encuentra dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_point_f(point)](#contains_point_f_point_4) | Determina si el punto especificado se encuentra dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Crea una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Crea un nuevo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a partir de dos puntos especificados. Los dos vértices del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creado serán iguales a los puntos _point1_ y _point2_ pasados. Estos suelen ser los vértices opuestos. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Crea y devuelve una copia inflada de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar. |
| [inflate(size)](#inflate_size_9) | Infla este [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) en la cantidad especificada. |
| [inflate(x, y)](#inflate_x_y_10) | Infla esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) en la cantidad especificada. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Crea y devuelve una copia inflada de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar. |
| [intersect(a, b)](#intersect_a_b_12) | Devuelve una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vacío. |
| [intersect(rect)](#intersect_rect_13) | Reemplaza esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la intersección de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Devuelve una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vacío. |
| [intersects_with(rect)](#intersects_with_rect_15) | Determina si este rectángulo intersecta con _rect_. |
| normalize() | Normaliza el rectángulo haciendo que su ancho y alto sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [offset(pos)](#offset_pos_16) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(x, y)](#offset_x_y_17) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [union(a, b)](#union_a_b_18) | Crea el tercer rectángulo más pequeño posible que pueda contener a ambos rectángulos que forman una unión. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Inicializa una nueva instancia de la clase RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Inicializa una nueva instancia de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa la esquina superior izquierda de la región rectangular. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Un [SizeF](/imaging/python-net/aspose.imaging/sizef/) que representa el ancho y la altura de la región rectangular. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Inicializa una nueva instancia de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo. |
| width | float | El ancho del rectángulo. |
| height | float | La altura del rectángulo. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Determina si el punto especificado se encuentra dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto representado por el parámetro _point_ está contenido dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); de lo contrario, false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si la región rectangular representada por _rect_ está completamente contenida dentro de la región rectangular representada por este [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); de lo contrario, false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Determina si el punto especificado se encuentra dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto definido por _x_ y _y_ está contenido dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); de lo contrario, false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Determina si el punto especificado se encuentra dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El [PointF](/imaging/python-net/aspose.imaging/pointf/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto representado por el parámetro _point_ está contenido dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); de lo contrario, false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si la región rectangular representada por _rect_ está completamente contenida dentro de la región rectangular representada por este [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); de lo contrario, false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| izquierda | float | La coordenada x de la esquina superior izquierda de la región rectangular. |
| superior | float | La coordenada y de la esquina superior izquierda de la región rectangular. |
| derecha | float | La coordenada x de la esquina inferior derecha de la región rectangular. |
| inferior | float | La coordenada y de la esquina inferior derecha de la región rectangular. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El nuevo [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que crea este método. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Crea un nuevo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a partir de dos puntos especificados. Los dos vértices del [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creado serán iguales a los puntos _point1_ y _point2_ pasados. Estos suelen ser los vértices opuestos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El primer [Point](/imaging/python-net/aspose.imaging/point/) para el nuevo rectángulo. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El segundo [Point](/imaging/python-net/aspose.imaging/point/) para el nuevo rectángulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) recién creado. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Crea y devuelve una copia inflada de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a copiar. Este rectángulo no se modifica. |
| x | float | La cantidad para inflar horizontalmente la copia del rectángulo. |
| y | float | La cantidad para inflar verticalmente la copia del rectángulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) inflado. |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Infla este [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La cantidad para inflar este rectángulo. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Infla esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La cantidad para inflar horizontalmente esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | La cantidad para inflar verticalmente esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Crea y devuelve una copia inflada de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a copiar. Este rectángulo no se modifica. |
| x | float | La cantidad para inflar horizontalmente la copia del rectángulo. |
| y | float | La cantidad para inflar verticalmente la copia del rectángulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) inflado. |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Devuelve una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vacío.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un primer rectángulo para intersectar. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un segundo rectángulo para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una tercera estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) cuyo tamaño representa el área superpuesta de los dos rectángulos especificados. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Reemplaza esta estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) con la intersección de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo a intersectar. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Devuelve una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vacío.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un primer rectángulo para intersectar. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un segundo rectángulo para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una tercera estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) cuyo tamaño representa el área superpuesta de los dos rectángulos especificados. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Determina si este rectángulo intersecta con _rect_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si hay alguna intersección. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La cantidad para desplazar la ubicación. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La cantidad para desplazar la ubicación horizontalmente. |
| y | float | La cantidad para desplazar la ubicación verticalmente. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Crea el tercer rectángulo más pequeño posible que pueda contener a ambos rectángulos que forman una unión.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un primer rectángulo para la unión. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un segundo rectángulo para la unión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una tercera estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que contiene ambos rectángulos que forman la unión. |


