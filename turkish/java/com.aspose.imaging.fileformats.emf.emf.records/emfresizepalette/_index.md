---
title: "EmfResizePalette"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_RESIZEPALETTE kaydı, mevcut bir LogPalette nesnesinin boyutunu (bölüm 2.2.17) artırır veya azaltır."
type: docs
weight: 108
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

EMR\_RESIZEPALETTE kaydı, mevcut bir LogPalette nesnesinin (bölüm 2.2.17) boyutunu artırır veya azaltır.

LogPalette nesnesinin yeni boyutu, bu yapının NumberOfEntries alanında YANSITILMELİDİR.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfResizePalette` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhPal()](#getIhPal--) | EMF Nesne Tablosundaki (bölüm 3.1.1.1) palet nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhPal(int value)](#setIhPal-int-) | EMF Nesne Tablosundaki (bölüm 3.1.1.1) palet nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


`EmfResizePalette` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


EMF Nesne Tablosundaki (bölüm 3.1.1.1) palet nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


EMF Nesne Tablosundaki (bölüm 3.1.1.1) palet nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

