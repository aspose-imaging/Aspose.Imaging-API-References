---
title: "SvgRasterizationOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "SVG rasterleştirme seçenekleri."
type: docs
weight: 46
url: /tr/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

SVG rasterleştirme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | `SvgRasterizationOptions` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getScaleX()](#getScaleX--) | Ölçek x'i alır veya ayarlar. |
| [setScaleX(float value)](#setScaleX-float-) | Ölçek x'i alır veya ayarlar. |
| [getScaleY()](#getScaleY--) | Ölçek y'i alır veya ayarlar. |
| [setScaleY(float value)](#setScaleY-float-) | Ölçek y'i alır veya ayarlar. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Bu örneği `vectorRasterizationOptions`'a kopyalar. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


`SvgRasterizationOptions` sınıfının yeni bir örneğini başlatır.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Ölçek x'i alır veya ayarlar.

**Returns:**
float - Ölçek x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Ölçek x'i alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Ölçek x. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, görüntü yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekir.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Bir görüntü için arka planın varsayılan rengini ayarlayın. Varsayılan değer beyazdır.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Sayfa boyutunu ayarla
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing, çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanır.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Her karakter, ipucu olmadan antialias'li glif bitmap'i kullanılarak çizilir.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Görüntü boyutunu 10 kat küçültün, yani çıktı boyutu orijinal boyutun %10'u olacaktır.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // PNG dosyasına kaydet
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Ölçek y'i alır veya ayarlar.

**Returns:**
float - Ölçek y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Ölçek y'i alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Ölçek y. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, görüntü yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekir.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Bir görüntü için arka planın varsayılan rengini ayarlayın. Varsayılan değer beyazdır.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Sayfa boyutunu ayarla
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing, çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanır.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Her karakter, ipucu olmadan antialias'li glif bitmap'i kullanılarak çizilir.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Görüntü boyutunu 10 kat küçültün, yani çıktı boyutu orijinal boyutun %10'u olacaktır.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // PNG dosyasına kaydet
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Bu örneği `vectorRasterizationOptions`'a kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Vektör rasterleştirme seçenekleri. |

