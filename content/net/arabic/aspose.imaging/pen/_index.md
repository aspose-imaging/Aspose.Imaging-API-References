---
title: Pen
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائنًا يستخدم لرسم الخطوط والمنحنيات والأشكال .
type: docs
weight: 10690
url: /ar/aspose.imaging/pen/
---
## Pen class

يحدد كائنًا يستخدم لرسم الخطوط والمنحنيات والأشكال .

```csharp
public class Pen : TransparencySupporter
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Pen](pen#constructor)(Brush) | يقوم بتهيئة مثيل جديد لملف[`Pen`](../pen) فئة مع المحدد[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | يقوم بتهيئة مثيل جديد لملف[`Pen`](../pen) فئة باللون المحدد. |
| [Pen](pen#constructor_1)(Brush, float) | يقوم بتهيئة مثيل جديد لملف[`Pen`](../pen) فئة مع المحدد[`Brush`](./brush) و[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | يقوم بتهيئة مثيل جديد لملف[`Pen`](../pen) فئة مع المحدد[`Color`](./color) و[`Width`](./width) الخصائص . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | الحصول على أو تعيين المحاذاة لهذا الغرض[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | يحصل أو يحدد ملف[`Brush`](./brush) التي تحدد سمات هذا[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | الحصول على اللون أو تحديده[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | الحصول على أو تعيين مصفوفة من القيم التي تحدد قلمًا مركبًا. قلم مركب يرسم خطًا مركبًا مكونًا من خطوط ومسافات متوازية. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | الحصول على أو تعيين حد أقصى مخصص لاستخدامه في نهاية السطور المرسومة بهذا[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | الحصول على غطاء مخصص أو تعيينه لاستخدامه في بداية السطور المرسومة بهذا[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | الحصول على أو تعيين نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | الحصول على المسافة من بداية السطر إلى بداية نمط الشرطة أو تحديدها . |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | الحصول على أو تعيين مصفوفة من الشرطات والمسافات المخصصة. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | الحصول على أو تحديد النمط المستخدم للخطوط المتقطعة المرسومة بهذا[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | الحصول على أو تحديد نمط الغطاء المستخدم في نهاية السطور المرسومة بهذا[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | الحصول على أو تحديد نمط الصلة لنهايات سطرين متتاليين مرسومين بهذا[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | الحصول على أو تعيين حد سماكة الوصلة في الزاوية الميتة . |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | الحصول على عتامة الكائن أو تعيينها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الكائن مرئي بالكامل ، بينما تعني القيمة 1 أن الكائن معتم بالكامل. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | يحصل على نمط الخطوط المرسومة بهذا[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | الحصول على أو تحديد نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | الحصول على نسخة من التحويل الهندسي لهذا الغرض أو تعيينها[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | الحصول على أو تحديد عرض هذا[`Pen`](../pen) ، بوحدات كائن الرسومات المستخدمة للرسم . |

## طُرق

| اسم | وصف |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | ضرب مصفوفة التحويل لهذا الغرض[`Pen`](../pen) حسب المحدد[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | ضرب مصفوفة التحويل لهذا الغرض[`Pen`](../pen) حسب المحدد[`Matrix`](../matrix) بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | يعيد تعيين مصفوفة التحويل الهندسي لهذا الغرض[`Pen`](../pen) للهوية . |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | يدير التحويل الهندسي المحلي بالزاوية المحددة. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | مقياس التحويل الهندسي المحلي بالعوامل المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | مقياس التحويل الهندسي المحلي بواسطة العوامل المحددة بالترتيب المحدد. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بواسطة هذا[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### أمثلة

يوضح هذا المثال إنشاء كائنات القلم واستخدامها. يقوم المثال بإنشاء صورة جديدة ورسم مستطيلات على سطح الصورة.

```csharp
[C#]

// قم بإنشاء مثيل لـ BmpOptions وقم بتعيين خصائصه المختلفة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل BmpOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

// إنشاء مثيل للصورة في المسار المحدد
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // قم بإنشاء مثيل للرسومات وقم بتهيئته باستخدام كائن صورة
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // مسح واجهة الرسومات باللون الأبيض
    graphics.Clear(Aspose.Imaging.Color.White);

    // إنشاء مثيل من القلم باللون الأحمر والعرض 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    // قم بإنشاء مثيل لـ HatchBrush وعيّن خصائصه
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    // إنشاء مثيل من Pen
    // قم بتهيئته باستخدام كائن وعرض HatchBrush
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // احفظ جميع التغييرات.
    image.Save();
}
```

### أنظر أيضا

* class [TransparencySupporter](../transparencysupporter)
* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
