---
title: "CmxImagePage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "CMX sayfasının görüntüsü"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

CMX sayfasının görüntüsü
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Yeni bir [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) sınıfı örneği başlatır. |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Yeni bir [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | CMX sayfasını alır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır. |
| [getWidthF()](#getWidthF--) | Nesnenin genişliğini inç cinsinden alır. |
| [getHeightF()](#getHeightF--) | Nesnenin yüksekliğini inç cinsinden alır. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [cacheData()](#cacheData--) | Önbellek kullanılamaz. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Yeni bir [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | CMX sayfası. |
| container | [Image](../../com.aspose.imaging/image) | Kapsayıcı. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Yeni bir [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | CMX sayfası. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


CMX sayfasını alır.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Dosya formatının bir değerini alır

**Returns:**
long - dosya formatı değeri
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - görüntünün piksel başına bit sayısı.
### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır.

Değer: Nesnenin verileri önbelleğe alınmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean - nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Nesnenin genişliğini inç cinsinden alır.

**Returns:**
float - nesnenin genişliği, inç cinsinden.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Nesnenin yüksekliğini inç cinsinden alır.

**Returns:**
float - nesnenin yüksekliği, inç cinsinden.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

Değer: Görüntünün genişliği.

**Returns:**
int - görüntünün genişliği.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

Değer: Görüntünün yüksekliği.

**Returns:**
int - görüntünün yüksekliği.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Varsayılan seçenekleri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | java.lang.Object[] | Argümanlar. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Önbellek kullanılamaz.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Bir CMX dosyasından görüntü yükle.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.cacheData();

    // Tüm sayfaları önbelleğe al, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Görüntü paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

