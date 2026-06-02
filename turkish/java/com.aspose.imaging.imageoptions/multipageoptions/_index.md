---
title: "MultiPageOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Birden çok sayfa destekleyen formatlar için temel sınıf"
type: docs
weight: 30
url: /tr/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Birden çok sayfa destekleyen formatlar için temel sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | `MultiPageOptions` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPages()](#getPages--) | Sayfaları alır veya ayarlar. |
| [setPages(int[] value)](#setPages-int---) | Sayfaları alır veya ayarlar. |
| [getPageTitles()](#getPageTitles--) | Sayfa başlıklarını alır veya ayarlar. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Sayfa başlıklarını alır veya ayarlar. |
| [getTimeInterval()](#getTimeInterval--) | Zaman aralığını alır. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Zaman aralığını ayarlar. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Sayfa rasterleştirme seçeneklerini alır. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Sayfa rasterleştirme seçeneklerini ayarlar. |
| [getExportArea()](#getExportArea--) | Dışa aktarma alanını alır veya ayarlar. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Dışa aktarma alanını alır veya ayarlar. |
| [getMode()](#getMode--) | Modu alır veya ayarlar. |
| [setMode(int value)](#setMode-int-) | Modu alır veya ayarlar. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için). |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için). |
| [getMergeLayers()](#getMergeLayers--) | Katmanları birleştir [merge layers] olup olmadığını gösteren bir değeri alır. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Katmanları birleştir [merge layers] olup olmadığını gösteren bir değeri ayarlar. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Sayfaları aralıklar dizisinden başlatır |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfalar | int[] | Sayfalar. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfalar | int[] | Sayfalar dizisi. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sayfa başlıkları. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sayfa başlıkları. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Bu `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Bu `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Bu `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Bu `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | int | Sayfa indeksi. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


`MultiPageOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | int | Sayfa indeksi. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Dışa aktarma alanı. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Sayfaları alır veya ayarlar.

Değer: Sayfalar.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Sayfaları alır veya ayarlar.

Değer: Sayfalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Not: Görüntü renkliyse, aşağıdaki seçeneğe göre otomatik olarak S/B formatına dönüştürülecektir:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Varsayılan olarak, tüm sayfalar çıktı TIFF'ine kaydedilir, ancak istenen sayfa kümesi açıkça belirtilebilir.
        // Yalnızca birinci ve ikinci sayfa dışa aktarılacaktır.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Sayfa başlıklarını ayarla.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // TIFF olarak kaydet
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Sayfa başlıklarını alır veya ayarlar.

Değer: Sayfa başlıkları.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Sayfa başlıklarını alır veya ayarlar.

Değer: Sayfa başlıkları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Not: Görüntü renkliyse, aşağıdaki seçeneğe göre otomatik olarak S/B formatına dönüştürülecektir:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Varsayılan olarak, tüm sayfalar çıktı TIFF'ine kaydedilir, ancak istenen sayfa kümesi açıkça belirtilebilir.
        // Yalnızca birinci ve ikinci sayfa dışa aktarılacaktır.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Sayfa başlıklarını ayarla.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // TIFF olarak kaydet
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


Zaman aralığını alır.

Değer: Zaman aralığı.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Zaman aralığını ayarlar.

Değer: Zaman aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | zaman aralığı. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Sayfa rasterleştirme seçeneklerini alır.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - sayfa rasterleştirme seçenekleri.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Sayfa rasterleştirme seçeneklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | sayfa rasterleştirme seçenekleri. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Dışa aktarma alanını alır veya ayarlar.

Değer: Dışa aktarma alanı.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Dışa aktarma alanını alır veya ayarlar.

Değer: Dışa aktarma alanı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Modu alır veya ayarlar.

Değer: Mod.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Modu alır veya ayarlar.

Değer: Mod.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için).

Değer: Çıktı katman adları.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için).

Değer: Çıktı katman adları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Katmanları birleştir [merge layers] olup olmadığını gösteren bir değeri alır.

Değer: `true` ise [merge layers]; aksi takdirde, `false`.

**Returns:**
boolean - [merge layers] belirten bir değer.
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Katmanları birleştir [merge layers] olup olmadığını gösteren bir değeri ayarlar.

Değer: `true` ise [merge layers]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [merge layers] belirten bir değer. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Sayfaları aralıklar dizisinden başlatır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Aralıklar. |

