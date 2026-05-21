---
title: "LinearGradientBrushBase"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un pennello con capacità di gradiente e proprietà appropriate."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Rappresenta un `Brush` con capacità di gradiente e proprietà appropriate.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRectangle()](#getRectangle--) | Ottiene una regione rettangolare che definisce i punti iniziale e finale del gradiente. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Imposta una regione rettangolare che definisce i punti iniziale e finale del gradiente. |
| [getAngle()](#getAngle--) | Ottiene l'angolo del gradiente. |
| [setAngle(float value)](#setAngle-float-) | Imposta l'angolo del gradiente. |
| [isAngleScalable()](#isAngleScalable--) | Ottiene un valore che indica se `LinearGradientBrushBase.Angle` viene modificato durante le trasformazioni con questo `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Imposta un valore che indica se `LinearGradientBrushBase.Angle` viene modificato durante le trasformazioni con questo `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | Ottiene un valore che indica se la correzione gamma è abilitata per questo `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Imposta un valore che indica se la correzione gamma è abilitata per questo `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Ottiene una regione rettangolare che definisce i punti iniziale e finale del gradiente.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Imposta una regione rettangolare che definisce i punti iniziale e finale del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Una struttura `com.aspose.imaging.RectangleF` che specifica i punti iniziale e finale del gradiente. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Ottiene l'angolo del gradiente.

**Returns:**
float - L'angolo del gradiente.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Imposta l'angolo del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'angolo del gradiente. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Ottiene un valore che indica se `LinearGradientBrushBase.Angle` viene modificato durante le trasformazioni con questo `LinearGradientBrushBase`.

**Returns:**
boolean - `true` se `LinearGradientBrushBase.Angle` viene modificato durante le trasformazioni con questo `LinearGradientBrushBase`; altrimenti, `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Imposta un valore che indica se `LinearGradientBrushBase.Angle` viene modificato durante le trasformazioni con questo `LinearGradientBrushBase`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se `LinearGradientBrushBase.Angle` viene modificato durante le trasformazioni con questo `LinearGradientBrushBase`; altrimenti, `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Ottiene un valore che indica se la correzione gamma è abilitata per questo `LinearGradientBrushBase`.

**Returns:**
boolean - Il valore è true se la correzione gamma è abilitata per questo `LinearGradientBrushBase`; altrimenti, false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Imposta un valore che indica se la correzione gamma è abilitata per questo `LinearGradientBrushBase`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Il valore è true se la correzione gamma è abilitata per questo `LinearGradientBrushBase`; altrimenti, false. |

