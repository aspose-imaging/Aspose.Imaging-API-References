---
title: "الفئة EmfSetTextAlign"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetTextAlign. سجل EMR_SETTEXTALIGN يحدد محاذاة النص."
type: docs
weight: 4610
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
## EmfSetTextAlign class

سجل EMR_SETTEXTALIGN يحدد محاذاة النص.

```csharp
public sealed class EmfSetTextAlign : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetTextAlign](emfsettextalign/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `EmfSetTextAlign`. |
| [EmfSetTextAlign](emfsettextalign/#constructor_1)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfSetTextAlign`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [TextAlignmentMode](../../aspose.imaging.fileformats.emf.emf.records/emfsettextalign/textalignmentmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد محاذاة النص باستخدام قناع من أعلام محاذاة النص. هذه إما [`WmfTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/) ([MS-WMF] القسم 2.1.2.3) للنص ذو الخط الأفقي، أو [`WmfVerticalTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/) ([MS-WMF] القسم 2.1.2.4) للنص ذو الخط العمودي. يمكن اختيار قيمة واحدة فقط من تلك التي تؤثر على المحاذاة الأفقية والعمودية. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

تستخدم سجلات EMR_SMALLTEXTOUT و EMR_EXTTEXTOUTA و EMR_EXTTEXTOUTW قيم محاذاة النص لتحديد موضع سلسلة نصية على وسط الإخراج. تحدد القيم العلاقة بين نقطة المرجع والمستطيل الذي يحد النص. تكون نقطة المرجع إما الموضع الحالي أو نقطة يتم تمريرها إلى سجل إخراج النص. المستطيل الذي يحد النص يتكون من خلايا الأحرف في سلسلة النص.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


