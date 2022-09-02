---
title: ApngOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Animasyonlu PNG dosya formatı seçenekleri
type: docs
weight: 9900
url: /tr/net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Animasyonlu PNG dosya formatı seçenekleri

```csharp
public class ApngOptions : PngOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ApngOptions](apngoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | Bit derinliği. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Rengin türünü alır veya ayarlar. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | 9'un maksimum sıkıştırma ve 0'ın depolama modu olduğu 0-9 aralığında png görüntü sıkıştırma düzeyi. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Varsayılan kare süresini alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | png dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır veya ayarlar. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Döngü animasyonu sayısını alır veya ayarlar. 0 sonsuz döngüyü belirtir. |
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

### Örnekler

Aşağıdaki örnek, apng APNG dosya biçiminin diğer animasyonlu olmayan çok sayfalı biçimden nasıl dışa aktarılacağını gösterir.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Varsayılan çerçeve süresini ayarlama
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

Aşağıdaki örnek, APNG dosya biçimine nasıl dışa aktarılacağını gösterir.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Varsayılan olarak sınırsız animasyon döngüsüyle APNG animasyonuna aktar
    image.Save("Animation1.webp.png", new ApngOptions());
    // Animasyon döngülerini ayarlama
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 döngü
}
```

Aşağıdaki örnek, başka bir tarama tek sayfalı görüntüden APNG görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 sn
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // Orada görüntü varsayılan çerçeve süresini ayarlamak mümkündür: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Görüntü varsayılan olarak bir kare içerdiğinden temizleme
        apngImage.RemoveAllFrames();

        // ilk kareyi ekle
        apngImage.AddFrame(sourceImage);

        // ara çerçeveler ekle
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // son kareyi ekle
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Ayrıca bakınız

* class [PngOptions](../pngoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
