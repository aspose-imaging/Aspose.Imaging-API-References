---
title: "PngOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle sıkıştırma seviyeleri, piksel başına bit derinlikleri ve alfa bitleri için özelleştirilebilir seçenekler sunarak yüksek kaliteli Portable Network Graphics PNG raster görüntülerini zahmetsizce oluşturun."
type: docs
weight: 38
url: /tr/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

API'mizle yüksek kaliteli Portable Network Graphics (PNG) raster görüntülerini zahmetsizce oluşturun; sıkıştırma seviyeleri, piksel başına bit derinlikleri ve alfa bitleri için özelleştirilebilir seçenekler sunar. XMP meta veri kapsayıcılarını sorunsuz bir şekilde işleyerek kapsamlı görüntü meta verisi yönetimini sağlar ve PNG görüntülerini tam olarak istediğiniz şekilde kolayca özelleştirmenize olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PngOptions()](#PngOptions--) | Yeni bir `PngOptions` sınıfı örneği başlatır. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Yeni bir `PngOptions` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Varsayılan sıkıştırma seviyesi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorType()](#getColorType--) | Renk tipini alır. |
| [setColorType(int value)](#setColorType-int-) | Renk tipini ayarlar. |
| [getProgressive()](#getProgressive--) | Bir [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin ilerlemeli olup olmadığını gösteren bir değer alır. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Bir [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin ilerlemeli olup olmadığını gösteren bir değeri ayarlar. |
| [getFilterType()](#getFilterType--) | png dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır. |
| [setFilterType(int value)](#setFilterType-int-) | png dosyası kaydetme işlemi sırasında kullanılan filtre türünü ayarlar. |
| [getCompressionLevel()](#getCompressionLevel--) | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini alır. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini ayarlar. |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini alır. |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini ayarlar. |
| [getBitDepth()](#getBitDepth--) | 1, 2, 4, 8, 16 aralığındaki bit derinliği değerlerini alır. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | 1, 2, 4, 8, 16 aralığındaki bit derinliği değerlerini ayarlar. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, PNG çok sayfalı bir format olmadığından yalnızca bir sayfa rasterleştirilecektir.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Yeni bir `PngOptions` sınıfı örneği başlatır.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Yeni bir `PngOptions` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | PNG seçenekleri. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Varsayılan sıkıştırma seviyesi.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Renk tipini alır.

Değer: Rengin tipi.

**Returns:**
int - renk tipi.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Renk tipini ayarlar.

Değer: Rengin tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | renk tipi. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// PNG görüntüsünü yükler        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Dizinli renk türünü kullan
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maksimum sıkıştırmayı kullan
    options.setCompressionLevel(9);
    // Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Çıktı dosya boyutu önemli ölçüde azaltılmalıdır
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
// Herhangi bir desteklenen formatta görüntüyü bir dosyadan veya akıştan da yükleyebilirsiniz.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Görüntüyü mavi-şeffaf degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // İlerlemeli yüklemeyi kullanın.
    saveOptions.setProgressive(true);

    // Yatay ve dikey çözünürlüğü inç başına 96 piksel olarak ayarlayın.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Her piksel, alfa bileşeni izleyen bir (kırmızı, yeşil, mavi) üçlüsüdür.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Maksimum sıkıştırma seviyesini ayarlayın.
    saveOptions.setCompressionLevel(9);

    // Bu en iyi sıkıştırmadır, ancak en yavaş yürütme süresine sahiptir.
    // Uyarlamalı filtreleme, kaydetme işleminin her veri satırı için en uygun filtreyi seçeceği anlamına gelir.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Kanal başına bit sayısı.
    saveOptions.setBitDepth((byte) 8);

    // Bir dosyaya kaydet.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Bir [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin ilerlemeli olup olmadığını gösteren bir değer alır.

Değer: `` eğer ilerlemeli; aksi takdirde, ``.

**Returns:**
boolean - bir [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin ilerlemeli olup olmadığını gösteren bir değer.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Bir [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin ilerlemeli olup olmadığını gösteren bir değeri ayarlar.

Değer: `` eğer ilerlemeli; aksi takdirde, ``.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | Bir [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin ilerlemeli olup olmadığını gösteren bir değer. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// PNG görüntüsünü yükler        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Dizinli renk türünü kullan
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maksimum sıkıştırmayı kullan
    options.setCompressionLevel(9);
    // Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Çıktı dosya boyutu önemli ölçüde azaltılmalıdır
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// Renk kanalı başına bit sayısı
createOptions.setBitDepth((byte) 8);

// Her piksel, alfa bileşeni izleyen bir (kırmızı, yeşil, mavi) üçlüsüdür.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// Maksimum sıkıştırma seviyesi.
createOptions.setCompressionLevel(9);

// Filtrelerin kullanımı, sürekli tonlu görüntüleri daha etkili bir şekilde sıkıştırmayı sağlar.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// İlerlemeli yüklemeyi kullanın
createOptions.setProgressive(true);

// Özel parametrelerle bir PNG görüntüsü oluşturun.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Görüntüyü yarı saydam bir degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Bir dosyaya kaydet.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


png dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır.

**Returns:**
int - png dosyası kaydetme işlemi sırasında kullanılan filtre türü.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


png dosyası kaydetme işlemi sırasında kullanılan filtre türünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | png dosyası kaydetme işlemi sırasında kullanılan filtre türü. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Yardımcı sınıf
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// İşte ana örnek.
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Bir filtre türü ayarlayın
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//Çıktı şöyle görünebilir:
//Filtre türü None, çıktı görüntü boyutu 116845 bayttır.
//Filtre türü Up, çıktı görüntü boyutu 86360 bayttır.
//Filtre türü Sub, çıktı görüntü boyutu 94907 bayttır.
//Filtre türü Paeth, çıktı görüntü boyutu 86403 bayttır.
//Filtre türü Avg, çıktı görüntü boyutu 89956 bayttır.
//Filtre türü Adaptive, çıktı görüntü boyutu 97248 bayttır.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini alır.

**Returns:**
int - [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesi.
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesi. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// PNG görüntüsünü yükler        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Dizinli renk türünü kullan
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maksimum sıkıştırmayı kullan
    options.setCompressionLevel(9);
    // Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Çıktı dosya boyutu önemli ölçüde azaltılmalıdır
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
// Herhangi bir desteklenen formatta görüntüyü bir dosyadan veya akıştan da yükleyebilirsiniz.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Görüntüyü mavi-şeffaf degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // İlerlemeli yüklemeyi kullanın.
    saveOptions.setProgressive(true);

    // Yatay ve dikey çözünürlüğü inç başına 96 piksel olarak ayarlayın.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Her piksel, alfa bileşeni izleyen bir (kırmızı, yeşil, mavi) üçlüsüdür.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Maksimum sıkıştırma seviyesini ayarlayın.
    saveOptions.setCompressionLevel(9);

    // Bu en iyi sıkıştırmadır, ancak en yavaş yürütme süresine sahiptir.
    // Uyarlamalı filtreleme, kaydetme işleminin her veri satırı için en uygun filtreyi seçeceği anlamına gelir.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Kanal başına bit sayısı.
    saveOptions.setBitDepth((byte) 8);

    // Bir dosyaya kaydet.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini alır.

**Returns:**
int - [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesi.
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sıkıştırma seviyesi. |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


1, 2, 4, 8, 16 aralığındaki bit derinliği değerlerini alır.

Sonraki sınırlara dikkat edin:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - 1, 2, 4, 8, 16 aralığındaki bit derinliği değerleri.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


1, 2, 4, 8, 16 aralığındaki bit derinliği değerlerini ayarlar.

Sonraki sınırlara dikkat edin:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | 1, 2, 4, 8, 16 aralığındaki bit derinliği değerleri. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
// Herhangi bir desteklenen formatta görüntüyü bir dosyadan veya akıştan da yükleyebilirsiniz.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Görüntüyü mavi-şeffaf degrade ile doldurun.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // İlerlemeli yüklemeyi kullanın.
    saveOptions.setProgressive(true);

    // Yatay ve dikey çözünürlüğü inç başına 96 piksel olarak ayarlayın.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Her piksel, alfa bileşeni izleyen bir (kırmızı, yeşil, mavi) üçlüsüdür.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Maksimum sıkıştırma seviyesini ayarlayın.
    saveOptions.setCompressionLevel(9);

    // Bu en iyi sıkıştırmadır, ancak en yavaş yürütme süresine sahiptir.
    // Uyarlamalı filtreleme, kaydetme işleminin her veri satırı için en uygun filtreyi seçeceği anlamına gelir.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Kanal başına bit sayısı.
    saveOptions.setBitDepth((byte) 8);

    // Bir dosyaya kaydet.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

