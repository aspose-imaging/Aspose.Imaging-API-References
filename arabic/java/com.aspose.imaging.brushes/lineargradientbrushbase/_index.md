---
title: "LinearGradientBrushBase"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل فرشاة ذات قدرات تدرج وخصائص مناسبة."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

يمثل `Brush` بقدرات تدرج وخصائص مناسبة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRectangle()](#getRectangle--) | يحصل على منطقة مستطيلة تحدد النقاط الابتدائية والنهائية للتدرج. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | يضبط منطقة مستطيلة تحدد النقاط الابتدائية والنهائية للتدرج. |
| [getAngle()](#getAngle--) | يحصل على زاوية التدرج. |
| [setAngle(float value)](#setAngle-float-) | يضبط زاوية التدرج. |
| [isAngleScalable()](#isAngleScalable--) | يحصل على قيمة تشير إلى ما إذا تم تغيير `LinearGradientBrushBase.Angle` أثناء التحويلات باستخدام هذا `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | يضبط قيمة تشير إلى ما إذا تم تغيير `LinearGradientBrushBase.Angle` أثناء التحويلات باستخدام هذا `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | يحصل على قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


يحصل على منطقة مستطيلة تحدد النقاط الابتدائية والنهائية للتدرج.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


يضبط منطقة مستطيلة تحدد النقاط الابتدائية والنهائية للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` يحدد نقطتي البداية والنهاية للتدرج. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


يحصل على زاوية التدرج.

**Returns:**
float - زاوية التدرج.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


يضبط زاوية التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | زاوية التدرج. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


يحصل على قيمة تشير إلى ما إذا تم تغيير `LinearGradientBrushBase.Angle` أثناء التحويلات باستخدام هذا `LinearGradientBrushBase`.

**Returns:**
boolean - `true` إذا تم تغيير `LinearGradientBrushBase.Angle` أثناء التحويلات باستخدام هذا `LinearGradientBrushBase`؛ وإلا `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


يضبط قيمة تشير إلى ما إذا تم تغيير `LinearGradientBrushBase.Angle` أثناء التحويلات باستخدام هذا `LinearGradientBrushBase`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا تم تغيير `LinearGradientBrushBase.Angle` أثناء التحويلات باستخدام هذا `LinearGradientBrushBase`؛ وإلا `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


يحصل على قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا `LinearGradientBrushBase`.

**Returns:**
boolean - القيمة true إذا تم تمكين تصحيح غاما لهذا `LinearGradientBrushBase`؛ وإلا false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا `LinearGradientBrushBase`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | القيمة true إذا تم تمكين تصحيح غاما لهذا `LinearGradientBrushBase`؛ وإلا false. |

