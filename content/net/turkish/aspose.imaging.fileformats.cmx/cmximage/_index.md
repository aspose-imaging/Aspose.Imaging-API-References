---
title: CmxImage
second_title: Aspose.Imaging for .NET API Referansı
description: CMX görüntüsü.
type: docs
weight: 1900
url: /tr/aspose.imaging.fileformats.cmx/cmximage/
---
## CmxImage class

CMX görüntüsü.

```csharp
public class CmxImage : VectorMultipageImage, ICmxImage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CmxImage](cmximage)(StreamContainer, LoadOptions) | Yeni bir örneğini başlatır[`CmxImage`](../cmximage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cmx/cmximage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [CmxPage](../../aspose.imaging.fileformats.cmx/cmximage/cmxpage) { get; } | CMX sayfasını alır. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [Document](../../aspose.imaging.fileformats.cmx/cmximage/document) { get; } | CMX belgesini alır. |
| override [FileFormat](../../aspose.imaging.fileformats.cmx/cmximage/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| override [Height](../../aspose.imaging/vectormultipageimage/height) { get; } | Görüntü yüksekliğini alır. |
| override [HeightF](../../aspose.imaging.fileformats.cmx/cmximage/heightf) { get; } | Nesne yüksekliğini inç cinsinden alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging.fileformats.cmx/cmximage/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| override [PageCount](../../aspose.imaging.fileformats.cmx/cmximage/pagecount) { get; } | Sayfa sayısını alır. |
| override [PageExportingAction](../../aspose.imaging.fileformats.cmx/cmximage/pageexportingaction) { get; set; } | Sayfa dışa aktarma eylemini alır veya ayarlar. Bu yöntemin ayarlanmasının, yürütüldükten sonra sayfa kaynaklarını otomatik olarak serbest bırakacağını lütfen unutmayın. Her sayfa kaydedilmeden hemen önce yürütülür. |
| override [Pages](../../aspose.imaging.fileformats.cmx/cmximage/pages) { get; } | Sayfaları alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Nesne boyutunu inç cinsinden alır. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| override [Width](../../aspose.imaging/vectormultipageimage/width) { get; } | Görüntü genişliğini alır. |
| override [WidthF](../../aspose.imaging.fileformats.cmx/cmximage/widthf) { get; } | Nesne genişliğini inç cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cmx/cmximage/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.cmx/cmximage/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Gömülü görüntüleri alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging.fileformats.cmx/cmximage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging.fileformats.cmx/cmximage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.imaging.fileformats.cmx/cmximage/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.imaging.fileformats.cmx/cmximage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Örnekler

Aşağıdaki örnek, bir CMX görüntüsünün tüm sayfalarının nasıl önbelleğe alınacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir CMX dosyasından bir resim yükleyin.
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.CacheData();

    // Temel veri akışından ek veri yüklemesi gerçekleştirilmeyecek şekilde tüm sayfaları önbelleğe alın.
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Ayrıca bakınız

* class [Image](../../aspose.imaging/image)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage)
* interface [ICmxImage](../icmximage)
* ad alanı [Aspose.Imaging.FileFormats.Cmx](../../aspose.imaging.fileformats.cmx)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
