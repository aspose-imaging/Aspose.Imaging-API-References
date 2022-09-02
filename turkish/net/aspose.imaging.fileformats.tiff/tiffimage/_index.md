---
title: TiffImage
second_title: Aspose.Imaging for .NET API Referansı
description: Tiff görüntüsü.
type: docs
weight: 7880
url: /tr/net/aspose.imaging.fileformats.tiff/tiffimage/
---
## TiffImage class

Tiff görüntüsü.

```csharp
public sealed class TiffImage : RasterCachedMultipageImage, IMultipageImageExt
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TiffImage](tiffimage#constructor)(TiffFrame) | Yeni bir örneğini başlatır[`TiffImage`](../tiffimage) sınıf. |
| [TiffImage](tiffimage#constructor_1)(TiffFrame[]) | Yeni bir örneğini başlatır[`TiffImage`](../tiffimage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe) { get; set; } | Etkin çerçeveyi alır veya ayarlar. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Paletin otomatik ayarlanıp ayarlanmadığını belirten bir değer alır veya ayarlar. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder) { get; set; } | Tiff bayt sırasını belirten bir değer alır veya ayarlar. |
| [Container](../../aspose.imaging/image/container) { get; } | [`Image`](../../aspose.imaging/image) kapsayıcı. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [ExifData](../../aspose.imaging.fileformats.tiff/tiffimage/exifdata) { get; set; } | Etkin çerçeve için EXIF verilerini alır veya ayarlar. |
| override [FileFormat](../../aspose.imaging.fileformats.tiff/tiffimage/fileformat) { get; } | dosya formatının bir değerini alır |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames) { get; } | Resmin Çerçeve dizisini alır. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha) { get; } | Has alfa kanalını alır. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Resmin saydam renge sahip olup olmadığını gösteren bir değer alır. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Görüntü yüksekliğini alır. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution) { get; set; } | Bunun inç başına piksel cinsinden yatay çözünürlüğünü alır.[`Image`](../../aspose.imaging/image) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Bu görüntünün opaklığını alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ham veri yüklemesinin mevcut olup olmadığını gösteren bir değer alır. |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount) { get; } | Sayfa sayısını alır. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | Sayfa dışa aktarma eylemini alır veya ayarlar. Bu yöntemin ayarlanmasının, yürütüldükten sonra sayfa kaynaklarını otomatik olarak serbest bırakacağını lütfen unutmayın. Her sayfa kaydedilmeden hemen önce yürütülür. |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages) { get; } | Sayfaları alır. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents) { get; set; } | Bileşenlerin önceden çoğaltılmasının gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
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
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution) { get; set; } | Bunun inç başına piksel cinsinden dikey çözünürlüğünü alır.[`Image`](../../aspose.imaging/image) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Görüntü genişliğini alır. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Çerçeveden XMP verilerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add)(TiffImage) | Belirtilen görüntünün çerçevelerini geçerli çerçeveye ekler. |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe)(TiffFrame) | Çerçeveyi image öğesine ekler |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes)(TiffFrame[]) | çerçeve dizisini image öğesine ekler |
| [AddPage](../../aspose.imaging.fileformats.tiff/tiffimage/addpage)(RasterImage) | Resme sayfa ekler. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness)(int) | Bir ayarı*brightness* resim için. |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) kontrast |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma#adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma#adjustgamma_1)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions)() | Yatay ve dikey çözünürlükleri eşit yapmak için yardımcı yöntem. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley#binarizebradley_1)(double, int) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed)(byte) | Önceden tanımlanmış eşik değeri olan bir görüntünün ikilileştirilmesi |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu)() | Otsu eşik değeri ile bir görüntünün ikilileştirilmesi |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Özel verileri önbelleğe alır. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop#crop)(Rectangle) | Görüntü kırpılıyor. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop#crop_1)(int, int, int, int) | Görüntüyü kaydırmalarla kırpın. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | 32-bit ARGB piksel görüntüsü alır. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Varsayılan 32 bit ARGB piksel dizisini alır. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Kaynak görüntüsünün en son değiştirildiği tarih ve saati alır. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../../aspose.imaging/datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../../aspose.imaging/image/save) ikinci parametre olarak yöntem. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Bir görüntü pikseli alır. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Eğim açısını alır. Bu yöntem, tarama sırasında eğrilik açısını belirlemek için taranan metin belgelerine uygulanabilir. |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale)() | Bir görüntünün gri tonlamalı temsiline dönüştürülmesi |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe)(int, TiffFrame) | Ekleme çerçevesi. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | 32 bit ARGB pikselleri yükler. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | 64 bit ARGB pikselleri yükler. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Pikselleri CMYK biçiminde yükler. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 32 bit ARGB piksellerini kısmen paketler halinde yükler. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Pikselleri paketlere göre kısmen yükler. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Piksel yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) ve[`Rotate`](../../aspose.imaging/rasterimage/rotate) yöntemler. |
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle#normalizeangle_1)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) ve[`Rotate`](./rotate) yöntemler. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe#removeframe)(int) | Çerçeveyi indeksine göre kaldırır. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe#removeframe_1)(TiffFrame) | Belirtilen çerçeveyi kaldırır. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe)(int, TiffFrame) | Belirtilen konumdaki çerçeveyi değiştirir. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Tüm saydam olmayan renkleri yeni renklerle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Tüm saydam olmayan renkleri yeni renkle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize#resize_1)(int, int, ImageResizeSettings) | Resmi yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional)(int, int, ResizeType) | Görüntü üzerinde orantılı yeniden boyutlandırma gerçekleştirir. Orantılı yeniden boyutlandırma, her kareyi*newWidth*/genişlik ve*newHeight* /yükseklik. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Resmi merkez çevresinde döndürün. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate#rotate_1)(float, bool, Color) | Resmi merkez çevresinde döndürün. |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip)(RotateFlipType) | Yalnızca Etkin çerçeveyi döndürür, çevirir veya döndürür ve döndürür. |
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
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution)(double, double) | Bunun için çözünürlüğü ayarlar[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |

### Örnekler

TIFF görüntüsünde Yol Kaynaklarından Grafik Yolu oluşturun.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // TIFF görüntüsünden PathResources kullanarak GraphicsPath'i oluşturun
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Kırmızı çizgi çiz ve görüntüyü kaydet
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Grafik Yolu kullanarak Yol Kaynakları oluşturun.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // GraphicsPath için dikdörtgen Şekil oluştur
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Figürümüzü kullanarak GraphicsPath oluşturun
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // GraphicsPath kullanarak PathResources'u ayarlayın
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Resmi kaydet
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

### Ayrıca bakınız

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* ad alanı [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
