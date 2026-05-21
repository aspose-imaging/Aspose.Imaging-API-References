---
title: "الفئة EmfMetafileHeaderExtension2"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMetafileHeaderExtension2. سجل EmfMetafileHeaderExtension2 هو سجل الرأس المستخدم في الامتداد الثاني لملفات EMF. بعد حقل EmfHeaderExtension2 تكون الحقول المتبقية اختيارية ويمكن أن تكون موجودة بأي ترتيب."
type: docs
weight: 3930
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---
## EmfMetafileHeaderExtension2 class

سجل EmfMetafileHeaderExtension2 هو سجل الرأس المستخدم في الامتداد الثاني لملفات EMF الوصفية. بعد حقل EmfHeaderExtension2، تكون الحقول المتبقية اختيارية ويمكن أن تظهر بأي ترتيب.

```csharp
public sealed class EmfMetafileHeaderExtension2 : EmfMetafileHeaderExtension1
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfMetafileHeaderExtension2](emfmetafileheaderextension2/#constructor)(EmfMetafileHeaderExtension1) | يُنشئ مثيلًا جديدًا للفئة `EmfMetafileHeaderExtension2`. |
| [EmfMetafileHeaderExtension2](emfmetafileheaderextension2/#constructor_1)(EmfMetafileHeaderExtension2) | يُنشئ مثيلًا جديدًا للفئة `EmfMetafileHeaderExtension2`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription/) { get; set; } | يحصل أو يعيّن وصف EMF. سلسلة Unicode UTF16-LE منتهية بصفر، اختيارية، بطول ومحتوى عشوائي. موقعها في السجل وعدد الأحرف محددان بواسطة حقلي offDescription و nDescription، على التوالي، في EmfHeader. إذا كانت قيمة أي من الحقلين صفرًا، فلا توجد سلسلة وصف. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer/) { get; set; } | يحصل أو يعيّن مخزن وصف EMF. مصفوفة اختيارية من البايتات تحتوي على سلسلة وصف EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeader. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" هو اختياري ويجب تجاهله. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader/) { get; set; } | يحصل أو يعيّن كائن Header (القسم 2.2.9)، الذي يحتوي على معلومات حول محتوى وبنية ملف الميتافيل. |
| [EmfHeaderExtension1](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfheaderextension1/) { get; set; } | يحصل أو يعيّن كائن HeaderExtension1، الذي يحدد معلومات إضافية حول الصورة في ملف الميتافيل. |
| [EmfHeaderExtension2](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/emfheaderextension2/) { get; set; } | يحصل أو يعيّن كائن HeaderExtension2، الذي يحدد معلومات إضافية حول الصورة في ملف الميتا. |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على باقي سجل رأس EMF. يجب أن يكون حجم هذا الحقل مضاعفًا لعدد 4 بايتات. |
| [EmfPixelFormatBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfpixelformatbuffer/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على موصِّف تنسيق بكسل EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeaderExtension1 أو مع سلسلة وصف EMF. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" هو اختياري ويجب تجاهله. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfMetafileHeaderExtension1](../emfmetafileheaderextension1/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


