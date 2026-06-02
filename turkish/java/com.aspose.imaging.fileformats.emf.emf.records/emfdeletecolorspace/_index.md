---
title: "EmfDeleteColorSpace"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_DELETECOLORSPACE kaydı, mantıksal bir renk uzayı nesnesini siler."
type: docs
weight: 42
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

EMR_DELETECOLORSPACE kaydı mantıksal bir renk uzayı nesnesini siler.

Mantıksal bir renk uzayı nesnesini silmek için EMR\_DELETECOLORSPACE yerine bir EMR\_DELETEOBJECT kaydı KULLANILMALIDIR.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfDeleteColorSpace` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhCS()](#getIhCS--) | EMF Nesne Tablosunda (bölüm 3.1.1.1) mantıksal bir renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhCS(int value)](#setIhCS-int-) | EMF Nesne Tablosunda (bölüm 3.1.1.1) mantıksal bir renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


`EmfDeleteColorSpace` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


EMF Nesne Tablosunda (bölüm 3.1.1.1) mantıksal bir renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

Bu nesne, bir WMF LogColorSpace veya LogColorSpaceW nesnesidir ([MS-WMF] bölümleri 2.2.2.11 ve 2.2.2.12, sırasıyla).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


EMF Nesne Tablosunda (bölüm 3.1.1.1) mantıksal bir renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

Bu nesne, bir WMF LogColorSpace veya LogColorSpaceW nesnesidir ([MS-WMF] bölümleri 2.2.2.11 ve 2.2.2.12, sırasıyla).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

