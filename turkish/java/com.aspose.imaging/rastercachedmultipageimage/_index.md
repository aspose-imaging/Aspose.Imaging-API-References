---
title: "RasterCachedMultipageImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Raster çok sayfalı görüntü"
type: docs
weight: 90
url: /tr/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

Raster çok sayfalı görüntü
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [isCached()](#isCached--) | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini gösteren bir değer alır. |
| [hasTransparentColor()](#hasTransparentColor--) | Görselin şeffaf bir renge sahip olup olmadığını gösteren bir değer alır. |
| [getImageOpacity()](#getImageOpacity--) | Bu görüntünün opaklığını alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değer alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengi için bir değer ayarlar. |
| [getMetadata()](#getMetadata--) | Kareden XMP verisini alır. |
| [getPageExportingAction()](#getPageExportingAction--) | Sayfa dışa aktarma eylemini alır. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Sayfa dışa aktarma eylemini ayarlar. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntü için bir `brightness` ayarı yapar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) kontrastı |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün gama düzeltmesi. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Bir görüntünün gama düzeltmesi. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Bu görüntü örneğini `overlay` görüntüsüyle harmanlar. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Sağlanan şifreye dayalı dijital imzayı görüntünün her sayfasına gömer. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Görüntüyü kırpar. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Görüntüyü kaydırmalarla kırpar. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mevcut görüntüde dithering uygular. |
| [grayscale()](#grayscale--) | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [normalizeHistogram()](#normalizeHistogram--) | Görüntü histogramını normalleştirir \\u2014 piksel değerlerini mevcut tüm aralığı kullanacak şekilde ayarlar. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` görüntüyü merkez etrafında döndürür. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Tüm sayfaları döndürür, çevirir veya döndürüp çevirir. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Tüm çevirme işlemini döndürür. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü yeniden boyutlandırır. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntüyü yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Belirtilen dikdörtgeni filtreler. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Açıyı normalleştirir. |
| [cacheData()](#cacheData--) | Verileri özel olarak önbelleğe alır. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//Tiff görüntülerini kaydetmeden (dışa aktarmadan) önce toplu dönüştürme olasılığı uygulanmıştır.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Sayfalar için toplu işlemi ayarla
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Önceki sayfalardan gereksiz çöp depolamayı önlemek için çöp toplama başlatır
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

Değer: Görüntünün yüksekliği.

**Returns:**
int - görüntünün yüksekliği.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

Değer: Görüntünün genişliği.

**Returns:**
int - görüntünün genişliği.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

Değer: Görüntünün piksel başına bit sayısı.

**Returns:**
int - görüntünün piksel başına bit sayısı.
### isCached() {#isCached--}
```
public boolean isCached()
```


Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır.

Değer: Görüntü verisi önbelleğe alındıysa `true`; aksi takdirde `false`.

**Returns:**
boolean - şu anda görüntü verisinin önbelleğe alınıp alınmadığını gösteren bir değer.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini gösteren bir değer alır.

Değer: Bu örnek alfa içeriyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean - bu örneğin alfa içerip içermediğini gösteren bir değer.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Görselin şeffaf bir renge sahip olup olmadığını gösteren bir değer alır.

--------------------

Bu uygulama, `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized) değerinin `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) değerini kontrol eder.

**Returns:**
boolean - görüntünün şeffaf bir renge sahip olup olmadığını gösteren bir değer.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Bu görüntünün opaklığını alır.

Değer: 0.0 (tamamen şeffaf) ile 1.0 (tamamen opak) arasında opaklık değeri.

**Returns:**
float - bu görüntünün opaklığı.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengi için bir değer alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengi için bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan rengi için bir değer. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Kareden XMP verisini alır.

Değer: XMP paket veri sarmalayıcısı

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Sayfa dışa aktarma eylemini alır. Lütfen bu yöntemin ayarlanmasının yürütüldükten sonra sayfa kaynaklarını otomatik olarak serbest bırakacağını unutmayın. Her sayfa kaydedilmeden hemen önce yürütülür.

Değer: Sayfa dışa aktarma eylemi.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Sayfa dışa aktarma eylemini ayarlar. Lütfen bu yöntemin ayarlanmasının yürütüldükten sonra sayfa kaynaklarını otomatik olarak serbest bırakacağını unutmayın. Her sayfa kaydedilmeden hemen önce yürütülür.

Değer: Sayfa dışa aktarma eylemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | sayfa dışa aktarma eylemi. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntü için bir `brightness` ayarı yapar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |

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

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Bir görüntünün gama düzeltmesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |

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

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Sağlanan şifreye dayalı dijital imzayı görüntünün her sayfasına gömer.

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

--------------------

Çok sayfalı görüntüler nedeniyle, sonuç hesaplanan `MIDDLE AVERAGED signing percentage` değerini temsil eder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | Gömülü veriyi çıkarmak için kullanılan parola. |

**Returns:**
int - Yüzde benzerlik değeri.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | İmzayı kontrol etmek için parola. |
|  | percentageThreshold | int | Görüntünün imzalı kabul edilip edilmediğini belirleyen eşik (yüzde olarak)[0-100]. Belirtilmezse, varsayılan eşik (`75`) uygulanır. |

--------------------

Bu yöntem, `GetSignPercentage` kullanarak en hızlı algılamayı sağlar. Çıkarılan veri belirtilen eşiği karşıladığında, algılama doğruluğunu artırmaya yönelik sonraki çıkarma adımları atlanır.

Sonuç, çok sayfalı görüntünün tüm sayfaları imzalı olarak tanındığında yalnızca `true` olur; aksi takdirde görüntü imzasız kabul edilir. |

**Returns:**
boolean - Görüntü imzalıysa true, aksi takdirde false.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |

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

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Otsu eşikleme ile bir görüntünün ikilileştirilmesi

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Görüntüyü kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Görüntüyü kaydırmalarla kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mevcut görüntüde dithering uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Bir görüntünün gri tonlamalı temsiline dönüşümü

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Görüntü histogramını normalleştirir \\u2014 piksel değerlerini mevcut tüm aralığı kullanacak şekilde ayarlar.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` görüntüyü merkez etrafında döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı dereceler cinsindendir. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve sadece `` görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Tüm sayfaları döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Tüm çevirme işlemini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlip | int | Dönüş çevirmesi. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntüyü yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntüyü yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

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

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorArgb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

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

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Açıyı normalleştirir. Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) ve [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) metodlarını kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeProportionally | boolean | Eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Verileri özel olarak önbelleğe alır.

