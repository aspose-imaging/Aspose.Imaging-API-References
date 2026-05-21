---
title: "الفئة LinearGradientBrush"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Brushes.LinearGradientBrush. تغلف فرشاة مع تدرج خطي. لا يمكن وراثة هذه الفئة"
type: docs
weight: 150
url: /ar/net/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

تغلف [`Brush`](../../aspose.imaging/brush/) مع تدرج خطي. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` بالمعلمات الافتراضية. اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة، والمستطيل يقع في (0,0) بحجم (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush`. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush`. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush`. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush`. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush`. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle/) { get; set; } | يحصل أو يعيّن زاوية التدرج. |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend/) { get; set; } | يحصل أو يعيّن [`Blend`](../../aspose.imaging/blend/) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor/) { get; set; } | يحصل أو يضبط لون التدرج النهائي. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح جاما مفعلاً لهذا [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [`Angle`](../lineargradientbrushbase/angle/) يتغير أثناء التحويلات مع هذا [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافقية الخلفية مع GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle/) { get; set; } | يحصل أو يعيّن منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor/) { get; set; } | يحصل أو يضبط لون التدرج الابتدائي. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | يحصل أو يعيّن نسخة من [`Matrix`](../../aspose.imaging/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | يحصل أو يعيّن تعداد [`WrapMode`](../../aspose.imaging/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [`TransformBrush`](../transformbrush/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من [`Brush`](../../aspose.imaging/brush/) الحالي. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix) | يضرب الـ[`Matrix`](../../aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة المحددة [`Matrix`](../../aspose.imaging/matrix/) عن طريق إلحاق المصفوفة المحددة [`Matrix`](../../aspose.imaging/matrix/). |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | يضرب الـ[`Matrix`](../../aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة المحددة [`Matrix`](../../aspose.imaging/matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | يعيد تعيين الخاصية [`Transform`](../transformbrush/transform/) إلى الهوية. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float) | يدور التحويل الهندسي المحلي بالمقدار المحدد. تقوم هذه الطريقة بإلحاق الدوران إلى التحويل. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالمقاسات المحددة. تقوم هذه الطريقة بإلحاق مصفوفة التكبير إلى التحويل. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالمقاسات المحددة بالترتيب المحدد. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | ينشئ تدرجًا خطيًا بلون مركزي وتناقصًا خطيًا إلى لون واحد في كلا الطرفين. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | ينشئ تدرجًا خطيًا بلون مركزي وتناقصًا خطيًا إلى لون واحد في كلا الطرفين. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | ينشئ تناقصًا في التدرج يعتمد على منحنى على شكل جرس. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | ينشئ تناقصًا في التدرج يعتمد على منحنى على شكل جرس. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تقوم هذه الطريقة بإلحاق الإزاحة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### انظر أيضًا

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


