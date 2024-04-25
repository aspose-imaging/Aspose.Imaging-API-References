---
title: RectangleShape
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفRectangleShapeaspose.imaging.shapes/rectangleshape فئة .
type: docs
weight: 10
url: /ar/aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`RectangleShape`](../../rectangleshape) فئة .

```csharp
public RectangleShape()
```

### أنظر أيضا

* class [RectangleShape](../../rectangleshape)
* مساحة الاسم [Aspose.Imaging.Shapes](../../rectangleshape)
* المجسم [Aspose.Imaging](../../../)

---

## RectangleShape(RectangleF) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`RectangleShape`](../../rectangleshape) فئة .

```csharp
public RectangleShape(RectangleF rectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rectangle | RectangleF | المستطيل. |

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

ينشئ هذا المثال صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures and GraphicsPath على سطح الصورة

```csharp
[C#]

// ينشئ مثيلاً لـ BmpOptions ويضبط خصائصه المختلفة            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل BmpOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

// إنشاء مثيل للصورة 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // إنشاء مثيل لفئة GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    // إنشاء مثيل لفئة الشكل
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    // إضافة شكل إلى كائن الشكل
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // إنشاء مثيل لفئة الشكل
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    // إضافة شكل إلى كائن الشكل
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    // إضافة كائن الشكل إلى GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // رسم المسار باستخدام كائن القلم ذي اللون الأسود
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // احفظ جميع التغييرات.
    image.Save();
}
```

### أنظر أيضا

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [RectangleShape](../../rectangleshape)
* مساحة الاسم [Aspose.Imaging.Shapes](../../rectangleshape)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
