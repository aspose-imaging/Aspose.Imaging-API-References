---
title: Image
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntü tüm görüntü türleri için temel sınıftır.
type: docs
weight: 9660
url: /tr/aspose.imaging/image/
---
## Image class

Görüntü, tüm görüntü türleri için temel sınıftır.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Görüntü yüksekliğini alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Görüntü genişliğini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | Sayfalar olarak belirtilen görüntüleri kullanarak yeni bir görüntü oluşturur |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | Belirtilen görüntüleri sayfalar olarak yeni bir görüntü oluşturur. |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | Belirtilen akıştan yeni bir resim yükler. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | Belirtilen dosyadan yeni bir resim yükler. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | Belirtilen akıştan yeni bir resim yükler. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | Belirtilen dosyadan yeni bir resim yükler. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](./save) ikinci parametre olarak yöntem. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save#save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | Resmin belirtilen dosya yolundan yüklenip yüklenemeyeceğini belirler. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen akıştan yüklenip yüklenemeyeceğini belirler.*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açık seçenekler kullanılarak yüklenip yüklenemeyeceğini belirler. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | Dosya biçimini alır. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | Dosya biçimini alır. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Geçerli görüntüye uyan dikdörtgeni alır. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Geçerli görüntüye uyan dikdörtgeni alır. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Orantılı bir yükseklik alır. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Orantılı bir genişlik alır. |

### Örnekler

Paletin resim tarafından kullanılıp kullanılmadığını belirleyin.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Belirli Yeniden Boyutlandırma Türünü kullanarak görüntüyü yeniden boyutlandırın.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

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

### Ayrıca bakınız

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
