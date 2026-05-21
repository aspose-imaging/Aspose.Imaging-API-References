---
title: "GraphicsPath.AddFigure"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GraphicsPath. تضيف شكلاً جديدًا"
type: docs
weight: 50
url: /ar/net/aspose.imaging/graphicspath/addfigure/
---
## GraphicsPath.AddFigure method

يضيف شكلاً جديداً.

```csharp
public void AddFigure(Figure figure)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| شكل | شكل | الشكل المراد إضافته. |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


