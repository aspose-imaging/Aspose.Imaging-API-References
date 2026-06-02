---
title: "EmfPolyBezier"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYBEZIER kaydı bir veya daha fazla Bezier eğrisini belirtir."
type: docs
weight: 85
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

EMR_POLYBEZIER kaydı, bir veya daha fazla Bezier eğrisi belirtir.

Kübik Bezier eğrileri, aPoints alanı tarafından belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır. İlk eğri, ikinci ve üçüncü noktalar kontrol noktası olarak kullanılarak birinci noktadan dördüncü noktaya çizilir. Ardışık dizideki her sonraki eğri tam olarak üç nokta daha gerektirir: önceki eğrinin bitiş noktası başlangıç noktası olarak kullanılır, dizideki sonraki iki nokta kontrol noktalarıdır ve üçüncü nokta bitiş noktasını oluşturur. Kübik Bezier eğrileri, mevcut kalem kullanılarak çizilmelidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfPolyBezier` sınıfının yeni bir örneğini başlatır. |
| [EmfPolyBezier()](#EmfPolyBezier--) | `EmfPolyBezier` sınıfının yeni bir örneğini başlatır. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


`EmfPolyBezier` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


`EmfPolyBezier` sınıfının yeni bir örneğini başlatır.

