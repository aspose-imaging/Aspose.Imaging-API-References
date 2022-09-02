---
title: EpsImage
second_title: Aspose.Imaging for .NET API Referansı
description: EPS formatı için temel sınıf
type: docs
weight: 6560
url: /tr/net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

EPS formatı için temel sınıf

```csharp
public abstract class EpsImage : VectorImage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | Sınırlayıcı kutunun sol alt konumunu alır |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | BoundingBox dize değerini alır |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | Sağ üst konumdaki sınırlayıcı kutuyu alır |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | CreationDate alanını alır |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | CreationDate alanı dize değerini alır |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Oluşturan alanını alır |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| abstract [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype) { get; } | EPS alt türü değerini alır |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| abstract [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview) { get; } | Bu örneğin biçime özgü tarama önizlemesine sahip olup olmadığını gösteren bir değer alır |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Görüntü yüksekliğini alır. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Nesne yüksekliğini inç cinsinden alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | Sayfa numarasını alır |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | Sayfa sayısını alır |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | Photoshop önizleme küçük resmini alır (ilk EPS verilerinde varsa) |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | PostScript sürümünü alır field |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Nesne boyutunu inç cinsinden alır. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Başlık alanını alır |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Görüntü genişliğini alır. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Nesne genişliğini inç cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | Önbellek kullanılamaz. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Gömülü görüntüleri alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Örnekler

EPS görüntüsünü yeniden boyutlandırın ve PNG formatına aktarın.

```csharp
[C#]

// EPS görüntüsünü yükle
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Mitchell kübik enterpolasyon yöntemini kullanarak görüntüyü yeniden boyutlandırın
    image.Resize(400, 400, ResizeType.Mitchell);

    // Resmi PNG formatına aktar
    image.Save("ExportResult.png", new PngOptions());
}
```

PostScript işlemeyi kullanarak EPS görüntüsünü PDF'ye dönüştürün.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Gerekli PDF uyumluluğunu ayarla
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

PostScript işlemeyi kullanarak EPS görüntüsünü PNG'ye dönüştürün.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // Resim Genişliği
            PageHeight = 500 // Görüntü yüksekliği
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // PostScript kullanarak raster görüntü oluştur
        }
    };

    image.Save("Sample.png", options);
}
```

Gelişmiş ayarları kullanarak EPS görüntüsünü yeniden boyutlandırın.

```csharp
[C#]

// EPS görüntüsünü yükle
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Gelişmiş yeniden boyutlandırma ayarlarını kullanarak görüntüyü yeniden boyutlandırın
    image.Resize(400, 400, new ImageResizeSettings
    {
        // enterpolasyon modunu ayarla
        Mode = ResizeType.LanczosResample,

        // Filtrenin türünü ayarla
        FilterType = ImageFilterType.SmallRectangular,

        // Renk karşılaştırma yöntemini ayarlar
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // Renk niceleme yöntemini ayarla
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // Resmi PNG formatına aktar
    image.Save("ExportResult.png", new PngOptions());
}
```

### Ayrıca bakınız

* class [VectorImage](../../aspose.imaging/vectorimage)
* ad alanı [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
