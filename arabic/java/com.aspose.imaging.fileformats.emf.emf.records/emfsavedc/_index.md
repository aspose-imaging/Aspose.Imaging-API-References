---
title: "EmfSaveDc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس الحالات التي تم حفظها بواسطة سجلات EMR_SAVEDC السابقة إن وجدت."
type: docs
weight: 112
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس الحالات التي تم حفظها بواسطة سجلات EMR\_SAVEDC السابقة، إن وجدت. تتكون الحالة من خصائص ورسومات كائنات، بما في ذلك الصورة النقطية، الفرشاة، اللوحة، الخط، القلم، والمنطقة المحددة حاليًا. يُستخدم سجل EMR\_RESTOREDC لاستعادة الحالة. لا يحدد سجل EMF هذا أي معلمات.

يمكن للمكدس أن يحتوي على معلومات حالة لعدة نسخ من سياق جهاز التشغيل. عند استعادة حالة، يجب التخلص من جميع نسخ الحالة التي تم حفظها مؤخرًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُهيئ نسخة جديدة من الفئة `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | يُهيئ نسخة جديدة من الفئة `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


يُهيئ نسخة جديدة من الفئة `EmfSaveDc`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


يُهيئ نسخة جديدة من الفئة `EmfSaveDc`.

