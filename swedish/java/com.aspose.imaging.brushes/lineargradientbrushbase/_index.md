---
title: "LinearGradientBrushBase"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en pensel med gradientfunktioner och lämpliga egenskaper."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Representerar en `Brush` med gradientfunktioner och lämpliga egenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRectangle()](#getRectangle--) | Hämtar ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Ställer in ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [getAngle()](#getAngle--) | Hämtar gradientvinkeln. |
| [setAngle(float value)](#setAngle-float-) | Ställer in gradientvinkeln. |
| [isAngleScalable()](#isAngleScalable--) | Hämtar ett värde som indikerar om `LinearGradientBrushBase.Angle` ändras under transformationer med denna `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Ställer in ett värde som indikerar om `LinearGradientBrushBase.Angle` ändras under transformationer med denna `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | Hämtar ett värde som indikerar om gamma‑korrektion är aktiverad för denna `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Ställer in ett värde som indikerar om gamma‑korrektion är aktiverad för denna `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Hämtar ett rektangulärt område som definierar start- och slutpunkterna för gradienten.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Ställer in ett rektangulärt område som definierar start- och slutpunkterna för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | En `com.aspose.imaging.RectangleF`‑struktur som specificerar start- och slutpunkterna för gradienten. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Hämtar gradientvinkeln.

**Returns:**
float – Gradientvinkeln.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Ställer in gradientvinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Gradientvinkeln. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Hämtar ett värde som indikerar om `LinearGradientBrushBase.Angle` ändras under transformationer med denna `LinearGradientBrushBase`.

**Returns:**
boolean – `true` om `LinearGradientBrushBase.Angle` ändras under transformationer med denna `LinearGradientBrushBase`; annars `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Ställer in ett värde som indikerar om `LinearGradientBrushBase.Angle` ändras under transformationer med denna `LinearGradientBrushBase`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om `LinearGradientBrushBase.Angle` ändras under transformationer med denna `LinearGradientBrushBase`; annars `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Hämtar ett värde som indikerar om gamma‑korrektion är aktiverad för denna `LinearGradientBrushBase`.

**Returns:**
boolean – Värdet är true om gamma‑korrektion är aktiverad för denna `LinearGradientBrushBase`; annars false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Ställer in ett värde som indikerar om gamma‑korrektion är aktiverad för denna `LinearGradientBrushBase`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Värdet är true om gamma‑korrektion är aktiverad för denna `LinearGradientBrushBase`; annars false. |

