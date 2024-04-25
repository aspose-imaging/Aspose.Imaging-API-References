---
title: GifOptions
second_title: Aspose.Imaging for .NET API Referansı
description: GIF dosyası biçimi oluşturma seçenekleri.
type: docs
weight: 10000
url: /tr/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

GIF dosyası biçimi oluşturma seçenekleri.

```csharp
public class GifOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Yeni bir örneğini başlatır[`GifOptions`](../gifoptions) sınıf. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Yeni bir örneğini başlatır[`GifOptions`](../gifoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Arka plan rengini alır veya ayarlar. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | GIF arka plan rengi dizinini alır veya ayarlar. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | GIF renk çözünürlüğünü alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değer alır veya ayarlar. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | GIF'in fragmanı olup olmadığını belirten bir değer alır veya ayarlar. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | GIF görüntüsünün saydam renge sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Görüntü geçmeliyse doğrudur. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değer alır veya ayarlar. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Döngü sayısını alır veya ayarlar (Varsayılan 1 döngü) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | İzin verilen maksimum piksel farkını alır veya ayarlar. Sıfırdan büyükse kayıplı sıkıştırma kullanılacaktır. Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ağırdır. Sıkıştırma algoritmasının sınırlandırılması nedeniyle en iyi sonucu verir. çok yüksek kayıp seviyeleri o kadar kazanç sağlamaz. İzin verilen değerler aralığı [0, 1000]'dir. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | GIF piksel en boy oranını alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |

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

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün belirli bir görüntü türüne başvurmadan genel olarak GIF formatına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Bu sayfalar, çıktı GIF'inde animasyonlu çerçeveler olarak sunulacaktır.
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

Bu örnek, Piksel bilgilerinin bir Renk Türü Dizisine nasıl yükleneceğini, diziyi nasıl değiştireceğini ve görüntüye geri ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için bu örnek, MemoryStream nesnesini kullanan yeni bir Görüntü dosyası (GIF formatında) oluşturur.

```csharp
[C#]

//MemoryStream örneğini oluştur
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Bir GifOptions örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Görüntü örneğini oluştur
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Alanı görüntü sınırı olarak belirterek görüntünün piksellerini alın
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Dizi üzerinde dolaş ve alrenative indekslenmiş pikselin rengini ayarla
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Dizine alınmış piksel rengini sarıya ayarla
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Dizinli piksel rengini maviye ayarla
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        // Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    // MemoryStream'i Dosyaya Yaz
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
