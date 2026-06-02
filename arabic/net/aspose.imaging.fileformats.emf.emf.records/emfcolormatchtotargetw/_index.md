---
title: "الفئة EmfColorMatchToTargetW"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfColorMatchToTargetW. السجل EMR_COLORMATCHTOTargetW يحدد ما إذا كان يجب إجراء مطابقة الألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف يونيكود."
type: docs
weight: 3430
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
## EmfColorMatchToTargetW class

يسجل EMR_COLORMATCHTOTargetW ما إذا كان يجب إجراء مطابقة ألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode.

```csharp
public sealed class EmfColorMatchToTargetW : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfColorMatchToTargetW](emfcolormatchtotargetw/)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfColorMatchToTargetW`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbdata/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم البيانات الخام لملف تعريف اللون المستهدف، إذا كان موجودًا في حقل Data. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbname/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/data/) { get; set; } | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بالبايت، التي تحدد اسم UTF16-LE والبيانات الخام لملف تعريف اللون المطلوب. |
| [DwAction](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwaction/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد قيمة من تعداد ColorSpace (القسم 2.1.7). |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwflags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد قيمة من تعداد ColorMatchToTarget (القسم 2.1.6). |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/name/) { get; } | يحصل على الاسم |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/rawdata/) { get; } | يحصل على البيانات الخام |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يمكن استخدام سجل EMR_COLORMATCHTOTargetW للتحكم فيما إذا كان يجب تطبيق تحويل اللون الحالي في سياق جهاز التشغيل. إذا كانت قيمة dwAction هي CS_ENABLE، يتم تمكين مطابقة الألوان، ويجب تطبيق تحويل اللون الحالي على عمليات الرسومات اللاحقة. إذا تم تعيين dwAction إلى CS_DISABLE، يجب عدم تطبيق تحويل اللون. بينما تكون مطابقة الألوان إلى الهدف مفعلة بقيمة dwAction = CS_ENABLE، لا تُطبق التغييرات على مساحة اللون أو تخطيط نطاق الألوان. ومع ذلك، يجب أن تُطبق تلك التغييرات عندما يتم تعطيل مطابقة الألوان إلى الهدف. يجب ألا يتم تعيين حقل dwAction إلى CS_DELETE_TRANSFORM إلا إذا كان إدارة الألوان قد تم تمكينها بالفعل بسجل EMR_SETICMMODE (القسم 2.3.11.14).

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


