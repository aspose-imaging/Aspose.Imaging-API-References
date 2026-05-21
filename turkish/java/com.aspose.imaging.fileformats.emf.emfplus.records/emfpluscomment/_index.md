---
title: "EmfPlusComment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusComment kaydı keyfi özel verileri belirtir."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

EmfPlusComment kaydı keyfi özel verileri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusComment` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Özel verilerin DataSize uzunluğunda bayt dizisini alır veya ayarlar. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Özel verilerin DataSize uzunluğunda bayt dizisini alır veya ayarlar. |
| [getFlags()](#getFlags--) | Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. |
| [setFlags(short value)](#setFlags-short-) | Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Yeni bir `EmfPlusComment` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Özel verilerin DataSize uzunluğunda bayt dizisini alır veya ayarlar. Kayda özgü verilerin ardından gelen baytlar.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Özel verilerin DataSize uzunluğunda bayt dizisini alır veya ayarlar. Kayda özgü verilerin ardından gelen baytlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

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

