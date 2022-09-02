---
title: GraphicsPath
second_title: Aspose.Imaging for .NET API Referansı
description: Bir dizi bağlantılı çizgi ve eğriyi temsil eder. Bu sınıf devralınamaz.
type: docs
weight: 9370
url: /tr/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

Bir dizi bağlantılı çizgi ve eğriyi temsil eder. Bu sınıf devralınamaz.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Yeni bir örneğini başlatır[`GraphicsPath`](../graphicspath) sınıf. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Yeni bir örneğini başlatır[`GraphicsPath`](../graphicspath) sınıf. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Yeni bir örneğini başlatır[`GraphicsPath`](../graphicspath) sınıf. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Yeni bir örneğini başlatır[`GraphicsPath`](../graphicspath) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Nesnenin sınırlarını alır veya ayarlar. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Yol rakamlarını alır. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Alır veya ayarlar[`FillMode`](../fillmode) buradaki şekillerin içlerinin nasıl olduğunu belirleyen numaralandırma[`GraphicsPath`](../graphicspath) dolduruldu. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Yeni bir şekil ekler. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Yeni rakamlar ekler. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Belirtilenleri ekler[`GraphicsPath`](../graphicspath) bu yola. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Belirtilenleri ekler[`GraphicsPath`](../graphicspath) bu yola. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Bu grafik yolunun derin bir klonunu gerçekleştirir. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Bu yoldaki her eğriyi bir dizi bağlantılı çizgi parçasına dönüştürür. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Belirtilen dönüşümü uygular ve ardından her eğriyi bu[`GraphicsPath`](../graphicspath) bağlı çizgi segmentleri dizisine dönüştürün. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Buradaki her eğriyi dönüştürür[`GraphicsPath`](../graphicspath) bağlı çizgi segmentleri dizisine dönüştürün. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) ve belirtilenleri kullanarak[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) ve belirtilenleri kullanarak[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) ve belirtilenleri kullanarak[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Belirtilen noktanın bu[`GraphicsPath`](../graphicspath) belirtilen ile çizildiğinde[`Pen`](../pen) ve belirtilenleri kullanarak[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) belirtilenin görünür klip bölgesinde[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Belirtilen noktanın bunun içinde bulunup bulunmadığını gösterir.[`GraphicsPath`](../graphicspath) , belirtilenleri kullanarak[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Bir rakamı kaldırır. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Rakamları kaldırır. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Grafik yolunu boşaltır ve[`FillMode`](../fillmode) ileAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Bunun her şeklindeki şekillerin, şekillerin ve noktaların sırasını tersine çevirir[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Belirtilen dönüşümü şekle uygular. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Buna bir dikdörtgen ve bir paralelkenar ile tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Yola ek bir anahat ekler. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | [`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Bunu değiştirir[`GraphicsPath`](../graphicspath)bu yol belirtilen kalem tarafından çizildiğinde doldurulan alanı çevreleyen eğrilerle. |

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

### Ayrıca bakınız

* class [ObjectWithBounds](../objectwithbounds)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
