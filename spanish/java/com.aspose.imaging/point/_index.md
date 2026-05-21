---
title: "Point"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional."
type: docs
weight: 86
url: /es/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.Point` con las coordenadas especificadas. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.Point` a partir de la estructura `Aspose.Imaging.Size`. |
| [Point(int dw)](#Point-int-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.Point` usando coordenadas especificadas por un valor entero. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `Aspose.Imaging.Point` que tiene los valores `Aspose.Imaging.Point.X` y `Aspose.Imaging.Point.Y` establecidos en cero. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Agrega el `Aspose.Imaging.Size` especificado al `Aspose.Imaging.Point` especificado. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Devuelve el resultado de restar el `Aspose.Imaging.Size` especificado del `Aspose.Imaging.Point` especificado. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Convierte el `Aspose.Imaging.PointF` especificado a un `Aspose.Imaging.Point` redondeando los valores del `Aspose.Imaging.PointF` al siguiente entero mayor. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Convierte el `Aspose.Imaging.PointF` especificado a un objeto `Aspose.Imaging.Point` redondeando los valores del `Aspose.Imaging.Point` al entero más cercano. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Convierte el `Aspose.Imaging.PointF` especificado a un `Aspose.Imaging.Point` truncando los valores del `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Traslada un `Aspose.Imaging.Point` mediante un `Aspose.Imaging.Size` dado. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Traslada un `Aspose.Imaging.Point` mediante el negativo de un `Aspose.Imaging.Size` dado. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Compara dos objetos `Aspose.Imaging.Point`. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Compara dos objetos `Aspose.Imaging.Point`. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Convierte la estructura `Aspose.Imaging.Point` especificada a una estructura `Aspose.Imaging.Size`. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Convierte la estructura `Point` especificada a la estructura `PointF`. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Descompone un objeto Point empaquetado en un objeto long para obtener los valores int X e Y por separado. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este `Aspose.Imaging.Point` está vacío. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de este `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Obtiene o establece la coordenada x de este `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de este `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Obtiene o establece la coordenada y de este `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Traslada este `Aspose.Imaging.Point` mediante el `Aspose.Imaging.Point` especificado. |
| [offset(int dx, int dy)](#offset-int-int-) | Traslada este `Aspose.Imaging.Point` mediante la cantidad especificada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Especifica si este `Aspose.Imaging.Point` contiene las mismas coordenadas que el `System.Object` especificado. |
| [hashCode()](#hashCode--) | Devuelve un código hash para este `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | Convierte este Point a un único valor long, que contiene las coordenadas X e Y en los bits altos y bajos. |
| [toString()](#toString--) | Convierte este `Aspose.Imaging.Point` a una cadena legible por humanos. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.Point` con las coordenadas especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La posición horizontal del punto. |
| y | int | La posición vertical del punto. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.Point` a partir de la estructura `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Contiene las nuevas coordenadas del punto. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.Point` usando coordenadas especificadas por un valor entero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dw | int | Un entero de 32 bits que especifica las coordenadas del nuevo punto. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Obtiene una nueva instancia de la estructura `Aspose.Imaging.Point` que tiene los valores `Aspose.Imaging.Point.X` y `Aspose.Imaging.Point.Y` establecidos en cero.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Agrega el `Aspose.Imaging.Size` especificado al `Aspose.Imaging.Point` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` al que se añadirá. |
| size | [Size](../../com.aspose.imaging/size) | El `Aspose.Imaging.Size` que se añadirá al `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Devuelve el resultado de restar el `Aspose.Imaging.Size` especificado del `Aspose.Imaging.Point` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` del que se restará. |
| size | [Size](../../com.aspose.imaging/size) | El `Aspose.Imaging.Size` que se restará del `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Convierte el `Aspose.Imaging.PointF` especificado a un `Aspose.Imaging.Point` redondeando los valores del `Aspose.Imaging.PointF` al siguiente entero mayor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `Aspose.Imaging.PointF` a convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Convierte el `Aspose.Imaging.PointF` especificado a un objeto `Aspose.Imaging.Point` redondeando los valores del `Aspose.Imaging.Point` al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `Aspose.Imaging.PointF` a convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Convierte el `Aspose.Imaging.PointF` especificado a un `Aspose.Imaging.Point` truncando los valores del `Aspose.Imaging.Point`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `Aspose.Imaging.PointF` a convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Traslada un `Aspose.Imaging.Point` mediante un `Aspose.Imaging.Size` dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` a trasladar. |
| size | [Size](../../com.aspose.imaging/size) | Un `Aspose.Imaging.Size` que especifica el par de números que se sumarán a las coordenadas de `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Traslada un `Aspose.Imaging.Point` mediante el negativo de un `Aspose.Imaging.Size` dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` a trasladar. |
| size | [Size](../../com.aspose.imaging/size) | Un `Aspose.Imaging.Size` que especifica el par de números que se restarán de las coordenadas de `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Compara dos objetos `Aspose.Imaging.Point`. El resultado indica si los valores de las propiedades `Aspose.Imaging.Point.X` y `Aspose.Imaging.Point.Y` de los dos objetos `Aspose.Imaging.Point` son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Un primer `Aspose.Imaging.Point` para comparar. |
| point2 | [Point](../../com.aspose.imaging/point) | Un segundo `Aspose.Imaging.Point` para comparar. |

**Returns:**
boolean - Verdadero si los valores `Aspose.Imaging.Point.X` y `Aspose.Imaging.Point.Y` de `point1` y `point2` son iguales; de lo contrario, falso.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Compara dos objetos `Aspose.Imaging.Point`. El resultado indica si los valores de la propiedad `Aspose.Imaging.Point.X` o `Aspose.Imaging.Point.Y` de los dos objetos `Aspose.Imaging.Point` son desiguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Un primer `Aspose.Imaging.Point` para comparar. |
| point2 | [Point](../../com.aspose.imaging/point) | Un segundo `Aspose.Imaging.Point` para comparar. |

**Returns:**
boolean - Verdadero si los valores de cualquiera de las propiedades `Aspose.Imaging.Point.X` o `Aspose.Imaging.Point.Y` de `point1` y `point2` difieren; de lo contrario, falso.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Convierte la estructura `Aspose.Imaging.Point` especificada a una estructura `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` a convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Convierte la estructura `Point` especificada a la estructura `PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Point` a convertir. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Descompone un objeto Point empaquetado en un objeto long para obtener los valores int X e Y por separado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| packedPoint | long | El objeto Point empaquetado en un valor long. |
| x | int[] | El extraído del valor X del Point empaquetado. |
| y | int[] | El extraído del valor Y del Point empaquetado. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si este `Aspose.Imaging.Point` está vacío.

**Returns:**
boolean - Verdadero si tanto `Aspose.Imaging.Point.X` como `Aspose.Imaging.Point.Y` son 0; de lo contrario, falso.
### getX() {#getX--}
```
public int getX()
```


Obtiene o establece la coordenada x de este `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtiene o establece la coordenada x de este `Aspose.Imaging.Point`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getY() {#getY--}
```
public int getY()
```


Obtiene o establece la coordenada y de este `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtiene o establece la coordenada y de este `Aspose.Imaging.Point`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Traslada este `Aspose.Imaging.Point` mediante el `Aspose.Imaging.Point` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` usado para desplazar este `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Traslada este `Aspose.Imaging.Point` mediante la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | int | La cantidad para desplazar la coordenada x. |
| dy | int | La cantidad para desplazar la coordenada y. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Especifica si este `Aspose.Imaging.Point` contiene las mismas coordenadas que el `System.Object` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para probar. |

**Returns:**
boolean - Verdadero si `obj` es un `Aspose.Imaging.Point` y tiene las mismas coordenadas que este `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para este `Aspose.Imaging.Point`.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### toLong() {#toLong--}
```
public final long toLong()
```


Convierte este Point a un único valor long, que contiene las coordenadas X e Y en los bits altos y bajos.

**Returns:**
long - El objeto Point empaquetado en un valor long.
### toString() {#toString--}
```
public String toString()
```


Convierte este `Aspose.Imaging.Point` a una cadena legible por humanos.

**Returns:**
java.lang.String - Un `System.String` que representa esta instancia.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
