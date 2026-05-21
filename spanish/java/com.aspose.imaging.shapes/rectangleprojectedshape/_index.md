---
title: "RectangleProjectedShape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una forma que se proyecta sobre un rectángulo girado a una orientación particular."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Representa una forma que se proyecta sobre un rectángulo girado a una orientación particular. Se especifica mediante cuatro puntos que pueden rotarse en el espacio manteniendo la misma longitud de los bordes y 90 grados entre los bordes adyacentes.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Obtiene el punto superior izquierdo del rectángulo. |
| [getRightTop()](#getRightTop--) | Obtiene el punto superior derecho del rectángulo. |
| [getLeftBottom()](#getLeftBottom--) | Obtiene el punto inferior izquierdo del rectángulo. |
| [getRightBottom()](#getRightBottom--) | Obtiene el punto inferior derecho del rectángulo. |
| [getCenter()](#getCenter--) | Obtiene el centro de la forma. |
| [getBounds()](#getBounds--) | Obtiene los límites del objeto. |
| [getRectangleWidth()](#getRectangleWidth--) | Obtiene el ancho del rectángulo. |
| [getRectangleHeight()](#getRectangleHeight--) | Obtiene la altura del rectángulo. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtiene los límites del objeto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Aplica la transformación especificada a la forma. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Obtiene el punto superior izquierdo del rectángulo.

Valor: El punto superior izquierdo del rectángulo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Obtiene el punto superior derecho del rectángulo.

Valor: El punto superior derecho del rectángulo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Obtiene el punto inferior izquierdo del rectángulo.

Valor: El punto inferior izquierdo del rectángulo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Obtiene el punto inferior derecho del rectángulo.

Valor: El punto inferior derecho del rectángulo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtiene el centro de la forma.

Valor: El centro de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene los límites del objeto.

Valor: Los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Obtiene el ancho del rectángulo.

Valor: El ancho del rectángulo.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Obtiene la altura del rectángulo.

Valor: La altura del rectángulo.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtiene un valor que indica si la forma tiene segmentos.

Valor: `True` si la forma tiene segmentos; de lo contrario, `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Aplica la transformación especificada a la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformación a aplicar. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `Object` especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
