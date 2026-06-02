---
title: "Tamaño"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el tamaño."
type: docs
weight: 104
url: /es/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Representa el tamaño.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.Size` a partir del `Aspose.Imaging.Point` especificado. |
| [Size(int width, int height)](#Size-int-int-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.Size` a partir de las dimensiones especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `Aspose.Imaging.Size` que tiene los valores `Aspose.Imaging.Size.Width` y `Aspose.Imaging.Size.Height` establecidos en cero. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Convierte el `Aspose.Imaging.Size` especificado a un `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Suma el ancho y alto de una estructura `Aspose.Imaging.Size` al ancho y alto de otra estructura `Aspose.Imaging.Size`. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Resta el ancho y alto de una estructura `Aspose.Imaging.Size` del ancho y alto de otra estructura `Aspose.Imaging.Size`. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Comprueba si dos estructuras `Aspose.Imaging.Size` son iguales. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Comprueba si dos estructuras `Aspose.Imaging.Size` son diferentes. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Convierte el `Aspose.Imaging.Size` especificado a un `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Suma el ancho y alto de una estructura `Aspose.Imaging.Size` al ancho y alto de otra estructura `Aspose.Imaging.Size`. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Convierte la estructura `Aspose.Imaging.SizeF` especificada a una estructura `Aspose.Imaging.Size` redondeando los valores de la estructura `Aspose.Imaging.Size` al siguiente entero superior. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Resta el ancho y alto de una estructura `Aspose.Imaging.Size` del ancho y alto de otra estructura `Aspose.Imaging.Size`. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Convierte la estructura `Aspose.Imaging.SizeF` especificada a una estructura `Aspose.Imaging.Size` truncando los valores de la estructura `Aspose.Imaging.SizeF` al siguiente entero inferior. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Convierte la estructura `Aspose.Imaging.SizeF` especificada a una estructura `Aspose.Imaging.Size` redondeando los valores de la estructura `Aspose.Imaging.SizeF` al entero más cercano. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este `Aspose.Imaging.Size` tiene ancho y alto de 0. |
| [getWidth()](#getWidth--) | Obtiene o establece el componente horizontal de este `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece el componente horizontal de este `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | Obtiene o establece el componente vertical de este `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece el componente vertical de este `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si el objeto especificado es un `Aspose.Imaging.Size` con las mismas dimensiones que este `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta estructura `Aspose.Imaging.Size`. |
| [toString()](#toString--) | Crea una cadena legible que representa este `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.Size` a partir del `Aspose.Imaging.Point` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | El `Aspose.Imaging.Point` desde el cual inicializar este `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.Size` a partir de las dimensiones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El componente de ancho del nuevo `Aspose.Imaging.Size`. |
| height | int | El componente de altura del nuevo `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Obtiene una nueva instancia de la estructura `Aspose.Imaging.Size` que tiene los valores `Aspose.Imaging.Size.Width` y `Aspose.Imaging.Size.Height` establecidos en cero.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Convierte el `Aspose.Imaging.Size` especificado a un `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | El `Aspose.Imaging.Size` a convertir. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Suma el ancho y alto de una estructura `Aspose.Imaging.Size` al ancho y alto de otra estructura `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | El primer `Aspose.Imaging.Size` a añadir. |
| size2 | [Size](../../com.aspose.imaging/size) | El segundo `Aspose.Imaging.Size` a añadir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Resta el ancho y alto de una estructura `Aspose.Imaging.Size` del ancho y alto de otra estructura `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado izquierdo del operador de resta. |
| size2 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado derecho del operador de resta. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Comprueba si dos estructuras `Aspose.Imaging.Size` son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado izquierdo del operador de igualdad. |
| size2 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado derecho del operador de igualdad. |

**Returns:**
boolean - Verdadero si `size1` y `size2` tienen el mismo ancho y altura; de lo contrario, falso.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Comprueba si dos estructuras `Aspose.Imaging.Size` son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado izquierdo del operador de desigualdad. |
| size2 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado derecho del operador de desigualdad. |

**Returns:**
boolean - Verdadero si `size1` y `size2` difieren en ancho o altura; falso si `size1` y `size2` son iguales.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Convierte el `Aspose.Imaging.Size` especificado a un `Aspose.Imaging.Point`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | El `Aspose.Imaging.Size` a convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Suma el ancho y alto de una estructura `Aspose.Imaging.Size` al ancho y alto de otra estructura `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | El primer `Aspose.Imaging.Size` a añadir. |
| size2 | [Size](../../com.aspose.imaging/size) | El segundo `Aspose.Imaging.Size` a añadir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Convierte la estructura `Aspose.Imaging.SizeF` especificada a una estructura `Aspose.Imaging.Size` redondeando los valores de la estructura `Aspose.Imaging.Size` al siguiente entero superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` a convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Resta el ancho y alto de una estructura `Aspose.Imaging.Size` del ancho y alto de otra estructura `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado izquierdo del operador de resta. |
| size2 | [Size](../../com.aspose.imaging/size) | La estructura `Aspose.Imaging.Size` en el lado derecho del operador de resta. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Convierte la estructura `Aspose.Imaging.SizeF` especificada a una estructura `Aspose.Imaging.Size` truncando los valores de la estructura `Aspose.Imaging.SizeF` al siguiente entero inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` a convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Convierte la estructura `Aspose.Imaging.SizeF` especificada a una estructura `Aspose.Imaging.Size` redondeando los valores de la estructura `Aspose.Imaging.SizeF` al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` a convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si este `Aspose.Imaging.Size` tiene ancho y alto de 0.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece el componente horizontal de este `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece el componente horizontal de este `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece el componente vertical de este `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece el componente vertical de este `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si el objeto especificado es un `Aspose.Imaging.Size` con las mismas dimensiones que este `Aspose.Imaging.Size`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para probar. |

**Returns:**
boolean - Verdadero si `obj` es un `Aspose.Imaging.Size` y tiene el mismo ancho y altura que este `Aspose.Imaging.Size`; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta estructura `Aspose.Imaging.Size`.

**Returns:**
int - Un valor entero que especifica un valor hash para esta estructura `Aspose.Imaging.Size`.
### toString() {#toString--}
```
public String toString()
```


Crea una cadena legible que representa este `Aspose.Imaging.Size`.

**Returns:**
java.lang.String - Una cadena que representa este `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
