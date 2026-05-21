---
title: "PsdOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle Photoshop Belgesi PSD görüntüleri oluşturun, farklı format sürümleri, sıkıştırma yöntemleri, renk modları ve renk kanalı başına bit sayısı gibi çeşitli seçenekler sunar."
type: docs
weight: 40
url: /tr/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

API'mizle Photoshop Belgesi (PSD) görüntüleri oluşturun, farklı format sürümleri, sıkıştırma yöntemleri, renk modları ve renk kanalı başına bit sayısı gibi çeşitli seçenekler sunar. XMP meta veri kapsayıcılarını sorunsuz bir şekilde yönetin, görüntü katmanları, katman maskeleri ve dosya bilgileri gibi PSD formatı özelliklerinin gücüyle kapsamlı görüntü işleme sağlayarak tasarımlarınızda özelleştirme ve yaratıcılık için destek verir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Yeni bir `PsdOptions` sınıfı örneği başlatır. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Yeni bir `PsdOptions` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | XMP veri kapsayıcısını al veya ayarla |
| [getVersion()](#getVersion--) | PSD dosya sürümünü alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | PSD dosya sürümünü alır veya ayarlar. |
| [getCompressionMethod()](#getCompressionMethod--) | PSD sıkıştırma yöntemini alır veya ayarlar. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | PSD sıkıştırma yöntemini alır veya ayarlar. |
| [getPsdVersion()](#getPsdVersion--) | Dosya formatı sürümünü alır. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Dosya formatı sürümünü ayarlar. |
| [getColorMode()](#getColorMode--) | PSD renk modunu alır veya ayarlar. |
| [setColorMode(short value)](#setColorMode-short-) | PSD renk modunu alır veya ayarlar. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Renk kanalı başına bit sayısını alır veya ayarlar. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Renk kanalı başına bit sayısını alır veya ayarlar. |
| [getChannelsCount()](#getChannelsCount--) | Renk kanalı sayısını alır. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Renk kanalı sayısını ayarlar. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Küresel metin motoru kaynağını kaldırma - İşleme sonrasında Adobe Photoshop'ta açılamayan bazı metin katmanlı PSD dosyaları için (çoğunlukla eksik fontlarla ilgili metin katmanları) kullanılan bir değeri alır. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Küresel metin motoru kaynağını kaldırma - İşleme sonrasında Adobe Photoshop'ta açılamayan bazı metin katmanlı PSD dosyaları için (çoğunlukla eksik fontlarla ilgili metin katmanları) kullanılan bir değeri ayarlar. |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Görüntü önizleme verilerini yenile [refresh image preview data] - başka PSD görüntüleyicilerle uyumluluğu en üst düzeye çıkarmak için kullanılan bir seçeneği gösteren bir değeri alır. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Görüntü önizleme verilerini yenile [refresh image preview data] - başka PSD görüntüleyicilerle uyumluluğu en üst düzeye çıkarmak için kullanılan bir seçeneği gösteren bir değeri ayarlar. |
| [getVectorizationOptions()](#getVectorizationOptions--) | PSD vektörleştirme seçeneklerini alır. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | PSD vektörleştirme seçeneklerini ayarlar. |

## Example: This example demonstrates the use of Aspose.
Bu örnek, Aspose.Imaging for Java API'sinin Görüntüleri PSD formatına dönüştürmek için kullanımını göstermektedir. Bu hedefe ulaşmak için bu örnek mevcut bir görüntüyü yükler ve ardından PSD formatında kaydeder.
``` java

// Image sınıfının bir örneğini oluşturun ve dosya yolu aracılığıyla mevcut bir dosyayla başlatın.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // PsdOptions sınıfının bir örneğini oluşturun.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // CompressionMethod'u RLE olarak ayarlayın.
    // Not: Diğer desteklenen CompressionMethod, CompressionMethod.RAW [Sıkıştırma Yok]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // ColorMode'u GrayScale olarak ayarlayın.
    // Not: Diğer desteklenen ColorModes, ColorModes.Bitmap ve ColorModes.RGB'dir.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Görüntüyü, sağlanan PsdOptions ayarlarıyla diske kaydedin.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktarın. Bu sayfalar, çıktı PSD'sinde katmanlar olarak sunulacaktır.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Yeni bir `PsdOptions` sınıfı örneği başlatır.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Yeni bir `PsdOptions` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Seçenekler. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP veri kapsayıcısını al veya ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


PSD dosya sürümünü alır veya ayarlar.

Değer: PSD dosya sürümü.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


PSD dosya sürümünü alır veya ayarlar.

Değer: PSD dosya sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Doğrusal mavi-şeffaf bir degrade tanımlayın.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // PNG görüntüsünü doğrusal mavi-şeffaf degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Aşağıdaki seçenekler, PNG görüntüsünü PSD formatında kaydetmek için kullanılacaktır.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Kanal başına bit sayısı
    saveOptions.setChannelBitsCount((byte) 8);

    // Kanal sayısı. Her renk bileşeni R,G,B,A için bir kanal.
    saveOptions.setChannelsCount((short) 4);

    // Renk modu
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Sıkıştırma yok
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Varsayılan sürüm 6'dır
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE sıkıştırması, çıktı görüntüsünün boyutunu azaltmaya olanak tanır
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Çıktı şöyle görünebilir:
    // RAW sıkıştırmalı PSD görüntüsünün boyutu: 40090
    // RLE sıkıştırmalı PSD görüntüsünün boyutu: 16185
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


PSD sıkıştırma yöntemini alır veya ayarlar.

Değer: Sıkıştırma yöntemi.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


PSD sıkıştırma yöntemini alır veya ayarlar.

Değer: Sıkıştırma yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |


**Example: This example demonstrates the use of Aspose.**
Bu örnek, Aspose.Imaging for Java API'sinin Görüntüleri PSD formatına dönüştürmek için kullanımını göstermektedir. Bu hedefe ulaşmak için bu örnek mevcut bir görüntüyü yükler ve ardından PSD formatında kaydeder.
``` java

// Image sınıfının bir örneğini oluşturun ve dosya yolu aracılığıyla mevcut bir dosyayla başlatın.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // PsdOptions sınıfının bir örneğini oluşturun.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // CompressionMethod'u RLE olarak ayarlayın.
    // Not: Diğer desteklenen CompressionMethod, CompressionMethod.RAW [Sıkıştırma Yok]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // ColorMode'u GrayScale olarak ayarlayın.
    // Not: Diğer desteklenen ColorModes, ColorModes.Bitmap ve ColorModes.RGB'dir.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Görüntüyü, sağlanan PsdOptions ayarlarıyla diske kaydedin.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Dosya formatı sürümünü alır. PSD veya PSB olabilir.

Değer: Dosya formatı sürümü.

**Returns:**
byte - dosya formatı sürümü.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Dosya formatı sürümünü ayarlar. PSD veya PSB olabilir.

Değer: Dosya formatı sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | dosya formatı sürümü. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


PSD renk modunu alır veya ayarlar.

Değer: Renk modu.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


PSD renk modunu alır veya ayarlar.

Değer: Renk modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |


**Example: This example demonstrates the use of Aspose.**
Bu örnek, Aspose.Imaging for Java API'sinin Görüntüleri PSD formatına dönüştürmek için kullanımını göstermektedir. Bu hedefe ulaşmak için bu örnek mevcut bir görüntüyü yükler ve ardından PSD formatında kaydeder.
``` java

// Image sınıfının bir örneğini oluşturun ve dosya yolu aracılığıyla mevcut bir dosyayla başlatın.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // PsdOptions sınıfının bir örneğini oluşturun.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // CompressionMethod'u RLE olarak ayarlayın.
    // Not: Diğer desteklenen CompressionMethod, CompressionMethod.RAW [Sıkıştırma Yok]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // ColorMode'u GrayScale olarak ayarlayın.
    // Not: Diğer desteklenen ColorModes, ColorModes.Bitmap ve ColorModes.RGB'dir.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Görüntüyü, sağlanan PsdOptions ayarlarıyla diske kaydedin.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Renk kanalı başına bit sayısını alır veya ayarlar.

Değer: Renk kanal başına bit sayısı.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Renk kanalı başına bit sayısını alır veya ayarlar.

Değer: Renk kanal başına bit sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Doğrusal mavi-şeffaf bir degrade tanımlayın.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // PNG görüntüsünü doğrusal mavi-şeffaf degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Aşağıdaki seçenekler, PNG görüntüsünü PSD formatında kaydetmek için kullanılacaktır.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Kanal başına bit sayısı
    saveOptions.setChannelBitsCount((byte) 8);

    // Kanal sayısı. Her renk bileşeni R,G,B,A için bir kanal.
    saveOptions.setChannelsCount((short) 4);

    // Renk modu
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Sıkıştırma yok
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Varsayılan sürüm 6'dır
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE sıkıştırması, çıktı görüntüsünün boyutunu azaltmaya olanak tanır
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Çıktı şöyle görünebilir:
    // RAW sıkıştırmalı PSD görüntüsünün boyutu: 40090
    // RLE sıkıştırmalı PSD görüntüsünün boyutu: 16185
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Renk kanalı sayısını alır.

**Returns:**
short - renk kanalı sayısı.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Renk kanalı sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | Renk kanalı sayısı. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Doğrusal mavi-şeffaf bir degrade tanımlayın.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // PNG görüntüsünü doğrusal mavi-şeffaf degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Aşağıdaki seçenekler, PNG görüntüsünü PSD formatında kaydetmek için kullanılacaktır.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Kanal başına bit sayısı
    saveOptions.setChannelBitsCount((byte) 8);

    // Kanal sayısı. Her renk bileşeni R,G,B,A için bir kanal.
    saveOptions.setChannelsCount((short) 4);

    // Renk modu
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Sıkıştırma yok
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Varsayılan sürüm 6'dır
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE sıkıştırması, çıktı görüntüsünün boyutunu azaltmaya olanak tanır
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Çıktı şöyle görünebilir:
    // RAW sıkıştırmalı PSD görüntüsünün boyutu: 40090
    // RLE sıkıştırmalı PSD görüntüsünün boyutu: 16185
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Bir değerin alınıp alınmadığını gösterir - Küresel metin motoru kaynağını kaldır - İşleme sonrasında bazı metin katmanlı PSD dosyalarında, yalnızca Adobe Photoshop'ta açılamadığında (çoğunlukla eksik yazı tipli metin katmanlarıyla ilgili) kullanılır. Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu işlemi yapmalıdır: Menü "Text" -> "Process absent fonts". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın.

**Returns:**
boolean - [remove global text engine resource] ise `true`; aksi takdirde `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Bir değerin ayarlanmasını gösterir - Küresel metin motoru kaynağını kaldır - İşleme sonrasında bazı metin katmanlı PSD dosyalarında, yalnızca Adobe Photoshop'ta açılamadığında (çoğunlukla eksik yazı tipli metin katmanlarıyla ilgili) kullanılır. Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu işlemi yapmalıdır: Menü "Text" -> "Process absent fonts". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` eğer [remove global text engine resource]; aksi takdirde `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Görüntü önizleme verilerini yenile [refresh image preview data] - başka PSD görüntüleyicilerle uyumluluğu en üst düzeye çıkarmak için kullanılan bir seçeneği gösteren bir değeri alır.

**Returns:**
boolean - `true` eğer [refresh image preview data]; aksi takdirde `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Görüntü önizleme verilerini yenile [refresh image preview data] - başka PSD görüntüleyicilerle uyumluluğu en üst düzeye çıkarmak için kullanılan bir seçeneği gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` eğer [refresh image preview data]; aksi takdirde `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


PSD vektörleştirme seçeneklerini alır.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


PSD vektörleştirme seçeneklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | PSD vektörleştirme seçenekleri. |

