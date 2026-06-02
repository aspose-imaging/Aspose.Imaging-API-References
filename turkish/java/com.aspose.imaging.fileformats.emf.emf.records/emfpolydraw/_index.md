---
title: "EmfPolyDraw"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYDRAW kaydı, bir dizi çizgi segmenti ve Bezier eğrilerini belirtir."
type: docs
weight: 89
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

EMR_POLYDRAW kaydı, bir dizi çizgi segmenti ve Bezier eğrisi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfPolyDraw` sınıfının yeni bir örneğini başlatır. |
| [EmfPolyDraw()](#EmfPolyDraw--) | [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Count uzunluğunda bayt değerleri dizisini alır; bu dizi, Gets or sets aPoints dizisindeki her noktanın nasıl kullanılacağını belirtir. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Count uzunluğunda bayt değerleri dizisini ayarlar; bu dizi, Gets or sets aPoints dizisindeki her noktanın nasıl kullanılacağını belirtir. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


`EmfPolyDraw` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


[EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) sınıfının yeni bir örneğini başlatır.

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Count uzunluğunda bayt değerleri dizisini alır; bu dizi, Gets or sets aPoints dizisindeki her noktanın nasıl kullanılacağını belirtir. Bu değer POINT (bölüm 2.1.26) enumerasyonunda olmalıdır.

**Returns:**
byte[] - Count uzunluğunda bayt değerleri dizisi; bu dizi, Gets or sets aPoints dizisindeki her noktanın nasıl kullanılacağını belirtir.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Count uzunluğunda bayt değerleri dizisini ayarlar; bu dizi, Gets or sets aPoints dizisindeki her noktanın nasıl kullanılacağını belirtir. Bu değer POINT (bölüm 2.1.26) enumerasyonunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] | Gets or sets aPoints dizisindeki her noktanın nasıl kullanılacağını belirten Count uzunluğunda bayt değerleri dizisi. |

