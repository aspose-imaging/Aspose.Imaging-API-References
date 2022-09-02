---
title: FillPie
second_title: Aspose.Imaging for .NET API Referansı
description: tarafından belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.RectangleFaspose.imaging/rectanglef yapı ve iki radyal çizgi.
type: docs
weight: 370
url: /tr/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

tarafından belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.[`RectangleF`](../../rectanglef) yapı ve iki radyal çizgi.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) dolgunun özelliklerini belirler. |
| rect | Rectangle | [`Rectangle`](../../rectangle)pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| startAngle | Single | x ekseninden pasta bölümünün ilk tarafına saat yönünde ölçülen derece cinsinden açı. |
| sweepAngle | Single | Saat yönünde ölçülen derece cinsinden açı*startAngle* pasta bölümünün ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* boş. |

### Örnekler

Aşağıdaki örnek, tek tek GIF bloklarından bir animasyonlu GIF görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100 x 100 piksellik bir GIF görüntüsü oluşturun.
// İlk blok varsayılan olarak tamamen siyahtır.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // İlk daire kırmızı
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // İkinci daire siyah
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Kırmızı yay şeklinin açısını kademeli olarak artırın.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Siyah yayın açısını kademeli olarak artırın ve kırmızı yayı silin.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Ayrıca bakınız

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

tarafından belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.[`RectangleF`](../../rectanglef) yapı ve iki radyal çizgi.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) dolgunun özelliklerini belirler. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| startAngle | Single | x ekseninden pasta bölümünün ilk tarafına saat yönünde ölçülen derece cinsinden açı. |
| sweepAngle | Single | Saat yönünde ölçülen derece cinsinden açı*startAngle* pasta bölümünün ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* boş. |

### Ayrıca bakınız

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Bir çift koordinat, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) dolgunun özelliklerini belirler. |
| x | Single | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Single | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Single | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Single | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Single | x ekseninden pasta bölümünün ilk tarafına saat yönünde ölçülen derece cinsinden açı. |
| sweepAngle | Single | Saat yönünde ölçülen derece cinsinden açı*startAngle* pasta bölümünün ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* boş. |

### Ayrıca bakınız

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Bir çift koordinat, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan pasta bölümünün içini doldurur.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) dolgunun özelliklerini belirler. |
| x | Int32 | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Int32 | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Int32 | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Int32 | Pasta bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Int32 | x ekseninden pasta bölümünün ilk tarafına saat yönünde ölçülen derece cinsinden açı. |
| sweepAngle | Int32 | Saat yönünde ölçülen derece cinsinden açı*startAngle* pasta bölümünün ikinci tarafına parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* boş. |

### Ayrıca bakınız

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* ad alanı [Aspose.Imaging](../../graphics)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
