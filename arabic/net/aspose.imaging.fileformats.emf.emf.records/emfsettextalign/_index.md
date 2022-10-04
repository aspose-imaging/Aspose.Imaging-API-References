---
title: EmfSetTextAlign
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EMR_SETTEXTALIGN محاذاة النص.
type: docs
weight: 4490
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
## EmfSetTextAlign class

يحدد سجل EMR_SETTEXTALIGN محاذاة النص.

```csharp
public sealed class EmfSetTextAlign : EmfStateRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfSetTextAlign](emfsettextalign#constructor)() | يقوم بتهيئة مثيل جديد لملف[`EmfSetTextAlign`](../emfsettextalign) فئة . |
| [EmfSetTextAlign](emfsettextalign#constructor_1)(EmfRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfSetTextAlign`](../emfsettextalign) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | الحصول على أو تحديد حجم السجل |
| [TextAlignmentMode](../../aspose.imaging.fileformats.emf.emf.records/emfsettextalign/textalignmentmode) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد محاذاة النص بواسطة باستخدام قناع إشارات محاذاة النص. هذه إما[`WmfTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags) ([MS-WMF] القسم 2.1.2.3) للنص ذي خط الأساس الأفقي ، أو[`WmfVerticalTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags) (القسم [MS-WMF] 2.1.2.4) للنص ذي خط الأساس العمودي . يمكن اختيار قيمة واحدة فقط من تلك التي تؤثر على المحاذاة الأفقية والعمودية. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | الحصول على النوع أو تحديده. |

### ملاحظات

تستخدم سجلات EMR_SMALLTEXTOUT و EMR_EXTTEXTOUTA و EMR_EXTTEXTOUTW قيم المحاذاة text لوضع سلسلة نصية على وسيط الإخراج. تحدد القيم العلاقة بين نقطة مرجعية ومستطيل يحد النص. النقطة المرجعية هي إما الموضع الحالي أو النقطة التي تم تمريرها إلى سجل إخراج النص. يتكون المستطيل الذي يحد النص من خلايا الأحرف في السلسلة النصية.

### أنظر أيضا

* class [EmfStateRecordType](../emfstaterecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->