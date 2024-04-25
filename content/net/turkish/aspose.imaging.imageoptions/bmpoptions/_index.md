---
title: BmpOptions
second_title: Aspose.Imaging for .NET API Referansı
description: bmp dosya biçimi oluşturma seçenekleri.
type: docs
weight: 9910
url: /tr/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

bmp dosya biçimi oluşturma seçenekleri.

```csharp
public class BmpOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [BmpOptions](bmpoptions#constructor)() | Yeni bir örneğini başlatır[`BmpOptions`](../bmpoptions) sınıf. |
| [BmpOptions](bmpoptions#constructor_1)(BmpOptions) | Yeni bir örneğini başlatır[`BmpOptions`](../bmpoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel) { get; set; } | Piksel sayısı başına görüntü bitlerini alır veya ayarlar. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression) { get; set; } | Sıkıştırmayı alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |

### Örnekler

Bu örnek, BmpOptions örneğinin Source özelliği tarafından belirtildiği gibi bazı disk konumlarında yeni bir Görüntü dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce BmpOptions örneği için çeşitli özellikler ayarlanır. Özellikle bu durumda gerçek disk konumuna atıfta bulunan Source özelliği.

```csharp
[C#]

// Bir BmpOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//FileCreateSource örneğini oluşturun ve bunu BmpOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

// Bir Image örneği oluşturun ve Create yöntemini çağırarak bunu BmpOptions örneğiyle başlatın
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // biraz görüntü işleme yap

    // tüm değişiklikleri kaydet
    image.Save();
}
```

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

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün, belirli bir görüntü türüne başvurmadan genel olarak BMP formatına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, BMP çok sayfalı bir format olmadığı için yalnızca bir sayfa rasterleştirilecektir.
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

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
