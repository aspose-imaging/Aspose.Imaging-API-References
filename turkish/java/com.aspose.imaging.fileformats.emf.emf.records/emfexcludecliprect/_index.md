---
title: "EmfExcludeClipRect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EXCLUDECLIPRECT kaydı, belirtilen dikdörtgen çıkarıldıktan sonra mevcut kırpma bölgesinden oluşan yeni bir kırpma bölgesi tanımlar."
type: docs
weight: 50
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

EMR\_EXCLUDECLIPRECT kaydı, belirtilen dikdörtgen çıkarıldıktan sonra mevcut kırpma bölgesinden oluşan yeni bir kırpma bölgesi tanımlar. Not: Bu bölümde açıklanmayan alanlar bölüm 2.3.2'de belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfExcludeClipRect` sınıfı örneği başlatır. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Yeni bir `EmfExcludeClipRect` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getClip()](#getClip--) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, mantıksal birimlerde kırpma dikdörtgenini tanımlayan bir WMF RectL nesnesi alır. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, mantıksal birimlerde kırpma dikdörtgenini tanımlayan bir WMF RectL nesnesi ayarlar. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Yeni bir `EmfExcludeClipRect` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Yeni bir `EmfExcludeClipRect` sınıfı örneği başlatır.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, mantıksal birimlerde kırpma dikdörtgenini tanımlayan bir WMF RectL nesnesi alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, mantıksal birimlerde kırpma dikdörtgenini tanımlayan bir WMF RectL nesnesi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

