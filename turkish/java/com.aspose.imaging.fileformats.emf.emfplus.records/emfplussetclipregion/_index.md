---
title: "EmfPlusSetClipRegion"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetClipRegion kaydı, mevcut kırpma bölgesi ile başka bir grafik bölgesini birleştirir."
type: docs
weight: 57
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

EmfPlusSetClipRegion kaydı, mevcut kırpma bölgesini başka bir grafik bölgesiyle birleştirir. Yeni mevcut kırpma bölgesi, önceki mevcut kırpma bölgesi ve belirtilen EmfPlusRegion nesnesi üzerinde CombineMode işlemi uygulanarak elde edilen sonuca ayarlanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusSetClipRegion` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCm()](#getCm--) | Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. |
| [setCm(byte value)](#setCm-byte-) | Alır veya ayarlar CM (4 bit): İki bölgeyi birleştirmek için mantıksal işlemi belirtir. |
| [getObjectId()](#getObjectId--) | Alır veya ayarlar EMF+ Nesne Tablosunda bir EmfPlusRegion nesnesinin (bölüm 2.2.1.8) dizinini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| [setObjectId(byte value)](#setObjectId-byte-) | Alır veya ayarlar EMF+ Nesne Tablosunda bir EmfPlusRegion nesnesinin (bölüm 2.2.1.8) dizinini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Yeni bir `EmfPlusSetClipRegion` sınıfı örneği başlatır.

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


Alır veya ayarlar EMF+ Nesne Tablosunda bir EmfPlusRegion nesnesinin (bölüm 2.2.1.8) dizinini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Alır veya ayarlar EMF+ Nesne Tablosunda bir EmfPlusRegion nesnesinin (bölüm 2.2.1.8) dizinini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

