---
title: "SvgOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizi kullanarak renk türleri ve sıkıştırma seviyeleri için çeşitli seçenekler sunan Scalar Vector Graphics (SVG) görüntü dosyaları oluşturun."
type: docs
weight: 45
url: /tr/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

API'mizi kullanarak renk türleri ve sıkıştırma seviyeleri için çeşitli seçenekler sunan Scalar Vector Graphics (SVG) görüntü dosyaları oluşturun. SVG görüntülerinizi hassas bir şekilde özelleştirerek tasarım ihtiyaçlarınız için optimum kalite ve uyumluluk sağlayın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorType()](#getColorType--) | SVG görüntüsü için renk tipini alır veya ayarlar. |
| [setColorType(int value)](#setColorType-int-) | SVG görüntüsü için renk tipini alır veya ayarlar. |
| [getTextAsShapes()](#getTextAsShapes--) | Metnin şekiller olarak render edilmesi gerekip gerekmediğini gösteren bir değeri alır. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | Metnin şekiller olarak render edilmesi gerekip gerekmediğini gösteren bir değeri ayarlar. |
| [getCallback()](#getCallback--) | Gömülü kaynakların (fontlar, iç içe rasterler) depolama stratejisini [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) için alır. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | Gömülü kaynakların (fontlar, iç içe rasterler) depolama stratejisini [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) için ayarlar. |
| [getCompress()](#getCompress--) | Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini belirten bir değeri alır. |
| [setCompress(boolean value)](#setCompress-boolean-) | Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini gösteren bir değeri ayarlar. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Aslında, SVG çok sayfalı bir format olmadığından yalnızca bir sayfa dönüştürülecek.
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


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgOptions() {#SvgOptions--}
```
public SvgOptions()
```


### getColorType() {#getColorType--}
```
public int getColorType()
```


SVG görüntüsü için renk tipini alır veya ayarlar.

**Returns:**
int - SVG görüntüsünün renginin türü.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


SVG görüntüsü için renk tipini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | SVG görüntüsünün renginin türü. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


Metnin şekiller olarak render edilmesi gerekip gerekmediğini gösteren bir değeri alır.

Değer: Dönüştürmede tüm metin SVG şekillerine dönüştürülmüşse `true`; aksi takdirde `false`.

**Returns:**
boolean - metnin şekiller olarak render edilmesi gerekip gerekmediğini gösteren bir değer.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


Metnin şekiller olarak render edilmesi gerekip gerekmediğini gösteren bir değeri ayarlar.

Değer: Dönüştürmede tüm metin SVG şekillerine dönüştürülmüşse `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | metnin şekiller olarak render edilmesi gerekip gerekmediğini gösteren bir değer. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, EMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Yatay kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderX(50);

    // Dikey kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getCallback() {#getCallback--}
```
public ISvgResourceKeeperCallback getCallback()
```


Gömülü kaynakların (fontlar, iç içe rasterler) depolama stratejisini [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) için alır.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


Gömülü kaynakların (fontlar, iç içe rasterler) depolama stratejisini [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) için ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) gibi gömülü kaynakların (fontlar, iç içe rasterler) depolama stratejisi. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini belirten bir değeri alır.

**Returns:**
boolean - çıktının sıkıştırılması gerekip gerekmediğini belirten bir değer.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | çıktının sıkıştırılması gerekip gerekmediğini belirten bir değer. |


**Example: The following example shows how to convert a svg images to svgz format**

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

