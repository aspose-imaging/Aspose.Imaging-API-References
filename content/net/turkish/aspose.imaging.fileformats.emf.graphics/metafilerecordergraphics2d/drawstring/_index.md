---
title: DrawString
second_title: Aspose.Imaging for .NET API Referansı
description: Dizeyi çizer.
type: docs
weight: 160
url: /tr/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/
---
## DrawString(string, Font, Color, int, int) {#drawstring}

Dizeyi çizer.

```csharp
public void DrawString(string @string, Font font, Color color, int x, int y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| string | String | Dize. |
| font | Font | Dizenin metin biçimini tanımlayan yazı tipi. |
| color | Color | Metin rengi. |
| x | Int32 | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | Int32 | Çizilen metnin sol üst köşesinin y koordinatı. |

### Örnekler

Bu örnek, bir dosyadan bir EMF görüntüsünün nasıl yükleneceğini ve üzerine bir metin dizesinin nasıl çizileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
        Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D.FromEmfImage(emfImage);

    // İlk olarak, resmin boyutunu alın
    int width = emfImage.Width;
    int height = emfImage.Height;

    // İkinci olarak, görüntünün ana köşegeni boyunca bir metin dizesi koymak için bir dönüşüm hesaplayın -
    // sol üst köşeden sağ üst köşeye.
    float emFontSize = 96f;
    float d = (float)System.Math.Sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float)height) / width;                
    double radians = System.Math.Atan(tan);
    double degrees = (180 * radians) / System.Math.PI;

    Aspose.Imaging.Matrix transform = new Aspose.Imaging.Matrix();
    transform.Rotate((float)degrees);
    transform.Scale(scaleFactor, scaleFactor);

    // Ardından, dönüşümü ayarlayın.
    graphics.SetTransform(transform);

    // Son olarak, ana köşegen boyunca bir filigran (pembe renkli metin dizisi) koyun.
    graphics.DrawString("WATERMARK", new Aspose.Imaging.Font("Courier New", emFontSize), Aspose.Imaging.Color.LightPink, 0, 0/*, (float)degrees*/);

    // Resmi filigranlı olarak başka bir EMF dosyasına kaydedin.
    using (Aspose.Imaging.FileFormats.Emf.EmfImage scaledEmfImage = graphics.EndRecording())
    {
        scaledEmfImage.Save(dir + "test.scaled.emf");
    }
}
```

Bu örnek, bir WMF görüntüsünün nasıl oluşturulacağını ve WmfRecorderGraphics2D kullanarak bazı geometrik şekillerin nasıl çizileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Bu, varsayılan ekran çözünürlüğüdür.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Bir WMF görüntüsü oluşturun.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// 1 piksel genişliğinde siyah bir kalem kullanarak görüntü kenarları boyunca siyah bir dikdörtgen çizin.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// 2 piksel genişliğinde mavi bir kalem kullanarak {0, 0, 200, 200} dikdörtgeni içinde bir yay çizin.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Bir yayı doldur
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 2 piksel genişliğinde kırmızı bir kalem kullanarak bir kübik bezier çizin.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Belirtilen konumda belirtilen boyutta bir raster görüntü çizin.
// Görüntü, istenen dikdörtgene sığacak şekilde ölçeklenir.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Bir metin dizesi çiz
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekiyor.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Tüm çizim komutlarını içeren son WMF görüntüsünü alın
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

Bu örnek, bir EMF görüntüsünün nasıl oluşturulacağını ve EmfRecorderGraphics2D kullanılarak bunun üzerine bazı geometrik şekillerin nasıl çizileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Piksel cinsinden görüntü boyutu
int deviceWidth = 600;
int deviceHeight = 400;

// Milimetre cinsinden görüntü boyutu
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Bir EMF görüntüsü oluşturun.
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// 1 piksel genişliğinde siyah bir kalem kullanarak görüntü kenarları boyunca siyah bir dikdörtgen çizin.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// 2 piksel genişliğinde mavi bir kalem kullanarak {0, 0, 200, 200} dikdörtgeni içinde bir yay çizin.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Bir yayı doldur
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 2 piksel genişliğinde kırmızı bir kalem kullanarak bir kübik bezier çizin.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Belirtilen konumda belirtilen boyutta bir raster görüntü çizin.
// Görüntü, istenen dikdörtgene sığacak şekilde ölçeklenir.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Bir metin dizesi çiz
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekiyor.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Tüm çizim komutlarını içeren son WMF görüntüsünü alın
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### Ayrıca bakınız

* class [Font](../../../aspose.imaging/font)
* struct [Color](../../../aspose.imaging/color)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* toplantı [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Color, int, int, float) {#drawstring_1}

Dizeyi çizer.

```csharp
public void DrawString(string @string, Font font, Color color, int x, int y, float angle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| string | String | Dize. |
| font | Font | Dizenin metin biçimini tanımlayan yazı tipi. |
| color | Color | Metin rengi. |
| x | Int32 | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | Int32 | Çizilen metnin sol üst köşesinin y koordinatı. |
| angle | Single | Eşapman vektörü ile cihazın x ekseni arasındaki derece cinsinden açı. Eşapman vektörü, bir metin satırının taban çizgisine paraleldir. |

### Ayrıca bakınız

* class [Font](../../../aspose.imaging/font)
* struct [Color](../../../aspose.imaging/color)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
