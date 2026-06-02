---
title: "EmfCommentEmfPlus"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COMMENT_EMFPLUS kaydı gömülü EMF kayıtlarını içerir."
type: docs
weight: 27
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

EMR\_COMMENT\_EMFPLUS kaydı gömülü EMF+ kayıtlarını içerir. Not: Bu bölümde açıklanmayan alanlar bölüm 2.3.3'te belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCommentEmfPlus` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Bu yorum kaydının EMF+ kayıtları içerdiğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Bu yorum kaydının EMF+ kayıtları içerdiğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Bir veya daha fazla EMF+ kaydı ([MS-EMFPLUS] bölüm 2.3.1) içeren bir bayt dizisini alır veya ayarlar. |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Bir veya daha fazla EMF+ kaydı ([MS-EMFPLUS] bölüm 2.3.1) içeren bir bayt dizisini alır veya ayarlar. |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


`EmfCommentEmfPlus` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Bu yorum kaydının EMF+ kayıtları içerdiğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. 0x2B464D45 değeri, ASCII dizesi "+FME" olup, bunu bir EMR\_COMMENT\_EMFPLUS kaydı olarak tanımlar.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Bu yorum kaydının EMF+ kayıtları içerdiğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. 0x2B464D45 değeri, ASCII dizesi "+FME" olup, bunu bir EMR\_COMMENT\_EMFPLUS kaydı olarak tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Bir veya daha fazla EMF+ kaydı ([MS-EMFPLUS] bölüm 2.3.1) içeren bir bayt dizisini alır veya ayarlar.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Bir veya daha fazla EMF+ kaydı ([MS-EMFPLUS] bölüm 2.3.1) içeren bir bayt dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

