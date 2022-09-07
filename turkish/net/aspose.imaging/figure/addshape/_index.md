---
title: AddShape
second_title: Aspose.Imaging for .NET API Referansı
description: Şekle bir şekil ekler.
type: docs
weight: 60
url: /tr/net/aspose.imaging/figure/addshape/
---
## Figure.AddShape method

Şekle bir şekil ekler.

```csharp
public void AddShape(Shape shape)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| shape | Shape | Eklenecek şekil. |

### Örnekler

Bu örnekler, bir Görüntü yüzeyinde Şekiller oluşturmak ve işlemek için GraphicsPath ve Graphics sınıfını kullanır. Örnek, yeni bir Görüntü (Tiff tipinde) oluşturur, yüzeyi temizler ve GraphicsPath sınıfının yardımıyla yollar çizer. Sonunda, yolları yüzeyde işlemek için Graphics sınıfı tarafından sunulan DrawPath yöntemi çağrılır.

```csharp
[C#]

//FileStream örneğini oluştur
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    // Bir TiffOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // ImageOptions örneğinin kaynağını ayarlayın
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Görüntü örneğini oluştur 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        // Graphics sınıfının bir örneğini oluştur ve başlat
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafik yüzeyini temizle
        graphics.Clear(Color.Wheat);

        // GraphicsPath sınıfının bir örneğini oluştur
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        // Figure sınıfının bir örneğini oluşturun
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // Figure nesnesine Şekiller Ekle
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        // Figure nesnesini GraphicsPath'e ekle
        graphicspath.AddFigure(figure);

        // Siyah renkli Pen nesnesiyle yol çiz
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // tüm değişiklikleri kaydet.
        image.Save();
    }
}
```

Bu örnek, yeni bir Görüntü oluşturur ve Görüntü yüzeyinde Figures ve GraphicsPath kullanarak çeşitli şekiller çizer.

```csharp
[C#]

//BmpOptions örneğini oluşturur ve çeşitli özelliklerini ayarlar            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//FileCreateSource örneğini oluşturun ve bunu BmpOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Görüntü örneğini oluştur 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    // GraphicsPath sınıfının bir örneğini oluştur
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    // Figure sınıfının bir örneğini oluşturun
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    // Figure nesnesine Şekil Ekle
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // Figure sınıfının bir örneğini oluşturun
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    // Figure nesnesine Şekil Ekle
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    // Figure nesnesini GraphicsPath'e ekle
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Siyah renkli Pen nesnesiyle yol çiz
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // tüm değişiklikleri kaydet.
    image.Save();
}
```

### Ayrıca bakınız

* class [Shape](../../shape)
* class [Figure](../../figure)
* ad alanı [Aspose.Imaging](../../figure)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
