---
title: "EmfNamedEscape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "MR_NAMEDESCAPE kaydı, belirli bir yazıcı sürücüsüne keyfi bilgi aktarır."
type: docs
weight: 75
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

MR_NAMEDESCAPE kaydı, belirtilen bir yazıcı sürücüsüne rastgele bilgi aktarır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfNamedEscape` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Alır veya ayarlar, DriverName alanındaki bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı. |
| [setCjDriver(int value)](#setCjDriver-int-) | Alır veya ayarlar, DriverName alanındaki bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı. |
| [getCjIn()](#getCjIn--) | Alır veya ayarlar, yazıcı sürücüsüne aktarılacak bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı. |
| [setCjIn(int value)](#setCjIn-int-) | Alır veya ayarlar, yazıcı sürücüsüne aktarılacak bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı. |
| [getDriverName()](#getDriverName--) | Alır veya ayarlar, veri alacak yazıcı sürücüsünün adını belirten 16 bitlik Unicode karakterlerinden oluşan bir dizeyi. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Alır veya ayarlar, veri alacak yazıcı sürücüsünün adını belirten 16 bitlik Unicode karakterlerinden oluşan bir dizeyi. |
| [getData()](#getData--) | Alır veya ayarlar, yazıcı sürücüsüne aktarılacak veriyi. |
| [setData(byte[] value)](#setData-byte---) | Alır veya ayarlar, yazıcı sürücüsüne aktarılacak veriyi. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


`EmfNamedEscape` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Alır veya ayarlar, DriverName alanındaki bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı. Bu değer MUST çift bir sayı olmalıdır.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Alır veya ayarlar, DriverName alanındaki bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı. Bu değer MUST çift bir sayı olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Alır veya ayarlar, yazıcı sürücüsüne aktarılacak bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Alır veya ayarlar, yazıcı sürücüsüne aktarılacak bayt sayısını belirten 32 bitlik işaretsiz tam sayıyı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Alır veya ayarlar, veri alacak yazıcı sürücüsünün adını belirten 16 bitlik Unicode karakterlerinden oluşan bir dizeyi. Bu değer MUST cjDriver bayt uzunluğunda olmalı ve MUST null karakteriyle sonlandırılmalıdır.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Alır veya ayarlar, veri alacak yazıcı sürücüsünün adını belirten 16 bitlik Unicode karakterlerinden oluşan bir dizeyi. Bu değer MUST cjDriver bayt uzunluğunda olmalı ve MUST null karakteriyle sonlandırılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Alır veya ayarlar, yazıcı sürücüsüne aktarılacak veriyi. cjIn baytının mevcut olması MUST gerekir.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Alır veya ayarlar, yazıcı sürücüsüne aktarılacak veriyi. cjIn baytının mevcut olması MUST gerekir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

