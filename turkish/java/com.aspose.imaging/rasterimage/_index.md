---
title: "RasterImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder."
type: docs
weight: 91
url: /tr/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Görüntü bileşenlerinin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Görüntü bileşenlerinin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [getUseRawData()](#getUseRawData--) | Ham veri yüklemenin mevcut olduğu durumlarda ham veri yüklemenin kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Ham veri yüklemenin mevcut olduğu durumlarda ham veri yüklemenin kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. |
| [getUpdateXmpData()](#getUpdateXmpData--) | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Dizine dayalı renk dönüştürücüyü alır veya ayarlar |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Dizine dayalı renk dönüştürücüyü alır veya ayarlar |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Özel renk dönüştürücüyü alır veya ayarlar |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Özel renk dönüştürücüyü alır veya ayarlar |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [getRawDataFormat()](#getRawDataFormat--) | Ham veri biçimini alır. |
| [getRawLineSize()](#getRawLineSize--) | Ham satır boyutunu bayt cinsinden alır. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ham veri yüklemenin mevcut olup olmadığını gösteren bir değeri alır. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| [hasTransparentColor()](#hasTransparentColor--) | Bu [RasterImage](../../com.aspose.imaging/rasterimage) örneğinin şeffaf bir rengi olup olmadığını gösteren bir değeri alır. |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini gösteren bir değer alır. |
| [getTransparentColor()](#getTransparentColor--) | Görüntünün şeffaf rengini alır. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Bu [RasterImage](../../com.aspose.imaging/rasterimage) örneğinin şeffaf bir rengi olup olmadığını gösteren bir değeri ayarlar. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Görüntünün şeffaf rengini alır. |
| [getImageOpacity()](#getImageOpacity--) | Bu görüntünün opaklığını alır. |
| [removeMetadata()](#removeMetadata--) | Bu `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) değerini `null` olarak ayarlayarak bu görüntü örneği meta verilerini kaldırır. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Kaynak görüntünün en son değiştirildiği tarih ve zamanı alır. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Mevcut görüntüde dithering uygular. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mevcut görüntüde dithering uygular. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Kısmi piksel yükleyiciyi kullanarak varsayılan ham veri dizisini alır. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Varsayılan ham veri dizisini alır. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Bir görüntünün pikselini alır. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Belirtilen konum için bir görüntünün 32-bit ARGB pikselini ayarlar. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Belirtilen konum için bir görüntünün pikselini ayarlar. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Belirtilen tarama satırı indeksine tüm tarama satırını yazar. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Belirtilen tarama satırı indeksine tüm tarama satırını yazar. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | 32-bit ARGB pikselleri paketler halinde kısmen yükler. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Pikselleri paketler halinde kısmen yükler. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | 32-bit ARGB pikselleri yükler. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | 64-bit ARGB pikselleri yükler. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | 64-bit ARGB pikselleri paketler halinde kısmen yükler. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Pikselleri yükler. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | CMYK formatında pikselleri yükler. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | CMYK formatında pikselleri yükler. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Kısmi işleme mekanizmasını kullanarak ham görüntü verisini yükler. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Ham veriyi yükler. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Ham veriyi kaydeder. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | 32-bit ARGB pikselleri kaydeder. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Pikselleri kaydeder. |
| [toBitmap()](#toBitmap--) | Raster görüntüyü bitmap'e dönüştürür. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Pikselleri kaydeder. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Pikselleri kaydeder. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Bu `RasterImage` için çözünürlüğü ayarlar. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
| [autoRotate()](#autoRotate--) | Exif üst verisinden çıkarılan yönlendirme verilerine dayanarak görüntüyü otomatik olarak döndürür. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntüyü genişletilmiş seçeneklerle yeniden boyutlandırır. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Görüntüyü merkezin etrafında döndür. |
| [rotate(float angle)](#rotate-float-) | Görüntüyü merkezin etrafında döndür. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Bu görüntü örneğini `overlay` görüntüsüyle harmanlar. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Bu görüntü örneğini `overlay` görüntüsüyle harmanlar. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Bu görüntü örneğini `overlay` ile alfa == 255 olduğunda harmanlar. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Bu görüntü örneğini `overlay` ile harmanlar. |
| [grayscale()](#grayscale--) | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [normalizeHistogram()](#normalizeHistogram--) | Görüntü histogramını normalleştirir \\u2014 piksel değerlerini mevcut tüm aralığı kullanacak şekilde ayarlar. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalizasyonu. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntünün parlaklığını ayarlar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Görüntü kontrastı |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Sağlanan şifreye dayalı dijital imzayı steganografi kullanarak görüntüye gömer. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün gama düzeltmesi. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Bir görüntünün gama düzeltmesi. |
| [getSkewAngle()](#getSkewAngle--) | Eğrilik açısını alır. |
| [normalizeAngle()](#normalizeAngle--) | Açıyı normalleştirir. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Açıyı normalleştirir. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Belirtilen dikdörtgeni filtreler. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// GifOptions bir örneği oluşturun ve Source özelliği dahil çeşitli özelliklerini ayarlayın
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Image örneği oluşturun
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Görüntünün piksellerini alanı görüntü sınırı olarak belirterek alın
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Diziyi döngüye al ve alternatif indeksli pikselin rengini ayarlar
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // İndeksli piksel rengini sarıya ayarla
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // İndeksli piksel rengini maviye ayarla
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Piksel değişikliklerini görüntüye uygula
    image.savePixels(image.getBounds(), pixels);

    // Tüm değişiklikleri kaydedin.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Görüntü bileşenlerinin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - `true` eğer görüntü bileşenleri önceden çarpılmış olmalıysa; aksi takdirde, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Görüntü bileşenlerinin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` eğer görüntü bileşenleri önceden çarpılmış olmalıysa; aksi takdirde, `false`. |


**Example: The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntü için pikselleri kaydet.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // Pikseller, orijinal görüntüde önceden çarpılmamış biçimde depolanır.
    // Önceden çarpılmış renk bileşenlerini elde etmek için ilgili seçeneği açıkça belirtmek gerekir.
    // Önceden çarpılmış renk bileşenleri aşağıdaki formüllerle hesaplanır:
    // kırmızı = orijinal_kırmızı * alfa / 255;
    // yeşil = orijinal_yeşil * alfa / 255;
    // mavi = orijinal_mavi * alfa / 255;
    rasterImage.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = rasterImage.loadPixels(rasterImage.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}
```

### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Ham veri yüklemenin mevcut olduğu durumlarda ham veri yüklemenin kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - `true` eğer ham veri yükleme mevcut olduğunda ham veri yükleme kullanılacaksa; aksi takdirde, `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Ham veri yüklemenin mevcut olduğu durumlarda ham veri yüklemenin kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` eğer ham veri yükleme mevcut olduğunda ham veri yükleme kullanılacaksa; aksi takdirde, `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - `true` eğer XMP meta verileri güncellenecekse; aksi takdirde, `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` eğer XMP meta verileri güncellenecekse; aksi takdirde, `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Dizine dayalı renk dönüştürücüyü alır veya ayarlar

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Dizine dayalı renk dönüştürücüyü alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | İndeksli renk dönüştürücü |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Özel renk dönüştürücüyü alır veya ayarlar

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Özel renk dönüştürücüyü alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Özel renk dönüştürücü |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar

**Returns:**
int - Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeks
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeks |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır.

Değer: `true` eğer palet görüntüde kullanılıyorsa; aksi takdirde, `false`.

**Returns:**
boolean - görüntü paletinin kullanılıp kullanılmadığını belirten bir değer.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Ham veri biçimini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Yüklenecek görüntü dosyaları.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, kullanılan kanallar: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, kullanılan kanallar: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Ham satır boyutunu bayt cinsinden alır.

**Returns:**
int - Ham satır boyutu bayt cinsinden.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Ham veri yüklemenin mevcut olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - `true` eğer bu ham veri yükleme mevcutsa; aksi takdirde, `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar.

**Returns:**
double - Yatay çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntünün yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Çıktı şöyle görünebilir:
    // Yatay çözünürlük, inç başına piksel olarak: 300.0
    // Dikey çözünürlük, inç başına piksel olarak: 300.0
    // Çözünürlük değerlerini 96 dpi olarak ayarlayın
    // Yatay çözünürlük, inç başına piksel olarak: 96.0
    // Dikey çözünürlük, inç başına piksel olarak: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Yatay çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar.

**Returns:**
double - Dikey çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntünün yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Çıktı şöyle görünebilir:
    // Yatay çözünürlük, inç başına piksel olarak: 300.0
    // Dikey çözünürlük, inç başına piksel olarak: 300.0
    // Çözünürlük değerlerini 96 dpi olarak ayarlayın
    // Yatay çözünürlük, inç başına piksel olarak: 96.0
    // Dikey çözünürlük, inç başına piksel olarak: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Dikey çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Bu [RasterImage](../../com.aspose.imaging/rasterimage) örneğinin şeffaf bir rengi olup olmadığını gösteren bir değeri alır.

--------------------

Temel uygulama, bu özelliği destekleyen belirli bir uygulamada geçersiz kılınmazsa etkili bir şekilde `` döndürür. Bu özellik, bir görüntü alfa kanalı aracılığıyla şeffaflığı desteklemiyorsa şeffaf bir renk ayarlamak için [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) tarafından öncelikli olarak kullanılır.

**Returns:**
boolean - bu [RasterImage](../../com.aspose.imaging/rasterimage) örneğinin şeffaf bir renge sahip olup olmadığını gösteren bir değer.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - bu örnek alfa içeriyorsa `true`; aksi takdirde `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Yüklenecek görüntü dosyaları.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, kullanılan kanallar: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, kullanılan kanallar: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Görüntünün şeffaf rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Bu [RasterImage](../../com.aspose.imaging/rasterimage) örneğinin şeffaf bir rengi olup olmadığını gösteren bir değeri ayarlar.

--------------------

Temel uygulama, bu özelliği destekleyen belirli bir uygulamada geçersiz kılınmazsa etkili bir şekilde `` döndürür. Bu özellik, bir görüntü alfa kanalı aracılığıyla şeffaflığı desteklemiyorsa şeffaf bir renk ayarlamak için [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) tarafından öncelikli olarak kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | bu [RasterImage](../../com.aspose.imaging/rasterimage) örneğinin şeffaf bir renge sahip olup olmadığını gösteren bir değer. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Görüntünün şeffaf rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Bu görüntünün opaklığını alır.

**Returns:**
float - 0.0 (tamamen şeffaf) ile 1.0 (tamamen opak) arasında bir opaklık değeri.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Bu `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) değerini `null` olarak ayarlayarak bu görüntü örneği meta verilerini kaldırır.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Kaynak görüntünün en son ne zaman değiştirildiğini gösteren tarih ve saat bilgisini alır. Bu yöntem değerli meta veriler sağlar ve kullanıcıların görüntü dosyasındaki güncellemeleri etkili bir şekilde izlemelerine ve yönetmelerine olanak tanır. Bu bilgilere erişerek, kullanıcılar görüntü varlıklarının bütünlüğünü ve güncelliğini garanti edebilir, görüntü kullanımı ve bakımıyla ilgili bilinçli kararlar almayı kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useDefault | boolean | `true` olarak ayarlanırsa, FileInfo'dan gelen bilgileri varsayılan değer olarak kullanır. |

**Returns:**
java.util.Date - Kaynak görüntünün en son değiştirildiği tarih ve saat.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Mevcut görüntüde dithering uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 16 renk içeren 4-bit renk paleti kullanarak eşik dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Sadece 2 renk (siyah ve beyaz) içeren 1-bit renk paleti kullanarak Floyd dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mevcut görüntüde dithering uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Kısmi piksel yükleyiciyi kullanarak varsayılan piksel dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksel alınacak dikdörtgen. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Kısmi piksel yükleyici. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Kısmi piksel yükleyiciyi kullanarak varsayılan ham veri dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksel alınacak dikdörtgen. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Kısmi ham veri yükleyicisi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Ham veri ayarları. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Varsayılan 32-bit ARGB piksel dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksel alınacak dikdörtgen. |

**Returns:**
int[] - Varsayılan piksel dizisi.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Varsayılan ham veri dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Ham veri alınacak dikdörtgen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Ham veri ayarları. |

**Returns:**
byte[] - Varsayılan ham veri dizisi.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Bir görüntünün 32-bit ARGB pikselini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x konumu. |
| y | int | Pikselin y konumu. |

**Returns:**
int - Belirtilen konum için 32-bit ARGB piksel.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntünün sol üst pikselinin renginin tam sayı temsilini alın.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // Bireysel renk bileşenlerinin değerlerini elde etmek için renk değerini ilgili bit sayısı kadar kaydırın.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Piksel(0,0) rengi A=255,R=0,G=0,B=0'dır
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Bir görüntünün pikselini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x konumu. |
| y | int | Pikselin y konumu. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntünün sol üst pikselinin rengini alın.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Bireysel renk bileşenlerinin değerlerini elde edin
    int alpha = color.getA();
    int red = color.getR();
    int green = color.getG();
    int blue = color.getB();

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}
```

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Belirtilen konum için bir görüntünün 32-bit ARGB pikselini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x konumu. |
| y | int | Pikselin y konumu. |
| argb32Color | int | Belirtilen konum için 32-bit ARGB piksel. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Sol üst pikselin rengini ayarlar.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Başka bir yol, com.aspose.imaging.Color örneğini doğrudan geçirmektir
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Belirtilen konum için bir görüntünün pikselini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x konumu. |
| y | int | Pikselin y konumu. |
| color | [Color](../../com.aspose.imaging/color) | Belirtilen konum için piksel rengi. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Sol üst pikselin rengini ayarlar.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Başka bir yol, com.aspose.imaging.Color örneğini doğrudan geçirmektir
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Belirtilen tarama satırı indeksiyle tüm tarama satırını okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns:**
com.aspose.imaging.Color[] - Tarama satırı piksel renk değerleri dizisi.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Belirtilen tarama satırı indeksiyle tüm tarama satırını okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns:**
int[] - Tarama satırı 32-bit ARGB renk değerleri dizisi.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Belirtilen tarama satırı indeksine tüm tarama satırını yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Yazılacak piksel renkleri dizisi. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Belirtilen tarama satırı indeksine tüm tarama satırını yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scanLineIndex | int | Tarama satırının sıfır tabanlı indeksi. |
| argb32Pixels | int[] | Yazılacak 32-bit ARGB renkler dizisi. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


32-bit ARGB pikselleri paketler halinde kısmen yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | İstenen dikdörtgen. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | 32-bit ARGB piksel yükleyicisi. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Aşağıdaki örnek, raster görüntünün piksellerini kendi kısmi işlemcinizle nasıl yükleyeceğinizi ve işleyeceğinizi gösterir. Örneğin, bir görüntünün tamamen şeffaf piksellerini sayma sorununu ele alalım. Şeffaf pikselleri kısmi yükleme mekanizmasıyla saymak için, com.aspose.imaging.IPartialArgb32PixelLoader arayüzünü uygulayan ayrı bir sınıf olan TransparentArgb32PixelCounter tanıtılır.
``` java

// İlk olarak, tüm tamamen şeffaf pikselleri saymak için com.aspose.imaging.IPartialArgb32PixelLoader'ı uygulayın.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentArgb32PixelCounter implements com.aspose.imaging.IPartialArgb32PixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>                 *
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, int[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (int pixel : pixels) {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0) {
                this.count++;
            }
        }
    }
}

// İşte sayacı kullanmaya ilişkin bir örnek.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // com.aspose.imaging.IPartialArgb32PixelLoader'ın bir örneğini oluşturun ve bunu com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels yöntemine geçirin.
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Tüm görüntü için pikselleri yükleyin. Görüntünün herhangi bir dikdörtgen bölümü, com.aspose.imaging.RasterImage.loadPartialArgb32Pixels yönteminin ilk parametresi olarak belirtilebilir.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Tamamen şeffaf piksel sayısı 55157'dir.
// Toplam piksel sayısı 120400'tür.
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Pikselleri paketler halinde kısmen yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | İstenen dikdörtgen. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Piksel yükleyici. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Aşağıdaki örnek, raster görüntünün piksellerini kendi kısmi işlemcinizle nasıl yükleyip işleyebileceğinizi gösterir. Örneğin, bir görüntünün tamamen şeffaf piksellerini sayma sorununu ele alalım. Şeffaf pikselleri kısmi yükleme mekanizmasıyla saymak için, com.aspose.imaging.IPartialPixelLoader'ı uygulayan ayrı bir TransparentPixelCounter sınıfı tanıtılmıştır.
``` java

// İlk olarak, tüm tamamen şeffaf pikselleri saymak için com.aspose.imaging.IPartialPixelLoader'ı uygulayın.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelCounter implements com.aspose.imaging.IPartialPixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, com.aspose.imaging.Color[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (com.aspose.imaging.Color pixel : pixels) {
            if (pixel.getA() == 0) {
                this.count++;
            }
        }
    }
}

// İşte sayacı kullanmaya ilişkin bir örnek.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // com.aspose.imaging.IPartialPixelLoader'ın bir örneğini oluşturun ve bunu com.aspose.imaging.RasterImage.loadPartialPixels yöntemine geçirin.
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Tüm görüntü için pikselleri yükleyin. Görüntünün herhangi bir dikdörtgen bölümü, com.aspose.imaging.RasterImage.loadPartialPixels yönteminin ilk parametresi olarak belirtilebilir.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Tamamen şeffaf piksel sayısı 55157'dir.
// Toplam piksel sayısı 120400'tür.
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


32-bit ARGB pikselleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
int[] - Yüklenen 32-bit ARGB piksel dizisi.

**Example: The following example shows how to load and process pixels of a raster image.**
Aşağıdaki örnek, raster görüntünün piksellerini nasıl yükleyip işleyebileceğinizi gösterir. Pikseller 32-bit tamsayı değerleri olarak temsil edilir. Örneğin, bir görüntünün tamamen şeffaf piksellerini sayma sorununu ele alalım.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntü için pikselleri yükleyin. Görüntünün herhangi bir dikdörtgen bölümü, com.aspose.imaging.RasterImage.loadArgb32Pixels yönteminin bir parametresi olarak belirtilebilir.
    int[] pixels = rasterImage.loadArgb32Pixels(rasterImage.getBounds());

    int count = 0;
    for (int pixel : pixels) {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.imaging.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


64-bit ARGB pikselleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
long[] - Yüklenen 64-bit ARGB piksel dizisi.

**Example: The following example shows how to load and process pixels of a raster image.**
Aşağıdaki örnek, raster görüntünün piksellerini nasıl yükleyip işleyebileceğinizi gösterir. Pikseller 64-bit tamsayı değerleri olarak temsil edilir. Örneğin, bir görüntünün tamamen şeffaf piksellerini sayma sorununu ele alalım.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntü için pikselleri yükleyin. Görüntünün herhangi bir dikdörtgen bölümü, com.aspose.imaging.RasterImage.loadArgb64Pixels yönteminin bir parametresi olarak belirtilebilir.
    // Görüntünün kendisinin örnek başına 16 bit olması gerektiğini unutmayın, çünkü com.aspose.imaging.RasterImage.loadArgb64Pixels 8 bit örnek başına çalışmaz.
    // 8 bit örnek başına çalışmak için lütfen eski iyi bilinen com.aspose.imaging.RasterImage.loadArgb32Pixels yöntemini kullanın.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Alfa dahil tüm renk bileşenlerinin 16-bit değerlerle temsil edildiğini ve bu nedenle izin verilen değerlerin [0, 63535] aralığında olduğunu unutmayın.
        long alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader) {#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-}
```
public final void loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)
```


64-bit ARGB pikselleri paketler halinde kısmen yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | İstenen dikdörtgen. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | 64-bit ARGB piksel yükleyici. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Pikselleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
com.aspose.imaging.Color[] - Yüklenen piksel dizisi.

**Example: The following example shows how to load and process pixels of a raster image.**
Aşağıdaki örnek, raster görüntünün piksellerini nasıl yükleyip işleyebileceğinizi gösterir. Örneğin, bir görüntünün tamamen şeffaf piksellerini sayma sorununu ele alalım.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntü için pikselleri yükleyin. Görüntünün herhangi bir dikdörtgen bölümü, Aspose.Imaging.RasterImage.LoadPixels yönteminin bir parametresi olarak belirtilebilir.
    com.aspose.imaging.Color[] pixels = rasterImage.loadPixels(rasterImage.getBounds());

    int count = 0;
    for (com.aspose.imaging.Color pixel : pixels) {
        if (pixel.getA() == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.imaging.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


CMYK formatında pikselleri yükler. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `loadCmyk32Pixels(Rectangle)` yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
com.aspose.imaging.CmykColor[] - Yüklenen CMYK piksel dizisi.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


CMYK formatında pikselleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin yükleneceği dikdörtgen. |

**Returns:**
int[] - Yüklenen CMYK pikseller 32-bit tam sayı değerleri olarak sunulur.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Kısmi işleme mekanizmasını kullanarak ham görüntü verisini yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Veri yüklenecek görüntünün istenen dikdörtgen alanı. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Ham veri ayarları. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Ham veri yükleyicisi. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
Aşağıdaki örnek, RawDataSettings kullanarak ham görüntü verisinden piksellerin nasıl çıkarılacağını gösterir. Örneğin, bir görüntünün tamamen şeffaf piksellerinin sayılması sorununu ele alalım.
``` java

// İlk olarak, bir sayaç uygulayın. Ham veri durumunda, sayaç şu şekilde görünebilir:
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelRawDataCounter implements com.aspose.imaging.IPartialRawDataLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * The raw data settings of the loaded image.
     */
    private com.aspose.imaging.RawDataSettings rawDataSettings;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.</p>
     *
     * @param settings The raw data settings allow to extract color components from raw data.
     */
    public TransparentPixelRawDataCounter(com.aspose.imaging.RawDataSettings settings) {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end)// throws java.lang.Exception
    {
        int[] channelBits = this.rawDataSettings.getPixelDataFormat().getChannelBits();

        // Kodun basitleştirilmesi için burada yalnızca basit formatlar ele alınmıştır.
        // Sadece örnek başına 8 bit olan görüntüleri ele alalım.
        for (int i = 0; i < channelBits.length; i++) {
            if (channelBits[i] != 8) {
                throw new java.lang.UnsupportedOperationException();
            }
        }

        switch (this.rawDataSettings.getPixelDataFormat().getPixelFormat()) {
            case com.aspose.imaging.PixelFormat.Rgb:
            case com.aspose.imaging.PixelFormat.Bgr: {
                if (channelBits.length == 4) {
                    // ARGB
                    for (int i = 0; i < data.length; i += 4) {
                        // Alfa kanalı, renk bileşenlerinden sonra, en son depolanır.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Gri Tonlu Alfa
                    for (int i = 0; i < data.length; i += 2) {
                        // Alfa kanalı, renk bileşenlerinden sonra, en son depolanır.
                        if (data[i + 1] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            default:
                throw new java.lang.IllegalArgumentException("PixelFormat");
        }
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>                 *
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     * @param loadOptions   The load options.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end, com.aspose.imaging.LoadOptions loadOptions) {
        this.process(dataRectangle, data, start, end);
    }
}

// İşte sayacı kullanmanın ana örneği
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Tüm görüntü için pikselleri yükleyin. Görüntünün herhangi bir dikdörtgen bölümü, Aspose.Imaging.RasterImage.LoadRawData metodunun bir parametresi olarak belirtilebilir.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Tamamen şeffaf piksel sayısı 55157'dir.
// Toplam piksel sayısı 120400'tür.
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Ham veriyi yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Ham verinin yükleneceği dikdörtgen. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntünün sınırları. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Yüklenen veri için kullanılacak ham veri ayarları. Veri belirtilen formatta değilse, veri dönüşümü gerçekleştirileceğini unutmayın. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Ham veri yükleyicisi. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Ham veriyi kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Ham veri. |
| dataOffset | int | Başlangıç ham veri ofseti. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Ham veri dikdörtgeni. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Verinin bulunduğu ham veri ayarları. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


32-bit ARGB pikselleri kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pikseller | int[] | 32-bit ARGB piksel dizisi. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Aşağıdaki örnek, com.aspose.imaging.RasterImage.saveArgb32Pixels metodunu kullanarak bir raster görüntünün merkezi alanını siyah piksellerle doldurur.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Siyah kare
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Siyah kareyi görüntünün ortasına çizin.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveArgb32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveArgb32Pixels.png");
} finally {
    image.dispose();
}
```

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Pikselleri kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Piksel dizisi. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Aşağıdaki örnek, com.aspose.imaging.RasterImage.savePixels metodunu kullanarak bir raster görüntünün merkezi alanını siyah piksellerle doldurur.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Siyah kare
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Siyah kareyi görüntünün ortasına çizin.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.savePixels(area, pixels);

    rasterImage.save(dir + "sample.SavePixels.png");
} finally {
    image.dispose();
}
```

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Raster görüntüyü bitmap'e dönüştürür.

**Returns:**
java.awt.image.BufferedImage - Bit eşlem

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Yerel Java bit eşlemine işleyin.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Pikselleri kaydeder. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `saveCmyk32Pixels(Rectangle, int[])` yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK piksel dizisi. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Pikselleri kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pikseller | int[] | CMYK pikseller 32-bit tamsayı değerleri olarak sunulur. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Aşağıdaki örnek, com.aspose.imaging.RasterImage.saveCmyk32Pixels metodunu kullanarak bir raster görüntünün merkezi alanını siyah piksellerle doldurur.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // CMYK renk uzayında siyahın tamsayı temsilini alın.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // Siyah kare.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Siyah kareyi görüntünün ortasına çizin.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveCmyk32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveCmyk32Pixels.png");
} finally {
    image.dispose();
}
```

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Bu `RasterImage` için çözünürlüğü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | `RasterImage`'in inç başına nokta cinsinden yatay çözünürlüğü. |
| dpiY | double | `RasterImage`'in inç başına nokta cinsinden dikey çözünürlüğü. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntünün yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Çıktı şöyle görünebilir:
    // Yatay çözünürlük, inç başına piksel olarak: 300.0
    // Dikey çözünürlük, inç başına piksel olarak: 300.0
    // Çözünürlük değerlerini 96 dpi olarak ayarlayın
    // Yatay çözünürlük, inç başına piksel olarak: 96.0
    // Dikey çözünürlük, inç başına piksel olarak: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Görüntü paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Görüntüyü, Exif meta verilerinden çıkarılan yönlendirme verilerine dayanarak otomatik olarak döndürür. Bu yöntem, görüntülerin doğru yönde gösterilmesini sağlayarak kullanıcı deneyimini artırır ve manuel ayarlama ihtiyacını ortadan kaldırır. Exif bilgileri analiz edilerek görüntü buna göre döndürülür, farklı platform ve cihazlarda sorunsuz bir görüntüleme deneyimi sunar. Bu otomatik döndürme süreci, görüntü işleme işlemlerini basitleştirir ve özellikle çeşitli yönlerdeki büyük görüntü topluluklarıyla çalışırken genel kullanılabilirliği iyileştirir.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntüyü genişletilmiş seçeneklerle yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |
| resizeProportionally | boolean | Eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |


**Example: The following example binarizes a raster image with the predefined threshold.**
Aşağıdaki örnek, önceden tanımlı eşik değeriyle bir raster görüntüyü ikili (binary) hale getirir. İkili görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntüyü 127 eşik değeriyle ikilileştirin.
    // Bir pikselin ilgili gri değeri 127'den büyükse, ona 255 değeri atanır, aksi takdirde 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Otsu eşikleme ile bir görüntünün ikilileştirilmesi


**Example: The following example binarizes a raster image with Otsu thresholding.**
Aşağıdaki örnek, Otsu eşikleme yöntemiyle bir raster görüntüyü ikili hale getirir. İkili görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntüyü Otsu eşikleme ile ikilileştirin.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |
| windowSize | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
Aşağıdaki örnek, belirtilen pencere boyutu ile Bradley'ın uyarlamalı eşikleme algoritmasını kullanarak bir raster görüntüyü ikili hale getirir. İkili görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Görüntüyü 5 parlaklık farkı ile ikili hale getirin. Parlaklık, bir piksel ile bu pikselin etrafındaki 10 x 10 pencere ortalaması arasındaki farktır.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-}
```
public final void blend(Point origin, RasterImage overlay, Rectangle overlayArea)
```


Bu görüntü örneğini `overlay` görüntüsüyle harmanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Arka plan görüntüsü karıştırma kaynağı. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Kaplama görüntüsü. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Kaplama alanı. |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Bu görüntü örneğini `overlay` görüntüsüyle harmanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Arka plan görüntüsü karıştırma kaynağı. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Kaplama görüntüsü. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Kaplama alanı. |
| overlayAlpha | byte | Kaplama alfa. |

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Bu görüntü örneğini `overlay` ile alfa == 255 olduğunda harmanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Arka plan görüntüsü karıştırma kaynağı. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Kaplama. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Bu görüntü örneğini `overlay` ile harmanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Arka plan görüntüsü karıştırma kaynağı. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Kaplama. |
| overlayAlpha | byte | Kaplama alfa. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Bir görüntünün gri tonlamalı temsiline dönüşümü


**Example: The following example transforms a colored raster image to its grayscale representation.**
Aşağıdaki örnek, renkli bir raster görüntüyü gri tonlamalı temsiline dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Görüntü histogramını normalleştirir \\u2014 piksel değerlerini mevcut tüm aralığı kullanacak şekilde ayarlar.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalizasyonu.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntünün parlaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Görüntü kontrastı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Sağlanan şifreye dayalı dijital imzayı steganografi kullanarak görüntüye gömer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | Dijital imza verisi oluşturmak için kullanılan parola |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | Gömülü veriyi çıkarmak için kullanılan parola. |

**Returns:**
int - Yüzde benzerlik değeri.
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder.

--------------------

Bu yöntem, `GetSignPercentage` kullanarak en hızlı algılamayı sağlar. Çıkarılan veri belirtilen eşiği karşıladığında, algılama doğruluğunu artırmaya yönelik sonraki çıkarma adımları atlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | İmzayı kontrol etmek için parola. |

**Returns:**
boolean - Görüntü imzalıysa true, aksi takdirde false.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder.

--------------------

Bu yöntem, `GetSignPercentage` kullanarak en hızlı algılamayı sağlar. Çıkarılan veri belirtilen eşiği karşıladığında, algılama doğruluğunu artırmaya yönelik sonraki çıkarma adımları atlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | İmzayı kontrol etmek için parola. |
| percentageThreshold | int | Görüntünün imzalı kabul edilip edilmediğini belirleyen eşik (yüzde olarak)[0-100]. Belirtilmezse, varsayılan eşik (`75`) uygulanır. |

**Returns:**
boolean - Görüntü imzalıysa true, aksi takdirde false.
### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Bir görüntünün gama düzeltmesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gama |
| gammaGreen | float | Yeşil kanal katsayısı için gama |
| gammaBlue | float | Mavi kanal katsayısı için gamma |


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gamma katsayılarını ayarlayın.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Bir görüntünün gama düzeltmesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Kırmızı, yeşil ve mavi kanallar için gamma katsayısını ayarlayın.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Eğim açısını alır. Bu yöntem, taranan metin belgelerinde tarama sırasında eğim açısını belirlemek için uygulanabilir.

**Returns:**
float - Eğim açısı, derece cinsinden.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Açıyı normalleştirir. Bu yöntem, kaymış taramayı gidermek için taranmış metin belgelerine uygulanabilir. Bu yöntem \#getSkewAngle.getSkewAngle ve [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-) yöntemlerini kullanır.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Açıyı normalleştirir. Bu yöntem, taranmış metin belgelerine uygulanabilir. Bu yöntem \#rotate(float, boolean, Color).rotate(float, boolean, Color) yöntemlerini kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeProportionally | boolean | Eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
Kayma, belge tarama işlemi sırasında metin/görüntülerin hafif bir açıyla döndürülmesi sonucu ortaya çıkabilecek bir artefakttır. Çeşitli nedenleri olabilir ancak en yaygın nedeni kağıdın tarama sırasında yerinden kaymasıdır. Bu nedenle, deskew, taranmış dosyalarda (ör. bitmap) bu sorunu tespit edip düzeltme sürecidir; böylece deskew uygulanmış belgelerde metin/görüntüler doğru ve yatay olarak ayarlanmış olur.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Varsayılan parametrelerle kaymış taramayı ortadan kaldırın.
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(inputFilePath);
try {
    // Deskew
    image.normalizeAngle(false /*do not resize*/, com.aspose.imaging.Color.getLightGray() /*background color*/);
    image.save(outputFilePath);
} finally {
    image.close();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Belirtilen dikdörtgeni filtreler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Değiştirilecek eski renk. |
| oldColorDiff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| newColor | [Color](../../com.aspose.imaging/color) | Eski rengi değiştirecek yeni renk. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldColorArgb | int | Değiştirilecek eski renk ARGB değeri. |
| oldColorDiff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| newColorArgb | int | Eski rengi değiştirmek için yeni renk ARGB değeri. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Şeffaf olmayan renkleri değiştirecek yeni renk. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorArgb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

