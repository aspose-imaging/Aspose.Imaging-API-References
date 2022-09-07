---
title: DrawPie
second_title: Aspose.Imaging for .NET API Referansı
description: tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.RectangleFaspose.imaging/rectanglef yapı ve iki radyal çizgi.
type: docs
weight: 280
url: /tr/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.[`RectangleF`](../../rectanglef) yapı ve iki radyal çizgi.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| startAngle | Single | x ekseninden pasta şeklinin ilk kenarına kadar saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Single | Saat yönünde derece cinsinden ölçülen açı*startAngle* pasta şeklinin ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Bir koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| x | Single | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Single | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Single | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Single | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Single | x ekseninden pasta şeklinin ilk kenarına kadar saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Single | Saat yönünde derece cinsinden ölçülen açı*startAngle* pasta şeklinin ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.[`Rectangle`](../../rectangle) yapı ve iki radyal çizgi.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| rect | Rectangle | [`Rectangle`](../../rectangle) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| startAngle | Single | x ekseninden pasta şeklinin ilk kenarına kadar saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Single | Saat yönünde derece cinsinden ölçülen açı*startAngle* pasta şeklinin ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Örnekler

Bu örnek, Görüntü yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PNG formatında yeni bir Görüntü oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Görüntü yüzeyine ilkel şekiller çizer.

```csharp
[C#]

//FileStream örneğini oluşturur
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //PngOptions örneğini oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //PngOptions için Kaynağı Ayarla
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Görüntü örneğini oluştur 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        // Graphics sınıfının bir örneğini oluştur ve başlat
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafik yüzeyini temizle
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
        //Yay, Başlangıç Açısı ve Süpürme Açısını çevreleyen bir Dikdörtgen
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Pen nesnesini Mavi renk ve koordinat Noktalarına sahip olarak belirterek bir Bezier çizin.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Yeşil renge ve bir dizi Noktaya sahip Pen nesnesini belirterek bir Eğri çizin
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Pen nesnesini ve çevresindeki Dikdörtgeni kullanarak bir Elips çizin
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Bir çizgi çiz 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Bir Pasta segmenti çizin
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Kırmızı renk ve bir dizi Noktaya sahip Pen nesnesini belirterek bir Çokgen çizin
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Bir Dikdörtgen Çiz
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //SolidBrush nesnesini ve Yazı Tipi'ni kullanarak belirli bir Noktada bir Dize çizin
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // tüm değişiklikleri kaydet.
        image.Save();
    }
}
```

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Bir koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| x | Int32 | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Int32 | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Int32 | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Int32 | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Int32 | x ekseninden pasta şeklinin ilk kenarına kadar saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Int32 | Saat yönünde derece cinsinden ölçülen açı*startAngle* pasta şeklinin ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
