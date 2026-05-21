---
title: "LinearGradientBrushBase"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un pincel con capacidades de degradado y propiedades apropiadas."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Representa un `Brush` con capacidades de degradado y propiedades apropiadas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRectangle()](#getRectangle--) | Obtiene una región rectangular que define los puntos inicial y final del degradado. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Establece una región rectangular que define los puntos inicial y final del degradado. |
| [getAngle()](#getAngle--) | Obtiene el ángulo del degradado. |
| [setAngle(float value)](#setAngle-float-) | Establece el ángulo del degradado. |
| [isAngleScalable()](#isAngleScalable--) | Obtiene un valor que indica si `LinearGradientBrushBase.Angle` se modifica durante transformaciones con este `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Establece un valor que indica si `LinearGradientBrushBase.Angle` se modifica durante transformaciones con este `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtiene un valor que indica si la corrección gamma está habilitada para este `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Establece un valor que indica si la corrección gamma está habilitada para este `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtiene una región rectangular que define los puntos inicial y final del degradado.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Establece una región rectangular que define los puntos inicial y final del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura `com.aspose.imaging.RectangleF` que especifica los puntos inicial y final del degradado. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Obtiene el ángulo del degradado.

**Returns:**
float - El ángulo del degradado.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Establece el ángulo del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El ángulo del degradado. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Obtiene un valor que indica si `LinearGradientBrushBase.Angle` se modifica durante transformaciones con este `LinearGradientBrushBase`.

**Returns:**
boolean - `true` si `LinearGradientBrushBase.Angle` se modifica durante transformaciones con este `LinearGradientBrushBase`; de lo contrario, `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Establece un valor que indica si `LinearGradientBrushBase.Angle` se modifica durante transformaciones con este `LinearGradientBrushBase`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si `LinearGradientBrushBase.Angle` se modifica durante transformaciones con este `LinearGradientBrushBase`; de lo contrario, `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtiene un valor que indica si la corrección gamma está habilitada para este `LinearGradientBrushBase`.

**Returns:**
boolean - El valor es true si la corrección gamma está habilitada para este `LinearGradientBrushBase`; de lo contrario, false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Establece un valor que indica si la corrección gamma está habilitada para este `LinearGradientBrushBase`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | El valor es true si la corrección gamma está habilitada para este `LinearGradientBrushBase`; de lo contrario, false. |

