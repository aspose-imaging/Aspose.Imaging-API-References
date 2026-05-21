---
title: "الفئة EmfEof"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfEof. سجل EMR_EOF يشير إلى نهاية ملف التعريف ويحدد لوحة ألوان."
type: docs
weight: 3690
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---
## EmfEof class

سجل EMR_EOF يشير إلى نهاية ملف الميتا ويحدد لوحة ألوان.

```csharp
public sealed class EmfEof : EmfControlRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfEof](emfeof/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfEof`. |
| [EmfEof](emfeof/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfEof`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PaletteArgb32Entries](../../aspose.imaging.fileformats.emf.emf.records/emfeof/paletteargb32entries/) { get; set; } | يحصل أو يعيّن مخزنًا اختياريًا يحتوي على بيانات لوحة الألوان، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR_EOF. بناءً على ذلك، الحقول في هذا المخزن التي تم تسميةها "UndefinedSpace" هي اختيارية ويجب تجاهلها. يجب أن يكون حجم هذا الحقل مضاعفًا لعدد 4 بايت. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SizeLast](../../aspose.imaging.fileformats.emf.emf.records/emfeof/sizelast/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يجب أن يكون مساويًا لـ Size ويجب أن يكون الحقل الأخير في السجل وبالتالي في ملف التعريف. يجب أن تسبق كائنات LogPaletteEntry، إذا وجدت، هذا الحقل. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfControlRecordType](../emfcontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


