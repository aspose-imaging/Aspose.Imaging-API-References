---
title: "EmfPolyBezier"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_POLYBEZIER يحدد منحنى بيزيه واحد أو أكثر."
type: docs
weight: 85
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

سجل EMR\_POLYBEZIER يحدد منحنى بيزيه واحد أو أكثر.

يتم تعريف منحنيات بيزيير المكعبة باستخدام نقاط النهاية ونقاط التحكم المحددة في الحقل aPoints. يتم رسم المنحنى الأول من النقطة الأولى إلى النقطة الرابعة، باستخدام النقطة الثانية والثالثة كنقاط تحكم. كل منحنى لاحق في التسلسل يحتاج إلى ثلاث نقاط إضافية بالضبط: تُستخدم نقطة النهاية للمنحنى السابق كنقطة بداية، والنقطتان التاليتان في التسلسل كنقاط تحكم، والنقطة الثالثة هي نقطة النهاية. SHOULD أن تُرسم منحنيات بيزيير المكعبة باستخدام القلم الحالي
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfPolyBezier`. |
| [EmfPolyBezier()](#EmfPolyBezier--) | يُنشئ مثيلًا جديدًا من الفئة `EmfPolyBezier`. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPolyBezier`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPolyBezier`.

