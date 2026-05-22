---
title: "EmfPlusEndOfFile"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusEndOfFile kaydı, metafildeki EMF verisinin sonunu belirtir."
type: docs
weight: 31
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusEndOfFile extends EmfPlusControlRecordType
```

EmfPlusEndOfFile kaydı, metafildeki EMF+ verisinin sonunu belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusEndOfFile(EmfPlusRecord source)](#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusEndOfFile` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFlags()](#getFlags--) | Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. |
| [setFlags(short value)](#setFlags-short-) | Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. |
### EmfPlusEndOfFile(EmfPlusRecord source) {#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndOfFile(EmfPlusRecord source)
```


`EmfPlusEndOfFile` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. Bu alan SHOULD sıfır olarak ayarlanmalı ve MUST alındığında yok sayılmalıdır.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. Bu alan SHOULD sıfır olarak ayarlanmalı ve MUST alındığında yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

