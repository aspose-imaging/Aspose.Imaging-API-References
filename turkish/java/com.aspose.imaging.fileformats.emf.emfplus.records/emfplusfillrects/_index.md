---
title: "EmfPlusFillRects"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFillRects kaydı, bir dizi dikdörtgenin içlerini doldurmayı belirtir"
type: docs
weight: 37
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

EmfPlusFillRects kaydı, bir dizi dikdörtgenin içlerini doldurmayı belirtir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusFillRects` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getCompressed()](#getCompressed--) | Bu `EmfPlusFillRects` nesnesinin sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Bu `EmfPlusFillRects` nesnesinin sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getBrushId()](#getBrushId--) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| [setBrushId(int value)](#setBrushId-int-) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| [getRectData()](#getRectData--) | Dikdörtgen verisini alır veya ayarlar. Count uzunluğunda bir EmfPlusRect veya EmfPlusRectF nesnelerinden oluşan bir dizi olup, dikdörtgen verisini tanımlar. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Dikdörtgen verisini alır veya ayarlar. Count uzunluğunda bir EmfPlusRect veya EmfPlusRectF nesnelerinden oluşan bir dizi olup, dikdörtgen verisini tanımlar. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


`EmfPlusFillRects` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, BrushId bir EmfPlusARGB nesnesi (bölüm 2.2.2.1) olarak bir rengi belirtir. Temizlenmişse, BrushId EMF+ Nesne Tablosunda bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) indeksini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, BrushId bir EmfPlusARGB nesnesi (bölüm 2.2.2.1) olarak bir rengi belirtir. Temizlenmişse, BrushId EMF+ Nesne Tablosunda bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) indeksini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Bu `EmfPlusFillRects` nesnesinin sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir. Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Bu `EmfPlusFillRects` nesnesinin sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir. Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Dikdörtgen verisini alır veya ayarlar. Count uzunluğunda bir EmfPlusRect veya EmfPlusRectF nesnelerinden oluşan bir dizi olup, dikdörtgen verisini tanımlar.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Dikdörtgen verisini alır veya ayarlar. Count uzunluğunda bir EmfPlusRect veya EmfPlusRectF nesnelerinden oluşan bir dizi olup, dikdörtgen verisini tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

