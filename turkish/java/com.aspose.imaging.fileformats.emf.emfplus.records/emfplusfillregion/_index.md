---
title: "EmfPlusFillRegion"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFillRegion kaydı, bir grafik bölgesinin içini doldurmayı belirtir"
type: docs
weight: 38
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRegion extends EmfPlusDrawingRecordType
```

EmfPlusFillRegion kaydı, bir grafik bölgesinin içini doldurmayı belirtir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillRegion(EmfPlusRecord source)](#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusFillRegion` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getBrushId()](#getBrushId--) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| [setBrushId(int value)](#setBrushId-int-) | Alır veya ayarlar fırça tanımlayıcısını: fırçayı tanımlayan 32 bitlik işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
### EmfPlusFillRegion(EmfPlusRecord source) {#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRegion(EmfPlusRecord source)
```


Yeni bir `EmfPlusFillRegion` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. EmfPlusRegion nesnesinin (bölüm 2.2.1.8) doldurulacak nesnesinin EMF+ Nesne Tablosundaki indeksi. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. EmfPlusRegion nesnesinin (bölüm 2.2.1.8) doldurulacak nesnesinin EMF+ Nesne Tablosundaki indeksi. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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

