---
title: "Clase Rectangle"
type: docs
weight: 7120
url: /es/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Inicializa una nueva instancia de la clase Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Inicializa una nueva instancia de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la ubicación y el tamaño especificados. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Inicializa una nueva instancia de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la ubicación y el tamaño especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bottom | int | r/w | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) y [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene una nueva instancia de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que tiene los valores [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) y [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) establecidos en cero. |
| height | int | r/w | Obtiene o establece la altura de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| is_empty | bool | r | Obtiene un valor que indica si todas las propiedades numéricas de este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) tienen valores cero. |
| left | int | r/w | Obtiene o establece la coordenada x del borde izquierdo de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece las coordenadas de la esquina superior izquierda de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| right | int | r/w | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) y [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtiene o establece el tamaño de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Obtiene o establece la coordenada y del borde superior de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| width | int | r/w | Obtiene o establece el ancho de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| x | int | r/w | Obtiene o establece la coordenada x de la esquina superior izquierda de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| y | int | r/w | Obtiene o establece la coordenada y de la esquina superior izquierda de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Convierte la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada a una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) redondeando los valores de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al siguiente número entero mayor. |
| [contains(point)](#contains_point_2) | Determina si el punto especificado está contenido dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| [contains(rect)](#contains_rect_3) | Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| [contains(x, y)](#contains_x_y_4) | Determina si el punto especificado está contenido dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| [contains_point(point)](#contains_point_point_5) | Determina si el punto especificado está contenido dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| [contains_rect(rect)](#contains_rect_rect_6) | Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Crea una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con las ubicaciones de borde especificadas. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Crea una nueva [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a partir de dos puntos especificados. Dos coordenadas verticales de la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creada serán iguales a los _point1_ y _point2_ pasados. Estos serían típicamente los vértices opuestos. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Crea y devuelve una copia inflada de la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada. La copia se infla en la cantidad especificada. La [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) original permanece sin modificar. |
| [inflate(size)](#inflate_size_10) | Infla esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en la cantidad especificada. |
| [inflate(width, height)](#inflate_width_height_11) | Infla esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en la cantidad especificada. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Crea y devuelve una copia inflada de la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada. La copia se infla en la cantidad especificada. La [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) original permanece sin modificar. |
| [intersect(a, b)](#intersect_a_b_13) | Devuelve una tercera [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa la intersección de dos [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) adicionales. Si no hay intersección, se devuelve una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vacía. |
| [intersect(rect)](#intersect_rect_14) | Reemplaza esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la intersección de ella misma y la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada. |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Devuelve una tercera [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa la intersección de dos [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) adicionales. Si no hay intersección, se devuelve una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vacía. |
| [intersects_with(rect)](#intersects_with_rect_16) | Determina si este rectángulo intersecta con _rect_. |
| normalize() | Normaliza el rectángulo haciendo que su ancho y alto sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [offset(pos)](#offset_pos_17) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(x, y)](#offset_x_y_18) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [round(value)](#round_value_19) | Convierte la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada a una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) redondeando los valores de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al número entero más cercano. |
| [truncate(value)](#truncate_value_20) | Convierte la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada a una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) truncando los valores de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(a, b)](#union_a_b_21) | Obtiene una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que contiene la unión de dos estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Inicializa una nueva instancia de la clase Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Inicializa una nueva instancia de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) que representa la esquina superior izquierda de la región rectangular. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Un [Size](/imaging/python-net/aspose.imaging/size/) que representa el ancho y la altura de la región rectangular. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Inicializa una nueva instancia de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo. |
| width | int | El ancho del rectángulo. |
| height | int | La altura del rectángulo. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Convierte la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada a una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) redondeando los valores de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al siguiente número entero mayor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Devuelve una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Determina si el punto especificado está contenido dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto representado por _point_ está contenido dentro de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); de lo contrario, false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si la región rectangular representada por _rect_ está totalmente contenida dentro de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); de lo contrario, false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determina si el punto especificado está contenido dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto definido por _x_ y _y_ está contenido dentro de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); de lo contrario, false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Determina si el punto especificado está contenido dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | El [Point](/imaging/python-net/aspose.imaging/point/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto representado por _point_ está contenido dentro de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); de lo contrario, false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Determina si la región rectangular representada por _rect_ está completamente contenida dentro de esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si la región rectangular representada por _rect_ está totalmente contenida dentro de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); de lo contrario, false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con las ubicaciones de borde especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| left | int | La coordenada x de la esquina superior izquierda de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | La coordenada y de la esquina superior izquierda de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | La coordenada x de la esquina inferior derecha de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| bottom | int | La coordenada y de la esquina inferior derecha de esta estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El nuevo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que crea este método. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Crea una nueva [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a partir de dos puntos especificados. Dos coordenadas verticales de la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) creada serán iguales a los _point1_ y _point2_ pasados. Estos serían típicamente los vértices opuestos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | El primer [Point](/imaging/python-net/aspose.imaging/point/) para el nuevo rectángulo. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | El segundo [Point](/imaging/python-net/aspose.imaging/point/) para el nuevo rectángulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) recién creado. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Crea y devuelve una copia inflada de la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada. La copia se infla en la cantidad especificada. La [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) original permanece sin modificar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con el que iniciar. Este rectángulo no se modifica. |
| x | int | La cantidad para inflar este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontalmente. |
| y | int | La cantidad para inflar este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) verticalmente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) inflado. |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Infla esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La cantidad para inflar este rectángulo. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Infla esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | La cantidad para inflar este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontalmente. |
| height | int | La cantidad para inflar este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) verticalmente. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Crea y devuelve una copia inflada de la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada. La copia se infla en la cantidad especificada. La [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) original permanece sin modificar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con el que iniciar. Este rectángulo no se modifica. |
| x | int | La cantidad para inflar este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontalmente. |
| y | int | La cantidad para inflar este [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) verticalmente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) inflado. |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Devuelve una tercera [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa la intersección de dos [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) adicionales. Si no hay intersección, se devuelve una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vacía.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un primer rectángulo para intersectar. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un segundo rectángulo para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa la intersección de _a_ y _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Reemplaza esta [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con la intersección de ella misma y la [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) con el que intersectar. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Devuelve una tercera [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa la intersección de dos [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) adicionales. Si no hay intersección, se devuelve una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vacía.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un primer rectángulo para intersectar. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un segundo rectángulo para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa la intersección de _a_ y _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Determina si este rectángulo intersecta con _rect_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si hay alguna intersección, de lo contrario false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Cantidad para desplazar la ubicación. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | El desplazamiento horizontal. |
| y | int | El desplazamiento vertical. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Convierte la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada a una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) redondeando los valores de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) al número entero más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un nuevo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Convierte la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada a una [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) truncando los valores de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un nuevo [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Obtiene una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que contiene la unión de dos estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un primer rectángulo para la unión. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un segundo rectángulo para la unión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que delimita la unión de las dos estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


