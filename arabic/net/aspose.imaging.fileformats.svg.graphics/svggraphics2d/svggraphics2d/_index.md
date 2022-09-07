---
title: SvgGraphics2D
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفSvgGraphics2Daspose.imaging.fileformats.svg.graphics/svggraphics2d فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/svggraphics2d/
---
## SvgGraphics2D(int, int, int) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`SvgGraphics2D`](../../svggraphics2d) فئة .

```csharp
public SvgGraphics2D(int width, int height, int dpi)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض صورة Svg الناتجة. |
| height | Int32 | عرض صورة Svg الناتجة. |
| dpi | Int32 | دقة الجهاز ، على سبيل المثال 96 نقطة في البوصة. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة SVG بالحجم المحدد وتنقيطها إلى PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 100;
int imageHeight = 100;
int dpi = 96;

// قم بإنشاء صورة SVG بحجم 100 × 100 بكسل.
Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 10);
Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

// املأ الصورة بأكملها باللون الأحمر.
// ارسم مستطيلًا أصفر بعرض 10 بكسل على طول حدود الصورة.
graphics.FillRectangle(pen, brush, 0, 0, imageWidth, imageHeight);

// احصل على صورة Svg النهائية التي تتضمن جميع أوامر الرسم
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

يوضح هذا المثال كيفية إنشاء صورة SVG بالحجم المحدد ورسم أشكال مختلفة عليها باستخدام SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// ارسم مستطيلًا أسود على طول حدود الصورة باستخدام قلم أسود بعرض 1 بكسل.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// املأ مستطيلاً بلون الدخان الأبيض.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// ارسم خطين قطريين باستخدام قلم أخضر غامق بعرض 1 بكسل.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// ارسم قوسًا داخل المستطيل {0 ، 0 ، 200 ، 200} باستخدام قلم أزرق بعرض 2 بكسل.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// املأ قوسًا
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// ارسم بيزيرًا مكعبًا باستخدام قلم أحمر بعرض 2 بكسل.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
// تم تحجيم الصورة لتناسب المستطيل المطلوب.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// ارسم سلسلة نصية
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// إنشاء مسار لملء
Aspose.Imaging.Figure figureToFill = new Aspose.Imaging.Figure();
figureToFill.IsClosed = true;

Aspose.Imaging.GraphicsPath pathToFill = new Aspose.Imaging.GraphicsPath();
pathToFill.AddFigure(figureToFill);

figureToFill.AddShapes(new Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.Rectangle(400, 0, 200, 100), 45, 300),
        new Aspose.Imaging.Shapes.BezierShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 200),
                new Aspose.Imaging.PointF(400, 200),
                new Aspose.Imaging.PointF(500, 100),
                new Aspose.Imaging.PointF(600, 200),
            }),
        new Aspose.Imaging.Shapes.PolygonShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 100),
            }),
        new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(0, 100, 200, 200)),
    });

// املأ المسار باستخدام فرشاة صفراء وقلم أخضر لرسم مخطط تفصيلي
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// إنشاء مسار للرسم
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// ارسم المسار باستخدام قلم برتقالي بعرض 5 بكسل.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// احصل على صورة SVG النهائية التي تتضمن جميع أوامر الرسم
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### أنظر أيضا

* class [SvgGraphics2D](../../svggraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* المجسم [Aspose.Imaging](../../../)

---

## SvgGraphics2D(SvgImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`SvgGraphics2D`](../../svggraphics2d) فئة .

```csharp
public SvgGraphics2D(SvgImage image)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | SvgImage | الصورة التي سيتم تنفيذ عمليات الرسم عليها. |

### أنظر أيضا

* class [SvgImage](../../../aspose.imaging.fileformats.svg/svgimage)
* class [SvgGraphics2D](../../svggraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
