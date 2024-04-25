---
title: SvgImage
second_title: Aspose.Imaging for .NET API Referansı
description: SVG görüntü sınıfını temsil eder.
type: docs
weight: 7550
url: /tr/aspose.imaging.fileformats.svg/svgimage/
---
## SvgImage class

SVG görüntü sınıfını temsil eder.

```csharp
public sealed class SvgImage : VectorImage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SvgImage](svgimage#constructor_2)(Stream) | Yeni bir örneğini başlatır[`SvgImage`](../svgimage) sınıf. |
| [SvgImage](svgimage#constructor_3)(string) | Yeni bir örneğini başlatır[`SvgImage`](../svgimage) sınıf. |
| [SvgImage](svgimage#constructor_1)(int, int) | Yeni bir örneğini başlatır[`SvgImage`](../svgimage) sınıf. |
| [SvgImage](svgimage#constructor)(SvgOptions, int, int) | Yeni bir örneğini başlatır[`SvgImage`](../svgimage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.svg/svgimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır bu parametre vektör görüntüleri için geçerli değildir |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| override [FileFormat](../../aspose.imaging.fileformats.svg/svgimage/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| override [Height](../../aspose.imaging.fileformats.svg/svgimage/height) { get; } | Görüntü yüksekliğini alır. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Nesne yüksekliğini inç cinsinden alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging.fileformats.svg/svgimage/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Nesne boyutunu inç cinsinden alır. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| override [Width](../../aspose.imaging.fileformats.svg/svgimage/width) { get; } | Görüntü genişliğini alır. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Nesne genişliğini inç cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.svg/svgimage/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.svg/svgimage/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Gömülü görüntüleri alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging.fileformats.svg/svgimage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging.fileformats.svg/svgimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.imaging.fileformats.svg/svgimage/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.imaging.fileformats.svg/svgimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Örnekler

Aşağıdaki örnek, bir svgz görüntüsünün svg fromat'a nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string file = "example.svgz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svg";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

Aşağıdaki örnek, bir svg görüntüsünün svgz fromat'a nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

Bu örnek, bir dosya akışından bir SVG görüntüsünün nasıl yükleneceğini ve PNG'ye nasıl rasterleştirileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir SVG görüntüsü yükleyin.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekiyor.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
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

### Ayrıca bakınız

* class [VectorImage](../../aspose.imaging/vectorimage)
* ad alanı [Aspose.Imaging.FileFormats.Svg](../../aspose.imaging.fileformats.svg)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
