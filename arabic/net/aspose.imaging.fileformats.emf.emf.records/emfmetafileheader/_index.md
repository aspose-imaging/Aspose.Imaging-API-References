---
title: "الفئة EmfMetafileHeader"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMetafileHeader. أنواع سجلات EMR_HEADER تحدد نقاط البداية لملفات EMF وتحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل ملف التعريف. تجعل المعلومات في سجل الرأس من الممكن أن تكون ملفات EMF مستقلة عن أي جهاز إخراج محدد. يمكن استخدام قيمة حقل Size للتمييز بين أنواع سجلات EMR_HEADER المختلفة المذكورة سابقًا في هذا القسم. هناك ثلاثة رؤوس محتملة: الرأس الأساسي وهو سجل EmfMetafileHeader. الجزء الثابت من هذا الرأس يبلغ 88 بايت ويحتوي على كائن Header. الرأس الأول للامتداد وهو سجل EmfMetafileHeaderExtension1. الجزء الثابت من هذا الرأس يبلغ 100 بايت ويحتوي على كائن Header وكائن HeaderExtension1 (القسم 2.2.10). الرأس الثاني للامتداد وهو سجل EmfMetafileHeaderExtension2. الجزء الثابت من هذا الرأس يبلغ 108 بايت ويحتوي على كائن Header وكائن HeaderExtension1 وكائن HeaderExtension2 (القسم 2.2.11)."
type: docs
weight: 3910
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

أنواع سجلات EMR_HEADER تحدد نقاط البداية لملفات EMF الوصفية وتحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل الملف الوصفي. تجعل المعلومات في سجل الرأس ملفات EMF مستقلة عن أي جهاز إخراج محدد. يمكن استخدام قيمة حقل Size للتمييز بين أنواع سجلات EMR_HEADER المختلفة المذكورة سابقًا في هذا القسم. هناك ثلاثة رؤوس محتملة: الرأس الأساسي، وهو سجل EmfMetafileHeader. الجزء ثابت الحجم من هذا الرأس هو 88 بايت، ويحتوي على كائن Header. رأس الامتداد الأول، وهو سجل EmfMetafileHeaderExtension1. الجزء ثابت الحجم من هذا الرأس هو 100 بايت، ويحتوي على كائن Header وكائن HeaderExtension1 (القسم 2.2.10). رأس الامتداد الثاني، وهو سجل EmfMetafileHeaderExtension2. الجزء ثابت الحجم من هذا الرأس هو 108 بايت، ويحتوي على كائن Header، وكائن HeaderExtension1، وكائن HeaderExtension2 (القسم 2.2.11).

```csharp
public class EmfMetafileHeader : EmfRecord
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfMetafileHeader`. |
| [EmfMetafileHeader](emfmetafileheader/#constructor_1)(EmfMetafileHeader) | ينشئ مثيلًا جديدًا للفئة `EmfMetafileHeader`. |
| [EmfMetafileHeader](emfmetafileheader/#constructor_2)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfMetafileHeader`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription/) { get; set; } | يحصل أو يعيّن وصف EMF. سلسلة Unicode UTF16-LE منتهية بصفر، اختيارية، بطول ومحتوى عشوائي. موقعها في السجل وعدد الأحرف محددان بواسطة حقلي offDescription و nDescription، على التوالي، في EmfHeader. إذا كانت قيمة أي من الحقلين صفرًا، فلا توجد سلسلة وصف. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer/) { get; set; } | يحصل أو يعيّن مخزن وصف EMF. مصفوفة اختيارية من البايتات تحتوي على سلسلة وصف EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeader. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" هو اختياري ويجب تجاهله. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader/) { get; set; } | يحصل أو يعيّن كائن Header (القسم 2.2.9)، الذي يحتوي على معلومات حول محتوى وبنية ملف الميتافيل. |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على باقي سجل رأس EMF. يجب أن يكون حجم هذا الحقل مضاعفًا لعدد 4 بايتات. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


