---
title: "EmfDrawEscape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_DRAWESCAPE kaydı, rastgele bilgileri bir yazıcı sürücüsüne iletir."
type: docs
weight: 44
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfDrawEscape extends EmfEscapeRecordType
```

EMR\_DRAWESCAPE kaydı, rastgele bilgileri bir yazıcı sürücüsüne iletir. Amacı, bilginin çizim yapılmasına yol açmasıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfDrawEscape(EmfRecord source)](#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfDrawEscape` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCjIn()](#getCjIn--) | Yazıcı sürücüsüne geçirilecek bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCjIn(int value)](#setCjIn-int-) | Yazıcı sürücüsüne geçirilecek bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getData()](#getData--) | Yazıcı sürücüsüne geçirilecek veriyi alır veya ayarlar. |
| [setData(byte[] value)](#setData-byte---) | Yazıcı sürücüsüne geçirilecek veriyi alır veya ayarlar. |
### EmfDrawEscape(EmfRecord source) {#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDrawEscape(EmfRecord source)
```


Yeni bir `EmfDrawEscape` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Yazıcı sürücüsüne geçirilecek bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Yazıcı sürücüsüne geçirilecek bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Yazıcı sürücüsüne geçirilecek veriyi alır veya ayarlar. cjIn baytının mevcut olması ZORUNLUDUR.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Yazıcı sürücüsüne geçirilecek veriyi alır veya ayarlar. cjIn baytının mevcut olması ZORUNLUDUR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

