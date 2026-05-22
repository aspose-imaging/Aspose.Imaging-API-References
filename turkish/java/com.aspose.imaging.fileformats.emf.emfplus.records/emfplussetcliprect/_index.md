---
title: "EmfPlusSetClipRect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetClipRect kaydı, mevcut kırpma bölgesi ile bir dikdörtgeni birleştirir."
type: docs
weight: 56
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

EmfPlusSetClipRect kaydı, mevcut kırpma bölgesi ile bir dikdörtgeni birleştirir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusSetClipRect` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCm()](#getCm--) | Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. |
| [setCm(byte value)](#setCm-byte-) | Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. |
| [getClipRect()](#getClipRect--) | CombineMode işlemi içinde kullanılacak dikdörtgeni tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | CombineMode işlemi içinde kullanılacak dikdörtgeni tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Yeni bir `EmfPlusSetClipRect` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getCm() {#getCm--}
```
public byte getCm()
```


Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. Değerlerin anlamları için CombineMode numaralandırmasına (bölüm 2.1.1.4) bakın.

Değer: cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. Değerlerin anlamları için CombineMode numaralandırmasına (bölüm 2.1.1.4) bakın.

Değer: cm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


CombineMode işlemi içinde kullanılacak dikdörtgeni tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


CombineMode işlemi içinde kullanılacak dikdörtgeni tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

