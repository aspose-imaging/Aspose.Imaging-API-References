---
title: "RasterCachedImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder."
type: docs
weight: 89
url: /tr/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Raster grafik işlemlerini destekleyen bir raster görüntüyü temsil eder. Bu görüntü gerektiğinde piksel verilerini önbelleğe alır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isCached()](#isCached--) | Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır. |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel `DataStreamSupporter.DataStreamContainer`'dan ek veri yüklemesinin yapılmayacağını garanti eder. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Bu görüntü örneğini `overlay` görüntüsüyle harmanlar. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü yeniden boyutlandırır. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntüyü yeniden boyutlandırır. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Görüntüyü merkezin etrafında döndür. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Görüntüyü kırpar. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mevcut görüntüde dithering uygular. |
| [grayscale()](#grayscale--) | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [normalizeHistogram()](#normalizeHistogram--) | Görüntü histogramını normalleştirir \\u2014 piksel değerlerini mevcut tüm aralığı kullanacak şekilde ayarlar. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalleştirmesi gerçekleştirir. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Bradley'in uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntünün parlaklığını ayarlar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Görüntü kontrastı |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün gama düzeltmesi. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Bir görüntünün gama düzeltmesi. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Sağlanan şifreye dayalı dijital imzayı steganografi kullanarak görüntüye gömer. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Sağlanan şifre ve eşik kullanılarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
Aşağıdaki örnek, renkli bir raster önbellekli görüntüyü gri tonlamalı temsiline dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


Görüntü verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değer alır.

**Returns:**
boolean - görüntü verisi önbelleğe alındıysa `true`; aksi takdirde `false`.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Verileri önbelleğe alır ve temel `DataStreamSupporter.DataStreamContainer`'dan ek veri yüklemesinin yapılmayacağını garanti eder.


**Example: The following example shows how raster image caching affects performance.**
Aşağıdaki örnek, raster görüntü önbelleklemenin performansı nasıl etkilediğini gösterir. Genel olarak, önbellekli veriyi okumak önbelleksiz veriyi okumaktan daha hızlı gerçekleşir.
``` java
String dir = "c:\\temp\\";

// Bir PNG dosyasından görüntü yükle.
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Tüm piksel verilerini önbelleğe al ki temel veri akışından ek veri yüklemesi yapılmasın
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Tüm pikselleri okumak oldukça hızlıdır.
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Bir PNG dosyasından bir görüntü yükle
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Tüm pikselleri okumak, önbelleğe alındığında olduğu kadar hızlı değil
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
//Tüm önbelleğe alınmış pikselleri okumak 2923 ms sürdü.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

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


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

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


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 enterpolasyonu üzerine kurulu uyarlamalı algoritma.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Küçük dikdörtgen filtre
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Palet içindeki renk sayısı.
resizeSettings.setEntriesCount(256);

// Renk kantitatizasyonu kullanılmaz
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Euclidian yöntemi
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Bu bir yardımcı sınıftır.
class LocalHelper {
    // Döndürme çevirme türünün dize temsilini alır.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// İşte ana örnek.
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // Döndür, çevir ve çıktıyı dosyaya kaydet.
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı dereceler cinsindendir. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | boolean | Eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Görüntüyü kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |


**Example: The following example crops a raster cached image.**
Aşağıdaki örnek bir raster önbellekli görüntüyü kırpar. Kırpma alanı com.aspose.imaging.Rectangle aracılığıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkezi alanıdır.
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // Kırpılmış görüntüyü PNG olarak kaydet.
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
Aşağıdaki örnek, renkli bir raster önbellekli görüntüyü gri tonlamalı temsiline dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalleştirmesi gerçekleştirir.

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

Bu yöntem, görüntünün görsel kalitesini kontrastı, yerel parlaklığı ve renk doğruluğunu artırarak iyileştirmek için gelişmiş uyarlanabilir filtrelerin (CLAHE, adaptive white stretch ve auto white balance) bir ardışık düzenini uygular.

`**Filter pipeline:**`

1.  Kontrast Sınırlı Uyarlanabilir Histogram Eşitlemesi (CLAHE) \\u2013 yerel kontrastı iyileştirir ve ince detayları artırır.
2.  Uyarlanabilir Beyaz Germe \\u2013 etkili beyaz seviyesini artırırken karanlık özellikleri korur.
3.  Otomatik Beyaz Denge \\u2013 kanal histogramlarını dengeleyerek renk kaymalarını düzeltir.

`**Note:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
Aşağıdaki örnek, önceden tanımlı eşik ile bir raster önbellekli görüntüyü ikili hale getirir. İkili görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
Aşağıdaki örnek, bir raster önbellekli görüntüyü Otsu eşikleme ile ikilileştirir. İkilileştirilmiş görüntüler yalnızca 2 renkten oluşur - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Görüntüyü Otsu eşikleme ile ikilileştirin.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
Aşağıdaki örnek, belirtilen pencere boyutuyla Bradley'ın uyarlamalı eşikleme algoritmasını kullanarak bir raster önbellekli görüntüyü ikilileştirir. İkilileştirilmiş görüntüler yalnızca 2 renkten oluşur - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Görüntüyü 5 parlaklık farkı ile ikilileştirin.
    // Parlaklık, bu pikselin etrafında merkezlenmiş 10 x 10 piksellik bir pencerenin ortalaması ile piksel arasındaki farktır.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
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


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
Aşağıdaki örnek, Bradley'ın uyarlamalı eşikleme algoritmasını kullanarak bir raster önbellekli görüntüyü ikilileştirir. İkilileştirilmiş görüntüler yalnızca 2 renkten oluşur - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Görüntüyü 5 parlaklık farkı ile ikilileştirin.
    // Parlaklık, bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki farktır.
    // Pencere boyutu otomatik olarak kalibre edilecektir.
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntünün parlaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Kırmızı, yeşil ve mavi kanallar için gamma katsayısını ayarlayın.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
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
