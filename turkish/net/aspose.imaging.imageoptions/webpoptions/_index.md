---
title: WebPOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Webp görüntü seçenekleri
type: docs
weight: 10280
url: /tr/net/aspose.imaging.imageoptions/webpoptions/
---
## WebPOptions class

Webp görüntü seçenekleri

```csharp
public class WebPOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WebPOptions](webpoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AnimBackgroundColor](../../aspose.imaging.imageoptions/webpoptions/animbackgroundcolor) { get; set; } | Animasyon arka planının rengini alır veya ayarlar. |
| [AnimLoopCount](../../aspose.imaging.imageoptions/webpoptions/animloopcount) { get; set; } | Animasyon döngü sayısını alır veya ayarlar. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [Lossless](../../aspose.imaging.imageoptions/webpoptions/lossless) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`WebPOptions`](../webpoptions) kayıpsızdır. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| [Quality](../../aspose.imaging.imageoptions/webpoptions/quality) { get; set; } | Kaliteyi alır veya ayarlar. |
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

Bu örnek, farklı sıkıştırma kalitesine sahip başka bir tarama görüntüsünden bir WebP görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// GIF animasyonu yükle
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // kayıpsız sıkıştırma için kalite ayarını artırmak sıkıştırma kalitesini artırır ve dosya boyutunu küçültür
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // dosya boyutu: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // dosya boyutu: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // dosya boyutu: 40 KB


    // kayıplı sıkıştırma için Kalite değerini artırmak görüntü kalitesini artırır ve dosya boyutunu artırır
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // dosya boyutu: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // dosya boyutu: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // dosya boyutu: 51 KB
}
```

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün belirli bir görüntü türüne başvurmadan genel olarak WEBP biçimine nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.webp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.WebPOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Bu sayfalar WEBP çıktısında animasyonlu çerçeveler olarak sunulacaktır.
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
