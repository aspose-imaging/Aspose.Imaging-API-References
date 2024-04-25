---
title: DrawLine
second_title: Aspose.Imaging for .NET API Referansı
description: İkiyi birbirine bağlayan bir çizgi çizerPointaspose.imaging/point yapılar.
type: docs
weight: 250
url: /tr/aspose.imaging/graphics/drawline/
---
## DrawLine(Pen, Point, Point) {#drawline}

İkiyi birbirine bağlayan bir çizgi çizer[`Point`](../../point) yapılar.

```csharp
public void DrawLine(Pen pen, Point point1, Point point2)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | Point | [`Point`](../../point) bağlanacak ilk noktayı temsil eden yapı. |
| point2 | Point | [`Point`](../../point) bağlanılacak ikinci noktayı temsil eden yapı. |

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
* struct [Point](../../point)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawLine(Pen, PointF, PointF) {#drawline_1}

İkiyi birbirine bağlayan bir çizgi çizer[`PointF`](../../pointf) yapılar.

```csharp
public void DrawLine(Pen pen, PointF point1, PointF point2)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | PointF | [`PointF`](../../pointf) bağlanacak ilk noktayı temsil eden yapı. |
| point2 | PointF | [`PointF`](../../pointf) bağlanılacak ikinci noktayı temsil eden yapı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawLine(Pen, int, int, int, int) {#drawline_2}

Koordinat çiftleri tarafından belirtilen iki noktayı birleştiren bir çizgi çizer.

```csharp
public void DrawLine(Pen pen, int x1, int y1, int x2, int y2)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | Int32 | İlk noktanın x koordinatı. |
| y1 | Int32 | İlk noktanın y koordinatı. |
| x2 | Int32 | İkinci noktanın x koordinatı. |
| y2 | Int32 | İkinci noktanın y koordinatı. |

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

## DrawLine(Pen, float, float, float, float) {#drawline_3}

Koordinat çiftleri tarafından belirtilen iki noktayı birleştiren bir çizgi çizer.

```csharp
public void DrawLine(Pen pen, float x1, float y1, float x2, float y2)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | Single | İlk noktanın x koordinatı. |
| y1 | Single | İlk noktanın y koordinatı. |
| x2 | Single | İkinci noktanın x koordinatı. |
| y2 | Single | İkinci noktanın y koordinatı. |

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
