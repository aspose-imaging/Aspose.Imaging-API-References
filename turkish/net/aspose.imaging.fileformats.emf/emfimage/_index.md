---
title: EmfImage
second_title: Aspose.Imaging for .NET API Referansı
description: EMF dosya biçimi görüntüsü.
type: docs
weight: 4670
url: /tr/net/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

EMF dosya biçimi görüntüsü.

```csharp
public sealed class EmfImage : MetaImage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfImage](emfimage#constructor)() | Yeni bir örneğini başlatır[`EmfImage`](../emfimage) sınıf. |
| [EmfImage](emfimage#constructor_1)(int, int) | Yeni bir örneğini başlatır[`EmfImage`](../emfimage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.emf/emfimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır bu parametre vektör görüntüleri için geçerli değildir |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| override [FileFormat](../../aspose.imaging.fileformats.emf/emfimage/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| [Header](../../aspose.imaging.fileformats.emf/emfimage/header) { get; set; } | başlık kaydını alır veya ayarlar |
| override [Height](../../aspose.imaging.fileformats.emf/emfimage/height) { get; } | Görüntü yüksekliğini alır. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Nesne yüksekliğini inç cinsinden alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging.fileformats.emf/emfimage/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| override [Records](../../aspose.imaging.fileformats.emf/emfimage/records) { get; set; } | Kayıtları alır veya ayarlar. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Nesne boyutunu inç cinsinden alır. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| override [Width](../../aspose.imaging.fileformats.emf/emfimage/width) { get; } | Görüntü genişliğini alır. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Nesne genişliğini inç cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.emf/emfimage/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| override [Crop](../../aspose.imaging.fileformats.emf/emfimage/crop#crop)(Rectangle) | Belirtilen dikdörtgeni kırpar. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Görüntüyü kaydırmalarla kırpın. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.emf/emfimage/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Gömülü görüntüleri alır. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Meta dosyası içinde kullanılan ancak bulunamayan yazı tiplerinin listesini döndürür. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.emf/emfimage/getusedfonts)() | Meta dosyası içinde kullanılan yazı tipinin listesini döndürür. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.emf/emfimage/resizecanvas)(Rectangle) | Tuvali yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.imaging.fileformats.emf/emfimage/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.imaging.fileformats.emf/emfimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Örnekler

Aşağıdaki örnek, emz görüntülerinin emf fromat'a nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

Aşağıdaki örnek, bir emf görüntülerinin emz fromat'a nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

Aşağıdaki örnek, sıkıştırılmış görüntülerin (*.emz,*.wmz, *.svgz) raster fromat'a nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

Bu örnek, bir dosyadan bir EMF görüntüsünün nasıl yükleneceğini ve EmfRasterizationOptions kullanılarak SVG'ye nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load'u kullanmak, EMF dahil her türlü görüntüyü yüklemek için birleşik bir yoldur.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Metin şekillere dönüştürülecek.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // Sayfa boyutu.
    rasterizationOptions.PageSize = emfImage.Size;

    // Gömülü emf varsa, emf oluştur; aksi takdirde wmf oluştur.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Yatay kenar boşluğunu ayarla
    rasterizationOptions.BorderX = 50;

    // Dikey kenar boşluğunu ayarla
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### Ayrıca bakınız

* class [MetaImage](../metaimage)
* ad alanı [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
