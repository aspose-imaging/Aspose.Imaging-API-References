---
title: JpegImage
second_title: Aspose.Imaging for .NET API Referansı
description: Bir jpeg resmi.
type: docs
weight: 6770
url: /tr/net/aspose.imaging.fileformats.jpeg/jpegimage/
---
## JpegImage class

Bir jpeg resmi.

```csharp
public sealed class JpegImage : RasterCachedImage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [JpegImage](jpegimage#constructor_1)(RasterImage) | Yeni bir örneğini başlatır[`JpegImage`](../jpegimage) sınıf. |
| [JpegImage](jpegimage#constructor_3)(Stream) | Yeni bir örneğini başlatır[`JpegImage`](../jpegimage) sınıf. |
| [JpegImage](jpegimage#constructor_4)(string) | Yeni bir örneğini başlatır[`JpegImage`](../jpegimage) sınıf. |
| [JpegImage](jpegimage#constructor_2)(int, int) | Yeni bir örneğini başlatır[`JpegImage`](../jpegimage) sınıf. |
| [JpegImage](jpegimage#constructor)(JpegOptions, int, int) | Yeni bir örneğini başlatır[`JpegImage`](../jpegimage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg/jpegimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [CmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile) { get; set; } | CMYK ve YCCK jpeg görüntüleri için CMYK renk profili. Doğru renk dönüşümü için RGBColorProfile ile eşleştirilmiş olmalıdır. |
| [Comment](../../aspose.imaging.fileformats.jpeg/jpegimage/comment) { get; set; } | jpeg dosyası yorumunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [DestinationCmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationcmykcolorprofile) { get; set; } | Görüntü kaydetme işlemi için kullanılan CMYK ve YCCK jpeg görüntüleri için CMYK renk profili. Doğru renk dönüşümü için RGBColorProfile ile eşleştirilmiş olmalıdır. |
| [DestinationRgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationrgbcolorprofile) { get; set; } | Görüntü kaydetme işlemi için kullanılan CMYK ve YCCK jpeg görüntüleri için RGB renk profili. Doğru renk dönüşümü için CMYKColorProfile ile eşleştirilmiş olmalıdır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [ExifData](../../aspose.imaging.fileformats.jpeg/jpegimage/exifdata) { get; set; } | Exif veri kapsayıcısını alın veya ayarlayın |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/fileformat) { get; } | dosya formatının bir değerini alır |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha) { get; } | Bu örneğin alfa olup olmadığını gösteren bir değer alır. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor) { get; set; } | Resmin saydam renge sahip olup olmadığını gösteren bir değer alır. |
| override [Height](../../aspose.imaging.fileformats.jpeg/jpegimage/height) { get; } | Görüntü yüksekliğini alır. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution) { get; set; } | Bunun yatay çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [IgnoreEmbeddedColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/ignoreembeddedcolorprofile) { get; set; } | Gömülü renk profilinin yoksayılıp yoksayılmadığını gösteren bir değer alır veya ayarlar. Katıştırılmış renk profili yoksayılırsa, varsayılan renk profili kullanılır. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Bu görüntünün opaklığını alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ham veri yüklemesinin mevcut olup olmadığını gösteren bir değer alır. |
| [Jfif](../../aspose.imaging.fileformats.jpeg/jpegimage/jfif) { get; set; } | jfif. öğesini alır veya ayarlar |
| [JpegOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions) { get; } | Bunu oluşturmak veya yüklemek için kullanılan JPEG seçeneklerini alır[`JpegImage`](../jpegimage) örnek. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Görüntü bileşenlerinin önceden çoğaltılması gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/rawdataformat) { get; } | Ham veri biçimini alır. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Geçerli ham veri ayarlarını alır. Bu ayarları kullanırken verilerin dönüşüm olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Palet dizini sınırların dışında olduğunda kullanılacak yedek dizini alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Dizine alınmış renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Bayt cinsinden ham satır boyutunu alır. |
| [RgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile) { get; set; } | CMYK ve YCCK jpeg görüntüleri için RGB renk profili. Doğru renk dönüşümü için CMYKColorProfile ile eşleştirilmiş olmalıdır. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Resmin saydam rengini alır. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | XMP meta verilerinin güncellenip güncellenmeyeceğini belirten bir değer alır veya ayarlar. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ham veri yükleme kullanılabilir olduğunda ham veri yüklemenin kullanılıp kullanılmayacağını belirten bir değer alır veya ayarlar. |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution) { get; set; } | Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.jpeg/jpegimage/width) { get; } | Görüntü genişliğini alır. |
| override [XmpData](../../aspose.imaging.fileformats.jpeg/jpegimage/xmpdata) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Görüntü için parlaklık ayarı. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Görüntü kontrastı |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| [AutoRotate](../../aspose.imaging.fileformats.jpeg/jpegimage/autorotate)() | Exif. tarafından sağlanan yönlendirme verilerine bağlı olarak görüntünün otomatik döndürülmesini gerçekleştirin |
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
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| override [GetModifyDate](../../aspose.imaging.fileformats.jpeg/jpegimage/getmodifydate)(bool) | Kaynak görüntüsünün en son değiştirildiği tarih ve saati alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
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
| override [SetResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/setresolution)(double, double) | Bunun için çözünürlüğü ayarlar[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |

### Örnekler

Jpeg görüntüsündeki kamera üreticisinin notlarına erişin.

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

Örnek, bir dosyadan bir JpegImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir JPEG görüntüsü yükleyin.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Biraz görüntü işleme yapın.
    // Başka bir JPEG dosyasına kaydedin.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Ayrıca bakınız

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
