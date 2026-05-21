---
title: "EmfCreateBrushIndirect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CREATEBRUSHINDIRECT kaydı, grafik işlemleri için mantıksal bir fırça tanımlar."
type: docs
weight: 35
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

EMR_CREATEBRUSHINDIRECT kaydı grafik işlemleri için mantıksal bir fırça tanımlar.

Bu kayıt tarafından tanımlanan mantıksal fırça nesnesi, sonraki grafik işlemlerinde kullanılacak mantıksal fırçayı belirten bir EMR\_SELECTOBJECT kaydı (bölüm 2.3.8.5) ile oynatma cihaz bağlamına seçilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCreateBrushIndirect` sınıfının yeni bir örneğini başlatır. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | `EmfCreateBrushIndirect` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Mantıksal fırça nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhBrush(int value)](#setIhBrush-int-) | Mantıksal fırça nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getLogBrush()](#getLogBrush--) | Mantıksal fırçanın stilini, rengini ve desenini belirten bir LogBrushEx nesnesini (bölüm 2.2.12) alır veya ayarlar. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Mantıksal fırçanın stilini, rengini ve desenini belirten bir LogBrushEx nesnesini (bölüm 2.2.12) alır veya ayarlar. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


`EmfCreateBrushIndirect` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


`EmfCreateBrushIndirect` sınıfının yeni bir örneğini başlatır.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Mantıksal fırça nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu indeks, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Mantıksal fırça nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) indeksini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu indeks, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Mantıksal fırçanın stilini, rengini ve desenini belirten bir LogBrushEx nesnesini (bölüm 2.2.12) alır veya ayarlar. Bu nesnedeki BrushStyle alanı BS\_SOLID, BS\_HATCHED veya BS\_NULL olmalıdır.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Mantıksal fırçanın stilini, rengini ve desenini belirten bir LogBrushEx nesnesini (bölüm 2.2.12) alır veya ayarlar. Bu nesnedeki BrushStyle alanı BS\_SOLID, BS\_HATCHED veya BS\_NULL olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

