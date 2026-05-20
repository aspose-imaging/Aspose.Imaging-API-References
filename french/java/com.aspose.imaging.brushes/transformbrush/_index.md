---
title: "TransformBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une brosse avec des capacités de transformation."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

Un `Brush` avec des capacités de transformation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit une énumération `Aspose.Imaging.WrapMode` qui indique le mode d'enroulement pour ce `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit une énumération `Aspose.Imaging.WrapMode` qui indique le mode d'enroulement pour ce `TransformBrush`. |
| [getTransform()](#getTransform--) | Obtient ou définit une copie `Aspose.Imaging.Matrix` qui définit une transformation géométrique locale pour ce `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Obtient ou définit une copie `Aspose.Imaging.Matrix` qui définit une transformation géométrique locale pour ce `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. |
| [resetTransform()](#resetTransform--) | Réinitialise la propriété `TransformBrush.Transform` à l'identité. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplie la `Aspose.Imaging.Matrix` qui représente la transformation géométrique locale de ce `LinearGradientBrush` par la `Aspose.Imaging.Matrix` spécifiée en préfixant la `Aspose.Imaging.Matrix` spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplie la `Aspose.Imaging.Matrix` qui représente la transformation géométrique locale de ce `LinearGradientBrush` par la `Aspose.Imaging.Matrix` spécifiée dans l'ordre spécifié. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale selon les dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Met à l'échelle la transformation géométrique locale selon les valeurs spécifiées. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Met à l'échelle la transformation géométrique locale selon les valeurs spécifiées dans l'ordre spécifié. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale selon la valeur spécifiée. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale selon la valeur spécifiée dans l'ordre spécifié. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit une énumération `Aspose.Imaging.WrapMode` qui indique le mode d'enroulement pour ce `TransformBrush`.

**Returns:**
int - Un `Aspose.Imaging.WrapMode` qui spécifie comment les remplissages dessinés avec ce `TransformBrush` sont disposés en mosaïque.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit une énumération `Aspose.Imaging.WrapMode` qui indique le mode d'enroulement pour ce `TransformBrush`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient ou définit une copie `Aspose.Imaging.Matrix` qui définit une transformation géométrique locale pour ce `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Obtient ou définit une copie `Aspose.Imaging.Matrix` qui définit une transformation géométrique locale pour ce `TransformBrush`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+.

Valeur : `True` si la transformation a été modifiée ; sinon, `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Réinitialise la propriété `TransformBrush.Transform` à l'identité.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie la `Aspose.Imaging.Matrix` qui représente la transformation géométrique locale de ce `LinearGradientBrush` par la `Aspose.Imaging.Matrix` spécifiée en préfixant la `Aspose.Imaging.Matrix` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `Aspose.Imaging.Matrix` par laquelle multiplier la transformation géométrique. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie la `Aspose.Imaging.Matrix` qui représente la transformation géométrique locale de ce `LinearGradientBrush` par la `Aspose.Imaging.Matrix` spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `Aspose.Imaging.Matrix` par laquelle multiplier la transformation géométrique. |
| ordre | int | Un `Aspose.Imaging.MatrixOrder` qui spécifie dans quel ordre multiplier les deux matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translater la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| ordre | int | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale selon les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Met à l'échelle la transformation géométrique locale selon les valeurs spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |
| ordre | int | Un `Aspose.Imaging.MatrixOrder` qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale selon la valeur spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale selon la valeur spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| ordre | int | Un `Aspose.Imaging.MatrixOrder` qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

