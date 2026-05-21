---
title: "الفئة LinearGradientBrushBase"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Brushes.LinearGradientBrushBase. تمثل فرشاة ذات قدرات تدرج وخصائص مناسبة."
type: docs
weight: 160
url: /ar/net/aspose.imaging.brushes/lineargradientbrushbase/
---
## LinearGradientBrushBase class

تمثل الـ[`Brush`](../../aspose.imaging/brush/) ذات قدرات تدرج وخصائص مناسبة.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle/) { get; set; } | يحصل أو يعيّن زاوية التدرج. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا `LinearGradientBrushBase`. |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان الـ[`Angle`](./angle/) يتغير أثناء التحويلات مع هذا `LinearGradientBrushBase`. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافقية الخلفية مع GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle/) { get; set; } | يحصل أو يعيّن منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | يحصل أو يعيّن نسخة من [`Matrix`](../../aspose.imaging/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | يحصل أو يعيّن تعداد [`WrapMode`](../../aspose.imaging/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [`TransformBrush`](../transformbrush/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من [`Brush`](../../aspose.imaging/brush/) الحالي. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix) | يضرب [`Matrix`](../../aspose.imaging/matrix/) التي تمثل التحويل الهندسي المحلي لهذا [`LinearGradientBrush`](../lineargradientbrush/) بالمصفوفة المحددة [`Matrix`](../../aspose.imaging/matrix/) عن طريق إلحاق المصفوفة المحددة [`Matrix`](../../aspose.imaging/matrix/) في المقدمة. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | يضرب [`Matrix`](../../aspose.imaging/matrix/) التي تمثل التحويل الهندسي المحلي لهذا [`LinearGradientBrush`](../lineargradientbrush/) بالمصفوفة المحددة [`Matrix`](../../aspose.imaging/matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | يعيد تعيين الخاصية [`Transform`](../transformbrush/transform/) إلى الهوية. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float) | يدور التحويل الهندسي المحلي بالمقدار المحدد. تقوم هذه الطريقة بإلحاق الدوران إلى التحويل. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالمقاسات المحددة. تقوم هذه الطريقة بإلحاق مصفوفة التكبير إلى التحويل. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالمقاسات المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تقوم هذه الطريقة بإلحاق الإزاحة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### انظر أيضًا

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


