---
title: PngImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni png resmi.
type: docs
weight: 7450
url: /tr/net/aspose.imaging.fileformats.png/pngimage/
---
## PngImage class

Yeni png resmi.

```csharp
public class PngImage : RasterCachedImage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PngImage](pngimage#constructor_1)(RasterImage) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor_5)(Stream) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor_6)(string) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor_3)(int, int) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor_2)(RasterImage, PngColorType) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor_7)(string, PngColorType) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor_4)(int, int, PngColorType) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |
| [PngImage](pngimage#constructor)(PngOptions, int, int) | Yeni bir örneğini başlatır[`PngImage`](../pngimage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| override [BackgroundColor](../../aspose.imaging.fileformats.png/pngimage/backgroundcolor) { get; set; } | Arka plan rengini alır. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.png/pngimage/bitsperpixel) { get; } | Piksel başına bitleri alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| override [FileFormat](../../aspose.imaging.fileformats.png/pngimage/fileformat) { get; } | dosya formatının bir değerini alır |
| override [HasAlpha](../../aspose.imaging.fileformats.png/pngimage/hasalpha) { get; } | Bu örneğin alfa olup olmadığını gösteren bir değer alın. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor) { get; set; } | Arka plan renginin olup olmadığını gösteren bir değer alır. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.png/pngimage/hastransparentcolor) { get; set; } | Resmin saydam renge sahip olup olmadığını gösteren bir değer alır. |
| override [Height](../../aspose.imaging.fileformats.png/pngimage/height) { get; } | Yüksekliği alır. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.png/pngimage/horizontalresolution) { get; set; } | Yatay çözünürlüğü alır veya ayarlar. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Bu görüntünün opaklığını alır. |
| [Interlaced](../../aspose.imaging.fileformats.png/pngimage/interlaced) { get; } | Bunun olup olmadığını gösteren bir değer alır.[`PngImage`](../pngimage) geçmeli. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [IsInterlaced](../../aspose.imaging.fileformats.png/pngimage/isinterlaced) { get; } | Bu görüntü örneğinin geçmeli olup olmadığını gösteren bir değer alır. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ham veri yüklemesinin mevcut olup olmadığını gösteren bir değer alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Görüntü bileşenlerinin önceden çoğaltılması gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| override [RawDataFormat](../../aspose.imaging.fileformats.png/pngimage/rawdataformat) { get; } | Ham veri biçimini alır. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Geçerli ham veri ayarlarını alır. Bu ayarları kullanırken verilerin dönüşüm olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Palet dizini sınırların dışında olduğunda kullanılacak yedek dizini alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Dizine alınmış renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Bayt cinsinden ham satır boyutunu alır. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| override [TransparentColor](../../aspose.imaging.fileformats.png/pngimage/transparentcolor) { get; set; } | Saydam rengi alır. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | XMP meta verilerinin güncellenip güncellenmeyeceğini belirten bir değer alır veya ayarlar. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ham veri yükleme kullanılabilir olduğunda ham veri yüklemenin kullanılıp kullanılmayacağını belirten bir değer alır veya ayarlar. |
| override [VerticalResolution](../../aspose.imaging.fileformats.png/pngimage/verticalresolution) { get; set; } | Dikey çözünürlüğü alır veya ayarlar. |
| override [Width](../../aspose.imaging.fileformats.png/pngimage/width) { get; } | Genişliği alır. |
| override [XmpData](../../aspose.imaging.fileformats.png/pngimage/xmpdata) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Görüntü için parlaklık ayarı. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Görüntü kontrastı |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Önceden tanımlanmış eşik değeri olan bir görüntünün ikilileştirilmesi |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Otsu eşik değeri ile bir görüntünün ikilileştirilmesi |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop)(Rectangle) | Görüntü kırpılıyor. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | Görüntüyü kaydırmalarla kırpın. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | 32-bit ARGB piksel görüntüsü alır. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Varsayılan 32 bit ARGB piksel dizisini alır. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.png/pngimage/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| override [GetModifyDate](../../aspose.imaging.fileformats.png/pngimage/getmodifydate)(bool) | Kaynak görüntüsünün en son değiştirildiği tarih ve saati alır. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.png/pngimage/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Bir görüntü pikseli alır. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Eğim açısını alır. Bu yöntem, tarama sırasında eğrilik açısını belirlemek için taranan metin belgelerine uygulanabilir. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Bir görüntünün gri tonlamalı temsiline dönüştürülmesi |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | 32 bit ARGB pikselleri yükler. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | 64 bit ARGB pikselleri yükler. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Pikselleri CMYK biçiminde yükler. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 32 bit ARGB piksellerini kısmen paketler halinde yükler. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Pikselleri paketlere göre kısmen yükler. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Piksel yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) ve[`Rotate`](../../aspose.imaging/rasterimage/rotate) yöntemler. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) ve[`Rotate`](../../aspose.imaging/rasterimage/rotate) yöntemler. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Tüm saydam olmayan renkleri yeni renklerle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Tüm saydam olmayan renkleri yeni renklerle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Resmi merkez çevresinde döndürün. |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate)(float, bool, Color) | Resmi merkez çevresinde döndürün. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | 32 bit ARGB piksellerini kaydeder. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Pikselleri kaydeder. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Pikselleri kaydeder. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Ham verileri kaydeder. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Belirtilen konum için bir 32-bit ARGB pikseli ayarlar. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Bunun için çözünürlüğü ayarlar[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |

### Örnekler

Bu örnek, bir dosyadan PNG görüntüsünün nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir PNG görüntüsü yükleyin.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Resmi gri tonlamalı gösterime dönüştürün
    pngImage.Grayscale();

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Ayrıca bakınız

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
