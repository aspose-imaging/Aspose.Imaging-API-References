---
title: "EmfPolyBezier16"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYBEZIER16 kaydı bir veya daha fazla Bezier eğrisi belirtir."
type: docs
weight: 86
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier16 extends EmfPolyShape
```

EMR\_POLYBEZIER16 kaydı bir veya daha fazla Bezier eğrisi belirtir. Eğriler mevcut kalem kullanılarak çizilir.

Kübik Bezier eğrileri, aPoints alanı tarafından belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır. İlk eğri, ikinci ve üçüncü noktalar kontrol noktası olarak kullanılarak birinci noktadan dördüncü noktaya çizilir. Ardışık dizideki her sonraki eğri tam olarak üç nokta daha gerektirir: önceki eğrinin bitiş noktası başlangıç noktası olarak kullanılır, dizideki sonraki iki nokta kontrol noktalarıdır ve üçüncü nokta bitiş noktasını oluşturur. Kübik Bezier eğrileri, mevcut kalem kullanılarak çizilmelidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyBezier16(EmfRecord source)](#EmfPolyBezier16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfPolyBezier16` sınıfı örneği başlatır. |
| [EmfPolyBezier16()](#EmfPolyBezier16--) | Yeni bir `EmfPolyBezier16` sınıfı örneği başlatır. |
### EmfPolyBezier16(EmfRecord source) {#EmfPolyBezier16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier16(EmfRecord source)
```


Yeni bir `EmfPolyBezier16` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPolyBezier16() {#EmfPolyBezier16--}
```
public EmfPolyBezier16()
```


Yeni bir `EmfPolyBezier16` sınıfı örneği başlatır.

