---
title: "EmfPlusPathPointTypeRle"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPathPointTypeRle especifica valores de tipo asociados a puntos en una ruta gráfica usando compresión RLE."
type: docs
weight: 62
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

El objeto EmfPlusPathPointTypeRle especifica valores de tipo asociados con puntos en una ruta gráfica usando compresión RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 bit): Si está establecido, los puntos de la ruta están en una curva Bézier. Si está despejado, los puntos de la ruta están en una línea gráfica. RunCount (6 bits): El recuento de ejecución, que es el número de puntos de la ruta que se asociarán con el tipo en el campo PointType. PointType (1 byte): Un objeto EmfPlusPathPointType (sección 2.2.2.31) que especifica el tipo a asociar con los puntos de la ruta.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getData()](#getData--) | Obtiene o establece los datos. |
| [setData(int value)](#setData-int-) | Obtiene o establece los datos. |
| [getBezier()](#getBezier--) | Obtiene o establece un valor que indica si este `EmfPlusPathPointTypeRle` es Bézier. |
| [setBezier(boolean value)](#setBezier-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusPathPointTypeRle` es Bézier. |
| [getRunCount()](#getRunCount--) | Obtiene o establece el recuento de ejecución. |
| [setRunCount(byte value)](#setRunCount-byte-) | Obtiene o establece el recuento de ejecución. |
| [getPointType()](#getPointType--) | Obtiene o establece el tipo del punto. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Obtiene o establece el tipo del punto. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Obtiene o establece los datos.

Valor: Los datos.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Obtiene o establece los datos.

Valor: Los datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Obtiene o establece un valor que indica si este `EmfPlusPathPointTypeRle` es Bézier. Si está establecido, los puntos de la ruta están en una curva Bézier. Si está despejado, los puntos de la ruta están en una línea gráfica.

Valor: `true` si es Bézier; de lo contrario, `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusPathPointTypeRle` es Bézier. Si está establecido, los puntos de la ruta están en una curva Bézier. Si está despejado, los puntos de la ruta están en una línea gráfica.

Valor: `true` si es Bézier; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Obtiene o establece el recuento de ejecución. RunCount (6 bits): El recuento de ejecución, que es el número de puntos de la ruta que se asociarán con el tipo en el campo PointType.

Valor: El recuento de ejecución.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Obtiene o establece el recuento de ejecución. RunCount (6 bits): El recuento de ejecución, que es el número de puntos de la ruta que se asociarán con el tipo en el campo PointType.

Valor: El recuento de ejecución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Obtiene o establece el tipo del punto. PointType (1 byte): Un objeto EmfPlusPathPointType (sección 2.2.2.31) que especifica el tipo a asociar con los puntos de la ruta.

Valor: El tipo del punto.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Obtiene o establece el tipo del punto. PointType (1 byte): Un objeto EmfPlusPathPointType (sección 2.2.2.31) que especifica el tipo a asociar con los puntos de la ruta.

Valor: El tipo del punto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

