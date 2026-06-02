---
title: "EmfBeginPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هذا السجل يفتح قوس مسار في سياق جهاز التشغيل الحالي."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

يفتح هذا السجل قوس مسار في سياق جهاز التشغيل الحالي. بعد فتح قوس المسار، يمكن للتطبيق بدء معالجة السجلات لتحديد النقاط التي تقع داخل المسار. يجب على التطبيق إغلاق قوس مسار مفتوح بمعالجة سجل EMR\_ENDPATH. عندما يعالج التطبيق سجل EMR\_BEGINPATH، يجب تجاهل جميع المسارات السابقة من سياق جهاز التشغيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | ينشئ مثيلًا جديدًا من الفئة `EmfBeginPath` class. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


ينشئ مثيلًا جديدًا من الفئة `EmfBeginPath` class.

