---
title: "EmfPolyBezierTo16"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_POLYBEZIERTO16 يحدد منحنى (أو أكثر) بيزيير استنادًا إلى الموضع الحالي."
type: docs
weight: 88
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo16 extends EmfPolyShape
```

سجل EMR\_POLYBEZIERTO16 يحدد منحنى بيزيه واحد أو أكثر بناءً على الموقع الحالي.

يتم تعريف منحنيات بيزيير المكعبة باستخدام نقاط النهاية ونقاط التحكم المحددة في الحقل aPoints. يتم رسم المنحنى الأول من النقطة الأولى إلى النقطة الرابعة، باستخدام النقطة الثانية والثالثة كنقاط تحكم. كل منحنى لاحق في التسلسل يحتاج إلى ثلاث نقاط إضافية بالضبط: تُستخدم نقطة النهاية للمنحنى السابق كنقطة بداية، والنقطتان التاليتان في التسلسل كنقاط تحكم، والنقطة الثالثة هي نقطة النهاية. SHOULD أن تُرسم منحنيات بيزيير المكعبة باستخدام القلم الحالي
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPolyBezierTo16(EmfRecord record)](#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بإنشاء نسخة جديدة من الفئة `EmfPolyBezierTo16`. |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16--) | يقوم بإنشاء نسخة جديدة من الفئة `EmfPolyBezierTo16`. |
### EmfPolyBezierTo16(EmfRecord record) {#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo16(EmfRecord record)
```


يقوم بإنشاء نسخة جديدة من الفئة `EmfPolyBezierTo16`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | السجل. |

### EmfPolyBezierTo16() {#EmfPolyBezierTo16--}
```
public EmfPolyBezierTo16()
```


يقوم بإنشاء نسخة جديدة من الفئة `EmfPolyBezierTo16`.

