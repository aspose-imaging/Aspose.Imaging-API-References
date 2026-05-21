---
title: "EmfPolyDraw16"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYDRAW16 kaydı, bir dizi çizgi segmenti ve Bezier eğrilerini belirtir."
type: docs
weight: 90
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

EMR_POLYDRAW16 kaydı, bir dizi çizgi segmenti ve Bezier eğrisi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfPolyDraw16` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Nokta türlerini belirten Count uzunluğunda bayt dizisini alır veya ayarlar. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Nokta türlerini belirten bir Count uzunluğunda bayt dizisini ayarlar. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


`EmfPolyDraw16` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Nokta türlerini belirten bir Count uzunluğunda bayt dizisini alır veya ayarlar. Bu değer Point (bölüm 2.1.26) numaralandırmasında OLMAK ZORUNDADIR.

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Nokta türlerini belirten bir Count uzunluğunda bayt dizisini ayarlar. Bu değer Point (bölüm 2.1.26) numaralandırmasında OLMAK ZORUNDADIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] | Nokta türlerini belirten bir Count uzunluğunda bayt dizisi. |

