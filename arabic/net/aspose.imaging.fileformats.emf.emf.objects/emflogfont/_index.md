---
title: "الفئة EmfLogFont"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogFont. يحدد كائن LogFont السمات الأساسية لخط منطقي."
type: docs
weight: 3120
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
## EmfLogFont class

كائن LogFont يحدد السمات الأساسية لخط منطقي.

```csharp
public class EmfLogFont : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfLogFont](emflogfont/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 8‑بت يحدد مجموعة رموز الأحرف. يجب أن تكون القيمة قيمة في تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كانت مجموعة الأحرف غير معروفة، يجب ألا تحاول معالجة ملف الميتا ترجمة أو تفسير السلاسل التي تم عرضها بهذا الخط. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 8‑بت يحدد دقة القص. تحدد دقة القص كيفية قص الأحرف التي هي جزئياً خارج منطقة القص. يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement/) { get; set; } | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين متجه الإزاحة ومحور x للجهاز. متجه الإزاحة موازٍ لخط الأساس لسطر النص. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename/) { get; set; } | الحصول أو تعيين اسم الوجه (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد اسم الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height/) { get; set; } | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الارتفاع، بوحدات منطقية، لخلية حرف الخط أو الحرف. قيمة ارتفاع الحرف، المعروفة أيضًا باسم حجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها القيمة الداخلية للخط. يجب على مخطط الخط تفسير القيمة المحددة في حقل Height بالطريقة التالية. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 8‑بت يحدد خطًا مائلًا إذا تم ضبطه على 0x01؛ وإلا يجب ضبطه على 0x00. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation/) { get; set; } | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الزاوية، بعشرات الدرجات، بين خط أساس كل حرف ومحور x للجهاز. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب مطابقة الخط للارتفاع والعرض والاتجاه والحرف والمسافة والنوع المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision enumeration |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily/) { get; set; } | يحصل أو يعيّن كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) يحدد درجة الخط وعائلته. تصف عائلات الخطوط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يتوفر نوع الخط المحدد. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون إحدى القيم في تعداد WMF FontQuality ([MS-WMF] القسم 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ وإلا يجب تعيينه إلى 0x00. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد خطًا مسطرًا إذا تم تعيينه إلى 0x01؛ وإلا يجب تعيينه إلى 0x00. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد وزن الخط في النطاق من صفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المتوسط، بوحدات منطقية، للأحرف في الخط. إذا كانت قيمة حقل العرض صفرًا، يجب حساب قيمة مناسبة من قيم LogFont الأخرى للعثور على خط يطابق نسبة الأبعاد المقصودة من قبل المصمم. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


