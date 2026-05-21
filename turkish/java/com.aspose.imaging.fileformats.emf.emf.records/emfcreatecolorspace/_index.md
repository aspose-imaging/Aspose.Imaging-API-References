---
title: "EmfCreateColorSpace"
second_title: "Aspose.Imaging for Java API Referansı"
description: "The EMR_CREATECOLORSPACE kaydı, ASCII karakterlerinden oluşan bir ada sahip bir renk profili kullanarak mantıksal bir renk uzayı nesnesi oluşturur."
type: docs
weight: 36
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

EMR_CREATECOLORSPACE kaydı, adı ASCII karakterlerinden oluşan bir renk profiliyle mantıksal bir renk uzayı nesnesi oluşturur.

Bu kayıt tarafından tanımlanan mantıksal renk uzayı nesnesi, sonraki grafik işlemlerinde kullanılacak mantıksal renk uzayını tanımlayan bir EMR\\_SETCOLORSPACE kaydı (bölüm 2.3.8.7) aracılığıyla oynatma aygıtı bağlamına seçilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCreateColorSpace` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhCS()](#getIhCS--) | EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setIhCS(int value)](#setIhCS-int-) | EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getLcs()](#getLcs--) | WMF LogColorSpace nesnesini ([MS-WMF] bölüm 2.2.2.11) alır veya ayarlar, bu nesne ASCII karakterlerinden oluşan bir renk profilinin adını belirtebilir. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | WMF LogColorSpace nesnesini ([MS-WMF] bölüm 2.2.2.11) alır veya ayarlar, bu nesne ASCII karakterlerinden oluşan bir renk profilinin adını belirtebilir. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


`EmfCreateColorSpace` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpace getLcs()
```


WMF LogColorSpace nesnesini ([MS-WMF] bölüm 2.2.2.11) alır veya ayarlar, bu nesne ASCII karakterlerinden oluşan bir renk profilinin adını belirtebilir.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


WMF LogColorSpace nesnesini ([MS-WMF] bölüm 2.2.2.11) alır veya ayarlar, bu nesne ASCII karakterlerinden oluşan bir renk profilinin adını belirtebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

