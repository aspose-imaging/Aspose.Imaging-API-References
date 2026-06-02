---
title: "EmfPlusDrawImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawImage kaydı ölçeklenmiş bir görüntü çizmeyi belirtir."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

EmfPlusDrawImage kaydı ölçeklenmiş bir görüntü çizmeyi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusDrawImage` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getImageAttributesId()](#getImageAttributesId--) | Görüntü öznitelikleri tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki isteğe bağlı bir EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) indeksini belirten 32-bit işaretsiz tamsayı. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Görüntü öznitelikleri tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki isteğe bağlı bir EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) indeksini belirten 32-bit işaretsiz tamsayı. |
| [getRectData()](#getRectData--) | Dikdörtgen verisini alır veya ayarlar. Görüntünün sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Dikdörtgen verisini alır veya ayarlar. Görüntünün sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| [getSrcRect()](#getSrcRect--) | Kaynak dikdörtgeni alır veya ayarlar. Görüntünün işlenecek bir bölümünü belirten bir EmfPlusRectF nesnesi. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Kaynak dikdörtgeni alır veya ayarlar. Görüntünün işlenecek bir bölümünü belirten bir EmfPlusRectF nesnesi. |
| [getSrcUnit()](#getSrcUnit--) | Kaynak birimini alır veya ayarlar. SrcRect alanının birimlerini belirten 32-bit işaretli tamsayı. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Kaynak birimini alır veya ayarlar. SrcRect alanının birimlerini belirten 32-bit işaretli tamsayı. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Yeni bir `EmfPlusDrawImage` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir. Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir. Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) dizini, renderlenecek görüntüyü belirtir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) dizini, renderlenecek görüntüyü belirtir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Görüntü öznitelikleri tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki isteğe bağlı bir EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) indeksini belirten 32-bit işaretsiz tamsayı.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Görüntü öznitelikleri tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki isteğe bağlı bir EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) indeksini belirten 32-bit işaretsiz tamsayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Dikdörtgen verisini alır veya ayarlar. Görüntünün sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. SrcRect alanı tarafından belirtilen görüntü bölümü bu dikdörtgene sığacak şekilde ölçeklendirilir.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Dikdörtgen verisini alır veya ayarlar. Görüntünün sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. SrcRect alanı tarafından belirtilen görüntü bölümü bu dikdörtgene sığacak şekilde ölçeklendirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Kaynak dikdörtgeni alır veya ayarlar. Görüntünün işlenecek bir bölümünü belirten bir EmfPlusRectF nesnesi. Bu dikdörtgen tarafından belirtilen görüntü bölümü, RectData alanı tarafından belirtilen hedef dikdörtgene sığacak şekilde ölçeklendirilir.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Kaynak dikdörtgeni alır veya ayarlar. Görüntünün işlenecek bir bölümünü belirten bir EmfPlusRectF nesnesi. Bu dikdörtgen tarafından belirtilen görüntü bölümü, RectData alanı tarafından belirtilen hedef dikdörtgene sığacak şekilde ölçeklendirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Kaynak birimini alır veya ayarlar. SrcRect alanının birimlerini belirten 32-bit işaretli tamsayı. Bu, UnitType enumarasyonunun (bölüm 2.1.1.33) UnitTypePixel üyesi olmalıdır.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Kaynak birimini alır veya ayarlar. SrcRect alanının birimlerini belirten 32-bit işaretli tamsayı. Bu, UnitType enumarasyonunun (bölüm 2.1.1.33) UnitTypePixel üyesi olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

