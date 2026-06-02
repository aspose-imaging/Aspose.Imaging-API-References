---
title: "الفئة EmfPlusSetTsGraphics"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTsGraphics. تحدد سجلات EmfPlusSetTSGraphics حالة سياق جهاز الرسوميات لخادم طرفية"
type: docs
weight: 6530
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

سجل EmfPlusSetTSGraphics يحدد حالة سياق جهاز الرسومات لخادم الطرفية.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics/)(EmfPlusRecord) | ينشئ مثيلاً جديدًا للفئة `EmfPlusSetTsGraphics`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد جودة رسم الخط، بما في ذلك نوع مضاد التعرج للخط. يجب أن يكون معرفًا في تعداد SmoothingMode (القسم 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors/) { get; } | يحصل على قيمة تشير إلى ما إذا كان [basic vga colors]. إذا تم التعيين، فإن لوحة الألوان تحتوي فقط على ألوان VGA الأساسية. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. يجب أن يكون قيمة في تعداد CompositingMode (القسم 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد درجة التنعيم التي تُطبق على الخطوط والمنحنيات وحواف المناطق المملوءة لجعلها تبدو أكثر استمرارية أو محددة بحدة. يجب أن يكون قيمة في تعداد CompositingQuality (القسم 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد كيفية تنفيذ التحجيم، بما في ذلك التمدد والتقليص. يجب أن يكون قيمة في تعداد FilterType (القسم 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كان [have palette]. إذا تم التعيين، يحتوي هذا السجل على كائن EmfPlusPalette (القسم 2.2.2.28) في حقل Palette بعد بيانات حالة الرسوميات. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette/) { get; set; } | يحصل أو يعيّن كائن EmfPlusPalette اختياري. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد الجودة العامة لعملية رسم الصورة والنص. يجب أن يكون قيمة في تعداد PixelOffsetMode (القسم 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت، وهو الإحداثي الأفقي للأصل عند رسم مصفوفات halftoning و dithering. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت، وهو الإحداثي الرأسي للأصل عند رسم مصفوفات halftoning و dithering. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح جاما المستخدمة في رسم النصوص المضادة للتعرج وClearType. يجب أن تكون هذه القيمة ضمن النطاق من 0 إلى 12 inclusive. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8‑بت يحدد جودة رسم النص، بما في ذلك نوع مضاد التعرج للنص. يجب أن يكون معرفًا في تعداد TextRenderingHint (القسم 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice/) { get; set; } | يحصل أو يعيّن كائن EmfPlusTransformMatrix 192‑بت (القسم 2.2.2.47) يحدد التحويلات من مساحة العالم إلى مساحة الجهاز. |

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


