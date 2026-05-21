---
title: "EmfCommentEmfSpool"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COMMENT_EMFSPOOL kaydı gömülü EMFSPOOL kayıtlarını içerir."
type: docs
weight: 28
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

EMR\_COMMENT\_EMFSPOOL kaydı gömülü EMFSPOOL kayıtlarını içerir. Not: Bu bölümde açıklanmayan alanlar bölüm 2.3.3'te belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCommentEmfSpool` sınıfının yeni bir örneğini başlatır. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | `EmfCommentEmfSpool` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Bu yorum kaydının EMFSPOOL kayıtlarını içerdiğini belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Bu yorum kaydının EMFSPOOL kayıtlarını içerdiğini belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | EMR\_COMMENT\_EMFSPOOL kaydının türünü belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | EMR\_COMMENT\_EMFSPOOL kaydının türünü belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Bir veya daha fazla EMFSPOOL yazı tipi tanım kaydını içeren değişken uzunlukta bir bayt dizisi alır veya ayarlar ([MS-EMFSPOOL] bölüm 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Bir veya daha fazla EMFSPOOL yazı tipi tanım kaydını içeren değişken uzunlukta bir bayt dizisi alır veya ayarlar ([MS-EMFSPOOL] bölüm 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


`EmfCommentEmfSpool` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


`EmfCommentEmfSpool` sınıfının yeni bir örneğini başlatır.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Bu yorum kaydının EMFSPOOL kayıtlarını içerdiğini belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. 0x00000000 değeri bu kaydı bir EMR\_COMMENT\_EMFSPOOL kaydı olarak tanımlar.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Bu yorum kaydının EMFSPOOL kayıtlarını içerdiğini belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. 0x00000000 değeri bu kaydı bir EMR\_COMMENT\_EMFSPOOL kaydı olarak tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


EMR\_COMMENT\_EMFSPOOL kaydının türünü belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


EMR\_COMMENT\_EMFSPOOL kaydının türünü belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Bir veya daha fazla EMFSPOOL yazı tipi tanım kaydını içeren değişken uzunlukta bir bayt dizisi alır veya ayarlar ([MS-EMFSPOOL] bölüm 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Bir veya daha fazla EMFSPOOL yazı tipi tanım kaydını içeren değişken uzunlukta bir bayt dizisi alır veya ayarlar ([MS-EMFSPOOL] bölüm 2.2.3.3).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

