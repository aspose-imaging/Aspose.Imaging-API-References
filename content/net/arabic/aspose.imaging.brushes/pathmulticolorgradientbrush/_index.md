---
title: PathMulticolorGradientBrush
second_title: Aspose.Imaging لمرجع NET API
description: يغلف أBrush../aspose.imaging/brush كائن مع التدرج. لا يمكن توريث هذه الفئة.
type: docs
weight: 200
url: /ar/aspose.imaging.brushes/pathmulticolorgradientbrush/
---
## PathMulticolorGradientBrush class

يغلف أ[`Brush`](../../aspose.imaging/brush) كائن مع التدرج. لا يمكن توريث هذه الفئة.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor)(GraphicsPath) | يقوم بتهيئة مثيل جديد لملف[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) فئة بالمسار المحدد. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_1)(PointF[]) | يقوم بتهيئة مثيل جديد لملف[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) فئة بالنقاط المحددة. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_3)(Point[]) | يقوم بتهيئة مثيل جديد لملف[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) فئة بالنقاط المحددة. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_2)(PointF[], WrapMode) | يقوم بتهيئة مثيل جديد لملف[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) فئة بالنقاط المحددة ووضع الالتفاف. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_4)(Point[], WrapMode) | يقوم بتهيئة مثيل جديد لملف[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) فئة بالنقاط المحددة ووضع الالتفاف. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | الحصول على أو تحديد النقطة المركزية لتدرج المسار. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | الحصول على نقطة التركيز الخاصة بانخفاض التدرج اللوني أو تعيينها. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | يحصل على المسار الرسومي الذي بنيت عليه هذه الفرشاة. |
| [InterpolationColors](../../aspose.imaging.brushes/pathmulticolorgradientbrush/interpolationcolors) { get; set; } | يحصل أو يحدد أ[`ColorBlend`](../../aspose.imaging/colorblend) التي تحدد تدرج خطي متعدد الألوان. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | يحصل على قيمة تشير إلى ما إذا كانت التحولات قد تغيرت بطريقة ما. على سبيل المثال إعداد مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافق مع الإصدارات السابقة مع GDI + . |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | الحصول على نقاط المسار التي تم بناء هذه الفرشاة عليها . |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | الحصول على نسخة أو تعيينها[`Matrix`](../../aspose.imaging/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا الغرض[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | يحصل أو يحدد أ[`WrapMode`](../../aspose.imaging/wrapmode) التعداد الذي يشير إلى وضع الالتفاف لهذا[`TransformBrush`](../transformbrush) . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | ينشئ استنساخًا عميقًا جديدًا للتيار[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | يضاعف[`Matrix`](../../aspose.imaging/matrix) التي تمثل التحويل الهندسي المحلي لهذا[`LinearGradientBrush`](../lineargradientbrush) حسب المحدد[`Matrix`](../../aspose.imaging/matrix) عن طريق إضافة الملف المحدد مسبقًا[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | يضاعف[`Matrix`](../../aspose.imaging/matrix) التي تمثل التحويل الهندسي المحلي لهذا[`LinearGradientBrush`](../lineargradientbrush) حسب المحدد[`Matrix`](../../aspose.imaging/matrix) بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | يعيد تعيين ملف[`Transform`](../transformbrush/transform) الخاصية للهوية . |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | مقياس التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | مقياس التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### أنظر أيضا

* class [PathGradientBrushBase](../pathgradientbrushbase)
* مساحة الاسم [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
