---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GraphicsPath. يضيف أشكالًا جديدة"
type: docs
weight: 60
url: /ar/net/aspose.imaging/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

يضيف أشكالاً جديدة.

```csharp
public void AddFigures(Figure[] figures)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الأشكال | Figure[] | الأشكال المراد إضافتها. |

## أمثلة

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


