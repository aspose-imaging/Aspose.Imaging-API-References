---
title: Pen
second_title: Aspose.Imaging for .NET API Referansı
description: Çizgiler eğriler ve şekiller çizmek için kullanılan bir nesneyi tanımlar.
type: docs
weight: 10690
url: /tr/net/aspose.imaging/pen/
---
## Pen class

Çizgiler, eğriler ve şekiller çizmek için kullanılan bir nesneyi tanımlar.

```csharp
public class Pen : TransparencySupporter
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Yeni bir örneğini başlatır[`Pen`](../pen) belirtilen sınıf[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Yeni bir örneğini başlatır[`Pen`](../pen) belirtilen renge sahip sınıf. |
| [Pen](pen#constructor_1)(Brush, float) | Yeni bir örneğini başlatır[`Pen`](../pen) belirtilen sınıf[`Brush`](./brush) ve[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Yeni bir örneğini başlatır[`Pen`](../pen) belirtilen sınıf[`Color`](./color) ve[`Width`](./width) özellikler. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Bunun için hizalamayı alır veya ayarlar[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Alır veya ayarlar[`Brush`](./brush) bu özellikleri belirleyen[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Bunun rengini alır veya ayarlar[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Bileşik kalemi belirten bir dizi değer alır veya ayarlar. Bileşik kalem, paralel çizgilerden ve boşluklardan oluşan bir bileşik çizgi çizer. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Bununla çizilen satırların sonunda kullanılacak özel bir başlık alır veya ayarlar[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Bununla çizilen satırların başında kullanılacak özel bir başlık alır veya ayarlar[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Bununla çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan büyük harf stilini alır veya ayarlar[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Çizginin başlangıcından kısa çizgi deseninin başlangıcına kadar olan mesafeyi alır veya ayarlar. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Bir dizi özel tire ve boşluk alır veya ayarlar. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Bununla çizilen kesikli çizgiler için kullanılan stili alır veya ayarlar[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Bununla çizilen satırların sonunda kullanılan büyük harf stilini alır veya ayarlar[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Bununla çizilen iki ardışık çizginin sonları için birleştirme stilini alır veya ayarlar[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Köşeli bir köşede birleştirmenin kalınlığının sınırını alır veya ayarlar. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Nesnenin opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri nesnenin tamamen görünür olduğu, 1 değeri nesnenin tamamen opak olduğu anlamına gelir. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Bununla çizilen çizgilerin stilini alır[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Bununla çizilen satırların başında kullanılan büyük harf stilini alır veya ayarlar[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Bunun için geometrik dönüşümün bir kopyasını alır veya ayarlar[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Bunun genişliğini alır veya ayarlar[`Pen`](../pen) , çizim için kullanılan Graphics nesnesinin birimlerinde. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Bunun için dönüşüm matrisini çarpar[`Pen`](../pen) belirtilen tarafından[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Bunun için dönüşüm matrisini çarpar[`Pen`](../pen) belirtilen tarafından[`Matrix`](../matrix) belirtilen sırada. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Bunun için geometrik dönüşüm matrisini sıfırlar[`Pen`](../pen) kimliğe. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem, dönüşü dönüşüme hazırlar. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen açıyla döndürür. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen faktörlere göre ölçekler. Bu yöntem, ölçeklendirme matrisini dönüşümün başına ekler. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen faktörlere göre ölçeklendirir. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Bunun tarafından çizilen satırları sonlandırmak için kullanılan başlık stilini belirleyen değerleri ayarlar.[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Belirtilen boyutlara göre yerel geometrik dönüşümü öteler. Bu yöntem, dönüşüme çeviriyi hazırlar. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen boyutlara göre çevirir. |

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

* class [TransparencySupporter](../transparencysupporter)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
