---
title: TransformBrush
second_title: Aspose.Imaging لمرجع NET API
description: أBrush../aspose.imaging/brush مع قدرات التحويل.
type: docs
weight: 230
url: /ar/net/aspose.imaging.brushes/transformbrush/
---
## TransformBrush class

أ[`Brush`](../../aspose.imaging/brush) مع قدرات التحويل.

```csharp
public abstract class TransformBrush : Brush
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | يحصل على قيمة تشير إلى ما إذا كانت التحولات قد تغيرت بطريقة ما. على سبيل المثال إعداد مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافق مع الإصدارات السابقة مع GDI + . |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | الحصول على نسخة أو تعيينها[`Matrix`](../../aspose.imaging/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا الغرض[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | يحصل أو يحدد أ[`WrapMode`](../../aspose.imaging/wrapmode) التعداد الذي يشير إلى وضع الالتفاف لهذا[`TransformBrush`](../transformbrush) . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | ينشئ استنساخًا عميقًا جديدًا للتيار[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform#multiplytransform)(Matrix) | يضاعف[`Matrix`](../../aspose.imaging/matrix) التي تمثل التحويل الهندسي المحلي لهذا[`LinearGradientBrush`](../lineargradientbrush) حسب المحدد[`Matrix`](../../aspose.imaging/matrix) عن طريق إضافة الملف المحدد مسبقًا[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | يضاعف[`Matrix`](../../aspose.imaging/matrix) التي تمثل التحويل الهندسي المحلي لهذا[`LinearGradientBrush`](../lineargradientbrush) حسب المحدد[`Matrix`](../../aspose.imaging/matrix) بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | يعيد تعيين ملف[`Transform`](./transform) الخاصية للهوية . |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform#rotatetransform)(float) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform#rotatetransform_1)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform#scaletransform)(float, float) | مقياس التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform#scaletransform_1)(float, float, MatrixOrder) | مقياس التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform#translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform#translatetransform_1)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### أنظر أيضا

* class [Brush](../../aspose.imaging/brush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->