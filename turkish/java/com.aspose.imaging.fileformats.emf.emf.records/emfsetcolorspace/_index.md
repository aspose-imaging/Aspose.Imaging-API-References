---
title: "EmfSetColorSpace"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETCOLORSPACE kaydı, grafik işlemleri için geçerli mantıksal renk uzayı nesnesini tanımlar."
type: docs
weight: 123
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

EMR\_SETCOLORSPACE kaydı, grafik işlemleri için mevcut mantıksal renk uzayı nesnesini tanımlar.

Bu kayıt tarafından tanımlanan mantıksal renk uzayı nesnesi, sonraki EMF kayıtları tarafından belirtilen çizim işlemlerinde KULLANILMALI, ya başka bir mantıksal renk uzayı nesnesi başka bir EMR\_SETCOLORSPACE kaydıyla belirtilene kadar ya da nesne bir EMR\_DELETECOLORSPACE kaydıyla kaldırılana kadar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetColorSpace` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhCS()](#getIhCS--) | EMF Nesne Tablosunda (bölüm 3.1.1.1) mantıksal bir renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhCS(int value)](#setIhCS-int-) | EMF Nesne Tablosunda (bölüm 3.1.1.1) mantıksal bir renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


`EmfSetColorSpace` sınıfının yeni bir örneğini başlatır.

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

