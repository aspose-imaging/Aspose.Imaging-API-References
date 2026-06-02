---
title: "Figure.AddShape"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Figure. تضيف شكلاً إلى الشكل."
type: docs
weight: 60
url: /ar/net/aspose.imaging/figure/addshape/
---
## Figure.AddShape method

يضيف شكلاً إلى الشكل.

```csharp
public void AddShape(Shape shape)
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

هذا المثال ينشئ صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures و GraphicsPath على سطح الصورة

```csharp
[C#]

//ينشئ نسخة من BmpOptions ويضبط خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//إنشاء مثيل من Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //إنشاء وتهيئة مثيل من فئة Graphics
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //إنشاء مثيل من فئة GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //إنشاء كائن من الفئة Figure
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //إضافة شكل إلى كائن Figure
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //إنشاء كائن من الفئة Figure
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //إضافة شكل إلى كائن Figure
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //رسم المسار باستخدام كائن Pen باللون الأسود
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.Imaging](../../figure/)
* assembly [Aspose.Imaging](../../../)


