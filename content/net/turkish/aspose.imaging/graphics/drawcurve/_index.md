---
title: DrawCurve
second_title: Aspose.Imaging for .NET API Referansı
description: Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.PointFaspose.imaging/pointf yapılar. Bu yöntem 05. varsayılan gerilimi kullanır
type: docs
weight: 200
url: /tr/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../../pointf) yapılar. Bu yöntem, 0,5. varsayılan gerilimi kullanır

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf) spline'ı tanımlayan yapılar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../../pointf) belirli bir gerilimi kullanan yapılar.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf) eğriyi tanımlayan noktaları temsil eden yapılar. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../../pointf) yapılar. Çizim, dizinin başlangıcından ofset olarak başlar. Bu yöntem, 0,5. varsayılan gerilimini kullanır.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf) spline'ı tanımlayan yapılar. |
| offset | Int32 | dizisindeki ilk elemandan ofset*points* parametreyi eğrideki başlangıç noktasına ayarlayın. |
| numberOfSegments | Int32 | Başlangıç noktasından sonra eğriye dahil edilecek segment sayısı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`PointF`](../../pointf)Belirli bir gerilim kullanan yapılar. Çizim, dizinin başından itibaren ofset ile başlar.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf) spline'ı tanımlayan yapılar. |
| offset | Int32 | dizisindeki ilk elemandan ofset*points* parametreyi eğrideki başlangıç noktasına ayarlayın. |
| numberOfSegments | Int32 | Başlangıç noktasından sonra eğriye dahil edilecek segment sayısı. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`Point`](../../point) yapılar.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | Point[] | dizisi[`Point`](../../point) spline'ı tanımlayan yapılar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

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

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`Point`](../../point) belirli bir gerilimi kullanan yapılar.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | Point[] | dizisi[`Point`](../../point) spline'ı tanımlayan yapılar. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Belirtilen bir dizi aracılığıyla bir ana eğri çizgi çizer.[`Point`](../../point) belirli bir gerilimi kullanan yapılar.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | Point[] | dizisi[`Point`](../../point) spline'ı tanımlayan yapılar. |
| offset | Int32 | dizisindeki ilk elemandan ofset*points* parametreyi eğrideki başlangıç noktasına ayarlayın. |
| numberOfSegments | Int32 | Başlangıç noktasından sonra eğriye dahil edilecek segment sayısı. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
