---
title: PngOptions
second_title: Aspose.Imaging for .NET API Referansı
description: png dosya biçimi seçenekler oluşturur.
type: docs
weight: 10120
url: /tr/aspose.imaging.imageoptions/pngoptions/
---
## PngOptions class

png dosya biçimi seçenekler oluşturur.

```csharp
public class PngOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PngOptions](pngoptions#constructor)() | Yeni bir örneğini başlatır[`PngOptions`](../pngoptions) sınıf. |
| [PngOptions](pngoptions#constructor_1)(PngOptions) | Yeni bir örneğini başlatır[`PngOptions`](../pngoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | Bit derinliği. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Rengin türünü alır veya ayarlar. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | 9'un maksimum sıkıştırma ve 0'ın depolama modu olduğu 0-9 aralığında png görüntü sıkıştırma düzeyi. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | png dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır veya ayarlar. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`PngOptions`](../pngoptions) ilericidir. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/defaultcompressionlevel) | Varsayılan sıkıştırma düzeyi. |

### Örnekler

Bu örnek, dışa aktarma amacıyla SaveOptions Ad Alanından farklı sınıfların kullanımını gösterir. Gif türünde bir görüntü, bir Görüntü örneğine yüklenir ve ardından çeşitli biçimlere dışa aktarılır.

```csharp
[C#]

string dir = "c:\\temp\\";

//Mevcut bir görüntüyü (Gif türünde) bir Image sınıfı örneğine yükleyin
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Varsayılan seçenekleri kullanarak BMP dosya formatına aktar
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına aktar
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına aktar
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına aktar
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün belirli bir görüntü türüne başvurmadan genel olarak PNG biçimine nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.png");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, PNG çok sayfalı bir biçim olmadığı için yalnızca bir sayfa rasterleştirilir.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

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

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
