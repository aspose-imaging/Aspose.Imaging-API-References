---
title: "الفئة PathGradientBrushBase"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Brushes.PathGradientBrushBase. تمثل فرشاة ذات وظيفة تدرج مسار أساسي."
type: docs
weight: 190
url: /ar/net/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

يمثل [`Brush`](../../aspose.imaging/brush/) مع وظيفة تدرج المسار الأساسي.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | يحصل أو يعيّن نقطة المركز لتدرج المسار. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales/) { get; set; } | يحصل أو يعيّن نقطة التركيز لتلاشي التدرج. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath/) { get; } | يحصل على مسار الرسومات الذي بُني عليه هذه الفرشاة. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافقية الخلفية مع GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints/) { get; } | يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة. |
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

## ملاحظات

لاحظ أنه عند إنشاء الفئة `PathGradientBrushBase` يجب تهيئتها بما لا يقل عن نقطتين. سيظل المسار الداخلي المُنشأ دائمًا شكلًا مغلقًا، حيث تربط النقطة الأخيرة النقطة الأولى. يتم ملء ذلك الشكل باستخدام `PathGradientBrushBase`. تُصدر تنفيذية GDI+ استثناء OutOfMemoryException عند تمرير مصفوفات فارغة أو مجموعة نقاط لها نفس الإحداثيات. تُصدر الفئة `PathGradientBrushBase` استثناءً عندما تحتوي مصفوفة النقاط على أقل من نقطتين، حيث يتم إلقاء ArgumentException بدلاً من OutOfMemoryException عندما تكون مصفوفة النقاط غير مقبولة. تُحسب نقطة المركز كمتوسط كتلة للنقاط الممررة بشكل افتراضي. يمكن للمستخدم تغيير هذه النقطة لاحقًا. مقياس التركيز هو نقطة فارغة (0.0, 0.0) بشكل افتراضي.

### انظر أيضًا

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


