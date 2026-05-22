---
title: "EmfCommentRecordType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Yorum kayıt türleri, diğer metafile biçimlerinde rastgele özel veri gömme kayıtlarını belirtmek ve yeni ya da özel amaçlı komutlar eklemek için biçimleri tanımlar."
type: docs
weight: 32
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

Yorum kayıt türleri, keyfi özel verileri belirtmek, kayıtları diğer metafile formatlarına gömmek ve yeni ya da özel amaçlı komutlar eklemek için biçimleri tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDataSize()](#getDataSize--) | Aşağıdaki RecordBuffer alanında bulunan CommentIdentifier ve CommentRecordParm alanlarının boyutunu (bayt cinsinden) belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setDataSize(int value)](#setDataSize-int-) | Aşağıdaki RecordBuffer alanında bulunan CommentIdentifier ve CommentRecordParm alanlarının boyutunu (bayt cinsinden) belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Yorum tanımlayıcısını alır veya ayarlar. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Yorum tanımlayıcısını alır veya ayarlar. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Aşağıdaki RecordBuffer alanında bulunan CommentIdentifier ve CommentRecordParm alanlarının boyutunu (bayt cinsinden) belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer, mevcutsa, kendisinin veya AlignmentPadding alanının boyutunu içermez.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Aşağıdaki RecordBuffer alanında bulunan CommentIdentifier ve CommentRecordParm alanlarının boyutunu (bayt cinsinden) belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer, mevcutsa, kendisinin veya AlignmentPadding alanının boyutunu içermez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Yorum tanımlayıcısını alır veya ayarlar.

Değer: Yorum tanımlayıcısı.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Yorum tanımlayıcısını alır veya ayarlar.

Değer: Yorum tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

