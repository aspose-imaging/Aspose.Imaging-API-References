---
title: "RectangleF"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo."
type: docs
weight: 94
url: /es/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Inicializa una nueva instancia de la estructura `com.aspose.imaging.RectangleF` con la ubicación y el tamaño especificados. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Inicializa una nueva instancia de la estructura `com.aspose.imaging.RectangleF` con la ubicación y el tamaño especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `com.aspose.imaging.RectangleF` que tiene los valores `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` y `com.aspose.imaging.RectangleF.Height` establecidos en cero. |
| [getLocation()](#getLocation--) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`. |
| [getSize()](#getSize--) | Obtiene o establece el tamaño de este `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Obtiene o establece el tamaño de este `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`. |
| [setX(float value)](#setX-float-) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`. |
| [setY(float value)](#setY-float-) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de esta estructura `com.aspose.imaging.RectangleF`. |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece el ancho de esta estructura `com.aspose.imaging.RectangleF`. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de esta estructura `com.aspose.imaging.RectangleF`. |
| [setHeight(float value)](#setHeight-float-) | Obtiene o establece la altura de esta estructura `com.aspose.imaging.RectangleF`. |
| [getLeft()](#getLeft--) | Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.RectangleF`. |
| [setLeft(float value)](#setLeft-float-) | Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.RectangleF`. |
| [getTop()](#getTop--) | Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.RectangleF`. |
| [setTop(float value)](#setTop-float-) | Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.RectangleF`. |
| [getRight()](#getRight--) | Obtiene o establece la coordenada x que es la suma de `com.aspose.imaging.RectangleF.X` y `com.aspose.imaging.RectangleF.Width` de esta estructura `com.aspose.imaging.RectangleF`. |
| [setRight(float value)](#setRight-float-) | Obtiene o establece la coordenada x que es la suma de `com.aspose.imaging.RectangleF.X` y `com.aspose.imaging.RectangleF.Width` de esta estructura `com.aspose.imaging.RectangleF`. |
| [getBottom()](#getBottom--) | Obtiene o establece la coordenada y que es la suma de `com.aspose.imaging.RectangleF.Y` y `com.aspose.imaging.RectangleF.Height` de esta estructura `com.aspose.imaging.RectangleF`. |
| [setBottom(float value)](#setBottom-float-) | Obtiene o establece la coordenada y que es la suma de `com.aspose.imaging.RectangleF.Y` y `com.aspose.imaging.RectangleF.Height` de esta estructura `com.aspose.imaging.RectangleF`. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si la propiedad `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` de este `com.aspose.imaging.RectangleF` tiene un valor de cero. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Crea un nuevo `Rectangle` a partir de dos puntos especificados. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Crea y devuelve una copia inflada de la estructura `com.aspose.imaging.RectangleF` especificada. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Devuelve una estructura `com.aspose.imaging.RectangleF` que representa la intersección de dos rectángulos. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Comprueba si dos estructuras `com.aspose.imaging.RectangleF` tienen la misma ubicación y tamaño. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Comprueba si dos estructuras `com.aspose.imaging.RectangleF` difieren en ubicación o tamaño. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Implementa el operador \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Implementa el operador /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Convierte la estructura `com.aspose.imaging.Rectangle` especificada a una estructura `com.aspose.imaging.RectangleF`. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Crea una estructura `com.aspose.imaging.RectangleF` con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| [normalize()](#normalize--) | Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [contains(float x, float y)](#contains-float-float-) | Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.RectangleF`. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.RectangleF`. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Determina si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura `com.aspose.imaging.RectangleF`. |
| [inflate(float x, float y)](#inflate-float-float-) | Infla esta estructura `com.aspose.imaging.RectangleF` en la cantidad especificada. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Infla este `com.aspose.imaging.RectangleF` en la cantidad especificada. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Reemplaza esta estructura `com.aspose.imaging.RectangleF` con la intersección de ella misma y la estructura `com.aspose.imaging.RectangleF` especificada. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Determina si este rectángulo intersecta con `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(float x, float y)](#offset-float-float-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si `obj` es un `com.aspose.imaging.RectangleF` con la misma ubicación y tamaño que este `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | Obtiene el código hash de esta estructura `com.aspose.imaging.RectangleF`. |
| [toString()](#toString--) | Convierte los atributos de este `com.aspose.imaging.RectangleF` a una cadena legible por humanos. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Inicializa una nueva instancia de la estructura `com.aspose.imaging.RectangleF` con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo. |
| width | float | El ancho del rectángulo. |
| height | float | La altura del rectángulo. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Inicializa una nueva instancia de la estructura `com.aspose.imaging.RectangleF` con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` que representa la esquina superior izquierda de la región rectangular. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Un `com.aspose.imaging.SizeF` que representa el ancho y la altura de la región rectangular. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Obtiene una nueva instancia de la estructura `com.aspose.imaging.RectangleF` que tiene los valores `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` y `com.aspose.imaging.RectangleF.Height` establecidos en cero.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Obtiene o establece el tamaño de este `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Obtiene o establece el tamaño de este `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getY() {#getY--}
```
public float getY()
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtiene o establece el ancho de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - El ancho de esta estructura `com.aspose.imaging.RectangleF`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtiene o establece el ancho de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtiene o establece la altura de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La altura de esta estructura `com.aspose.imaging.RectangleF`.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtiene o establece la altura de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.RectangleF`.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordenada y del borde superior de esta estructura `com.aspose.imaging.RectangleF`.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Obtiene o establece la coordenada x que es la suma de `com.aspose.imaging.RectangleF.X` y `com.aspose.imaging.RectangleF.Width` de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordenada x que es la suma de `com.aspose.imaging.RectangleF.X` y `com.aspose.imaging.RectangleF.Width` de esta estructura `com.aspose.imaging.RectangleF`.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Obtiene o establece la coordenada x que es la suma de `com.aspose.imaging.RectangleF.X` y `com.aspose.imaging.RectangleF.Width` de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Obtiene o establece la coordenada y que es la suma de `com.aspose.imaging.RectangleF.Y` y `com.aspose.imaging.RectangleF.Height` de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordenada y que es la suma de `com.aspose.imaging.RectangleF.Y` y `com.aspose.imaging.RectangleF.Height` de esta estructura `com.aspose.imaging.RectangleF`.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Obtiene o establece la coordenada y que es la suma de `com.aspose.imaging.RectangleF.Y` y `com.aspose.imaging.RectangleF.Height` de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si la propiedad `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` de este `com.aspose.imaging.RectangleF` tiene un valor de cero.

**Returns:**
boolean - Esta propiedad devuelve true si la propiedad `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` de este `com.aspose.imaging.RectangleF` tiene un valor de cero; de lo contrario, false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crea un nuevo `Rectangle` a partir de dos puntos especificados. Dos vértices del `Rectangle` creado serán iguales a los `point1` y `point2` pasados. Estos suelen ser los vértices opuestos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | El primer `Point` para el nuevo rectángulo. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | El segundo `Point` para el nuevo rectángulo. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crea y devuelve una copia inflada de la estructura `com.aspose.imaging.RectangleF` especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | El `com.aspose.imaging.RectangleF` a copiar. Este rectángulo no se modifica. |
| x | float | La cantidad para inflar la copia del rectángulo horizontalmente. |
| y | float | La cantidad para inflar la copia del rectángulo verticalmente. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Devuelve una estructura `com.aspose.imaging.RectangleF` que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un `com.aspose.imaging.RectangleF` vacío.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Un primer rectángulo para intersectar. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Un segundo rectángulo para intersectar. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Un primer rectángulo para unir. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Un segundo rectángulo para unir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Comprueba si dos estructuras `com.aspose.imaging.RectangleF` tienen la misma ubicación y tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` que está a la izquierda del operador de igualdad. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` que está a la derecha del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si las dos estructuras `com.aspose.imaging.RectangleF` especificadas tienen iguales las propiedades `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` y `com.aspose.imaging.RectangleF.Height`.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Comprueba si dos estructuras `com.aspose.imaging.RectangleF` difieren en ubicación o tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` que está a la izquierda del operador de desigualdad. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si cualquiera de las propiedades `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` o `com.aspose.imaging.RectangleF.Height` de las dos estructuras `com.aspose.imaging.RectangleF` son desiguales; de lo contrario false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementa el operador \*.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo. |
| multiplicador | float | El multiplicador. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementa el operador /.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo. |
| divisor | float | El divisor. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Convierte la estructura `com.aspose.imaging.Rectangle` especificada a una estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` para convertir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Crea una estructura `com.aspose.imaging.RectangleF` con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | float | La coordenada x de la esquina superior izquierda de la región rectangular. |
| superior | float | La coordenada y de la esquina superior izquierda de la región rectangular. |
| derecha | float | La coordenada x de la esquina inferior derecha de la región rectangular. |
| inferior | float | La coordenada y de la esquina inferior derecha de la región rectangular. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto definido por `x` y `y` está contenido dentro de esta estructura `com.aspose.imaging.RectangleF`; de lo contrario, false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a probar. |

**Returns:**
boolean - Este método devuelve true si el punto representado por el parámetro `point` está contenido dentro de esta estructura `com.aspose.imaging.RectangleF`; de lo contrario, false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Determina si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | El `com.aspose.imaging.RectangleF` a probar. |

**Returns:**
boolean - Este método devuelve true si la región rectangular representada por `rect` está completamente contenida dentro de la región rectangular representada por esta `com.aspose.imaging.RectangleF`; de lo contrario, false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Infla esta estructura `com.aspose.imaging.RectangleF` en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La cantidad para inflar horizontalmente esta estructura `com.aspose.imaging.RectangleF`. |
| y | float | La cantidad para inflar verticalmente esta estructura `com.aspose.imaging.RectangleF`. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Infla este `com.aspose.imaging.RectangleF` en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La cantidad para inflar este rectángulo. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Reemplaza esta estructura `com.aspose.imaging.RectangleF` con la intersección de ella misma y la estructura `com.aspose.imaging.RectangleF` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo para intersectar. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Determina si este rectángulo intersecta con `rect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo a probar. |

**Returns:**
boolean - Este método devuelve true si hay alguna intersección.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | La cantidad para desplazar la ubicación. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La cantidad para desplazar la ubicación horizontalmente. |
| y | float | La cantidad para desplazar la ubicación verticalmente. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si `obj` es un `com.aspose.imaging.RectangleF` con la misma ubicación y tamaño que este `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para probar. |

**Returns:**
boolean - Este método devuelve true si `obj` es un `com.aspose.imaging.RectangleF` y sus propiedades X, Y, Width y Height son iguales a las propiedades correspondientes de este `com.aspose.imaging.RectangleF`; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de esta estructura `com.aspose.imaging.RectangleF`.

**Returns:**
int - El código hash de este `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Convierte los atributos de este `com.aspose.imaging.RectangleF` a una cadena legible por humanos.

**Returns:**
java.lang.String - Una cadena que contiene la posición, el ancho y la altura de esta estructura `com.aspose.imaging.RectangleF`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
