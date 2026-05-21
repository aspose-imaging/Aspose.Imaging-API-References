---
title: "ApngOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Animated PNG Animated Portable Network Graphics görüntü dosyası formatı oluşturma API'si, etkileyici animasyonlu görseller üretmek isteyen geliştiriciler için dinamik bir araçtır."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

Animated PNG (Animated Portable Network Graphics) görüntü dosyası formatı oluşturma API'si, etkileyici animasyonlu görseller üretmek isteyen geliştiriciler için dinamik bir araçtır. Çerçeve süresi ve döngü sayısı gibi özelleştirilebilir seçeneklerle, bu API belirli ihtiyaçlara göre animasyonlu içeriği ince ayar yapmanıza olanak tanır. Çekici web grafikleri ya da etkileşimli görseller oluştururken, bu API'yi APNG görüntülerini sorunsuz bir şekilde entegre etmek ve animasyon parametreleri üzerinde hassas kontrol sağlamak için kullanabilirsiniz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Yeni bir [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) sınıfı örneği başlatır. |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | `ApngOptions` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Animasyonun kaç kez döngü yapacağını alır. |
| [setNumPlays(int value)](#setNumPlays-int-) | Animasyonun kaç kez döngü yapacağını ayarlar. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Varsayılan çerçeve süresini alır. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Varsayılan çerçeve süresini ayarlar. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // APNG animasyonunu varsayılan olarak sınırsız animasyon döngüsüyle dışa aktar
    image.save("Animation1.webp.png", new ApngOptions());
    // Animasyon döngülerini ayarlama
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Varsayılan kare süresini ayarlama
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Yeni bir [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) sınıfı örneği başlatır.

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


`ApngOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | PNG seçenekleri. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Animasyonun kaç kez döngüye gireceğini alır. 0, sınırsız döngüyü gösterir.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // APNG animasyonunu varsayılan olarak sınırsız animasyon döngüsüyle dışa aktar
    image.save("Animation1.webp.png", new ApngOptions());
    // Animasyon döngülerini ayarlama
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Animasyonun kaç kez döngüye gireceğini ayarlar. 0, sınırsız döngüyü gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // APNG animasyonunu varsayılan olarak sınırsız animasyon döngüsüyle dışa aktar
    image.save("Animation1.webp.png", new ApngOptions());
    // Animasyon döngülerini ayarlama
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Varsayılan çerçeve süresini alır.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Varsayılan çerçeve süresini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

