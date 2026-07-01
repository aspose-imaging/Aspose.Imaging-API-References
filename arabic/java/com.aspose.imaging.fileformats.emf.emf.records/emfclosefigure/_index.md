---
title: "EmfCloseFigure"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هذا السجل يغلق شكلًا مفتوحًا في مسار."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

يقوم هذا السجل بإغلاق شكل مفتوح في مسار. يجب أن يغلق معالجة سجل EMR\_CLOSEFIGURE الشكل عن طريق رسم خط من الموقع الحالي إلى النقطة الأولى للشكل، ثم يجب أن يربط الخطوط باستخدام نمط وصل الخط. إذا تم إغلاق الشكل بمعالجة سجل EMR\_LINETO بدلاً من سجل EMR\_CLOSEFIGURE، تُستخدم أغطية النهاية لإنشاء الزاوية بدلاً من الوصل. يُحدد EMR\_LINETO في القسم 2.3.5.13. يجب أن يُستخدم سجل EMR\_CLOSEFIGURE فقط إذا كان هناك قوس مسار مفتوح في سياق جهاز التشغيل. يكون الشكل في مسار مفتوحًا ما لم يتم إغلاقه صراحةً بمعالجة هذا السجل.

ملاحظة: يمكن أن يكون الشكل مفتوحًا حتى إذا كانت النقطة الحالية ونقطة بدء الشكل هي نفسها. بعد معالجة سجل EMR\_CLOSEFIGURE، يجب أن يبدأ إضافة خط أو منحنى إلى المسار شكلًا جديدًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | ينشئ مثلاً جديداً من الفئة `EmfCloseFigure`. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


ينشئ مثلاً جديداً من الفئة `EmfCloseFigure`.

