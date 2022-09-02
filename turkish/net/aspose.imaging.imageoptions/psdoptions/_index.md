---
title: PsdOptions
second_title: Aspose.Imaging for .NET API Referansı
description: psd dosya biçimi seçenekler oluşturur.
type: docs
weight: 10140
url: /tr/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

psd dosya biçimi seçenekler oluşturur.

```csharp
public class PsdOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Yeni bir örneğini başlatır[`PsdOptions`](../psdoptions) sınıf. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Yeni bir örneğini başlatır[`PsdOptions`](../psdoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Renk kanalı başına bit sayısını alır veya ayarlar. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Renkli kanal sayısını alır veya ayarlar. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | psd renk modunu alır veya ayarlar. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | psd sıkıştırma yöntemini alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Dosya biçimi sürümünü alır veya ayarlar. PSD veya PSB olabilir. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | [Görüntü önizleme verilerini yenile] - seçeneğin diğer PSD resim görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılıp kullanılmadığını belirten bir değer alır veya ayarlar. Lütfen unutmayın, metin katmanlarının son düzene çizimi Compact Framework platformu için desteklenmez |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Şunları belirten bir değer alır veya ayarlar - Genel metin motoru kaynağını kaldır - Bazı metin katmanlı psd dosyaları için, yalnızca işlendikten sonra Adobe Photoshop'ta açılamadıkları zaman kullanılır (çoğunlukla metin katmanlarıyla ilgili olmayan fontlar için). Bu seçeneği kullandıktan sonra, kullanıcının Photoshop dosyasında açılan sonrakini yap: Menü "Metin" -&gt; "Yok yazı tiplerini işle". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | PSD vektörleştirme seçeneklerini alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | psd dosyası sürümünü alır veya ayarlar. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | XMP veri kapsayıcısını alın veya ayarlayın |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |

### Örnekler

Bu örnek, Görüntüleri PSD formatına dönüştürmek için Aspsoe.Imaging for .Net API'sinin kullanımını gösterir. Bu amaca ulaşmak için bu örnek, mevcut bir görüntüyü yükler ve ardından onu PSD formatına geri kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

//Görüntü sınıfının bir örneğini oluşturur ve onu Dosya yolu aracılığıyla mevcut bir dosyayla başlatır
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //PsdOptions sınıfının bir örneğini oluşturun
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //CompressionMethod'u RLE olarak ayarla
    //Not: Desteklenen diğer CompressionMethod, CompressionMethod.RAW'dır [Sıkıştırma Yok]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //ColorMode'u GrayScale olarak ayarlayın
    //Not: Desteklenen diğer ColorMode'lar ColorModes.Bitmap ve ColorModes.RGB'dir.
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Verilen PsdOptions ayarlarıyla görüntüyü disk konumuna kaydedin
    image.Save(dir + "output.psd", psdOptions);
}
```

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün belirli bir görüntü türüne başvurmadan genel olarak PSD formatına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Bu sayfalar çıktı PSD'sinde katmanlar olarak sunulacaktır.
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
