---
title: "EmfSaveDc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس من الحالات التي تم حفظها بواسطة سجلات EMR_SAVEDDC السابقة إذا وجدت."
type: docs
weight: 112
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس من الحالات التي تم حفظها بواسطة سجلات EMR\_SAVEDC السابقة، إذا وجدت. تتكون الحالة من خصائص ورسومات، بما في ذلك ملف bitmap، الفرشاة، لوحة الألوان، الخط، القلم، والمنطقة المحددة حاليًا. يُستخدم سجل EMR\_RESTOREDC لاستعادة الحالة. لا يحدد سجل EMF هذا أي معلمات.

يمكن للمكدس أن يحتوي على معلومات حالة لعدة نسخ من سياق جهاز التشغيل. عند استعادة حالة، يجب التخلص من جميع نسخ الحالة التي تم حفظها مؤخرًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | يقوم بتهيئة نسخة جديدة من الفئة `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfSaveDc`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfSaveDc`.

