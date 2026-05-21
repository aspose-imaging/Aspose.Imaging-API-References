---
title: "الفئة EmfLogFontPanose"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogFontPanose class. يحدد كائن LogFontPanose خصائص PANOSE لخط منطقي."
type: docs
weight: 3150
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
## EmfLogFontPanose class

كائن LogFontPanose يحدد خصائص PANOSE لخط منطقي.

```csharp
public sealed class EmfLogFontPanose : EmfLogFont
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfLogFontPanose](emflogfontpanose/)(EmfLogFont) | يُنشئ مثيلًا جديدًا من الفئة `EmfLogFontPanose`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 8‑بت يحدد مجموعة رموز الأحرف. يجب أن تكون القيمة قيمة في تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كانت مجموعة الأحرف غير معروفة، يجب ألا تحاول معالجة ملف الميتا ترجمة أو تفسير السلاسل التي تم عرضها بهذا الخط. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 8‑بت يحدد دقة القص. تحدد دقة القص كيفية قص الأحرف التي هي جزئياً خارج منطقة القص. يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision. |
| [Culture](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/culture/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يُضبط على الصفر ويجب تجاهله. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement/) { get; set; } | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. متجه الإزاحة موازٍ لخط الأساس لسطر النص. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename/) { get; set; } | الحصول أو تعيين اسم الوجه (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد اسم الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/fullname/) { get; set; } | يحصل أو يعيّن سلسلة مكوّنة من 64 حرفًا يونيكود تُعرّف الاسم الكامل للخط. إذا كان طول هذه السلسلة أقل من 64 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height/) { get; set; } | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. قيمة ارتفاع الحرف، المعروفة أيضًا باسم حجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها القيمة الداخلية للخط. يجب على مخطط الخط تفسير القيمة المحددة في حقل Height بالطريقة التالية. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 8‑بت يحدد خطًا مائلًا إذا تم ضبطه على 0x01؛ وإلا يجب ضبطه على 0x00. |
| [Match](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/match/) { get; set; } | يحصل أو يعيّن هذا الحقل يجب تجاهله. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation/) { get; set; } | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب مطابقة الخط للارتفاع والعرض والاتجاه والحرف والمسافة والنوع المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision enumeration |
| [Padding](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/padding/) { get; set; } | يحصل أو يعيّن حقلًا موجودًا فقط لضمان محاذاة 32 بت لهذه البنية. يجب تجاهله. |
| [Panose](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/panose/) { get; set; } | يحصل أو يعيّن كائن Panose (القسم 2.2.21) يحدد خصائص PANOSE للخط المنطقي. إذا كانت جميع حقول هذا الكائن صفرًا، يجب تجاهله. |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily/) { get; set; } | يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الخط وعائلته. تصف عائلات الخطوط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يتوفر نوع الخط المحدد. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون إحدى القيم في تعداد WMF FontQuality ([MS-WMF] القسم 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ وإلا يجب تعيينه إلى 0x00. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/style/) { get; set; } | يحصل أو يعيّن سلسلة مكوّنة من 32 حرف يونيكود تحدد نمط الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل. |
| [StyleSize](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/stylesize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم النقطة الذي يُجرى فيه تحسين الخط. إذا تم ضبطه على الصفر، يتم إجراء تحسين الخط بحجم النقطة المقابل لحقل Height في كائن LogFont في حقل LogFont. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد خطًا مسطرًا إذا تم تعيينه إلى 0x01؛ وإلا يجب تعيينه إلى 0x00. |
| [VendorId](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/vendorid/) { get; set; } | يحصل أو يعيّن هذا الحقل يجب تجاهله. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/version/) { get; set; } | يحصل أو يعيّن هذا الحقل يجب تجاهله. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد وزن الخط في النطاق من صفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. إذا كانت قيمة حقل العرض صفرًا، يجب حساب قيمة مناسبة من قيم LogFont الأخرى للعثور على خط يطابق نسبة الأبعاد المقصودة من قبل المصمم. |

### انظر أيضًا

* class [EmfLogFont](../emflogfont/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


