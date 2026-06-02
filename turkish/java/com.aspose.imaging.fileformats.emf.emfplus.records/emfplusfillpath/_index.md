---
title: "EmfPlusFillPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Fill path kaydı FLAGS, işlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi sağlayan 16-bit işaretsiz tam sayıdır."
type: docs
weight: 34
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Fill path kaydı FLAGS: İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi sağlayan 16-bit işaretsiz tam sayı. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 bit): Bu bit, BrushId alanındaki veri tipini gösterir. Ayarlanmışsa, BrushId bir EmfPlusARGB nesnesi (bölüm 2.2.2.1) olarak bir rengi belirtir. Temizlenmişse, BrushId EMF+ Nesne Tablosunda bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) indeksini içerir. X (1 bit): Ayrılmıştır ve YOK SAYILMALIDIR. ObjectId (1 byte): EMF+ Nesne Tablosunda doldurulacak EmfPlusPath nesnesinin (bölüm 2.2.1.6) indeksidir. Değer 0 ile 63 arasında olmalıdır, dahil.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusFillPath` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getBrushId()](#getBrushId--) | Fırça kimliğini alır veya ayarlar. Fırçayı tanımlayan, içeriği Flags alanındaki S biti tarafından belirlenen 32-bit işaretsiz tam sayı. |
| [setBrushId(int value)](#setBrushId-int-) | Fırça kimliğini alır veya ayarlar. Fırçayı tanımlayan, içeriği Flags alanındaki S biti tarafından belirlenen 32-bit işaretsiz tam sayı. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


`EmfPlusFillPath` sınıfının yeni bir örneğini başlatır.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda doldurulacak EmfPlusPath nesnesinin (bölüm 2.2.1.6) indeksidir. Değer 0 ile 63 arasında olmalıdır, dahil.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda doldurulacak EmfPlusPath nesnesinin (bölüm 2.2.1.6) indeksidir. Değer 0 ile 63 arasında olmalıdır, dahil.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Fırça kimliğini alır veya ayarlar. Fırçayı tanımlayan, içeriği Flags alanındaki S biti tarafından belirlenen 32-bit işaretsiz tam sayı.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Fırça kimliğini alır veya ayarlar. Fırçayı tanımlayan, içeriği Flags alanındaki S biti tarafından belirlenen 32-bit işaretsiz tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

