---
title: "فئة GraphicsPath"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.GraphicsPath. تمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن وراثة هذه الفئة."
type: docs
weight: 9550
url: /ar/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | ينشئ مثيلاً جديداً من فئة `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | ينشئ مثيلاً جديداً من فئة `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | ينشئ مثيلاً جديداً من فئة `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | ينشئ مثيلاً جديداً من فئة `GraphicsPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds/) { get; } | يحصل أو يضبط حدود الكائن. |
| [Figures](../../aspose.imaging/graphicspath/figures/) { get; } | يحصل على أشكال المسار. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode/) { get; set; } | يحصل أو يضبط تعداد [`FillMode`](../fillmode/) الذي يحدد كيفية تعبئة داخل الأشكال في هذا `GraphicsPath`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure/)(Figure) | يضيف شكلاً جديداً. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures/)(Figure[]) | يضيف أشكالاً جديدة. |
| [AddPath](../../aspose.imaging/graphicspath/addpath/#addpath)(GraphicsPath) | يضيف `GraphicsPath` المحدد إلى هذا المسار. |
| [AddPath](../../aspose.imaging/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | يضيف `GraphicsPath` المحدد إلى هذا المسار. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone/)() | ينفذ استنساخاً عميقاً لهذا المسار الرسومي. |
| override [Equals](../../aspose.imaging/graphicspath/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| [Flatten](../../aspose.imaging/graphicspath/flatten/#flatten)() | يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة. |
| [Flatten](../../aspose.imaging/graphicspath/flatten/#flatten_1)(Matrix) | يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا `GraphicsPath` إلى سلسلة من القطع الخطية المتصلة. |
| [Flatten](../../aspose.imaging/graphicspath/flatten/#flatten_2)(Matrix, float) | يحوّل كل منحنى في هذا `GraphicsPath` إلى سلسلة من القطع الخطية المتصلة. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| override [GetHashCode](../../aspose.imaging/graphicspath/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمها باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible)(Point) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_2)(PointF) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_6)(float, float) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_4)(int, int) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath` في منطقة القص المرئية لـ [`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath` باستخدام [`Graphics`](../graphics/) المحدد. |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure/)(Figure) | يزيل شكلاً. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures/)(Figure[]) | يزيل الأشكال. |
| [Reset](../../aspose.imaging/graphicspath/reset/)() | يفرغ مسار الرسومات ويضبط [`FillMode`](../fillmode/) إلى Alternate. |
| [Reverse](../../aspose.imaging/graphicspath/reverse/)() | يعكس ترتيب الأشكال والأشكال الهندسية والنقاط في كل شكل من هذا `GraphicsPath`. |
| override [Transform](../../aspose.imaging/graphicspath/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp)(PointF[], RectangleF) | يطبق تحويل تشويه، معرف بمستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | يطبق تحويل تشويه، معرف بمستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | يطبق تحويل تشويه، معرف بمستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | يطبق تحويل تشويه، معرف بمستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Widen](../../aspose.imaging/graphicspath/widen/#widen)(Pen) | يضيف مخططًا إضافيًا إلى المسار. |
| [Widen](../../aspose.imaging/graphicspath/widen/#widen_1)(Pen, Matrix) | يضيف مخططًا إضافيًا إلى `GraphicsPath`. |
| [Widen](../../aspose.imaging/graphicspath/widen/#widen_2)(Pen, Matrix, float) | يستبدل هذا `GraphicsPath` بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد. |

## أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة (من نوع Tiff)، يمسح السطح ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لعرض المسارات على السطح.

```csharp
[C#]

//إنشاء مثيل من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //إنشاء مثيل من TiffOptions وتعيين خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //تعيين المصدر لمثيل ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //إنشاء وتهيئة مثيل من فئة Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //مسح سطح Graphics
        graphics.Clear(Color.Wheat);

        //إنشاء مثيل من فئة GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //إنشاء كائن من الفئة Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //إضافة أشكال إلى كائن Figure
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //إضافة كائن Figure إلى GraphicsPath
        graphicspath.AddFigure(figure);

        //رسم المسار باستخدام كائن Pen باللون الأسود
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### انظر أيضًا

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


