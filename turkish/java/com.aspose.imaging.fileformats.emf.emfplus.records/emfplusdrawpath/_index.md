---
title: "EmfPlusDrawPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawPath kaydı bir grafik yolunu çizmeyi belirtir."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

EmfPlusDrawPath kaydı bir grafik yolunu çizmeyi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusDrawPath` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getPenId()](#getPenId--) | Kalem tanımlayıcısını alır veya ayarlar. EmfPlusPen nesnesi (bölüm 2.2.1.7) için EMF+ Nesne Tablosunda bir dizini belirten 32 bit işaretsiz tamsayı, EmfPlusPath'i çizmeye kullanılır. |
| [setPenId(int value)](#setPenId-int-) | Kalem tanımlayıcısını alır veya ayarlar. EmfPlusPen nesnesi (bölüm 2.2.1.7) için EMF+ Nesne Tablosunda bir dizini belirten 32 bit işaretsiz tamsayı, EmfPlusPath'i çizmeye kullanılır. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Yeni bir `EmfPlusDrawPath` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda çizilecek EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda çizilecek EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Kalem tanımlayıcısını alır veya ayarlar. EmfPlusPen nesnesi (bölüm 2.2.1.7) için EMF+ Nesne Tablosunda bir dizini belirten 32 bit işaretsiz tamsayı, EmfPlusPath'i çizmeye kullanılır. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Kalem tanımlayıcısını alır veya ayarlar. EmfPlusPen nesnesi (bölüm 2.2.1.7) için EMF+ Nesne Tablosunda bir dizini belirten 32 bit işaretsiz tamsayı, EmfPlusPath'i çizmeye kullanılır. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

