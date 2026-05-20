---
title: "LinearGradientBrushBase"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt einen Pinsel mit Farbverlaufsfähigkeiten und entsprechenden Eigenschaften dar."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Stellt einen `Brush` mit Gradientfähigkeiten und entsprechenden Eigenschaften dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRectangle()](#getRectangle--) | Liefert einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Legt einen rechteckigen Bereich fest, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [getAngle()](#getAngle--) | Liefert den Winkel des Farbverlaufs. |
| [setAngle(float value)](#setAngle-float-) | Legt den Winkel des Farbverlaufs fest. |
| [isAngleScalable()](#isAngleScalable--) | Liefert einen Wert, der angibt, ob `LinearGradientBrushBase.Angle` während Transformationen mit diesem `LinearGradientBrushBase` geändert wird. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Legt einen Wert fest, der angibt, ob `LinearGradientBrushBase.Angle` während Transformationen mit diesem `LinearGradientBrushBase` geändert wird. |
| [getGammaCorrection()](#getGammaCorrection--) | Liefert einen Wert, der angibt, ob die Gammakorrektur für dieses `LinearGradientBrushBase` aktiviert ist. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Legt einen Wert fest, der angibt, ob die Gammakorrektur für dieses `LinearGradientBrushBase` aktiviert ist. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Liefert einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Legt einen rechteckigen Bereich fest, der die Start- und Endpunkte des Farbverlaufs definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Eine `com.aspose.imaging.RectangleF`-Struktur, die die Start- und Endpunkte des Farbverlaufs angibt. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Liefert den Winkel des Farbverlaufs.

**Returns:**
float - Der Winkel des Farbverlaufs.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Legt den Winkel des Farbverlaufs fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Winkel des Farbverlaufs. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Liefert einen Wert, der angibt, ob `LinearGradientBrushBase.Angle` während Transformationen mit diesem `LinearGradientBrushBase` geändert wird.

**Returns:**
boolean - `true`, wenn `LinearGradientBrushBase.Angle` während Transformationen mit diesem `LinearGradientBrushBase` geändert wird; andernfalls `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Legt einen Wert fest, der angibt, ob `LinearGradientBrushBase.Angle` während Transformationen mit diesem `LinearGradientBrushBase` geändert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn `LinearGradientBrushBase.Angle` während Transformationen mit diesem `LinearGradientBrushBase` geändert wird; andernfalls `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Liefert einen Wert, der angibt, ob die Gammakorrektur für dieses `LinearGradientBrushBase` aktiviert ist.

**Returns:**
boolean - Der Wert ist true, wenn die Gammakorrektur für dieses `LinearGradientBrushBase` aktiviert ist; andernfalls false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Legt einen Wert fest, der angibt, ob die Gammakorrektur für dieses `LinearGradientBrushBase` aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Der Wert ist true, wenn die Gammakorrektur für dieses `LinearGradientBrushBase` aktiviert ist; andernfalls false. |

