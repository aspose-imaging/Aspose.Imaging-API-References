---
title: "WebPOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizi kullanarak modern WebP raster web görüntüleri oluşturun; kayıpsız ve kayıplı sıkıştırma, alfa kanalları ve animasyon döngüleri için güçlü destek sunar."
type: docs
weight: 53
url: /tr/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

API'mizi kullanarak modern WebP raster web görüntüleri oluşturun; kayıpsız ve kayıplı sıkıştırma, alfa kanalları ve animasyon döngüleri için güçlü destek sağlar. Web içeriğinizi dinamik görsellerle zenginleştirin ve dosya boyutlarını optimize ederek daha hızlı yükleme ve daha iyi kullanıcı deneyimi elde edin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLossless()](#getLossless--) | Bu `WebPOptions`'ın kayıpsız olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setLossless(boolean value)](#setLossless-boolean-) | Bu `WebPOptions`'ın kayıpsız olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getQuality()](#getQuality--) | Kaliteyi alır veya ayarlar. |
| [setQuality(float value)](#setQuality-float-) | Kaliteyi alır veya ayarlar. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Animasyon döngü sayısını alır veya ayarlar. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Animasyon döngü sayısını alır veya ayarlar. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Animasyon arka planının rengini alır veya ayarlar. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Animasyon arka planının rengini alır veya ayarlar. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Bu sayfalar çıktı WEBP'te animasyonlu kareler olarak sunulacak.
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

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Bu `WebPOptions`'ın kayıpsız olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - kayıpsız ise `true`; aksi takdirde `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Bu `WebPOptions`'ın kayıpsız olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` kayıpsız ise; aksi takdirde `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Kaliteyi alır veya ayarlar.

**Returns:**
float - Kalite.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Kaliteyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kalite. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Animasyon döngü sayısını alır veya ayarlar.

**Returns:**
int - Animasyon döngü sayısı, 0 - sonsuz.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Animasyon döngü sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Animasyon döngü sayısı, 0 - sonsuz. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Animasyon arka planının rengini alır veya ayarlar.

**Returns:**
long - Animasyon arka planının rengi.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Animasyon arka planının rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Animasyon arka planının rengi. |

