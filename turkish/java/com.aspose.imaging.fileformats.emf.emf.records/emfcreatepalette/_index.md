---
title: "EmfCreatePalette"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CREATEPALETTE kaydı, grafik işlemleri için mantıksal bir palet tanımlar."
type: docs
weight: 40
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

EMR_CREATEPALETTE kaydı grafik işlemleri için mantıksal bir palet tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCreatePalette` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhPal()](#getIhPal--) | EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal palet nesnesinin dizinini belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhPal(int value)](#setIhPal-int-) | EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal palet nesnesinin dizinini belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [getLogPalette()](#getLogPalette--) | LogPalette nesnesini (bölüm 2.2.17) alır veya ayarlar. |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | LogPalette nesnesini (bölüm 2.2.17) alır veya ayarlar. |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


`EmfCreatePalette` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal palet nesnesinin dizinini belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal palet nesnesinin dizinini belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


LogPalette nesnesini (bölüm 2.2.17) alır veya ayarlar. Bu nesnenin Version alanı 0x0300 olarak ayarlanmalıdır. Bu nesnedeki NumberOfEntries değeri sıfır ise, bu kaydın işlenmesi BAŞARISIZ OLMALIDIR.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


LogPalette nesnesini (bölüm 2.2.17) alır veya ayarlar. Bu nesnenin Version alanı 0x0300 olarak ayarlanmalıdır. Bu nesnedeki NumberOfEntries değeri sıfır ise, bu kaydın işlenmesi BAŞARISIZ OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

