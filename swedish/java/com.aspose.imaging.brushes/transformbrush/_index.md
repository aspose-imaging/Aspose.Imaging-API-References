---
title: "TransformBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "En Brush med transformmöjligheter."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

En `Brush` med transformfunktioner.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger en `Aspose.Imaging.WrapMode`-enumeration som indikerar omslagsläget för detta `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger en `Aspose.Imaging.WrapMode`-enumeration som indikerar omslagsläget för detta `TransformBrush`. |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av `Aspose.Imaging.Matrix` som definierar en lokal geometrisk transform för detta `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Hämtar eller anger en kopia av `Aspose.Imaging.Matrix` som definierar en lokal geometrisk transform för detta `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. |
| [resetTransform()](#resetTransform--) | Återställer egenskapen `TransformBrush.Transform` till identitet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplicerar `Aspose.Imaging.Matrix` som representerar den lokala geometriska transformen för detta `LinearGradientBrush` med den angivna `Aspose.Imaging.Matrix` genom att föregå den angivna `Aspose.Imaging.Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplicerar `Aspose.Imaging.Matrix` som representerar den lokala geometriska transformen för detta `LinearGradientBrush` med den angivna `Aspose.Imaging.Matrix` i den angivna ordningen. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformen med de angivna mängderna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformen med de angivna mängderna i den angivna ordningen. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roterar den lokala geometriska transformen med den angivna mängden. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roterar den lokala geometriska transformen med den angivna mängden i den angivna ordningen. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger en `Aspose.Imaging.WrapMode`-enumeration som indikerar omslagsläget för detta `TransformBrush`.

**Returns:**
int - En `Aspose.Imaging.WrapMode` som specificerar hur fyllningar ritade med denna `TransformBrush` upprepas.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger en `Aspose.Imaging.WrapMode`-enumeration som indikerar omslagsläget för detta `TransformBrush`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar eller anger en kopia av `Aspose.Imaging.Matrix` som definierar en lokal geometrisk transform för detta `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Hämtar eller anger en kopia av `Aspose.Imaging.Matrix` som definierar en lokal geometrisk transform för detta `TransformBrush`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egendomen introduceras för bakåtkompatibilitet med GDI+.

Värde: `True` om transformationen har ändrats; annars `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Återställer egenskapen `TransformBrush.Transform` till identitet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar `Aspose.Imaging.Matrix` som representerar den lokala geometriska transformen för detta `LinearGradientBrush` med den angivna `Aspose.Imaging.Matrix` genom att föregå den angivna `Aspose.Imaging.Matrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Den `Aspose.Imaging.Matrix` som ska multipliceras med den geometriska transformen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar `Aspose.Imaging.Matrix` som representerar den lokala geometriska transformen för detta `LinearGradientBrush` med den angivna `Aspose.Imaging.Matrix` i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Den `Aspose.Imaging.Matrix` som ska multipliceras med den geometriska transformen. |
| order | int | En `Aspose.Imaging.MatrixOrder` som specificerar i vilken ordning de två matriserna ska multipliceras. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod förhandslägger översättningen på transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för förflyttningen i x. |
| dy | float | Värdet för förflyttningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för förflyttningen i x. |
| dy | float | Värdet för förflyttningen i y. |
| order | int | Den ordning (före eller efter) i vilken förflyttningen ska tillämpas. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformen med de angivna mängderna. Denna metod förhandslägger skalningsmatrisen på transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Mängden att skala transformen i x-axelns riktning. |
| sy | float | Mängden att skala transformen i y-axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformen med de angivna mängderna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Mängden att skala transformen i x-axelns riktning. |
| sy | float | Mängden att skala transformen i y-axelns riktning. |
| order | int | En `Aspose.Imaging.MatrixOrder` som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformen med den angivna mängden. Denna metod förhandslägger rotationen på transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roterar den lokala geometriska transformen med den angivna mängden i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |
| order | int | En `Aspose.Imaging.MatrixOrder` som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

