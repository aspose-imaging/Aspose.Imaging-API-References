---
title: "الفئة TextureBrush"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Brushes.TextureBrush. كل خاصية من خصائص الفئة TextureBrush هي كائن Brush يستخدم صورة لملء داخل الشكل. لا يمكن وراثة هذه الفئة"
type: docs
weight: 220
url: /ar/net/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

كل خاصية من الفئة `TextureBrush` هي كائن [`Brush`](../../aspose.imaging/brush/) يستخدم صورة لملء داخل الشكل. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class TextureBrush : TransformBrush
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة، المستطيل المحيط، وسمات الصورة. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة، المستطيل المحيط، وسمات الصورة. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | ينشئ مثيلًا جديدًا من الفئة `TextureBrush` التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [Image](../../aspose.imaging.brushes/texturebrush/image/) { get; } | يحصل على كائن [`Image`](../../aspose.imaging/image/) المرتبط بهذا الكائن `TextureBrush`. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes/) { get; } | يحصل على [`ImageAttributes`](./imageattributes/) المرتبطة بهذا `TextureBrush`. |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle/) { get; } | يحصل على [`Rectangle`](../../aspose.imaging/rectangle/) المرتبط بهذا `TextureBrush`. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافقية الخلفية مع GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
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


