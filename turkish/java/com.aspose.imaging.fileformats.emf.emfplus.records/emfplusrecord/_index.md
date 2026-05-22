---
title: "EmfPlusRecord"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Emf temel kayıt türü."
type: docs
weight: 46
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Emf+ temel kayıt türü.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | `EmfPlusRecord` sınıfının yeni bir örneğini başlatır. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusRecord` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |
| [getFlags()](#getFlags--) | Bazı kayıtların işlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır. |
| [setFlags(short value)](#setFlags-short-) | Bazı kayıtların işlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı ayarlar. |
| [getSize()](#getSize--) | Tüm kayıttaki, 12 baytlık kayıt başlığı ve kayıt‑özel verileri dahil olmak üzere, 32-bit hizalanmış bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır. |
| [setSize(int value)](#setSize-int-) | Tüm kayıttaki, 12 baytlık kayıt başlığı ve kayıt‑özel verileri dahil olmak üzere, 32-bit hizalanmış bayt sayısını belirten 32-bit işaretsiz tam sayıyı ayarlar. |
| [getDataSize()](#getDataSize--) | Sonraki RecordData alanındaki veri baytlarının 32-bit\u2013hizalanmış sayısını MUST tanımlamalı olan 32-bit işaretsiz tam sayıyı alır. |
| [setDataSize(int value)](#setDataSize-int-) | Sonraki RecordData alanındaki veri baytlarının 32-bit\u2013hizalanmış sayısını MUST tanımlamalı olan 32-bit işaretsiz tam sayıyı ayarlar. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


`EmfPlusRecord` sınıfının yeni bir örneğini başlatır.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


`EmfPlusRecord` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getType() {#getType--}
```
public short getType()
```


Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Bazı kayıtların işlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır.

**Returns:**
short - Bayraklar.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Bazı kayıtların işlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | Bayraklar. |

### getSize() {#getSize--}
```
public int getSize()
```


Tüm kayıttaki, 12 baytlık kayıt başlığı ve kayıt‑özel verileri dahil olmak üzere, 32-bit hizalanmış bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır.

**Returns:**
int - Boyut.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Tüm kayıttaki, 12 baytlık kayıt başlığı ve kayıt‑özel verileri dahil olmak üzere, 32-bit hizalanmış bayt sayısını belirten 32-bit işaretsiz tam sayıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Boyut. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


32-bit işaretsiz bir tamsayı alır; bu tamsayı, ardından gelen RecordData alanındaki verinin 32-bit\u2013hizalanmış bayt sayısını TANIMLAMALIDIR. Bu sayı 12 baytlık kayıt başlığını içermez.

**Returns:**
int - Verinin boyutu.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


32-bit işaretsiz bir tamsayı ayarlar; bu tamsayı, ardından gelen RecordData alanındaki verinin 32-bit\u2013hizalanmış bayt sayısını TANIMLAMALIDIR. Bu sayı 12 baytlık kayıt başlığını içermez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Verinin boyutu. |

