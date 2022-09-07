---
title: SvgGraphics2D
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırSvgGraphics2Daspose.imaging.fileformats.svg.graphics/svggraphics2d sınıf.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/svggraphics2d/
---
## SvgGraphics2D(int, int, int) {#constructor_1}

Yeni bir örneğini başlatır[`SvgGraphics2D`](../../svggraphics2d) sınıf.

```csharp
public SvgGraphics2D(int width, int height, int dpi)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Çıktı Svg görüntüsünün genişliği. |
| height | Int32 | Çıktı Svg görüntüsünün genişliği. |
| dpi | Int32 | Cihaz çözünürlüğü, örneğin inç başına 96 nokta. |

### Örnekler

Bu örnek, belirtilen boyutta bir SVG görüntüsünün nasıl oluşturulacağını ve PNG olarak rasterleştirileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 100;
int imageHeight = 100;
int dpi = 96;

// 100x100 piksellik bir SVG görüntüsü oluşturun.
Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 10);
Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

// Resmin tamamını kırmızı ile doldurun.
// Görüntü sınırları boyunca 10 piksel genişliğinde sarı bir dikdörtgen çizin.
graphics.FillRectangle(pen, brush, 0, 0, imageWidth, imageHeight);

// Tüm çizim komutlarını içeren son Svg görüntüsünü alın
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

Bu örnek, belirtilen boyutta bir SVG görüntüsünün nasıl oluşturulacağını ve SvgGraphics2D kullanılarak bunun üzerine farklı şekiller çizileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// 1 piksel genişliğinde siyah bir kalem kullanarak görüntü kenarları boyunca siyah bir dikdörtgen çizin.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// 2 piksel genişliğinde mavi bir kalem kullanarak {0, 0, 200, 200} dikdörtgeni içinde bir yay çizin.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Bir yayı doldur
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 2 piksel genişliğinde kırmızı bir kalem kullanarak bir kübik bezier çizin.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Belirtilen konumda belirtilen boyutta bir raster görüntü çizin.
// Görüntü, istenen dikdörtgene sığacak şekilde ölçeklenir.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Bir metin dizesi çiz
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Doldurulacak bir yol oluştur
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

// Anahat çizmek için sarı bir fırça ve yeşil bir kalem kullanarak yolu doldurun
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Çizmek için bir yol oluşturun
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// 5 piksel genişliğinde turuncu bir kalem kullanarak yolu çizin.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Tüm çizim komutlarını içeren son SVG görüntüsünü alın
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Ayrıca bakınız

* class [SvgGraphics2D](../../svggraphics2d)
* ad alanı [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* toplantı [Aspose.Imaging](../../../)

---

## SvgGraphics2D(SvgImage) {#constructor}

Yeni bir örneğini başlatır[`SvgGraphics2D`](../../svggraphics2d) sınıf.

```csharp
public SvgGraphics2D(SvgImage image)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | SvgImage | Üzerinde çizim işlemlerinin gerçekleştirileceği görüntü. |

### Ayrıca bakınız

* class [SvgImage](../../../aspose.imaging.fileformats.svg/svgimage)
* class [SvgGraphics2D](../../svggraphics2d)
* ad alanı [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
