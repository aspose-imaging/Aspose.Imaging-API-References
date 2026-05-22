---
title: "EmfComment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COMMENT kaydı, rastgele özel veri içerir."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

EMR\_COMMENT kaydı, rastgele özel veri içerir. Not: Bu bölümde açıklanmayan alanlar bölüm 2.3.3'te belirtilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfComment` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Özel veriyi belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Özel veriyi belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Yorum tanımlayıcısını alır veya ayarlar. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Yorum tanımlayıcısını alır veya ayarlar. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Yeni bir `EmfComment` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Özel veriyi belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. Bu verinin ilk DWORD'u, bölüm 2.3.3'te belirtilen önceden tanımlanmış yorum tanımlayıcı değerlerinden biri OLMAMALIDIR. Özel veri EMF tarafından bilinmez; yalnızca verinin formatını ve nasıl kullanılacağını bilen uygulamalar için anlamlıdır. EMR\_COMMENT özel veri kayıtları YOK SAYILABİLİR.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Özel veriyi belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. Bu verinin ilk DWORD'u, bölüm 2.3.3'te belirtilen önceden tanımlanmış yorum tanımlayıcı değerlerinden biri OLMAMALIDIR. Özel veri EMF tarafından bilinmez; yalnızca verinin formatını ve nasıl kullanılacağını bilen uygulamalar için anlamlıdır. EMR\_COMMENT özel veri kayıtları YOK SAYILABİLİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

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

