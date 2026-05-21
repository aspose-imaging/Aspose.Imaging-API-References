---
title: "EmfSetMapperFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETMAPPERFLAGS kaydı, yazı tipi eşleyicisi tarafından gerçekleştirilen mantıksal yazı tiplerini fiziksel yazı tiplerine eşleştirme sürecinin parametrelerini belirtir."
type: docs
weight: 131
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

EMR\_SETMAPPERFLAGS kaydı, yazı tipi eşleyicisi tarafından gerçekleştirilen mantıksal yazı tiplerini fiziksel yazı tiplerine eşleştirme sürecinin parametrelerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetMapperFlags` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFlags()](#getFlags--) | Yazı tipi eşleştirme sürecinin parametrelerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setFlags(int value)](#setFlags-int-) | Yazı tipi eşleştirme sürecinin parametrelerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


`EmfSetMapperFlags` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Yazı tipi eşleştirme sürecinin parametrelerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

0x00000001 Yazı tipi eşleyicisi, oynatma aygıtı bağlamında şu anda tanımlandığı gibi, çıktı aygıtının en‑boy oranına uyan yalnızca yazı tiplerini seçmelidir.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Yazı tipi eşleştirme sürecinin parametrelerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

0x00000001 Yazı tipi eşleyicisi, oynatma aygıtı bağlamında şu anda tanımlandığı gibi, çıktı aygıtının en‑boy oranına uyan yalnızca yazı tiplerini seçmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

