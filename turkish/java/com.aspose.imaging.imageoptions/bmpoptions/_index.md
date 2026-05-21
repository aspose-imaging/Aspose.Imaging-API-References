---
title: "BmpOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BMP ve DIB raster görüntü formatı oluşturma seçenekleri için API, geliştiricilere özel Bitmap BMP ve Device Independent Bitmap DIB görüntüleri oluşturmak için çok yönlü bir araç seti sunar."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

BMP ve DIB raster görüntü formatı oluşturma seçenekleri için API, geliştiricilere özel Bitmap (BMP) ve Device Independent Bitmap (DIB) görüntüleri oluşturmak için çok yönlü bir araç seti sunar. Bu API ile piksel başına bit sayısı, sıkıştırma seviyesi ve sıkıştırma türü gibi görüntü özelliklerini kesin olarak tanımlayabilir, çıktıyı belirli gereksinimlere göre özelleştirebilirsiniz. Özellik açısından zengin bu API, geliştiricilerin yüksek kaliteli, özelleştirilmiş raster görüntüleri kolaylık ve esneklikle çeşitli uygulamalar için oluşturmasını sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | `BmpOptions` sınıfının yeni bir örneğini başlatır. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | `BmpOptions` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır veya ayarlar. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Görüntünün piksel başına bit sayısını alır veya ayarlar. |
| [getCompression()](#getCompression--) | Sıkıştırma türünü alır. |
| [setCompression(long value)](#setCompression-long-) | Sıkıştırma türünü ayarlar. |

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


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, BMP çok sayfalı bir format olmadığından yalnızca bir sayfa rasterleştirilecektir.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


`BmpOptions` sınıfının yeni bir örneğini başlatır.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


`BmpOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | BMP seçenekleri. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır veya ayarlar.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Görüntünün piksel başına bit sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Görüntünün piksel başına bit sayısı. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // BmpOptions oluştur
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Çıktı görüntüsünün boyutunu azaltmak için piksel başına 8 bit kullan.
    saveOptions.setBitsPerPixel(8);

    // Görüntü piksellerinin en yüksek sayısını kapsayan en yakın 8-bit renk paletini ayarlayın, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Sıkıştırma olmadan kaydet.
    // Çıktı görüntüsünün boyutunu azaltmak için RLE-8 sıkıştırmasını da kullanabilirsiniz.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Yatay ve dikey çözünürlüğü 96 dpi olarak ayarla.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Sıkıştırma türünü alır. Varsayılan sıkıştırma türü, şeffaflıkla bir [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) kaydetmeye izin veren [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields) dir.

Değer: Sıkıştırma türü.

**Returns:**
long - sıkıştırma türü.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Sıkıştırma türünü ayarlar. Varsayılan sıkıştırma türü [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields) olup, bir [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) dosyasını şeffaflıkla kaydetmeye izin verir.

Değer: Sıkıştırma türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | sıkıştırma türü. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // BmpOptions oluştur
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Çıktı görüntüsünün boyutunu azaltmak için piksel başına 8 bit kullan.
    saveOptions.setBitsPerPixel(8);

    // Görüntü piksellerinin en yüksek sayısını kapsayan en yakın 8-bit renk paletini ayarlayın, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Sıkıştırma olmadan kaydet.
    // Çıktı görüntüsünün boyutunu azaltmak için RLE-8 sıkıştırmasını da kullanabilirsiniz.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Yatay ve dikey çözünürlüğü 96 dpi olarak ayarla.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Bir dosyadan PNG görüntüsü yükle.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir.
    // Bu modu açıkça belirtmek istiyorsanız, BmpOptions'ın Compression özelliği BitmapCompression.Bitfields olarak ayarlanmalıdır.
    // BitmapCompression.Bitfields sıkıştırma yöntemi BmpOptions içinde varsayılan sıkıştırma yöntemidir.
    // Bu nedenle, şeffaflıkla bir Bmp görüntüsü dışa aktarmanın aynı sonucu aşağıdaki yöntemlerden biriyle elde edilebilir.
    // Örtük bir varsayılan seçenekle:
    pngImage.save(outputPathPng);
    // Açık bir varsayılan seçenekle:
    pngImage.save(outputPathBmp, new BmpOptions());
    // BitmapCompression.Bitfields sıkıştırma yöntemini belirterek:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Bir dosyadan PNG görüntüsü yükle.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir, bu BitmapCompression.Bitfields sıkıştırma yöntemi kullanılarak sağlanır.
    // RGB sıkıştırma yöntemiyle bir BMP görüntüsü kaydetmek için, Compression özelliği BitmapCompression.Rgb olarak ayarlanmış BmpOptions belirtilmelidir.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

