---
title: GraphicsPath
second_title: Aspose.Imaging لمرجع NET API
description: يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن توريث هذه الفئة.
type: docs
weight: 9370
url: /ar/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن توريث هذه الفئة.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../graphicspath) فئة . |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../graphicspath) فئة . |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../graphicspath) فئة . |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../graphicspath) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | الحصول على أو تعيين حدود الكائن. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | الحصول على أرقام المسار . |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | يحصل أو يحدد أ[`FillMode`](../fillmode) التعداد الذي يحدد كيفية الأشكال الداخلية للأشكال في هذا[`GraphicsPath`](../graphicspath) ممتلئة . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | يضيف رقمًا جديدًا . |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | إضافة أرقام جديدة . |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | لإلحاق المحدد[`GraphicsPath`](../graphicspath) إلى هذا المسار. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | لإلحاق المحدد[`GraphicsPath`](../graphicspath) إلى هذا المسار. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | يقوم بإجراء استنساخ عميق لمسار الرسوم هذا. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | يحول كل منحنى في هذا المسار إلى سلسلة من مقاطع الخط المتصلة. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | يطبق التحويل المحدد ثم يحول كل منحنى في هذا[`GraphicsPath`](../graphicspath) في سلسلة من مقاطع الخط المتصلة. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | تحويل كل منحنى في هذا[`GraphicsPath`](../graphicspath) في سلسلة من مقاطع الخط المتصلة. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | يحصل على حدود الكائن . |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) واستخدام المحدد[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) واستخدام المحدد[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) واستخدام المحدد[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا[`GraphicsPath`](../graphicspath) عند رسمها مع المحدد[`Pen`](../pen) واستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) في منطقة المقطع المرئية للملف[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا[`GraphicsPath`](../graphicspath) باستخدام المحدد[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | يزيل شكل . |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | يزيل الأشكال . |
| [Reset](../../aspose.imaging/graphicspath/reset)() | يفرغ مسار الرسومات ويعين ملف[`FillMode`](../fillmode) إلىAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | عكس ترتيب الأشكال والأشكال والنقاط في كل شكل من أشكال هذا[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | يطبق التحويل المحدد على الشكل. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | يضيف مخططًا تفصيليًا إضافيًا إلى المسار . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | يضيف مخططًا إضافيًا إلى ملف[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | يستبدل هذا[`GraphicsPath`](../graphicspath)بمنحنيات تحيط بالمساحة المملوءة عندما يتم رسم هذا المسار بواسطة القلم المحدد. |

### أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. ينشئ المثال صورة جديدة (من النوع Tiff) ، ويمسح السطح ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح.

```csharp
[C#]

// إنشاء مثيل لـ FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // تعيين المصدر لمثيل ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        // إنشاء وتهيئة مثيل لفئة الرسومات
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        // مسح سطح الرسومات
        graphics.Clear(Color.Wheat);

        // إنشاء مثيل لفئة GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        // إنشاء مثيل لفئة الشكل
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // إضافة أشكال إلى كائن الشكل
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        // إضافة كائن الشكل إلى GraphicsPath
        graphicspath.AddFigure(figure);

        // رسم المسار باستخدام كائن القلم ذي اللون الأسود
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### أنظر أيضا

* class [ObjectWithBounds](../objectwithbounds)
* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
