---
title: "الفئة PathGradientBrush"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Brushes.PathGradientBrush. تغلف كائن Brush مع تدرج. لا يمكن وراثة هذه الفئة."
type: docs
weight: 180
url: /ar/net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

تغلف كائن [`Brush`](../../aspose.imaging/brush/) مع تدرج. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالمسار المحدد. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend/) { get; set; } | يحصل أو يعيّن [`Blend`](../../aspose.imaging/blend/) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor/) { get; set; } | يحصل أو يضبط اللون في مركز تدرج المسار. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | يحصل أو يعيّن نقطة المركز لتدرج المسار. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales/) { get; set; } | يحصل أو يعيّن نقطة التركيز لتلاشي التدرج. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath/) { get; } | يحصل على مسار الرسومات الذي بُني عليه هذه الفرشاة. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافقية الخلفية مع GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints/) { get; } | يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors/) { get; set; } | يحصل أو يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا `PathGradientBrush`. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | ينشئ تدرجًا بلون مركزي وتناقصًا خطيًا إلى لون محيط واحد. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | ينشئ تدرجًا بلون مركزي وتناقصًا خطيًا إلى كل لون محيط. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار نحو حدود المسار. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار نحو حدود المسار. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تقوم هذه الطريقة بإلحاق الإزاحة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

## ملاحظات

اللون المركزي هو أبيض افتراضيًا. يمكن للمستخدم تغيير هذه القيمة في أي وقت لاحق.

يتم تهيئة مصفوفة الألوان المحيطة بعنصر واحد يحتوي على اللون الأبيض افتراضيًا. يمكن تغيير الألوان المحيطة لاحقًا، لكن يلزم وجود عنصر واحد على الأقل عند إعداد الألوان المحيطة.

انظر الـ[`Blend`](./blend/) لمزيد من التفاصيل حول تهيئته.

### انظر أيضًا

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


