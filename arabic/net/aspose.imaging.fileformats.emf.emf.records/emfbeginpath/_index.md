---
title: "الفئة EmfBeginPath"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBeginPath فئة. هذا السجل يفتح قوس مسار في سياق جهاز التشغيل الحالي. بعد فتح قوس المسار يمكن للتطبيق بدء معالجة السجلات لتحديد النقاط التي تقع داخل المسار. يجب على التطبيق إغلاق قوس المسار المفتوح بمعالجة سجل EMR_ENDPATH. عندما يعالج التطبيق سجل EMR_BEGINPATH يجب تجاهل جميع المسارات السابقة من سياق جهاز التشغيل."
type: docs
weight: 3330
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
## EmfBeginPath class

يفتح هذا السجل قوس مسار في سياق جهاز التشغيل الحالي. بعد فتح قوس المسار، يمكن للتطبيق بدء معالجة السجلات لتحديد النقاط الموجودة في المسار. يجب على التطبيق إغلاق قوس مسار مفتوح بمعالجة سجل EMR_ENDPATH. عند معالجة التطبيق لسجل EMR_BEGINPATH، يجب إلغاء جميع المسارات السابقة من سياق جهاز التشغيل.

```csharp
public sealed class EmfBeginPath : EmfPathBracketRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfBeginPath](emfbeginpath/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


