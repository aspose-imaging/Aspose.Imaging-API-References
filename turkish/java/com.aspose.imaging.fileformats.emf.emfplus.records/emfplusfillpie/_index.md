---
title: "EmfPlusFillPie"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFillPie kaydı, bir elipsin içindeki bir bölümü doldurmayı belirtir"
type: docs
weight: 35
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

EmfPlusFillPie kaydı, bir elipsin içindeki bir bölümü doldurmayı belirtir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusFillPie` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getStartAngle()](#getStartAngle--) | Başlangıç açısını alır veya ayarlar. X ekseni ile dilim başlangıç noktası arasındaki açıyı belirten 32 bit, negatif olmayan kayan nokta değeri. |
| [setStartAngle(float value)](#setStartAngle-float-) | Başlangıç açısını alır veya ayarlar. X ekseni ile dilim başlangıç noktası arasındaki açıyı belirten 32 bit, negatif olmayan kayan nokta değeri. |
| [getSweepAngle()](#getSweepAngle--) | Tarama açısını alır veya ayarlar. Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, derece cinsinden dilimi çizen yay uzunluğunu belirten 32 bit kayan nokta değeri. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Tarama açısını alır veya ayarlar. Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, derece cinsinden dilimi çizen yay uzunluğunu belirten 32 bit kayan nokta değeri. |
| [getRectData()](#getRectData--) | Dikdörtgen verilerini alır veya ayarlar. Dilimi içeren elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Dikdörtgen verilerini alır veya ayarlar. Dilimi içeren elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| [getBrushId()](#getBrushId--) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| [setBrushId(int value)](#setBrushId-int-) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


`EmfPlusFillPie` sınıfının yeni bir örneğini başlatır.

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

### isColor() {#isColor--}
```
public boolean isColor()
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

