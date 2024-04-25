---
title: RasterImage
second_title: Aspose.Imaging for .NET API Referansı
description: Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder.
type: docs
weight: 10810
url: /tr/aspose.imaging/rasterimage/
---
## RasterImage class

Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
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
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha) { get; } | Bu örneğin alfa olup olmadığını gösteren bir değer alır. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını belirten bir değer alır veya ayarlar. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor) { get; set; } | Resmin saydam renge sahip olup olmadığını gösteren bir değer alır. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Görüntü yüksekliğini alır. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Bunun yatay çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../rasterimage) . |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Bu görüntünün opaklığını alır. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ham veri yüklemesinin mevcut olup olmadığını gösteren bir değer alır. |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../rasterimage) . |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Görüntü genişliğini alır. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.imaging/rasterimage/adjustbrightness)(int) | Görüntü için parlaklık ayarı. |
| virtual [AdjustContrast](../../aspose.imaging/rasterimage/adjustcontrast)(float) | Görüntü kontrastı |
| virtual [AdjustGamma](../../aspose.imaging/rasterimage/adjustgamma#adjustgamma)(float) | Bir görüntünün gama düzeltmesi. |
| virtual [AdjustGamma](../../aspose.imaging/rasterimage/adjustgamma#adjustgamma_1)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| virtual [BinarizeBradley](../../aspose.imaging/rasterimage/binarizebradley#binarizebradley)(double) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| virtual [BinarizeBradley](../../aspose.imaging/rasterimage/binarizebradley#binarizebradley_1)(double, int) | Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi |
| virtual [BinarizeFixed](../../aspose.imaging/rasterimage/binarizefixed)(byte) | Önceden tanımlanmış eşik değeri olan bir görüntünün ikilileştirilmesi |
| virtual [BinarizeOtsu](../../aspose.imaging/rasterimage/binarizeotsu)() | Otsu eşik değeri ile bir görüntünün ikilileştirilmesi |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop#crop)(Rectangle) | Belirtilen dikdörtgeni kırpar. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop#crop_1)(int, int, int, int) | Görüntüyü kaydırmalarla kırpın. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| [Dither](../../aspose.imaging/rasterimage/dither#dither)(DitheringMethod, int) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| abstract [Dither](../../aspose.imaging/rasterimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Geçerli görüntüde renk taklidi gerçekleştirir. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | 32-bit ARGB piksel görüntüsü alır. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Varsayılan 32 bit ARGB piksel dizisini alır. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata#getdefaultrawdata)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Kaynak görüntüsünün en son değiştirildiği tarih ve saati alır. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmemeye yardımcı olabilir. Örneğin, piksel başına 1 bitlik siyah beyaz bir PNG görüntüsü yükler ve ardından the kullanarak kaydedin[`Save`](../datastreamsupporter/save) yöntemi, piksel başına 8 bitlik çıktı PNG görüntüsü üretilecektir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, ilgili kaydetme seçeneklerini almak için bu yöntemi kullanın ve bunları [`Save`](../image/save) ikinci parametre olarak yöntem. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Bir görüntü pikseli alır. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Eğim açısını alır. Bu yöntem, tarama sırasında eğrilik açısını belirlemek için taranan metin belgelerine uygulanabilir. |
| virtual [Grayscale](../../aspose.imaging/rasterimage/grayscale)() | Bir görüntünün gri tonlamalı temsiline dönüştürülmesi |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | 32 bit ARGB pikselleri yükler. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | 64 bit ARGB pikselleri yükler. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Pikselleri CMYK biçiminde yükler. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 32 bit ARGB piksellerini kısmen paketler halinde yükler. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Pikselleri paketlere göre kısmen yükler. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Piksel yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham verileri yükler. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle#normalizeangle)() | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](./getskewangle) ve[`Rotate`](./rotate) yöntemler. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle#normalizeangle_1)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğri taramadan kurtulmak için taranan metin belgelerine uygulanabilir. Bu yöntem şunları kullanır:[`GetSkewAngle`](./getskewangle) ve[`Rotate`](./rotate) yöntemler. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Belirtilen tarama satırı dizinine göre tüm tarama satırını okur. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor#replacecolor)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor#replacecolor_1)(int, byte, int) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve düzgün kenarları kaydetmek için orijinal alfa değerini korur. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors#replacenontransparentcolors)(Color) | Tüm saydam olmayan renkleri yeni renklerle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Tüm saydam olmayan renkleri yeni renklerle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Bunu saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.imaging/rasterimage/resize#resize_1)(int, int, ImageResizeSettings) | Genişletilmiş seçeneklerle görüntüyü yeniden boyutlandırır. |
| override [Resize](../../aspose.imaging/rasterimage/resize#resize_2)(int, int, ResizeType) | Resmi yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Genişliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate#rotate)(float) | Resmi merkez çevresinde döndürün. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate#rotate_1)(float, bool, Color) | Resmi merkez çevresinde döndürün. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve döndürür. |
| [Save](../../aspose.imaging/image/save)() | Görüntü verilerini temel alınan akışa kaydeder. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| override [Save](../../aspose.imaging/image/save)(string) | Resmi belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.imaging/rasterimage/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | 32 bit ARGB piksellerini kaydeder. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Pikselleri kaydeder. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Pikselleri kaydeder. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Ham verileri kaydeder. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Belirtilen konum için bir 32-bit ARGB pikseli ayarlar. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Bunun için çözünürlüğü ayarlar[`RasterImage`](../rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Raster görüntüyü bitmap'e dönüştürür. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı dizinine yazar. |

### Örnekler

Bu örnek, Piksel bilgilerinin bir Renk Türü Dizisine nasıl yükleneceğini, diziyi nasıl değiştireceğini ve görüntüye geri ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için bu örnek, MemoryStream nesnesini kullanan yeni bir Görüntü dosyası (GIF formatında) oluşturur.

```csharp
[C#]

//MemoryStream örneğini oluştur
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Bir GifOptions örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Görüntü örneğini oluştur
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Alanı görüntü sınırı olarak belirterek görüntünün piksellerini alın
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Dizi üzerinde dolaş ve alrenative indekslenmiş pikselin rengini ayarla
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Dizine alınmış piksel rengini sarıya ayarla
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Dizinli piksel rengini maviye ayarla
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        // Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    // MemoryStream'i Dosyaya Yaz
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Ayrıca bakınız

* class [Image](../image)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
