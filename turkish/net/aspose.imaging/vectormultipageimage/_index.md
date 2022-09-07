---
title: VectorMultipageImage
second_title: Aspose.Imaging for .NET API Referansı
description: Vektör çok sayfalı image
type: docs
weight: 11220
url: /tr/net/aspose.imaging/vectormultipageimage/
---
## VectorMultipageImage class

Vektör çok sayfalı image

```csharp
public abstract class VectorMultipageImage : VectorImage, IMultipageImage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging/vectormultipageimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| override [Height](../../aspose.imaging/vectormultipageimage/height) { get; } | Görüntü yüksekliğini alır. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Nesne yüksekliğini inç cinsinden alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging/vectormultipageimage/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| abstract [PageCount](../../aspose.imaging/vectormultipageimage/pagecount) { get; } | Sayfa sayısını alır. |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction) { get; set; } | Sayfa dışa aktarma eylemini alır veya ayarlar. Bu yöntemin ayarlanmasının, yürütüldükten sonra sayfa kaynaklarını otomatik olarak serbest bırakacağını lütfen unutmayın. Her sayfa kaydedilmeden hemen önce yürütülür. |
| abstract [Pages](../../aspose.imaging/vectormultipageimage/pages) { get; } | Sayfaları alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Nesne boyutunu inç cinsinden alır. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| override [Width](../../aspose.imaging/vectormultipageimage/width) { get; } | Görüntü genişliğini alır. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Nesne genişliğini inç cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata)() | Verileri önbelleğe alır ve altta yatan öğesinden ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Gömülü görüntüleri alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../image/save) ikinci parametre olarak yöntem. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.imaging/vectormultipageimage/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Ayrıca bakınız

* class [VectorImage](../vectorimage)
* interface [IMultipageImage](../imultipageimage)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
