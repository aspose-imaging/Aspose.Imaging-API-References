---
title: "SizeF"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo."
type: docs
weight: 105
url: /es/java/com.aspose.imaging/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.imaging.SizeF-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.SizeF` a partir del `Aspose.Imaging.SizeF` especificado. |
| [SizeF(PointF point)](#SizeF-com.aspose.imaging.PointF-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.SizeF` a partir del `Aspose.Imaging.PointF` especificado. |
| [SizeF(float width, float height)](#SizeF-float-float-) | Inicializa una nueva instancia de la estructura `Aspose.Imaging.SizeF` a partir de las dimensiones especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura `Aspose.Imaging.SizeF` que tiene los valores `Aspose.Imaging.SizeF.Width` y `Aspose.Imaging.SizeF.Height` establecidos en cero. |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Suma el ancho y la altura de una estructura `Aspose.Imaging.SizeF` al ancho y la altura de otra estructura `Aspose.Imaging.SizeF`. |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Resta el ancho y la altura de una estructura `Aspose.Imaging.SizeF` del ancho y la altura de otra estructura `Aspose.Imaging.SizeF`. |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Comprueba si dos estructuras `Aspose.Imaging.SizeF` son iguales. |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Comprueba si dos estructuras `Aspose.Imaging.SizeF` son diferentes. |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.imaging.SizeF-) | Convierte el `Aspose.Imaging.SizeF` especificado a un `Aspose.Imaging.PointF`. |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Suma el ancho y la altura de una estructura `Aspose.Imaging.SizeF` al ancho y la altura de otra estructura `Aspose.Imaging.SizeF`. |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Resta el ancho y la altura de una estructura `Aspose.Imaging.SizeF` del ancho y la altura de otra estructura `Aspose.Imaging.SizeF`. |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) |  |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este `Aspose.Imaging.SizeF` tiene ancho y altura cero. |
| [getWidth()](#getWidth--) | Obtiene o establece el componente horizontal de este `Aspose.Imaging.SizeF`. |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece el componente horizontal de este `Aspose.Imaging.SizeF`. |
| [getHeight()](#getHeight--) | Obtiene o establece el componente vertical de este `Aspose.Imaging.SizeF`. |
| [setHeight(float value)](#setHeight-float-) | Obtiene o establece el componente vertical de este `Aspose.Imaging.SizeF`. |
| [toPointF()](#toPointF--) | Convierte un `Aspose.Imaging.SizeF` a un `Aspose.Imaging.PointF`. |
| [toSize()](#toSize--) | Convierte un `Aspose.Imaging.SizeF` a una estructura `Aspose.Imaging.Size` con valores de tamaño truncados. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si el objeto especificado es un `Aspose.Imaging.SizeF` con las mismas dimensiones que este `Aspose.Imaging.SizeF`. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta estructura `Aspose.Imaging.Size`. |
| [toString()](#toString--) | Crea una cadena legible por humanos que representa este `Aspose.Imaging.SizeF`. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.imaging.SizeF-) |  |
| [Clone()](#Clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.imaging.SizeF-}
```
public SizeF(SizeF size)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.SizeF` a partir del `Aspose.Imaging.SizeF` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | El `Aspose.Imaging.SizeF` del cual crear el nuevo `Aspose.Imaging.SizeF`. |

### SizeF(PointF point) {#SizeF-com.aspose.imaging.PointF-}
```
public SizeF(PointF point)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.SizeF` a partir del `Aspose.Imaging.PointF` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `Aspose.Imaging.PointF` del cual inicializar este `Aspose.Imaging.SizeF`. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Inicializa una nueva instancia de la estructura `Aspose.Imaging.SizeF` a partir de las dimensiones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | float | El componente de ancho del nuevo `Aspose.Imaging.SizeF`. |
| height | float | El componente de altura del nuevo `Aspose.Imaging.SizeF`. |

### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


Obtiene una nueva instancia de la estructura `Aspose.Imaging.SizeF` que tiene los valores `Aspose.Imaging.SizeF.Width` y `Aspose.Imaging.SizeF.Height` establecidos en cero.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


Suma el ancho y la altura de una estructura `Aspose.Imaging.SizeF` al ancho y la altura de otra estructura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | El primer `Aspose.Imaging.SizeF` a añadir. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | El segundo `Aspose.Imaging.SizeF` a agregar. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


Resta el ancho y la altura de una estructura `Aspose.Imaging.SizeF` del ancho y la altura de otra estructura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | El `Aspose.Imaging.SizeF` en el lado izquierdo del operador de resta. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | El `Aspose.Imaging.SizeF` en el lado derecho del operador de resta. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` that is the result of the subtraction operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


Comprueba si dos estructuras `Aspose.Imaging.SizeF` son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` en el lado izquierdo del operador de igualdad. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` en el lado derecho del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si `size1` y `size2` tienen ancho y alto iguales; de lo contrario, false.
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


Comprueba si dos estructuras `Aspose.Imaging.SizeF` son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` en el lado izquierdo del operador de desigualdad. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` en el lado derecho del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si `size1` y `size2` difieren ya sea en ancho o en alto; false si `size1` y `size2` son iguales.
### to_PointF(SizeF size) {#to-PointF-com.aspose.imaging.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


Convierte el `Aspose.Imaging.SizeF` especificado a un `Aspose.Imaging.PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` a convertir |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `Aspose.Imaging.PointF` structure to which this operator converts.
### add(SizeF size1, SizeF size2) {#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


Suma el ancho y la altura de una estructura `Aspose.Imaging.SizeF` al ancho y la altura de otra estructura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | El primer `Aspose.Imaging.SizeF` a añadir. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | El segundo `Aspose.Imaging.SizeF` a agregar. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


Resta el ancho y la altura de una estructura `Aspose.Imaging.SizeF` del ancho y la altura de otra estructura `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` en el lado izquierdo del operador de resta. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | La estructura `Aspose.Imaging.SizeF` en el lado derecho del operador de resta. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` that is a result of the subtraction operation.
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.imaging/sizef) |  |
| obj2 | [SizeF](../../com.aspose.imaging/sizef) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si este `Aspose.Imaging.SizeF` tiene ancho y altura cero.

**Returns:**
boolean - Esta propiedad devuelve true cuando este `Aspose.Imaging.SizeF` tiene tanto ancho como alto cero; de lo contrario, false.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtiene o establece el componente horizontal de este `Aspose.Imaging.SizeF`.

**Returns:**
float - El componente horizontal de este `Aspose.Imaging.SizeF`, típicamente medido en píxeles.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtiene o establece el componente horizontal de este `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtiene o establece el componente vertical de este `Aspose.Imaging.SizeF`.

**Returns:**
float - El componente vertical de este `Aspose.Imaging.SizeF`, típicamente medido en píxeles.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtiene o establece el componente vertical de este `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### toPointF() {#toPointF--}
```
public PointF toPointF()
```


Convierte un `Aspose.Imaging.SizeF` a un `Aspose.Imaging.PointF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns a `Aspose.Imaging.PointF` structure.
### toSize() {#toSize--}
```
public Size toSize()
```


Convierte un `Aspose.Imaging.SizeF` a una estructura `Aspose.Imaging.Size` con valores de tamaño truncados.

**Returns:**
[Size](../../com.aspose.imaging/size) - Returns a `Aspose.Imaging.Size` structure.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si el objeto especificado es un `Aspose.Imaging.SizeF` con las mismas dimensiones que este `Aspose.Imaging.SizeF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para probar. |

**Returns:**
boolean - Este método devuelve true si `obj` es un `Aspose.Imaging.SizeF` y tiene el mismo ancho y alto que este `Aspose.Imaging.SizeF`; de lo contrario, false.
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


Crea una cadena legible por humanos que representa este `Aspose.Imaging.SizeF`.

**Returns:**
java.lang.String - Una cadena que representa este `Aspose.Imaging.SizeF`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.imaging.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.imaging/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
