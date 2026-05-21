---
title: "الفئة Pen"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Pen. تُعرّف كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال."
type: docs
weight: 11260
url: /ar/net/aspose.imaging/pen/
---
## Pen class

يحدد كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال.

```csharp
public class Pen : TransparencySupporter
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | ينشئ مثيلًا جديدًا من الفئة `Pen` باستخدام الـ[`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | ينشئ مثيلًا جديدًا من الفئة `Pen` باستخدام اللون المحدد. |
| [Pen](pen/#constructor_1)(Brush, float) | ينشئ مثيلًا جديدًا من الفئة `Pen` باستخدام الـ[`Brush`](./brush/) و[`Width`](./width/) المحددين. |
| [Pen](pen/#constructor_3)(Color, float) | ينشئ مثيلًا جديدًا من الفئة `Pen` باستخدام خصائص الـ[`Color`](./color/) و[`Width`](./width/) المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment/) { get; set; } | يحصل أو يضبط المحاذاة لهذا `Pen`. |
| [Brush](../../aspose.imaging/pen/brush/) { get; set; } | يحصل أو يضبط الـ[`Brush`](./brush/) الذي يحدد سمات هذا `Pen`. |
| [Color](../../aspose.imaging/pen/color/) { get; set; } | يحصل أو يضبط لون هذا `Pen`. |
| [CompoundArray](../../aspose.imaging/pen/compoundarray/) { get; set; } | يحصل أو يضبط مصفوفة من القيم التي تحدد قلمًا مركبًا. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية ومسافات. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap/) { get; set; } | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`. |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap/) { get; set; } | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`. |
| [DashCap](../../aspose.imaging/pen/dashcap/) { get; set; } | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`. |
| [DashOffset](../../aspose.imaging/pen/dashoffset/) { get; set; } | يحصل أو يضبط المسافة من بداية الخط إلى بداية نمط الشرطة. |
| [DashPattern](../../aspose.imaging/pen/dashpattern/) { get; set; } | يحصل أو يضبط مصفوفة من الشرطات والمسافات المخصصة. |
| [DashStyle](../../aspose.imaging/pen/dashstyle/) { get; set; } | يحصل أو يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`. |
| [EndCap](../../aspose.imaging/pen/endcap/) { get; set; } | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا `Pen`. |
| [LineJoin](../../aspose.imaging/pen/linejoin/) { get; set; } | يحصل أو يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`. |
| [MiterLimit](../../aspose.imaging/pen/miterlimit/) { get; set; } | يحصل أو يضبط حد سمك الوصل عند زاوية مائلة. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity/) { get; set; } | يحصل أو يعيّن شفافية الكائن. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الكائن مرئي بالكامل، والقيمة 1 تعني أن الكائن غير شفاف تمامًا. |
| [PenType](../../aspose.imaging/pen/pentype/) { get; } | يحصل على نمط الخطوط المرسومة بهذا `Pen`. |
| [StartCap](../../aspose.imaging/pen/startcap/) { get; set; } | يحصل أو يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا `Pen`. |
| [Transform](../../aspose.imaging/pen/transform/) { get; set; } | يحصل أو يضبط نسخة من التحويل الهندسي لهذا `Pen`. |
| [Width](../../aspose.imaging/pen/width/) { get; set; } | يحصل أو يضبط عرض هذا `Pen`، بوحدات كائن Graphics المستخدم للرسم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging/pen/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetHashCode](../../aspose.imaging/pen/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform/#multiplytransform)(Matrix) | يضرب مصفوفة التحويل لهذا `Pen` بالـ[`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | يضرب مصفوفة التحويل لهذا `Pen` بالـ[`Matrix`](../matrix/) المحدد بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging/pen/resettransform/)() | يعيد تعيين مصفوفة التحويل الهندسي لهذا `Pen` إلى هوية. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform/#rotatetransform)(float) | يدور التحويل الهندسي المحلي بالزاوية المحددة. هذه الطريقة تسبق الدوران في التحويل. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform/#scaletransform)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. هذه الطريقة تسبق مصفوفة التكبير في التحويل. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap/)(LineCap, LineCap, DashCap) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بهذا `Pen`. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform/#translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة في التحويل. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |

## أمثلة

يوضح هذا المثال إنشاء واستخدام كائنات Pen. ينشئ المثال صورة جديدة ويرسم مستطيلات على سطح الصورة.

```csharp
[C#]

//أنشئ مثيلاً من BmpOptions وعيّن خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//أنشئ مثيلاً من Image في المسار المحدد
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //أنشئ مثيلاً من Graphics وابدأه باستخدام كائن Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //امسح سطح Graphics باللون الأبيض
    graphics.Clear(Aspose.Imaging.Color.White);

    //أنشئ مثيلاً من Pen باللون الأحمر وعرض 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //أنشئ مثيلاً من HatchBrush وعيّن خصائصه
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //أنشئ مثيلاً من Pen
    //ابدأه بكائن HatchBrush والعرض
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //ارسم مستطيلات بتحديد كائن Pen
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //ارسم مستطيلات بتحديد كائن Pen
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


