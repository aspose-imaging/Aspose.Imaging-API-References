---
title: "PointF"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un par ordenado de coordenadas x e y de punto flotante que define un punto en un plano bidimensional."
type: docs
weight: 87
url: /es/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Representa un par ordenado de coordenadas x e y de punto flotante que define un punto en un plano bidimensional.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Inicializa una nueva instancia de la estructura `com.aspose.imaging.PointF` con las coordenadas especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `com.aspose.imaging.PointF` que tiene los valores `com.aspose.imaging.PointF.X` y `com.aspose.imaging.PointF.Y` establecidos en cero. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Traslada un `com.aspose.imaging.PointF` mediante un `com.aspose.imaging.Size` dado. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Traslada un `com.aspose.imaging.PointF` mediante el negativo de un `com.aspose.imaging.Size` dado. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Traslada el `com.aspose.imaging.PointF` mediante el `com.aspose.imaging.SizeF` especificado. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Traslada un `com.aspose.imaging.PointF` mediante el negativo de un `com.aspose.imaging.SizeF` especificado. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Compara dos estructuras `com.aspose.imaging.PointF`. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Determina si las coordenadas de los puntos especificados no son iguales. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Traslada un `com.aspose.imaging.PointF` dado mediante el `com.aspose.imaging.Size` especificado. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Traslada un `com.aspose.imaging.PointF` mediante el negativo de un tamaño especificado. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Traslada un `com.aspose.imaging.PointF` dado mediante un `com.aspose.imaging.SizeF` especificado. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Traslada un `com.aspose.imaging.PointF` mediante el negativo de un tamaño especificado. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este `com.aspose.imaging.PointF` está vacío. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de este `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | Obtiene o establece la coordenada x de este `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de este `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | Obtiene o establece la coordenada y de este `com.aspose.imaging.PointF`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Especifica si este `com.aspose.imaging.PointF` contiene las mismas coordenadas que el `System.Object` especificado. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta estructura `com.aspose.imaging.PointF`. |
| [toString()](#toString--) | Convierte este `com.aspose.imaging.PointF` a una cadena legible por humanos. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Inicializa una nueva instancia de la estructura `com.aspose.imaging.PointF` con las coordenadas especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La posición horizontal del punto. |
| y | float | La posición vertical del punto. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Obtiene una nueva instancia de la estructura `com.aspose.imaging.PointF` que tiene los valores `com.aspose.imaging.PointF.X` y `com.aspose.imaging.PointF.Y` establecidos en cero.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Traslada un `com.aspose.imaging.PointF` mediante un `com.aspose.imaging.Size` dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` que especifica el par de números que se deben añadir a las coordenadas de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Traslada un `com.aspose.imaging.PointF` mediante el negativo de un `com.aspose.imaging.Size` dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` a traducir. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` que especifica los números que se deben restar de las coordenadas x e y del `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Traslada el `com.aspose.imaging.PointF` mediante el `com.aspose.imaging.SizeF` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [SizeF](../../com.aspose.imaging/sizef) | El `com.aspose.imaging.SizeF` que especifica los números que se deben añadir a las coordenadas x e y del `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Traslada un `com.aspose.imaging.PointF` mediante el negativo de un `com.aspose.imaging.SizeF` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [SizeF](../../com.aspose.imaging/sizef) | El `com.aspose.imaging.SizeF` que especifica los números que se deben restar de las coordenadas de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Compara dos estructuras `com.aspose.imaging.PointF`. El resultado indica si los valores de las propiedades `com.aspose.imaging.PointF.X` y `com.aspose.imaging.PointF.Y` de las dos estructuras `com.aspose.imaging.PointF` son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Un primer `com.aspose.imaging.PointF` para comparar. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Un segundo `com.aspose.imaging.PointF` para comparar. |

**Returns:**
boolean - Verdadero si los valores `com.aspose.imaging.PointF.X` y `com.aspose.imaging.PointF.Y` de las estructuras `com.aspose.imaging.PointF` primera y segunda son iguales; de lo contrario, falso.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Determina si las coordenadas de los puntos especificados no son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Un primer `com.aspose.imaging.PointF` para comparar. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Un segundo `com.aspose.imaging.PointF` para comparar. |

**Returns:**
boolean - Verdadero para indicar que los valores `com.aspose.imaging.PointF.X` y `com.aspose.imaging.PointF.Y` de `point1` y `point2` no son iguales; de lo contrario, falso.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Traslada un `com.aspose.imaging.PointF` dado mediante el `com.aspose.imaging.Size` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [Size](../../com.aspose.imaging/size) | El `com.aspose.imaging.Size` que especifica los números que se deben añadir a las coordenadas de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Traslada un `com.aspose.imaging.PointF` mediante el negativo de un tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [Size](../../com.aspose.imaging/size) | El `com.aspose.imaging.Size` que especifica los números que se deben restar de las coordenadas de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Traslada un `com.aspose.imaging.PointF` dado mediante un `com.aspose.imaging.SizeF` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [SizeF](../../com.aspose.imaging/sizef) | El `com.aspose.imaging.SizeF` que especifica los números que se deben añadir a las coordenadas de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Traslada un `com.aspose.imaging.PointF` mediante el negativo de un tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `com.aspose.imaging.PointF` a traducir. |
| size | [SizeF](../../com.aspose.imaging/sizef) | El `com.aspose.imaging.SizeF` que especifica los números que se deben restar de las coordenadas de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si este `com.aspose.imaging.PointF` está vacío.

**Returns:**
boolean - Verdadero si tanto `com.aspose.imaging.PointF.X` como `com.aspose.imaging.PointF.Y` son 0; de lo contrario, falso.
### getX() {#getX--}
```
public float getX()
```


Obtiene o establece la coordenada x de este `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtiene o establece la coordenada x de este `com.aspose.imaging.PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getY() {#getY--}
```
public float getY()
```


Obtiene o establece la coordenada y de este `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtiene o establece la coordenada y de este `com.aspose.imaging.PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Especifica si este `com.aspose.imaging.PointF` contiene las mismas coordenadas que el `System.Object` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para probar. |

**Returns:**
boolean - Este método devuelve verdadero si `obj` es un `com.aspose.imaging.PointF` y tiene las mismas coordenadas que este `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta estructura `com.aspose.imaging.PointF`.

**Returns:**
int - Un valor entero que especifica un valor hash para esta estructura `com.aspose.imaging.PointF`.
### toString() {#toString--}
```
public String toString()
```


Convierte este `com.aspose.imaging.PointF` a una cadena legible por humanos.

**Returns:**
java.lang.String - Una cadena que representa este `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
