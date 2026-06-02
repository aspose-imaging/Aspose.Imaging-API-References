---
title: "LoadOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Yükleme seçeneklerini temsil eder."
type: docs
weight: 70
url: /tr/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Yükleme seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Veri kurtarma modunu alır. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Veri kurtarma modunu ayarlar. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | `Image` arka plan `Color` değerini alır. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | `Image` arka plan `Color` değerini ayarlar. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri ayarlar. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Görüntüye özgü yazı tiplerini sağlamak için özel yazı tipi kaynağını ekler. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Eşzamanlı görüntü işleme [concurrent image processing] olup olmadığını gösteren bir değeri alır. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Eşzamanlı görüntü işleme [concurrent image processing] olup olmadığını gösteren bir değeri ayarlar. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | İlerleme olay işleyicisini alır. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | İlerleme olay işleyicisini ayarlar. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Veri kurtarma modunu alır.

**Returns:**
int - Veri kurtarma modu.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Veri kurtarma modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Veri kurtarma modu. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


`Image` arka plan `Color` değerini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Genellikle piksel değeri veri bozulması nedeniyle kurtarılamadığında arka plan rengi ayarlanır.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


`Image` arka plan `Color` değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | Arka plan rengi. |

Genellikle piksel değeri veri bozulması nedeniyle kurtarılamadığında arka plan rengi ayarlanır. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Görüntüye özgü yazı tiplerini sağlamak için özel yazı tipi kaynağını ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | Özel yazı tipi kaynağı sağlayıcı işlevi. |
| argümanlar | java.lang.Object[] | Argümanlar. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Returns:**
int - tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
Aşağıdaki örnek, JPEG görüntüsü yüklenirken bir bellek sınırının nasıl ayarlanacağını gösterir. Bellek sınırı, tüm iç tamponlar için izin verilen maksimum boyuttur (megabayt cinsinden).
``` java
String workDir = "c:\\temp\\";
// Hedef yüklenen görüntü için 50 megabayt bellek sınırı ayarlanıyor
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


Eşzamanlı görüntü işleme [concurrent image processing] olup olmadığını gösteren bir değeri alır.

Değer: `true` eğer [concurrent image processing]; aksi takdirde `false`.

**Returns:**
boolean - [concurrent image processing] olup olmadığını gösteren bir değer.
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Eşzamanlı görüntü işleme [concurrent image processing] olup olmadığını gösteren bir değeri ayarlar.

Değer: `true` eğer [concurrent image processing]; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | eşzamanlı görüntü işleme [concurrent image processing] olup olmadığını gösteren bir değer. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


İlerleme olay işleyicisini alır.

Değer: İlerleme olay işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


İlerleme olay işleyicisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | ilerleme olay işleyicisi. |

