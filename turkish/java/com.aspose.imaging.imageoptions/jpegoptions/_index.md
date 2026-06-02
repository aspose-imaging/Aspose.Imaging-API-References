---
title: "JpegOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle yüksek kaliteli JPEG görüntülerini zahmetsizce oluşturun; sıkıştırma seviyelerini ayarlayarak depolama boyutunu optimize ederken görüntü kalitesinden ödün vermeyin."
type: docs
weight: 26
url: /tr/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

API'mizle yüksek kaliteli JPEG görüntülerini zahmetsizce oluşturun; sıkıştırma seviyelerini ayarlayarak depolama boyutunu optimize ederken görüntü kalitesinden ödün vermeyin. Çeşitli sıkıştırma tipleri, neredeyse kayıpsız kodlama, RGB ve CMYK renk profilleri, ayrıca EXIF, JFIF görüntü verileri ve XMP konteynerleri desteği sayesinde, görüntü oluşturma ihtiyaçlarınız için çok yönlü ve özelleştirilebilir seçeneklerden yararlanın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | `JpegOptions` sınıfının yeni bir örneğini başlatır. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | `JpegOptions` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Varsayılan bellek tahsis sınırını alır. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Varsayılan bellek tahsis sınırını ayarlar. |
| [getJfif()](#getJfif--) | jfif'i alır. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | jfif'i ayarlar. |
| [getComment()](#getComment--) | jpeg dosya yorumunu alır. |
| [setComment(String value)](#setComment-java.lang.String-) | jpeg dosya yorumunu ayarlar. |
| [getExifData()](#getExifData--) | Exif veri kapsayıcısını alır. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Exif verisini ayarlar. |
| [getJpegExifData()](#getJpegExifData--) | Exif veri kapsayıcısını al. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Exif veri kapsayıcısını al veya ayarla |
| [getCompressionType()](#getCompressionType--) | Sıkıştırma türünü alır. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sıkıştırma türünü ayarlar. |
| [getColorType()](#getColorType--) | jpeg görüntüsü için renk tipini alır. |
| [setColorType(int value)](#setColorType-int-) | jpeg görüntüsü için renk tipini ayarlar. |
| [getBitsPerChannel()](#getBitsPerChannel--) | kayıpsız jpeg görüntüsü için kanal başına bit sayısını alır. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | kayıpsız jpeg görüntüsü için kanal başına bit sayısını ayarlar. |
| [getQuality()](#getQuality--) | görüntü kalitesini alır. |
| [setQuality(int value)](#setQuality-int-) | görüntü kalitesini ayarlar. |
| [getScaledQuality()](#getScaledQuality--) | Ölçeklenmiş kalite. |
| [getRdOptSettings()](#getRdOptSettings--) | RD optimizasyon ayarlarını alır. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | RD optimizasyon ayarlarını ayarlar. |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK jpeg görüntüleri için hedef RGB renk profili. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK jpeg görüntüleri için hedef RGB renk profili. |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK jpeg görüntüleri için hedef CMYK renk profili. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK jpeg görüntüleri için hedef CMYK renk profili. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | JPEG-LS yakın-kayıpsız kodlama için fark sınırını alır (JPEG-LS spesifikasyonundaki NEAR parametresi). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | JPEG-LS yakın-kayıpsız kodlama için fark sınırını ayarlar (JPEG-LS spesifikasyonundaki NEAR parametresi). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | JPEG-LS ara birleştirme modunu alır. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | JPEG-LS ara birleştirme modunu ayarlar. |
| [getJpegLsPreset()](#getJpegLsPreset--) | JPEG-LS ön ayar parametrelerini alır. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | JPEG-LS ön ayar parametrelerini ayarlar. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Her bileşen için yatay alt örneklemeleri alır. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Her bileşen için yatay alt örneklemeleri ayarlar. |
| [getVerticalSampling()](#getVerticalSampling--) | Her bileşen için dikey alt örneklemeleri alır. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Her bileşen için dikey alt örneklemeleri ayarlar. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | 8-bit değeri n-bit değere sığdırmak için örnek yuvarlama modunu alır. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8-bit değeri n-bit değere sığdırmak için örnek yuvarlama modunu ayarlar. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Alfa kanalı mevcutsa kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını gösteren bir değeri alır. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Alfa kanalı mevcutsa kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını gösteren bir değeri ayarlar. |
| [getResolutionUnit()](#getResolutionUnit--) | Çözünürlük birimini alır. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Çözünürlük birimini ayarlar. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Bu örnek, dışa aktarma amaçları için SaveOptions ad alanındaki farklı sınıfların kullanımını gösterir. Gif türünde bir görüntü, Image sınıfının bir örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.
``` java
String dir = "c:\\temp\\";

//Image sınıfının bir örneğine mevcut bir görüntüyü (Gif türünde) yükleyin
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Varsayılan seçenekleri kullanarak BMP dosya formatına dışa aktar
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına dışa aktar
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına dışa aktar
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına dışa aktar
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, JPEG çok sayfalı bir format olmadığından yalnızca bir sayfa rasterleştirilecektir.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


`JpegOptions` sınıfının yeni bir örneğini başlatır.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


`JpegOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | JPEG seçenekleri. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Varsayılan bellek tahsis sınırını alır.

**Returns:**
int - Varsayılan bellek tahsis sınırı.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Varsayılan bellek tahsis sınırını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Varsayılan bellek tahsis sınırı. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


jfif'i alır.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


jfif'i ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


jpeg dosya yorumunu alır.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpeg dosya yorumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Exif veri kapsayıcısını alır.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Exif verisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif verileri. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Exif veri kapsayıcısını al.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Exif veri kapsayıcısını al veya ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Sıkıştırma türünü alır.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Sıkıştırma türünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir JPEG görüntüsü oluştur.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Kanal başına bit sayısı, Y, Cr, Cb bileşenleri için sırasıyla 8, 8, 8'dir.
createOptions.setBitsPerChannel((byte) 8);

// Sıkıştırmanın ilerleyici tipini ayarlayın.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
createOptions.setQuality(100);

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk doygunluğu bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Görüntüyü gri tonlamalı bir degrade ile doldur
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Bir dosyaya kaydet.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg görüntüsü için renk tipini alır.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir JPEG görüntüsü oluştur.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Kanal başına bit sayısı, Y, Cr, Cb bileşenleri için sırasıyla 8, 8, 8'dir.
createOptions.setBitsPerChannel((byte) 8);

// Sıkıştırmanın ilerleyici tipini ayarlayın.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
createOptions.setQuality(100);

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk doygunluğu bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Görüntüyü gri tonlamalı bir degrade ile doldur
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Bir dosyaya kaydet.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg görüntüsü için renk tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Bir BMP görüntüsünü dosyadan yükleyin.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Bazı görüntü işleme işlemleri yapın.

    // İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Kanal başına bit sayısı 8'dir.
    // Bir palet kullanıldığında, renk indeksi renk yerine görüntü verilerinde depolanır.
    saveOptions.setBitsPerChannel((byte) 8);

    // Sıkıştırmanın ilerleyici tipini ayarlayın.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
    saveOptions.setQuality(100);

    // Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Kaynak görüntü renkliyse, gri tonlamaya dönüştürülecektir.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Çıktı boyutunu azaltmak için bir palet kullanın.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Kayıpsız jpeg görüntüsü için kanal başına bitleri alır. Şimdi kanal başına 2 ila 8 bit arasında desteklenmektedir.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Kayıpsız jpeg görüntüsü için kanal başına bitleri ayarlar. Şimdi kanal başına 2 ila 8 bit arasında desteklenmektedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir JPEG görüntüsü oluştur.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Kanal başına bit sayısı, Y, Cr, Cb bileşenleri için sırasıyla 8, 8, 8'dir.
createOptions.setBitsPerChannel((byte) 8);

// Sıkıştırmanın ilerleyici tipini ayarlayın.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
createOptions.setQuality(100);

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk doygunluğu bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Görüntüyü gri tonlamalı bir degrade ile doldur
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Bir dosyaya kaydet.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


görüntü kalitesini alır.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


görüntü kalitesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir JPEG görüntüsü oluştur.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Kanal başına bit sayısı, Y, Cr, Cb bileşenleri için sırasıyla 8, 8, 8'dir.
createOptions.setBitsPerChannel((byte) 8);

// Sıkıştırmanın ilerleyici tipini ayarlayın.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
createOptions.setQuality(100);

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk doygunluğu bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Görüntüyü gri tonlamalı bir degrade ile doldur
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Bir dosyaya kaydet.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Ölçeklenmiş kalite.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


RD optimizasyon ayarlarını alır.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


RD optimizasyon ayarlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | RD optimizasyon ayarları. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


CMYK jpeg görüntüleri için hedef RGB renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için CMYKColorProfile ile eşleşmelidir.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


CMYK jpeg görüntüleri için hedef RGB renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için CMYKColorProfile ile eşleşmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Aşağıdaki örnek, PNG'yi özel bir ICC profili kullanarak CMYK JPEG olarak yükler ve kaydeder. Ardından CMYK JPEG'i yükleyip tekrar PNG olarak kaydeder. RGB'den CMYK'ye ve CMYK'den RGB'ye renk dönüşümü, özel ICC profilleri kullanılarak gerçekleştirilir.
``` java
String dir = "c:\\temp\\";

// PNG'yi yükle ve CMYK JPEG olarak kaydet
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Özel ICC profilleri kullanın
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// CMYK JPEG'i yükle ve PNG olarak kaydet
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Özel ICC profilleri kullanın
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


CMYK jpeg görüntüleri için hedef CMYK renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için RGBColorProfile ile eşleşmelidir.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK jpeg görüntüleri için hedef CMYK renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için RGBColorProfile ile eşleşmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Aşağıdaki örnek, PNG'yi özel bir ICC profili kullanarak CMYK JPEG olarak yükler ve kaydeder. Ardından CMYK JPEG'i yükleyip tekrar PNG olarak kaydeder. RGB'den CMYK'ye ve CMYK'den RGB'ye renk dönüşümü, özel ICC profilleri kullanılarak gerçekleştirilir.
``` java
String dir = "c:\\temp\\";

// PNG'yi yükle ve CMYK JPEG olarak kaydet
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Özel ICC profilleri kullanın
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// CMYK JPEG'i yükle ve PNG olarak kaydet
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Özel ICC profilleri kullanın
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


JPEG-LS yakın-kayıpsız kodlama için fark sınırını alır (JPEG-LS spesifikasyonundaki NEAR parametresi).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


JPEG-LS yakın-kayıpsız kodlama için fark sınırını ayarlar (JPEG-LS spesifikasyonundaki NEAR parametresi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


JPEG-LS ara birleştirme modunu alır.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


JPEG-LS ara birleştirme modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


JPEG-LS ön ayar parametrelerini alır.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


JPEG-LS ön ayar parametrelerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Her bileşen için yatay alt örneklemeleri alır.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Her bileşen için yatay alt örneklemeleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Her bileşen için dikey alt örneklemeleri alır.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Her bileşen için dikey alt örneklemeleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8-bit bir değeri n-bit bir değere sığdırmak için örnek yuvarlama modunu alır. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8-bit bir değeri n-bit bir değere sığdırmak için örnek yuvarlama modunu ayarlar. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Alfa kanalı mevcutsa kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını gösteren bir değeri alır.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Alfa kanalı mevcutsa kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Çözünürlük birimini alır.

**Returns:**
byte - çözünürlük birimi.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir JPEG görüntüsü oluştur.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Kanal başına bit sayısı, Y, Cr, Cb bileşenleri için sırasıyla 8, 8, 8'dir.
createOptions.setBitsPerChannel((byte) 8);

// Sıkıştırmanın ilerleyici tipini ayarlayın.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
createOptions.setQuality(100);

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk doygunluğu bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Görüntüyü gri tonlamalı bir degrade ile doldur
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Bir dosyaya kaydet.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Çözünürlük birimini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | çözünürlük birimi. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Bir BMP görüntüsünü dosyadan yükleyin.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Bazı görüntü işleme işlemleri yapın.

    // İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Kanal başına bit sayısı 8'dir.
    // Bir palet kullanıldığında, renk indeksi renk yerine görüntü verilerinde depolanır.
    saveOptions.setBitsPerChannel((byte) 8);

    // Sıkıştırmanın ilerleyici tipini ayarlayın.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
    saveOptions.setQuality(100);

    // Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Kaynak görüntü renkliyse, gri tonlamaya dönüştürülecektir.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Çıktı boyutunu azaltmak için bir palet kullanın.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

