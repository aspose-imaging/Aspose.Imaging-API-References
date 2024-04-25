---
title: TextureBrush
second_title: Aspose.Imaging لمرجع NET API
description: كل خاصية من ممتلكاتTextureBrush./texturebrush الطبقة هيBrush../aspose.imaging/brush كائن يستخدم صورة لملء الجزء الداخلي للشكل. لا يمكن توريث هذه الفئة.
type: docs
weight: 220
url: /ar/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

كل خاصية من ممتلكات[`TextureBrush`](../texturebrush) الطبقة هي[`Brush`](../../aspose.imaging/brush) كائن يستخدم صورة لملء الجزء الداخلي للشكل. لا يمكن توريث هذه الفئة.

```csharp
public sealed class TextureBrush : TransformBrush
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم الصورة المحددة. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم سمات الصورة المحددة والمستطيل المحيط والصورة. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم سمات الصورة المحددة والمستطيل المحيط والصورة. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم الصورة المحددة ووضع الالتفاف والمستطيل المحيط. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | يقوم بتهيئة مثيل جديد لملف[`TextureBrush`](../texturebrush) فئة تستخدم الصورة المحددة ووضع الالتفاف والمستطيل المحيط. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) كائن مرتبط بهذا[`TextureBrush`](../texturebrush) الكائن . |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | يحصل على ملف[`ImageAttributes`](./imageattributes) المرتبطة بهذا[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | يحصل على ملف[`Rectangle`](../../aspose.imaging/rectangle) المرتبطة بهذا[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | يحصل على قيمة تشير إلى ما إذا كانت التحولات قد تغيرت بطريقة ما. على سبيل المثال إعداد مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافق مع الإصدارات السابقة مع GDI + . |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |
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

* class [TransformBrush](../transformbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
