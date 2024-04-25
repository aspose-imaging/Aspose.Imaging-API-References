---
title: Jpeg2000Options
second_title: Aspose.Imaging for .NET API Referansı
description: Jpeg2000 dosya biçimi seçenekleri.
type: docs
weight: 10020
url: /tr/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Jpeg2000 dosya biçimi seçenekleri.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Yeni bir örneğini başlatır[`Jpeg2000Options`](../jpeg2000options) sınıf. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Yeni bir örneğini başlatır[`Jpeg2000Options`](../jpeg2000options) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec) { get; set; } | JPEG2000 codec bileşenini alır veya ayarlar |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments) { get; set; } | Jpeg yorum işaretçilerini alır veya ayarlar. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios) { get; set; } | Dizi sıkıştırma oranını alır veya ayarlar. Ardışık katmanlar için farklı sıkıştırma oranları. Her kalite düzeyi için belirtilen oran, istenen sıkıştırma faktörüdür. Gerekli oranların azaltılması. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible) { get; set; } | Geri döndürülemez DWT 9-7 (doğru) veya kayıpsız DWT 5-3 sıkıştırması (varsayılan) kullandığını belirten bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.imaging.imageoptions/jpeg2000options/xmpdata) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |

### Örnekler

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün belirli bir görüntü türüne başvurmadan genel olarak JPEG 2000 biçimine nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, JPEG 2000 çok sayfalı bir format olmadığı için yalnızca bir sayfa rasterleştirilecektir.
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
