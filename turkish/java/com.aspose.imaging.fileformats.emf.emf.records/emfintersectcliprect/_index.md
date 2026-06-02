---
title: "EmfIntersectClipRect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_INTERSECTCLIPRECT kaydı, mevcut kırpma bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi tanımlar."
type: docs
weight: 66
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

EMR\_INTERSECTCLIPRECT kaydı, mevcut kırpma bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi tanımlar. Not: Bu bölümde açıklanmayan alanlar bölüm 2.3.2'de belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfIntersectClipRect` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getClip()](#getClip--) | Mantıksal birimlerde dikdörtgeni belirten bir WMF RectL nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Mantıksal birimlerde dikdörtgeni belirten bir WMF RectL nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


`EmfIntersectClipRect` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Mantıksal birimlerde dikdörtgeni belirten bir WMF RectL nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19).

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Mantıksal birimlerde dikdörtgeni belirten bir WMF RectL nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

