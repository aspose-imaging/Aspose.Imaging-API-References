---
title: "EmfExtCreateFontIndirectW"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EXTCREATEFONTINDIRECTW kaydı, grafik işlemleri için mantıksal bir yazı tipini tanımlar."
type: docs
weight: 51
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

EMR\_EXTCREATEFONTINDIRECTW kaydı, grafik işlemleri için mantıksal bir yazı tipi tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfExtCreateFontIndirectW` sınıfının yeni bir örneğini başlatır. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | `EmfExtCreateFontIndirectW` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki mantıksal yazı tipi nesnesinin dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhFonts(int value)](#setIhFonts-int-) | EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki mantıksal yazı tipi nesnesinin dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getElw()](#getElw--) | Mantıksal yazı tipini belirten LogFontExDv nesnesini (bölüm 2.2.15) alır veya ayarlar. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Mantıksal yazı tipini belirten LogFontExDv nesnesini (bölüm 2.2.15) alır veya ayarlar. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


`EmfExtCreateFontIndirectW` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


`EmfExtCreateFontIndirectW` sınıfının yeni bir örneğini başlatır.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki mantıksal yazı tipi nesnesinin dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki mantıksal yazı tipi nesnesinin dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Mantıksal yazı tipini belirten LogFontExDv nesnesini (bölüm 2.2.15) alır veya ayarlar. Bunun yerine bir LogFont nesnesi 2.2.13 bulunabilir.[90]Bu alandaki nesnenin türünün belirlenme süreci aşağıda açıklanmıştır.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Mantıksal yazı tipini belirten LogFontExDv nesnesini (bölüm 2.2.15) alır veya ayarlar. Bunun yerine bir LogFont nesnesi 2.2.13 bulunabilir.[90]Bu alandaki nesnenin türünün belirlenme süreci aşağıda açıklanmıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

