---
title: "Rectángulo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo."
type: docs
weight: 93
url: /es/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Inicializa una nueva instancia de la estructura `com.aspose.imaging.Rectangle` con la ubicación y el tamaño especificados. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Inicializa una nueva instancia de la estructura `com.aspose.imaging.Rectangle` con la ubicación y el tamaño especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `com.aspose.imaging.Rectangle` que tiene los valores `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` y `com.aspose.imaging.Rectangle.Height` establecidos en cero. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Crea un nuevo `Rectangle` a partir de dos puntos especificados. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Convierte la estructura `com.aspose.imaging.RectangleF` especificada a una estructura `com.aspose.imaging.Rectangle` redondeando los valores de `com.aspose.imaging.RectangleF` al siguiente número entero superior. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Convierte el `com.aspose.imaging.RectangleF` especificado a un `com.aspose.imaging.Rectangle` truncando los valores de `com.aspose.imaging.RectangleF`. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Convierte el `com.aspose.imaging.RectangleF` especificado a un `com.aspose.imaging.Rectangle` redondeando los valores del `com.aspose.imaging.RectangleF` al entero más cercano. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Crea y devuelve una copia inflada de la estructura `com.aspose.imaging.Rectangle` especificada. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Devuelve una tercera estructura `com.aspose.imaging.Rectangle` que representa la intersección de dos estructuras `com.aspose.imaging.Rectangle` distintas. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Obtiene una estructura `com.aspose.imaging.Rectangle` que contiene la unión de dos estructuras `com.aspose.imaging.Rectangle`. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Comprueba si dos estructuras `com.aspose.imaging.Rectangle` tienen la misma ubicación y tamaño. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Comprueba si dos estructuras `com.aspose.imaging.Rectangle` difieren en ubicación o tamaño. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Crea una estructura `com.aspose.imaging.Rectangle` con las ubicaciones de borde especificadas. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| [getSize()](#getSize--) | Obtiene o establece el tamaño de este `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Obtiene o establece el tamaño de este `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| [setX(int value)](#setX-int-) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| [setY(int value)](#setY-int-) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| [getWidth()](#getWidth--) | Obtiene el ancho de esta estructura `com.aspose.imaging.Rectangle`. |
| [setWidth(int value)](#setWidth-int-) | Establece el ancho de esta estructura `com.aspose.imaging.Rectangle`. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de esta estructura `com.aspose.imaging.Rectangle`. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece la altura de esta estructura `com.aspose.imaging.Rectangle`. |
| [getLeft()](#getLeft--) | Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.Rectangle`. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.Rectangle`. |
| [getTop()](#getTop--) | Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.Rectangle`. |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.Rectangle`. |
| [getRight()](#getRight--) | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Width` de esta estructura `com.aspose.imaging.Rectangle`. |
| [setRight(int value)](#setRight-int-) | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Width` de esta estructura `com.aspose.imaging.Rectangle`. |
| [getBottom()](#getBottom--) | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.Y` y `com.aspose.imaging.Rectangle.Height` de esta estructura `com.aspose.imaging.Rectangle`. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.Y` y `com.aspose.imaging.Rectangle.Height` de esta estructura `com.aspose.imaging.Rectangle`. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si todas las propiedades numéricas de este `com.aspose.imaging.Rectangle` tienen valores cero. |
| [contains(int x, int y)](#contains-int-int-) | Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.Rectangle`. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.Rectangle`. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Determina si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura `com.aspose.imaging.Rectangle`. |
| [inflate(int width, int height)](#inflate-int-int-) | Infla este `com.aspose.imaging.Rectangle` en la cantidad especificada. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Infla este `com.aspose.imaging.Rectangle` en la cantidad especificada. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Reemplaza este `com.aspose.imaging.Rectangle` con la intersección de sí mismo y el `com.aspose.imaging.Rectangle` especificado. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Determina si este rectángulo intersecta con `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(int x, int y)](#offset-int-int-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [normalize()](#normalize--) | Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si `obj` es una estructura `com.aspose.imaging.Rectangle` con la misma ubicación y tamaño que esta estructura `com.aspose.imaging.Rectangle`. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta estructura `com.aspose.imaging.Rectangle`. |
| [toString()](#toString--) | Convierte los atributos de esta `com.aspose.imaging.Rectangle` a una cadena legible por humanos. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Inicializa una nueva instancia de la estructura `com.aspose.imaging.Rectangle` con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo. |
| width | int | El ancho del rectángulo. |
| height | int | La altura del rectángulo. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Inicializa una nueva instancia de la estructura `com.aspose.imaging.Rectangle` con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` que representa la esquina superior izquierda de la región rectangular. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` que representa el ancho y la altura de la región rectangular. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Obtiene una nueva instancia de la estructura `com.aspose.imaging.Rectangle` que tiene los valores `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` y `com.aspose.imaging.Rectangle.Height` establecidos en cero.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crea un nuevo `Rectangle` a partir de dos puntos especificados. Los dos vértices verticales del `Rectangle` creado serán iguales a los puntos `point1` y `point2` pasados. Estos suelen ser los vértices opuestos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | El primer `Point` para el nuevo rectángulo. |
| point2 | [Point](../../com.aspose.imaging/point) | El segundo `Point` para el nuevo rectángulo. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Convierte la estructura `com.aspose.imaging.RectangleF` especificada a una estructura `com.aspose.imaging.Rectangle` redondeando los valores de `com.aspose.imaging.RectangleF` al siguiente número entero superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | La estructura `com.aspose.imaging.RectangleF` a convertir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Convierte el `com.aspose.imaging.RectangleF` especificado a un `com.aspose.imaging.Rectangle` truncando los valores de `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | El `com.aspose.imaging.RectangleF` a convertir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Convierte el `com.aspose.imaging.RectangleF` especificado a un `com.aspose.imaging.Rectangle` redondeando los valores del `com.aspose.imaging.RectangleF` al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | El `com.aspose.imaging.RectangleF` a convertir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Crea y devuelve una copia inflada de la estructura `com.aspose.imaging.Rectangle` especificada. La copia se infla en la cantidad especificada. La estructura original `com.aspose.imaging.Rectangle` permanece sin modificar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El `com.aspose.imaging.Rectangle` con el que iniciar. Este rectángulo no se modifica. |
| x | int | La cantidad para inflar horizontalmente este `com.aspose.imaging.Rectangle`. |
| y | int | La cantidad para inflar verticalmente este `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Devuelve una tercera estructura `com.aspose.imaging.Rectangle` que representa la intersección de dos estructuras `com.aspose.imaging.Rectangle` adicionales. Si no hay intersección, se devuelve un `com.aspose.imaging.Rectangle` vacío.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Un primer rectángulo para intersectar. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Un segundo rectángulo para intersectar. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Obtiene una estructura `com.aspose.imaging.Rectangle` que contiene la unión de dos estructuras `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Un primer rectángulo para unir. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Un segundo rectángulo para unir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Comprueba si dos estructuras `com.aspose.imaging.Rectangle` tienen la misma ubicación y tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` que está a la izquierda del operador de igualdad. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` que está a la derecha del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si las dos estructuras `com.aspose.imaging.Rectangle` tienen iguales las propiedades `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` y `com.aspose.imaging.Rectangle.Height`.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Comprueba si dos estructuras `com.aspose.imaging.Rectangle` difieren en ubicación o tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` que está a la izquierda del operador de desigualdad. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | La estructura `com.aspose.imaging.Rectangle` que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si alguna de las propiedades `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` o `com.aspose.imaging.Rectangle.Height` de las dos estructuras `com.aspose.imaging.Rectangle` es desigual; de lo contrario, false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Crea una estructura `com.aspose.imaging.Rectangle` con las ubicaciones de borde especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | int | La coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| superior | int | La coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |
| derecha | int | La coordenada x de la esquina inferior derecha de esta estructura `com.aspose.imaging.Rectangle`. |
| inferior | int | La coordenada y de la esquina inferior derecha de esta estructura `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | Un `Point` que representa la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |

### getSize() {#getSize--}
```
public Size getSize()
```


Obtiene o establece el tamaño de este `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Obtiene o establece el tamaño de este `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` que representa el ancho y la altura de esta estructura `com.aspose.imaging.Rectangle`. |

### getX() {#getX--}
```
public int getX()
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada x de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |

### getY() {#getY--}
```
public int getY()
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada y de la esquina superior izquierda de esta estructura `com.aspose.imaging.Rectangle`. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - El ancho de esta estructura `com.aspose.imaging.Rectangle`.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Establece el ancho de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El ancho de esta estructura `com.aspose.imaging.Rectangle`. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece la altura de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La altura de esta estructura `com.aspose.imaging.Rectangle`.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece la altura de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La altura de esta estructura `com.aspose.imaging.Rectangle`. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.Rectangle`.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtiene o establece la coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada x del borde izquierdo de esta estructura `com.aspose.imaging.Rectangle`. |

### getTop() {#getTop--}
```
public int getTop()
```


Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordenada y del borde superior de esta estructura `com.aspose.imaging.Rectangle`.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtiene o establece la coordenada y del borde superior de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada y del borde superior de esta estructura `com.aspose.imaging.Rectangle`. |

### getRight() {#getRight--}
```
public int getRight()
```


Obtiene o establece la coordenada x que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Width` de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordenada x que es la suma de `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Width` de esta `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Obtiene o establece la coordenada x que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Width` de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada x que es la suma de `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Width` de esta `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtiene o establece la coordenada y que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.Y` y `com.aspose.imaging.Rectangle.Height` de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordenada y que es la suma de `com.aspose.imaging.Rectangle.Y` y `com.aspose.imaging.Rectangle.Height` de esta `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtiene o establece la coordenada y que es la suma de los valores de las propiedades `com.aspose.imaging.Rectangle.Y` y `com.aspose.imaging.Rectangle.Height` de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada y que es la suma de `com.aspose.imaging.Rectangle.Y` y `com.aspose.imaging.Rectangle.Height` de esta `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si todas las propiedades numéricas de este `com.aspose.imaging.Rectangle` tienen valores cero.

**Returns:**
boolean - Esta propiedad devuelve true si las propiedades `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` y `com.aspose.imaging.Rectangle.Y` de este `com.aspose.imaging.Rectangle` tienen valores cero; de lo contrario, false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto definido por `x` y `y` está contenido dentro de esta estructura `com.aspose.imaging.Rectangle`; de lo contrario false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Determina si el punto especificado está contenido dentro de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `com.aspose.imaging.Point` a probar. |

**Returns:**
boolean - Este método devuelve true si el punto representado por `point` está contenido dentro de esta estructura `com.aspose.imaging.Rectangle`; de lo contrario false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determina si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El `com.aspose.imaging.Rectangle` a probar. |

**Returns:**
boolean - Este método devuelve true si la región rectangular representada por `rect` está completamente contenida dentro de esta estructura `com.aspose.imaging.Rectangle`; de lo contrario false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Infla este `com.aspose.imaging.Rectangle` en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | La cantidad para inflar horizontalmente este `com.aspose.imaging.Rectangle`. |
| height | int | La cantidad para inflar verticalmente este `com.aspose.imaging.Rectangle`. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Infla este `com.aspose.imaging.Rectangle` en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | La cantidad para inflar este rectángulo. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Reemplaza este `com.aspose.imaging.Rectangle` con la intersección de sí mismo y el `com.aspose.imaging.Rectangle` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El `com.aspose.imaging.Rectangle` con el que intersectar. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Determina si este rectángulo intersecta con `rect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo a probar. |

**Returns:**
boolean - Este método devuelve true si hay alguna intersección, de lo contrario false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Cantidad para desplazar la ubicación. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | El desplazamiento horizontal. |
| y | int | El desplazamiento vertical. |

### normalize() {#normalize--}
```
public void normalize()
```


Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si `obj` es una estructura `com.aspose.imaging.Rectangle` con la misma ubicación y tamaño que esta estructura `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para probar. |

**Returns:**
boolean - Este método devuelve true si `obj` es una estructura `com.aspose.imaging.Rectangle` y sus propiedades `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` y `com.aspose.imaging.Rectangle.Height` son iguales a las propiedades correspondientes de esta estructura `com.aspose.imaging.Rectangle`; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta estructura `com.aspose.imaging.Rectangle`.

**Returns:**
int - Un entero que representa el código hash de este rectángulo.
### toString() {#toString--}
```
public String toString()
```


Convierte los atributos de esta `com.aspose.imaging.Rectangle` a una cadena legible por humanos.

**Returns:**
java.lang.String - Una cadena que contiene la posición, el ancho y la altura de esta estructura `com.aspose.imaging.Rectangle`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
