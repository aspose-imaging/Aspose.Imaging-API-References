---
title: "الفئة EmfCloseFigure"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCloseFigure الفئة. هذا السجل يغلق شكلاً مفتوحًا في مسار. يجب أن يغلق سجل EMR_CLOSEFIGURE الشكل عن طريق رسم خط من الموضع الحالي إلى النقطة الأولى للشكل ثم يجب أن يربط الخطوط باستخدام نمط وصل الخط. إذا تم إغلاق الشكل بمعالجة سجل EMR_LINETO بدلاً من سجل EMR_CLOSEFIGURE، تُستخدم نهايات الخط لإنشاء الزاوية بدلاً من الوصل. يُحدد EMR_LINETO في القسم 2.3.5.13. يجب أن يُستخدم سجل EMR_CLOSEFIGURE فقط إذا كان هناك قوس مسار مفتوح في سياق جهاز التشغيل. الشكل في المسار يكون مفتوحًا ما لم يُغلق صراحةً بمعالجة هذا السجل."
type: docs
weight: 3410
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
## EmfCloseFigure class

يغلق هذا السجل شكلًا مفتوحًا في مسار. يجب أن يغلق سجل EMR_CLOSEFIGURE الشكل عن طريق رسم خط من الموضع الحالي إلى أول نقطة في الشكل، ثم يجب ربط الخطوط باستخدام نمط وصل الخط. إذا تم إغلاق الشكل بمعالجة سجل EMR_LINETO بدلاً من سجل EMR_CLOSEFIGURE، تُستخدم نهايات الخط لإنشاء الزاوية بدلاً من الوصل. يُحدد EMR_LINETO في القسم 2.3.5.13. يجب استخدام سجل EMR_CLOSEFIGURE فقط إذا كان هناك قوس مسار مفتوح في سياق جهاز التشغيل. يظل الشكل في المسار مفتوحًا ما لم يتم إغلاقه صراحةً بمعالجة هذا السجل.

```csharp
public sealed class EmfCloseFigure : EmfPathBracketRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCloseFigure](emfclosefigure/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

ملاحظة: يمكن أن يكون الشكل مفتوحًا حتى إذا كان النقطة الحالية ونقطة بدء الشكل هي نفسها. بعد معالجة سجل EMR_CLOSEFIGURE، يجب أن يبدأ إضافة خط أو منحنى إلى المسار شكلًا جديدًا.

### انظر أيضًا

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


