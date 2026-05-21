---
title: "EmfCommentPublicRecordType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COMMENT_PUBLIC kayıt türleri, EMF işleme için uzantıları belirtir."
type: docs
weight: 31
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

EMR_COMMENT_PUBLIC kayıt türleri EMF işleme için uzantıları belirtir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Bu yorum kaydının genel veri belirttiğini tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Bu yorum kaydının genel veri belirttiğini tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Genel yorum kaydının türünü tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Genel yorum kaydının türünü tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Bu yorum kaydının genel veri belirttiğini tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. 0x43494447 değeri, ASCII \"CIDG\" dizesi olup, bunu bir EMR\_COMMENT\_PUBLIC kaydı olarak tanımlar.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Bu yorum kaydının genel veri belirttiğini tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. 0x43494447 değeri, ASCII \"CIDG\" dizesi olup, bunu bir EMR\_COMMENT\_PUBLIC kaydı olarak tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Genel yorum kaydının türünü tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu, önceden listelenen tabloda belirtilen değerlerden biri olmalıdır; bu değerler EmrComment numaralandırmasında (bölüm 2.1.10) tanımlanmıştır, aksi takdirde yazıcı sunucusunda ek genel yorum kayıt türleri uygulanmış olabilir.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Genel yorum kaydının türünü tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu, önceden listelenen tabloda belirtilen değerlerden biri olmalıdır; bu değerler EmrComment numaralandırmasında (bölüm 2.1.10) tanımlanmıştır, aksi takdirde yazıcı sunucusunda ek genel yorum kayıt türleri uygulanmış olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

