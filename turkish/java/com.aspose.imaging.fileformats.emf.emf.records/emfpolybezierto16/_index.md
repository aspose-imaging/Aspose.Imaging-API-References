---
title: "EmfPolyBezierTo16"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYBEZIERTO16 kaydı, geçerli konuma dayanarak bir veya daha fazla Bezier eğrisi tanımlar."
type: docs
weight: 88
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo16 extends EmfPolyShape
```

EMR_POLYBEZIERTO16 kaydı, mevcut konuma dayanarak bir veya daha fazla Bezier eğrisi belirtir.

Kübik Bezier eğrileri, aPoints alanı tarafından belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır. İlk eğri, ikinci ve üçüncü noktalar kontrol noktası olarak kullanılarak birinci noktadan dördüncü noktaya çizilir. Ardışık dizideki her sonraki eğri tam olarak üç nokta daha gerektirir: önceki eğrinin bitiş noktası başlangıç noktası olarak kullanılır, dizideki sonraki iki nokta kontrol noktalarıdır ve üçüncü nokta bitiş noktasını oluşturur. Kübik Bezier eğrileri, mevcut kalem kullanılarak çizilmelidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyBezierTo16(EmfRecord record)](#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfPolyBezierTo16` sınıfının örneğini başlatır. |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16--) | Yeni bir `EmfPolyBezierTo16` sınıfının örneğini başlatır. |
### EmfPolyBezierTo16(EmfRecord record) {#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo16(EmfRecord record)
```


Yeni bir `EmfPolyBezierTo16` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kayıt. |

### EmfPolyBezierTo16() {#EmfPolyBezierTo16--}
```
public EmfPolyBezierTo16()
```


Yeni bir `EmfPolyBezierTo16` sınıfının örneğini başlatır.

