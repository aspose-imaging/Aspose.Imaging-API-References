---
title: "LengthRecord"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Alt Yol Uzunluğu Kayıt Sınıfı"
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Alt Yol Uzunluğu Kayıt Sınıfı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Yeni bir [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) sınıfının örneğini başlatır. |
| [LengthRecord()](#LengthRecord--) | Yeni bir [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isClosed()](#isClosed--) | Bu örneğin kapalı olup olmadığını belirten bir değeri alır. |
| [setClosed(boolean value)](#setClosed-boolean-) | Bu örneğin kapalı olup olmadığını belirten bir değeri ayarlar. |
| [isOpen()](#isOpen--) | Bu örneğin açık olup olmadığını belirten bir değeri alır. |
| [setOpen(boolean value)](#setOpen-boolean-) | Bu örneğin açık olup olmadığını belirten bir değeri ayarlar. |
| [getRecordCount()](#getRecordCount--) | Kayıt sayısını alır. |
| [setRecordCount(int value)](#setRecordCount-int-) | Kayıt sayısını ayarlar. |
| [getType()](#getType--) | Türü alır. |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Bezier düğüm kayıt sayısını alır. |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Bezier düğüm kayıt sayısını ayarlar. |
| [getPathOperations()](#getPathOperations--) | Yol işlemlerini alır. |
| [setPathOperations(int value)](#setPathOperations-int-) | Yol işlemlerini ayarlar. |
| [getShapeIndex()](#getShapeIndex--) | Katmandaki mevcut yol şeklinin indeksini alır. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Katmandaki mevcut yol şeklinin indeksini ayarlar. |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Yeni bir [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Kayıt verileri. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Yeni bir [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) sınıfının örneğini başlatır.

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Bu örneğin kapalı olup olmadığını belirten bir değeri alır.

Değer: Bu örnek kapalıysa `true`; aksi takdirde `false`.

**Returns:**
boolean - bu örneğin kapalı olup olmadığını belirten bir değer.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Bu örneğin kapalı olup olmadığını belirten bir değeri ayarlar.

Değer: Bu örnek kapalıysa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | bu örneğin kapalı olup olmadığını belirten bir değer. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Bu örneğin açık olup olmadığını belirten bir değeri alır.

Değer: Bu örnek açıksa `true`; aksi takdirde `false`.

**Returns:**
boolean - bu örneğin açık olup olmadığını belirten bir değer.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Bu örneğin açık olup olmadığını belirten bir değeri ayarlar.

Değer: Bu örnek açıksa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | bu örneğin açık olup olmadığını belirten bir değer. |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Kayıt sayısını alır.

Değer: Kayıt sayısı.

**Returns:**
int - kayıt sayısı.
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Kayıt sayısını ayarlar.

Değer: Kayıt sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | kayıt sayısı. |

### getType() {#getType--}
```
public short getType()
```


Türü alır.

Değer: Tür.

**Returns:**
short - tür.
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Bezier düğüm kayıt sayısını alır.

**Returns:**
int - bezier düğüm kayıt sayısı.
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Bezier düğüm kayıt sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | bezier düğüm kayıt sayısı. |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Yol işlemlerini alır.

**Returns:**
int - yol işlemleri.
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Yol işlemlerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yol işlemleri. |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Katmandaki mevcut yol şeklinin indeksini alır.

**Returns:**
int - katmandaki mevcut yol şeklinin indeksi.
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Katmandaki mevcut yol şeklinin indeksini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | katmandaki mevcut yol şeklinin indeksi. |

