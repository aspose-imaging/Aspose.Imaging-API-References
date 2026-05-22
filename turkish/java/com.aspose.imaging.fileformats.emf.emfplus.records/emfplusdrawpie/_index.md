---
title: "EmfPlusDrawPie"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawPie kaydı bir elipsin iç kısmının bir bölümünü çizmeyi belirtir."
type: docs
weight: 26
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

EmfPlusDrawPie kaydı bir elipsin iç kısmının bir bölümünü çizmeyi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawPie` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getStartAngle()](#getStartAngle--) | Başlangıç açısını alır veya ayarlar. X ekseni ile dilim başlangıç noktası arasındaki açıyı belirten 32 bit, negatif olmayan kayan nokta değeri. |
| [setStartAngle(float value)](#setStartAngle-float-) | Başlangıç açısını alır veya ayarlar. X ekseni ile dilim başlangıç noktası arasındaki açıyı belirten 32 bit, negatif olmayan kayan nokta değeri. |
| [getSweepAngle()](#getSweepAngle--) | Tarama açısını alır veya ayarlar. Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, derece cinsinden dilimi çizen yay uzunluğunu belirten 32 bit kayan nokta değeri. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Tarama açısını alır veya ayarlar. Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, derece cinsinden dilimi çizen yay uzunluğunu belirten 32 bit kayan nokta değeri. |
| [getRectData()](#getRectData--) | Dikdörtgen verilerini alır veya ayarlar. Dilimi içeren elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Dikdörtgen verilerini alır veya ayarlar. Dilimi içeren elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


`EmfPlusDrawPie` sınıfının yeni bir örneğini başlatır.

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


Nesne tanımlayıcısını alır veya ayarlar. Pasta çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. Pasta çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Başlangıç açısını alır veya ayarlar. X ekseni ile dilim başlangıç noktası arasındaki açıyı belirten 32 bit, negatif olmayan kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak 360 modulo olarak yorumlanmalı ve kullanılan sonuç 0.0 dahil, 360.0 hariç aralığında olmalıdır.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Başlangıç açısını alır veya ayarlar. X ekseni ile dilim başlangıç noktası arasındaki açıyı belirten 32 bit, negatif olmayan kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak 360 modulo olarak yorumlanmalı ve kullanılan sonuç 0.0 dahil, 360.0 hariç aralığında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Tarama açısını alır veya ayarlar. Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, derece cinsinden dilimi çizen yay uzunluğunu belirten 32 bit kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 arasında (dahil) sınırlanmalıdır. Pozitif bir değer, taramanın saat yönünde tanımlandığını, negatif bir değer ise saat yönünün tersinde tanımlandığını gösterir.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Tarama açısını alır veya ayarlar. Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, derece cinsinden dilimi çizen yay uzunluğunu belirten 32 bit kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 arasında (dahil) sınırlanmalıdır. Pozitif bir değer, taramanın saat yönünde tanımlandığını, negatif bir değer ise saat yönünün tersinde tanımlandığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Dikdörtgen verilerini alır veya ayarlar. Dilimi içeren elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. Bu dikdörtgen, dilimin konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne tipi Flags alanının değeriyle belirtilir.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Dikdörtgen verilerini alır veya ayarlar. Dilimi içeren elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. Bu dikdörtgen, dilimin konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne tipi Flags alanının değeriyle belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

