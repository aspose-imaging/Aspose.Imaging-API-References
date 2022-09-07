---
title: ApngImage
second_title: Aspose.Imaging for .NET API Referansı
description: Animasyonlu PNG resmi.
type: docs
weight: 1320
url: /tr/net/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

Animasyonlu PNG resmi.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ApngImage](apngimage)(ApngOptions, int, int) | Yeni bir örneğini başlatır[`ApngImage`](../apngimage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime) { get; set; } | Varsayılan kare süresini alır veya ayarlar. Yeni kareler oluşturulurken kullanılır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat) { get; } | dosya formatının bir değerini alır |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Bu örneğin alfa olup olmadığını gösteren bir değer alır. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Resmin saydam renge sahip olup olmadığını gösteren bir değer alır. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Görüntü yüksekliğini alır. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Bunun yatay çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Bu görüntünün opaklığını alır. |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced) { get; } | Bunun olup olmadığını gösteren bir değer alır.[`PngImage`](../../aspose.imaging.fileformats.png/pngimage) geçmeli. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ham veri yüklemesinin mevcut olup olmadığını gösteren bir değer alır. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays) { get; set; } | Döngü animasyonu sayısını alır veya ayarlar. 0 sonsuz döngüyü belirtir. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount) { get; } | Sayfa sayısını alır. |
| override [PageExportingAction](../../aspose.imaging.fileformats.apng/apngimage/pageexportingaction) { get; set; } | Sayfa dışa aktarma eylemini alır veya ayarlar. Bu yöntemin ayarlanmasının, yürütüldükten sonra sayfa kaynaklarını otomatik olarak serbest bırakacağını lütfen unutmayın. Her sayfa kaydedilmeden hemen önce yürütülür. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages) { get; } | Sayfaları alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Görüntü bileşenlerinin önceden çoğaltılması gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Ham veri biçimini alır. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Geçerli ham veri ayarlarını alır. Bu ayarları kullanırken verilerin dönüşüm olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Palet dizini sınırların dışında olduğunda kullanılacak yedek dizini alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Dizine alınmış renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Bayt cinsinden ham satır boyutunu alır. |
| [Size](../../aspose.imaging/image/size) { get; } | Görüntü boyutunu alır. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Resmin saydam rengini alır. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | XMP meta verilerinin güncellenip güncellenmeyeceğini belirten bir değer alır veya ayarlar. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değer alır. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ham veri yükleme kullanılabilir olduğunda ham veri yüklemenin kullanılıp kullanılmayacağını belirten bir değer alır veya ayarlar. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Görüntü genişliğini alır. |
| override [XmpData](../../aspose.imaging.fileformats.apng/apngimage/xmpdata) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe)() | Kendi çerçeve koleksiyonunun sonuna yeni çerçeve ekler. Geçerli görüntünün boyutuna göre yeni bir çerçeve oluşturulur. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_1)(RasterImage) | Kendi çerçeve koleksiyonunun sonuna yeni çerçeve ekler. Yeni çerçevenin içeriği belirtilen görüntüden doldurulur. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_2)(RasterImage, uint) | Kendi çerçeve koleksiyonunun sonuna yeni çerçeve ekler. Yeni çerçevenin içeriği belirtilen görüntüden doldurulur. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage)(RasterImage) | Resme sayfa ekler. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness)(int) | Bir ayarı*brightness* resim için. |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) kontrast |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma_1)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley#binarizebradley_1)(double, int) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed)(byte) | Önceden tanımlanmış eşik değeri olan bir görüntünün ikilileştirilmesi |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu)() | Otsu eşik değeri ile bir görüntünün ikilileştirilmesi |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Özel verileri önbelleğe alır. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop)(Rectangle) | Görüntü kırpılıyor. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop_1)(int, int, int, int) | Görüntüyü kaydırmalarla kırpın. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | 32-bit ARGB piksel görüntüsü alır. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Varsayılan 32 bit ARGB piksel dizisini alır. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate)(bool) | Kaynak görüntüsünün en son değiştirildiği tarih ve saati alır. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Bir görüntü pikseli alır. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Eğim açısını alır. Bu yöntem, tarama sırasında eğrilik açısını belirlemek için taranan metin belgelerine uygulanabilir. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale)() | Bir görüntünün gri tonlamalı temsiline dönüştürülmesi |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe)(int) | Belirtilen dizindeki kendi çerçeve koleksiyonuna yeni çerçeve ekler. Geçerli görüntünün boyutuna göre yeni bir çerçeve oluşturulur. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_1)(int, RasterImage) | Belirtilen dizindeki kendi çerçeve koleksiyonuna yeni çerçeve ekler. Yeni çerçevenin içeriği belirtilen görüntüden doldurulur. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_2)(int, RasterImage, uint) | Belirtilen dizindeki kendi çerçeve koleksiyonuna yeni çerçeve ekler. Yeni çerçevenin içeriği belirtilen görüntüden doldurulur. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | 32 bit ARGB pikselleri yükler. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | 64 bit ARGB pikselleri yükler. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Pikselleri CMYK biçiminde yükler. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 32 bit ARGB piksellerini kısmen paketler halinde yükler. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Pikselleri paketlere göre kısmen yükler. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Piksel yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) ve[`Rotate`](../../aspose.imaging/rasterimage/rotate) yöntemler. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:!:GetSkewAngle ve[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) yöntemler. |
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat)(int) | Kendi çerçeve koleksiyonunun belirtilen dizinindeki çerçeveyi kaldırır ve döndürür. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes)() | Kendi çerçeve koleksiyonundan tüm çerçeveleri kaldırır. |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat)(int) | Kendi çerçeve koleksiyonunun belirtilen dizinindeki çerçeveyi kaldırır. Silinecek çerçeve atılır. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Tüm saydam olmayan renkleri yeni renklerle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Tüm saydam olmayan renkleri yeni renkle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage)() | Önceden ayarlanmış bir varsayılan resmi siler. Bundan sonra, varsayılan resim kendi çerçeve koleksiyonundaki ilk karedir (bu yöntem kullanılarak silinemez). |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Resmi merkez çevresinde döndürün. |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate merkezin etrafındaki görüntü. |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip)(RotateFlipType) | Yalnızca Etkin çerçeveyi döndürür, çevirir veya döndürür ve döndürür. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage)(RasterImage) | Belirtilen tarama görüntüsünü geçerli animasyonun varsayılan görüntüsü olarak ayarlar. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Bunun için çözünürlüğü ayarlar[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |

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

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* ad alanı [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
