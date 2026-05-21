---
title: "LinearGradientBrushBase"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente un pinceau avec des capacités de dégradé et les propriétés appropriées."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Représente un `Brush` avec des capacités de dégradé et des propriétés appropriées.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) | Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [getAngle()](#getAngle--) | Obtient l'angle du dégradé. |
| [setAngle(float value)](#setAngle-float-) | Définit l'angle du dégradé. |
| [isAngleScalable()](#isAngleScalable--) | Obtient une valeur indiquant si `LinearGradientBrushBase.Angle` est modifié lors des transformations avec ce `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Définit une valeur indiquant si `LinearGradientBrushBase.Angle` est modifié lors des transformations avec ce `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtient une valeur indiquant si la correction gamma est activée pour ce `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Définit une valeur indiquant si la correction gamma est activée pour ce `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtient une région rectangulaire qui définit les points de départ et d'arrivée du dégradé.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure `com.aspose.imaging.RectangleF` qui spécifie les points de départ et d'arrivée du dégradé. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Obtient l'angle du dégradé.

**Returns:**
float - L'angle du dégradé.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Définit l'angle du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'angle du dégradé. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Obtient une valeur indiquant si `LinearGradientBrushBase.Angle` est modifié lors des transformations avec ce `LinearGradientBrushBase`.

**Returns:**
boolean - `true` si `LinearGradientBrushBase.Angle` est modifié lors des transformations avec ce `LinearGradientBrushBase` ; sinon, `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Définit une valeur indiquant si `LinearGradientBrushBase.Angle` est modifié lors des transformations avec ce `LinearGradientBrushBase`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si `LinearGradientBrushBase.Angle` est modifié lors des transformations avec ce `LinearGradientBrushBase` ; sinon, `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtient une valeur indiquant si la correction gamma est activée pour ce `LinearGradientBrushBase`.

**Returns:**
boolean - La valeur est vraie si la correction gamma est activée pour ce `LinearGradientBrushBase` ; sinon, false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Définit une valeur indiquant si la correction gamma est activée pour ce `LinearGradientBrushBase`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | La valeur est vraie si la correction gamma est activée pour ce `LinearGradientBrushBase` ; sinon, false. |

