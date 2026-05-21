---
title: "Jpeg2000Options"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle gelişmiş dalgacık teknolojisini kullanarak kayıpsız içerik kodlamak için JPEG2000 JP2 görüntü dosyaları oluşturun."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

API'mizle JPEG2000 (JP2) görüntü dosyaları oluşturun, kayıpsız içerik kodlamak için gelişmiş dalgacık teknolojisini kullanın. Geri dönüşümsüz ve kayıpsız sıkıştırma dahil çeşitli kodek desteği, ayrıca XMP meta veri kapsayıcıları sayesinde çok yönlülük ve ihtiyaçlarınıza göre özelleştirilmiş yüksek kaliteli görüntü oluşturmanın avantajını elde edin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | `Jpeg2000Options` sınıfının yeni bir örneğini başlatır. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | `Jpeg2000Options` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getComments()](#getComments--) | Jpeg yorum işaretçilerini alır veya ayarlar. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Jpeg yorum işaretçilerini alır veya ayarlar. |
| [getCodec()](#getCodec--) | JPEG2000 kodeğini alır veya ayarlar. |
| [setCodec(int value)](#setCodec-int-) | JPEG2000 kodeğini alır veya ayarlar. |
| [getCompressionRatios()](#getCompressionRatios--) | Sıkıştırma oranı dizisini alır veya ayarlar. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Sıkıştırma oranı dizisini alır veya ayarlar. |
| [getIrreversible()](#getIrreversible--) | Geri dönüşümsüz DWT 9-7 (true) kullanılıp kullanılmadığını veya kayıpsız DWT 5-3 sıkıştırmanın (varsayılan) kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Geri dönüşümsüz DWT 9-7 (true) kullanılıp kullanılmadığını veya kayıpsız DWT 5-3 sıkıştırmanın (varsayılan) kullanılıp kullanılmadığını gösteren bir değeri ayarlar. |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, JPEG 2000 çok sayfalı bir format olmadığından yalnızca bir sayfa rasterleştirilecektir.
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

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


`Jpeg2000Options` sınıfının yeni bir örneğini başlatır.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


`Jpeg2000Options` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Ayarların kopyalanacağı Jpeg2000 dosya formatı seçenekleri. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Jpeg yorum işaretçilerini alır veya ayarlar.

**Returns:**
java.lang.String[] - Jpeg yorum işaretçileri.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Jpeg yorum işaretçilerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] | Jpeg yorum işaretçileri. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


JPEG2000 kodeğini alır veya ayarlar.

**Returns:**
int - JPEG2000 kodeği
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


JPEG2000 kodeğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | JPEG2000 kodeği |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Tüm görüntüyü kırmızıyla doldurun.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Geri dönüşümsüz Ayrık Dalga Dönüşümü 9-7'yi kullanın
    saveOptions.setIrreversible(true);

    // JP2, JPEG 2000 kod akışları için "container" formatıdır.
    // J2K, bir kapsayıcı olmadan ham sıkıştırılmış veridir.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Bir dosyaya kaydet
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Sıkıştırma oranı dizisini alır veya ayarlar. Ardışık katmanlar için farklı sıkıştırma oranları. Her kalite seviyesi için belirtilen oran istenen sıkıştırma faktörüdür. Azalan oranlar gereklidir.

**Returns:**
int[] - Sıkıştırma oranları.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Sıkıştırma oranı dizisini alır veya ayarlar. Ardışık katmanlar için farklı sıkıştırma oranları. Her kalite seviyesi için belirtilen oran istenen sıkıştırma faktörüdür. Azalan oranlar gereklidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Sıkıştırma oranları. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Geri dönüşümsüz DWT 9-7 (true) kullanılıp kullanılmadığını veya kayıpsız DWT 5-3 sıkıştırmanın (varsayılan) kullanılıp kullanılmadığını gösteren bir değeri alır.

**Returns:**
boolean - geri dönüşümsüz DWT 9-7 (true) kullanıp kullanmadığınızı veya kayıpsız DWT 5-3 sıkıştırmayı kullanıp kullanmadığınızı gösteren bir değer
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Geri dönüşümsüz DWT 9-7 (true) kullanılıp kullanılmadığını veya kayıpsız DWT 5-3 sıkıştırmanın (varsayılan) kullanılıp kullanılmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | geri dönüşümsüz DWT 9-7 (true) kullanıp kullanmadığınızı veya kayıpsız DWT 5-3 sıkıştırmayı kullanıp kullanmadığınızı gösteren bir değer |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir PNG görüntüsü oluşturun.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Tüm görüntüyü kırmızıyla doldurun.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Geri dönüşümsüz Ayrık Dalga Dönüşümü 9-7'yi kullanın
    saveOptions.setIrreversible(true);

    // JP2, JPEG 2000 kod akışları için "container" formatıdır.
    // J2K, bir kapsayıcı olmadan ham sıkıştırılmış veridir.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Bir dosyaya kaydet
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

