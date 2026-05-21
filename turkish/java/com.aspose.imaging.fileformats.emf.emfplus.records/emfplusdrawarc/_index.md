---
title: "EmfPlusDrawArc"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawArc kaydı bir elipsin yayını çizmeyi belirtir."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

EmfPlusDrawArc kaydı bir elipsin yayını çizmeyi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusDrawArc` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDataSize()](#getDataSize--) | Verinin boyutunu alır. |
| [setDataSize(int value)](#setDataSize-int-) | Verinin boyutunu ayarlar. |
| [getRectFloat()](#getRectFloat--) | Verinin EmfPlusRectF veya EmfPlusRect kayıtlarını içerip içermediğini gösteren bir değeri alır. Bu bit, RectData alanındaki verinin sıkıştırılıp sıkıştırılmadığını gösterir. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Verinin EmfPlusRectF veya EmfPlusRect kayıtlarını içerip içermediğini gösteren bir değeri ayarlar. Bu bit, RectData alanındaki verinin sıkıştırılıp sıkıştırılmadığını gösterir. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını ayarlar. |
| [getSize()](#getSize--) | Boyutu alır. |
| [setSize(int value)](#setSize-int-) | Boyutu ayarlar. |
| [getStartAngle()](#getStartAngle--) | Başlangıç açısını alır. Yayın başlangıç noktasını x ekseni ile belirten açıyı tanımlayan 32 bit negatif olmayan kayan nokta değeri. |
| [setStartAngle(float value)](#setStartAngle-float-) | Başlangıç açısını ayarlar. Yayın başlangıç noktasını x ekseni ile belirten açıyı tanımlayan 32 bit negatif olmayan kayan nokta değeri. |
| [getSweepAngle()](#getSweepAngle--) | Tarama açısını alır. Çizilecek yay uzunluğunu, BaşlangıçAçısı değeriyle tanımlanan başlangıç noktasından ölçülen derece cinsinden açıyı belirten 32 bit kayan nokta değeri. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Tarama açısını ayarlar. Çizilecek yay uzunluğunu, BaşlangıçAçısı değeriyle tanımlanan başlangıç noktasından ölçülen derece cinsinden açıyı belirten 32 bit kayan nokta değeri. |
| [getRectangleData()](#getRectangleData--) | Dikdörtgen verisini alır. Yayla aynı doğrultuda olan elipsin sınırlayıcı kutusunu tanımlayan EmfPlusRect veya EmfPlusRectF nesnesi. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Dikdörtgen verisini ayarlar. Yayla aynı doğrultuda olan elipsin sınırlayıcı kutusunu tanımlayan EmfPlusRect veya EmfPlusRectF nesnesi. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Yeni bir `EmfPlusDrawArc` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Verinin boyutunu alır. Takip eden kayıt‑özel verinin 32‑bit hizalanmış bayt sayısını belirten 32 bit işaretsiz tam sayı. Bu kayıt türü için değer Aşağıdakilerden biri olmalıdır: 0x00000010 Eğer Flags alanındaki C biti ayarlıysa. 0x00000018 Eğer Flags alanındaki C biti temizse.

**Returns:**
int - Verinin boyutu.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Verinin boyutunu ayarlar. Takip eden kayıt‑özel verinin 32‑bit hizalanmış bayt sayısını belirten 32 bit işaretsiz tam sayı. Bu kayıt türü için değer Aşağıdakilerden biri olmalıdır: 0x00000010 Eğer Flags alanındaki C biti ayarlıysa. 0x00000018 Eğer Flags alanındaki C biti temizse.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Verinin boyutu. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Verinin EmfPlusRectF veya EmfPlusRect kayıtlarını içerip içermediğini gösteren bir değeri alır. Bu bit, RectData alanındaki verinin sıkıştırılıp sıkıştırılmadığını gösterir. Eğer ayarlıysa, RectData bir EmfPlusRect nesnesi içerir (bölüm 2.2.2.38). Eğer temizse, RectData bir EmfPlusRectF nesnesi içerir (bölüm 2.2.2.39).

**Returns:**
boolean - `true` ise float; aksi takdirde `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Verinin EmfPlusRectF veya EmfPlusRect kayıtlarını içerip içermediğini gösteren bir değer ayarlar. Bu bit, RectData alanındaki verinin sıkıştırılıp sıkıştırılmadığını gösterir. Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir. Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` ise float; aksi takdirde `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır. Yay çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

**Returns:**
byte - Nesne tanımlayıcısı.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını ayarlar. Yay çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Nesne tanımlayıcısı. |

### getSize() {#getSize--}
```
public int getSize()
```


Boyutu alır. Tüm kayıttaki, 12 baytlık kayıt başlığı ve kayıt‑özel verileri dahil olmak üzere, 32‑bit hizalanmış bayt sayısını belirten 32‑bit işaretsiz tamsayıdır. Bu kayıt türü için değer aşağıdakilerden biri olmalıdır: 0x0000001C Eğer Flags alanındaki C biti ayarlıysa. 0x00000024 Eğer Flags alanındaki C biti temizse.

**Returns:**
int - Boyut.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Boyutu ayarlar. Tüm kayıttaki, 12 baytlık kayıt başlığı ve kayıt‑özel verileri dahil olmak üzere, 32‑bit hizalanmış bayt sayısını belirten 32‑bit işaretsiz tamsayıdır. Bu kayıt türü için değer aşağıdakilerden biri olmalıdır: 0x0000001C Eğer Flags alanındaki C biti ayarlıysa. 0x00000024 Eğer Flags alanındaki C biti temizse.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Boyut. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Başlangıç açısını alır. X ekseni ile yay başlangıç noktası arasındaki açıyı belirten 32‑bit negatif olmayan kayan nokta değeridir. Herhangi bir değer kabul edilebilir, ancak 360 modunda yorumlanmalı ve kullanılan sonuç 0.0 dahil, 360.0 hariç aralığında olmalıdır.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Başlangıç açısını ayarlar. X ekseni ile yay başlangıç noktası arasındaki açıyı belirten 32‑bit negatif olmayan kayan nokta değeridir. Herhangi bir değer kabul edilebilir, ancak 360 modunda yorumlanmalı ve kullanılan sonuç 0.0 dahil, 360.0 hariç aralığında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Tarama açısını alır. Yay başlangıç noktasından ölçülen, derece cinsinden yay uzunluğunu belirten 32‑bit kayan nokta değeridir. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 arasında, dahil olmak üzere sınırlanmalıdır. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde tanımlandığını gösterir.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Tarama açısını ayarlar. Yay başlangıç noktasından ölçülen, derece cinsinden yay uzunluğunu belirten 32‑bit kayan nokta değeridir. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 arasında, dahil olmak üzere sınırlanmalıdır. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde tanımlandığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Dikdörtgen verisini alır. Yay ile kollinear olan elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesidir. Bu dikdörtgen yayının konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne tipi Flags alanının değeriyle belirlenir.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Dikdörtgen verisini ayarlar. Yay ile kollinear olan elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesidir. Bu dikdörtgen yayının konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne tipi Flags alanının değeriyle belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

