---
title: "TransformBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Un Brush con capacidades de transformación."
type: docs
weight: 19
url: /es/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

Un `Brush` con capacidades de transformación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece una enumeración `Aspose.Imaging.WrapMode` que indica el modo de envoltura para este `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece una enumeración `Aspose.Imaging.WrapMode` que indica el modo de envoltura para este `TransformBrush`. |
| [getTransform()](#getTransform--) | Obtiene o establece una copia `Aspose.Imaging.Matrix` que define una transformación geométrica local para este `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Obtiene o establece una copia `Aspose.Imaging.Matrix` que define una transformación geométrica local para este `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. |
| [resetTransform()](#resetTransform--) | Restablece la propiedad `TransformBrush.Transform` a la identidad. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplica la `Aspose.Imaging.Matrix` que representa la transformación geométrica local de este `LinearGradientBrush` por la `Aspose.Imaging.Matrix` especificada, anteponiendo la `Aspose.Imaging.Matrix` especificada. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplica la `Aspose.Imaging.Matrix` que representa la transformación geométrica local de este `LinearGradientBrush` por la `Aspose.Imaging.Matrix` especificada en el orden especificado. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por las cantidades especificadas. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por las cantidades especificadas en el orden especificado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local por la cantidad especificada. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local por la cantidad especificada en el orden especificado. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece una enumeración `Aspose.Imaging.WrapMode` que indica el modo de envoltura para este `TransformBrush`.

**Returns:**
int - Un `Aspose.Imaging.WrapMode` que especifica cómo se repiten los rellenos dibujados con este `TransformBrush`.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece una enumeración `Aspose.Imaging.WrapMode` que indica el modo de envoltura para este `TransformBrush`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene o establece una copia `Aspose.Imaging.Matrix` que define una transformación geométrica local para este `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Obtiene o establece una copia `Aspose.Imaging.Matrix` que define una transformación geométrica local para este `TransformBrush`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+.

Valor: `True` si la transformación fue modificada; de lo contrario, `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Restablece la propiedad `TransformBrush.Transform` a la identidad.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la `Aspose.Imaging.Matrix` que representa la transformación geométrica local de este `LinearGradientBrush` por la `Aspose.Imaging.Matrix` especificada, anteponiendo la `Aspose.Imaging.Matrix` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `Aspose.Imaging.Matrix` por la cual multiplicar la transformación geométrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la `Aspose.Imaging.Matrix` que representa la transformación geométrica local de este `LinearGradientBrush` por la `Aspose.Imaging.Matrix` especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `Aspose.Imaging.Matrix` por la cual multiplicar la transformación geométrica. |
| order | int | Un `Aspose.Imaging.MatrixOrder` que especifica en qué orden multiplicar las dos matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| order | int | El orden (anteponer o anexar) en el que aplicar la traslación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por las cantidades especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |
| order | int | Un `Aspose.Imaging.MatrixOrder` que especifica si se debe añadir al final o anteponer la matriz de escala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local por la cantidad especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| order | int | Un `Aspose.Imaging.MatrixOrder` que especifica si se debe añadir al final o anteponer la matriz de rotación. |

