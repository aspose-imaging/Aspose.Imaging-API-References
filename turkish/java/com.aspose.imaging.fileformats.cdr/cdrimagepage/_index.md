---
title: "CdrImagePage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Cdr görüntü sayfası"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

Cdr görüntü sayfası
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParentImage()](#getParentImage--) | Üst görüntüyü alır. |
| [getPageNumber()](#getPageNumber--) | Sayfa numarasını alır. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |
| [getCdrDocument()](#getCdrDocument--) | CDR belgesini alır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Üst görüntüyü alır.

Değer: Üst görüntü.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Sayfa numarasını alır.

Değer: Sayfa numarası.

**Returns:**
int - sayfa numarası.
### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - görüntünün piksel başına bit sayısı.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Dosya formatının bir değerini alır

**Returns:**
long - dosya formatı değeri
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


CDR belgesini alır.

Değer: CDR belgesi.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
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
public synchronized void cacheData()
```


Verileri önbelleğe alır ve temel `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` üzerinden ek veri yüklemesinin yapılmayacağını garanti eder.

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

