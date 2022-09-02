---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EmfPlusSetTSGraphics حالة سياق جهاز الرسومات لوحدة خدمة المحطة الطرفية.
type: docs
weight: 6410
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

يحدد سجل EmfPlusSetTSGraphics حالة سياق جهاز الرسومات لوحدة خدمة المحطة الطرفية.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد جودة عرض الخط ، بما في ذلك نوع تنعيم الخط. يجب تعريفه في تعداد SmoothingMode (القسم 2.1.1.28) . |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | يحصل على قيمة تشير إلى ما إذا كانت [ألوان vga الأساسية] . في حالة الضبط ، تحتوي اللوحة على ألوان VGA الأساسية فقط. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. يجب أن تكون قيمة في CompositingMode enumeration (القسم 2.1.1.5) . |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد درجة التجانس لتطبيقها على الخطوط والمنحنيات وحواف المساحات المعبأة لجعلها تظهر بشكل أكبر مستمر أو محدد بشكل حاد. يجب أن تكون قيمة في تعداد جودة التركيب (القسم 2.1.1.6) . |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت والذي يجب أن يحدد عدد 32 بت المحاذي للعدد بايت من البيانات في حقل RecordData التالي. لا يتضمن هذا الرقم رأس السجل 12 بايت. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد كيفية إجراء القياس ، بما في ذلك stretching and shrinking. يجب أن تكون قيمة في تعداد نوع المرشح (القسم 2.1.1.11) . |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وبنية السجل. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | يحصل على قيمة تشير إلى [تحتوي على لوحة] . إذا تم تعيينه ، فإن هذا السجل يحتوي على كائن EmfPlusPalette (القسم 2.2.2.28) في حقل اللوحة الذي يتبع بيانات حالة الرسومات. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | الحصول على أو تعيين كائن EmfPlusPalette اختياري. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد الجودة الإجمالية للصورة وعملية عرض النص. يجب أن تكون قيمة في تعداد PixelOffsetMode (القسم 2.1.1.26) . |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 16 بت ، وهو الإحداثي الأفقي لأصل لعرض مصفوفات الألوان النصفية وثبات الألوان. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 16 بت ، وهو الإحداثي الرأسي للأصل لعرض مصفوفات الألوان النصفية وثبات الألوان. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد محاذاة 32 بت من بايت في السجل بأكمله ، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد قيمة تصحيح جاما المستخدمة لتقديم نص مصقول ونص ClearType. يجب أن تكون هذه القيمة في النطاق من 0 إلى 12 ، ضمناً . |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد جودة عرض text ، بما في ذلك نوع صقل النص. يجب أن يتم تعريفه في تعداد TextRenderingHint (القسم 2.1.1.32) . |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | الحصول على عدد صحيح بدون إشارة 16 بت يحدد نوع السجل. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | الحصول على أو تعيين كائن EmfPlusTransformMatrix 192 بت (القسم 2.2.2.47) الذي يحدد مساحة العالم لتحويل مساحة الجهاز. |

### أنظر أيضا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
