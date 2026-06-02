---
title: "EmfPolyBezierTo"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_POLYBEZIERTO يحدد منحنى بيزيير واحد أو أكثر بناءً على الموضع الحالي."
type: docs
weight: 87
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo extends EmfPolyShape
```

سجل EMR\_POLYBEZIERTO يحدد منحنى بيزيه واحد أو أكثر بناءً على الموقع الحالي.

يتم تعريف منحنيات بيزيير المكعبة باستخدام نقاط النهاية ونقاط التحكم المحددة في الحقل aPoints. يتم رسم المنحنى الأول من النقطة الأولى إلى النقطة الرابعة، باستخدام النقطة الثانية والثالثة كنقاط تحكم. كل منحنى لاحق في التسلسل يحتاج إلى ثلاث نقاط إضافية بالضبط: تُستخدم نقطة النهاية للمنحنى السابق كنقطة بداية، والنقطتان التاليتان في التسلسل كنقاط تحكم، والنقطة الثالثة هي نقطة النهاية. SHOULD أن تُرسم منحنيات بيزيير المكعبة باستخدام القلم الحالي
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPolyBezierTo(EmfRecord source)](#EmfPolyBezierTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPolyBezierTo`. |
| [EmfPolyBezierTo()](#EmfPolyBezierTo--) | ينشئ مثيلًا جديدًا من الفئة `EmfPolyBezierTo`. |
### EmfPolyBezierTo(EmfRecord source) {#EmfPolyBezierTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPolyBezierTo`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfPolyBezierTo() {#EmfPolyBezierTo--}
```
public EmfPolyBezierTo()
```


ينشئ مثيلًا جديدًا من الفئة `EmfPolyBezierTo`.

