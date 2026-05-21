---
title: "فئة Figure"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.Figure class. الشكل. حاوية للأشكال"
type: docs
weight: 1320
url: /ar/net/aspose.imaging/figure/
---
## Figure class

الشكل. حاوية للأشكال.

```csharp
public class Figure : ObjectWithBounds
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Figure](figure/)() | يُنشئ مثيلًا جديدًا لـ `Figure`. مُنشئ مطلوب لتسلسل JSON. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.imaging/figure/bounds/) { get; } | يحصل أو يضبط حدود الكائن. |
| [IsClosed](../../aspose.imaging/figure/isclosed/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيُحدث الشكل المغلق فرقًا فقط في الحالة التي تكون فيها أشكال الشكل الأول والأخير أشكالًا متصلة. في هذه الحالة، سيتم ربط النقطة الأولى للشكل الأول بخط مستقيم من النقطة الأخيرة للشكل الأخير. |
| [Segments](../../aspose.imaging/figure/segments/) { get; } | يحصل على جميع مقاطع الشكل. |
| [Shapes](../../aspose.imaging/figure/shapes/) { get; } | يحصل على الأشكال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddShape](../../aspose.imaging/figure/addshape/)(Shape) | يضيف شكلاً إلى الشكل. |
| [AddShapes](../../aspose.imaging/figure/addshapes/)(Shape[]) | يضيف مجموعة من الأشكال إلى الشكل. |
| override [Equals](../../aspose.imaging/figure/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| override [GetBounds](../../aspose.imaging/figure/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.imaging/figure/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| override [GetHashCode](../../aspose.imaging/figure/gethashcode/)() | يعمل كدالة التجزئة الافتراضية. |
| [RemoveShape](../../aspose.imaging/figure/removeshape/)(Shape) | يزيل شكلاً من الشكل. |
| [RemoveShapes](../../aspose.imaging/figure/removeshapes/)(Shape[]) | يزيل مجموعة من الأشكال من الشكل. |
| [Reverse](../../aspose.imaging/figure/reverse/)() | يعكس ترتيب أشكال هذا الشكل وترتيب نقاط الأشكال. |
| override [Transform](../../aspose.imaging/figure/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

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


