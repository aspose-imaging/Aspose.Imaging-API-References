---
title: "LinearGradientBrushBase"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Degrade yeteneklerine ve uygun özelliklere sahip bir Fırçayı temsil eder."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Degrade yetenekleri ve uygun özelliklere sahip bir `Brush` nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRectangle()](#getRectangle--) | Degrade'nin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölgeyi alır. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Degrade'nin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölgeyi ayarlar. |
| [getAngle()](#getAngle--) | Degrade açısını alır. |
| [setAngle(float value)](#setAngle-float-) | Degrade açısını ayarlar. |
| [isAngleScalable()](#isAngleScalable--) | Bu `LinearGradientBrushBase` ile yapılan dönüşümler sırasında `LinearGradientBrushBase.Angle` değerinin değişip değişmediğini gösteren bir değeri alır. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Bu `LinearGradientBrushBase` ile yapılan dönüşümler sırasında `LinearGradientBrushBase.Angle` değerinin değişip değişmediğini gösteren bir değeri ayarlar. |
| [getGammaCorrection()](#getGammaCorrection--) | Bu `LinearGradientBrushBase` için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Bu `LinearGradientBrushBase` için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri ayarlar. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Degrade'nin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölgeyi alır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Degrade'nin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölgeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Degrade'nin başlangıç ve bitiş noktalarını belirten bir `com.aspose.imaging.RectangleF` yapısı. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Degrade açısını alır.

**Returns:**
float - Degrade açısı.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Degrade açısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Degrade açısı. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Bu `LinearGradientBrushBase` ile yapılan dönüşümler sırasında `LinearGradientBrushBase.Angle` değerinin değişip değişmediğini gösteren bir değeri alır.

**Returns:**
boolean - `LinearGradientBrushBase.Angle` bu `LinearGradientBrushBase` ile dönüşümler sırasında değiştirildiyse `true`; aksi takdirde `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Bu `LinearGradientBrushBase` ile yapılan dönüşümler sırasında `LinearGradientBrushBase.Angle` değerinin değişip değişmediğini gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` eğer `LinearGradientBrushBase.Angle` bu `LinearGradientBrushBase` ile dönüşümler sırasında değiştirildiyse; aksi takdirde `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Bu `LinearGradientBrushBase` için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Bu `LinearGradientBrushBase` için gama düzeltmesi etkinse değer true; aksi takdirde false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Bu `LinearGradientBrushBase` için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Değer, bu `LinearGradientBrushBase` için gama düzeltmesi etkinse true; aksi takdirde false. |

