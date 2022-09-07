---
title: DrawImage
second_title: Aspose.Imaging لمرجع NET API
description: رسم الصورة المحددة  باستخدام حجمها المادي الأصلي  في المكان المحدد.
type: docs
weight: 80
url: /ar/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

رسم الصورة المحددة ، باستخدام حجمها المادي الأصلي ، في المكان المحدد.

```csharp
public void DrawImage(RasterImage image, Point location)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد رسمها. |
| location | Point | موقع الزاوية اليسرى العلوية للصورة المرسومة. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* المجسم [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Rectangle, Rectangle, GraphicsUnit) {#drawimage_1}

رسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد رسمها. |
| destRect | Rectangle | هيكل المستطيل الذي يحدد موقع وحجم الصورة المرسومة. تم تحجيم الصورة لتناسب المستطيل. |
| srcRect | Rectangle | هيكل المستطيل الذي يحدد الجزء المراد رسمه من كائن الصورة. |
| srcUnit | GraphicsUnit | وحدات القياس المستخدمة بواسطة معلمة srcRect. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | srcUnit ؛ دعم وحدة البكسل فقط |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة WMF ورسم بعض الأشكال الهندسية باستخدام WmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// هذه هي دقة الشاشة الافتراضية.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// قم بإنشاء صورة WMF.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// ارسم مستطيلًا أسود على طول حدود الصورة باستخدام قلم أسود بعرض 1 بكسل.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// املأ مستطيلاً بلون الدخان الأبيض.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// ارسم خطين قطريين باستخدام قلم أخضر غامق بعرض 1 بكسل.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// ارسم قوسًا داخل المستطيل {0 ، 0 ، 200 ، 200} باستخدام قلم أزرق بعرض 2 بكسل.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// املأ قوسًا
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// ارسم بيزيرًا مكعبًا باستخدام قلم أحمر بعرض 2 بكسل.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
// تم تحجيم الصورة لتناسب المستطيل المطلوب.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// ارسم سلسلة نصية
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// من أجل تحويل SVG إلى صيغة نقطية ، نحتاج إلى تحديد خيارات التنقيط.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// احصل على صورة WMF النهائية التي تتضمن جميع أوامر الرسم
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

يوضح هذا المثال كيفية إنشاء صورة EMF ورسم بعض الأشكال الهندسية عليها باستخدام EmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

// حجم الصورة بالبكسل
int deviceWidth = 600;
int deviceHeight = 400;

// حجم الصورة بالميليمتر
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// إنشاء صورة EMF.
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// ارسم مستطيلًا أسود على طول حدود الصورة باستخدام قلم أسود بعرض 1 بكسل.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// املأ مستطيلاً بلون الدخان الأبيض.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// ارسم خطين قطريين باستخدام قلم أخضر غامق بعرض 1 بكسل.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// ارسم قوسًا داخل المستطيل {0 ، 0 ، 200 ، 200} باستخدام قلم أزرق بعرض 2 بكسل.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// املأ قوسًا
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// ارسم بيزيرًا مكعبًا باستخدام قلم أحمر بعرض 2 بكسل.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
// تم تحجيم الصورة لتناسب المستطيل المطلوب.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// ارسم سلسلة نصية
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// من أجل تحويل SVG إلى صيغة نقطية ، نحتاج إلى تحديد خيارات التنقيط.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// احصل على صورة WMF النهائية التي تتضمن جميع أوامر الرسم
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* المجسم [Aspose.Imaging](../../../)

---

## DrawImage(byte[], Rectangle, GraphicsUnit) {#drawimage_2}

يرسم الصورة .

```csharp
public void DrawImage(byte[] imageBytes, Rectangle destRect, GraphicsUnit srcUnit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageBytes | Byte[] | بايت الصورة. |
| destRect | Rectangle | وجه مستقيم. |
| srcUnit | GraphicsUnit | وحدة المصدر. |

### أنظر أيضا

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* المجسم [Aspose.Imaging](../../../)

---

## DrawImage(Stream, Rectangle, GraphicsUnit) {#drawimage_3}

يرسم الصورة .

```csharp
public void DrawImage(Stream stream, Rectangle destRect, GraphicsUnit srcUnit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق. |
| destRect | Rectangle | وجه مستقيم. |
| srcUnit | GraphicsUnit | وحدة المصدر. |

### أنظر أيضا

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
