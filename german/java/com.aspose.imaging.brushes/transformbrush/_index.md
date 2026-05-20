---
title: "TransformBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Ein Brush mit Transformationsfähigkeiten."
type: docs
weight: 19
url: /de/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

Ein `Brush` mit Transformationsfähigkeiten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt eine `Aspose.Imaging.WrapMode`-Aufzählung, die den Wrap-Modus für diesen `TransformBrush` angibt. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine `Aspose.Imaging.WrapMode`-Aufzählung, die den Wrap-Modus für diesen `TransformBrush` angibt. |
| [getTransform()](#getTransform--) | Liest oder setzt eine Kopie von `Aspose.Imaging.Matrix`, die eine lokale geometrische Transformation für diesen `TransformBrush` definiert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Liest oder setzt eine Kopie von `Aspose.Imaging.Matrix`, die eine lokale geometrische Transformation für diesen `TransformBrush` definiert. |
| [isTransformChanged()](#isTransformChanged--) | Liest einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. |
| [resetTransform()](#resetTransform--) | Setzt die `TransformBrush.Transform`-Eigenschaft auf die Identität zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multipliziert die `Aspose.Imaging.Matrix`, die die lokale geometrische Transformation dieses `LinearGradientBrush` darstellt, mit der angegebenen `Aspose.Imaging.Matrix`, indem die angegebene `Aspose.Imaging.Matrix` vorangestellt wird. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multipliziert die `Aspose.Imaging.Matrix`, die die lokale geometrische Transformation dieses `LinearGradientBrush` darstellt, mit der angegebenen `Aspose.Imaging.Matrix` in der angegebenen Reihenfolge. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder setzt eine `Aspose.Imaging.WrapMode`-Aufzählung, die den Wrap-Modus für diesen `TransformBrush` angibt.

**Returns:**
int - Ein `Aspose.Imaging.WrapMode`, der angibt, wie mit diesem `TransformBrush` gezeichnete Füllungen gekachelt werden.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder setzt eine `Aspose.Imaging.WrapMode`-Aufzählung, die den Wrap-Modus für diesen `TransformBrush` angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liest oder setzt eine Kopie von `Aspose.Imaging.Matrix`, die eine lokale geometrische Transformation für diesen `TransformBrush` definiert.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Liest oder setzt eine Kopie von `Aspose.Imaging.Matrix`, die eine lokale geometrische Transformation für diesen `TransformBrush` definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Gibt einen Wert zurück, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder das Aufrufen einer der Methoden, die die Transformationsmatrix ändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt.

Wert: `True`, wenn die Transformation geändert wurde; andernfalls `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Setzt die `TransformBrush.Transform`-Eigenschaft auf die Identität zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die `Aspose.Imaging.Matrix`, die die lokale geometrische Transformation dieses `LinearGradientBrush` darstellt, mit der angegebenen `Aspose.Imaging.Matrix`, indem die angegebene `Aspose.Imaging.Matrix` vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die `Aspose.Imaging.Matrix`, mit der die geometrische Transformation multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die `Aspose.Imaging.Matrix`, die die lokale geometrische Transformation dieses `LinearGradientBrush` darstellt, mit der angegebenen `Aspose.Imaging.Matrix` in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die `Aspose.Imaging.Matrix`, mit der die geometrische Transformation multipliziert wird. |
| order | int | Ein `Aspose.Imaging.MatrixOrder`, der angibt, in welcher Reihenfolge die beiden Matrizen multipliziert werden. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |
| order | int | Die Reihenfolge (voranstellen oder anhängen), in der die Translation angewendet wird. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungsmatrix vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| order | int | Ein `Aspose.Imaging.MatrixOrder`, der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt werden soll. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation vor der Transformation ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel. |
| order | int | Ein `Aspose.Imaging.MatrixOrder`, der angibt, ob die Rotationsmatrix angehängt oder vorangestellt werden soll. |

