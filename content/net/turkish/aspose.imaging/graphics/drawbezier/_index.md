---
title: DrawBezier
second_title: Aspose.Imaging for .NET API Referansı
description: Noktaları temsil eden sıralı dört koordinat çifti tarafından tanımlanan bir Bézier spline çizer.
type: docs
weight: 170
url: /tr/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Noktaları temsil eden sıralı dört koordinat çifti tarafından tanımlanan bir Bézier spline çizer.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve stilini belirler. |
| x1 | Single | Eğrinin başlangıç noktasının x koordinatı. |
| y1 | Single | Eğrinin başlangıç noktasının y koordinatı. |
| x2 | Single | Eğrinin ilk kontrol noktasının x koordinatı. |
| y2 | Single | Eğrinin ilk kontrol noktasının y koordinatı. |
| x3 | Single | Eğrinin ikinci kontrol noktasının x koordinatı. |
| y3 | Single | Eğrinin ikinci kontrol noktasının y koordinatı. |
| x4 | Single | Eğrinin bitiş noktasının x koordinatı. |
| y4 | Single | Eğrinin bitiş noktasının y koordinatı. |

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

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Dört ile tanımlanan bir Bézier spline çizer[`PointF`](../../pointf) yapılar.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve stilini belirler. |
| pt1 | PointF | [`PointF`](../../pointf) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | PointF | [`PointF`](../../pointf) eğri için ilk kontrol noktasını temsil eden yapı. |
| pt3 | PointF | [`PointF`](../../pointf) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | PointF | [`PointF`](../../pointf) eğrinin bitiş noktasını temsil eden yapı. |

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

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Dört ile tanımlanan bir Bézier spline çizer[`Point`](../../point) yapılar.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve stilini belirleyen yapı. |
| pt1 | Point | [`Point`](../../point) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | Point | [`Point`](../../point) eğri için ilk kontrol noktasını temsil eden yapı. |
| pt3 | Point | [`Point`](../../point) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | Point | [`Point`](../../point) eğrinin bitiş noktasını temsil eden yapı. |

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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
