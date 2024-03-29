---
title: BackgroundColor
second_title: Aspose.Imaging for .NET API Referansı
description: Tarama çizgileri arasındaki boşlukların rengini alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/aspose.imaging.brushes/hatchbrush/backgroundcolor/
---
## HatchBrush.BackgroundColor property

Tarama çizgileri arasındaki boşlukların rengini alır veya ayarlar.

```csharp
public Color BackgroundColor { get; set; }
```

### Mülk değeri

Tarama çizgileri arasındaki boşlukların rengi.

### Örnekler

Bu örnek, Pen nesnelerinin oluşturulmasını ve kullanımını gösterir. Örnek, yeni bir Görüntü oluşturur ve Görüntü yüzeyinde Dikdörtgenler çizer.

```csharp
[C#]

// Bir BmpOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//FileCreateSource örneğini oluşturun ve bunu BmpOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Belirtilen Yolda bir Görüntü örneği oluştur
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Bir Graphics örneği oluşturun ve Image nesnesiyle başlatın
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // Grafik yüzeyini Beyaz Renk ile temizle
    graphics.Clear(Aspose.Imaging.Color.White);

    //Kırmızı renk ve 5 genişlikte bir Kalem örneği oluşturun
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //HatchBrush örneğini oluşturun ve özelliklerini ayarlayın
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Pen örneğini oluştur
    // HatchBrush nesnesi ve genişliği ile başlat
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //Pen nesnesini belirterek Dikdörtgenler çizin
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //Pen nesnesini belirterek Dikdörtgenler çizin
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // tüm değişiklikleri kaydet.
    image.Save();
}
```

### Ayrıca bakınız

* struct [Color](../../../aspose.imaging/color)
* class [HatchBrush](../../hatchbrush)
* ad alanı [Aspose.Imaging.Brushes](../../hatchbrush)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
