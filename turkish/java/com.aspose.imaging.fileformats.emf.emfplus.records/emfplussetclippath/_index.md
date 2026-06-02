---
title: "EmfPlusSetClipPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetClipPath kaydı, mevcut kırpma bölgesi ile bir grafik yolunu birleştirir."
type: docs
weight: 55
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

EmfPlusSetClipPath kaydı, mevcut kırpma bölgesini bir grafik yolu ile birleştirir. Yeni mevcut kırpma bölgesi, CombineMode işleminin sonucu olarak ayarlanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusSetClipPath` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCm()](#getCm--) | Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. |
| [setCm(byte value)](#setCm-byte-) | Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. |
| [getObjectId()](#getObjectId--) | EMF+ Nesne Tablosunda bir EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizinini alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | EMF+ Nesne Tablosunda bir EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizinini alır veya ayarlar. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


`EmfPlusSetClipPath` sınıfının yeni bir örneğini başlatır.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


EMF+ Nesne Tablosunda bir EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizinini alır veya ayarlar. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


EMF+ Nesne Tablosunda bir EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizinini alır veya ayarlar. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

