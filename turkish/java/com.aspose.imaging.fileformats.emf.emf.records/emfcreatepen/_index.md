---
title: "EmfCreatePen"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CREATEPEN kaydı, grafik işlemleri için mantıksal bir kalem tanımlar."
type: docs
weight: 41
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

EMR_CREATEPEN kaydı grafik işlemleri için mantıksal bir kalem tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCreatePen` sınıfının yeni bir örneğini başlatır. |
| [EmfCreatePen()](#EmfCreatePen--) | `EmfCreatePen` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhPen()](#getIhPen--) | EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal kalem nesnesinin dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setIhPen(int value)](#setIhPen-int-) | EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal kalem nesnesinin dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getLogPen()](#getLogPen--) | Mantıksal kalemin stilini, genişliğini ve rengini belirten bir LogPen nesnesini (bölüm 2.2.19) alır veya ayarlar. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Mantıksal kalemin stilini, genişliğini ve rengini belirten bir LogPen nesnesini (bölüm 2.2.19) alır veya ayarlar. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


`EmfCreatePen` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


`EmfCreatePen` sınıfının yeni bir örneğini başlatır.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal kalem nesnesinin dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


EMF Nesne Tablosu (bölüm 3.1.1.1) içinde mantıksal kalem nesnesinin dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Mantıksal kalemin stilini, genişliğini ve rengini belirten bir LogPen nesnesini (bölüm 2.2.19) alır veya ayarlar.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Mantıksal kalemin stilini, genişliğini ve rengini belirten bir LogPen nesnesini (bölüm 2.2.19) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

