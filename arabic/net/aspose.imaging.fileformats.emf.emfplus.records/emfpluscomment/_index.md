---
title: "الفئة EmfPlusComment"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusComment. يُحدِّد سجل EmfPlusComment بيانات خاصة عشوائية."
type: docs
weight: 6000
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
## EmfPlusComment class

سجل EmfPlusComment يحدد بيانات خاصة عشوائية.

```csharp
public sealed class EmfPlusComment : EmfPlusRecord
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusComment](emfpluscomment/)(EmfPlusRecord) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusComment`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت غير مستخدم. يجب ضبط هذا الحقل إلى الصفر ويجب تجاهله عند الاستلام. |
| [PrivateData](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/privatedata/) { get; set; } | يحصل أو يعيّن مصفوفة بايت بطول DataSize من البيانات الخاصة. بايتات من البيانات الخاصة بالسجل التي تلي. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusRecord](../emfplusrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


