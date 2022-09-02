---
title: EmfLogFontPanose
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن LogFontPanose خصائص PANOSE لخط منطقي.
type: docs
weight: 3060
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
## EmfLogFontPanose class

يحدد كائن LogFontPanose خصائص PANOSE لخط منطقي.

```csharp
public sealed class EmfLogFontPanose : EmfLogFont
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfLogFontPanose](emflogfontpanose)(EmfLogFont) | يقوم بتهيئة مثيل جديد لملف[`EmfLogFontPanose`](../emflogfontpanose) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد مجموعة الحروف الرسومية للأحرف. يجب أن تكون قيمة في تعداد WMF CharacterSet (القسم [MS-WMF] 2.1.1.5). إذا كانت مجموعة الأحرف غير معروفة ، فيجب ألا تحاول معالجة ملف التعريف ترجمة أو تفسير سلاسل التي يتم تقديمها بهذا الخط. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد دقة القطع. تحدد دقة القص كيفية قص الأحرف الموجودة جزئيًا خارج منطقة القطع. يمكن أن يكون واحدًا أو أكثر من WMF ClipPrecision Flags |
| [Culture](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/culture) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يجب تعيينه على صفر ويجب تجاهله. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد الزاوية ، بعشر الدرجات ، بين متجه الميزان والمحور السيني للجهاز. متجه الميزان موازٍ للخط الأساسي لصف من النص. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | الحصول على أو تعيين اسم الوجه (64 بايت): سلسلة لا تزيد عن 32 حرفًا من أحرف Unicode تحدد اسم محرف الخط . إذا كان طول هذه السلسلة أقل من 32 حرفًا ، فيجب وجود علامة إنهاء NULL ، وبعد ذلك يجب تجاهل باقي هذا الحقل. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/fullname) { get; set; } | الحصول على أو تعيين سلسلة من 64 حرف Unicode تحدد الاسم الكامل للخط. إذا كان طول هذه السلسلة أقل من 64 حرفًا ، فيجب أن يكون الإنهاء NULL موجودًا ، بعد حيث يجب تجاهل باقي هذا الحقل. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد الارتفاع ، بالوحدات المنطقية ، لخلية أو حرف الخط . قيمة ارتفاع الحرف ، والمعروفة أيضًا باسم حجم em ، هي قيمة ارتفاع خلية الحرف مطروحًا منها قيمة المسافة البادئة الداخلية. يجب أن يفسر معين الخط القيمة المحددة في حقل الارتفاع بالطريقة التالية. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد خطًا مائلًا إذا تم تعيينه على 0x01 ؛ وإلا ، يجب تعيين إلى 0x00. |
| [Match](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/match) { get; set; } | الحصول على هذا الحقل أو تعيينه يجب تجاهلها. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد الزاوية ، بعشر الدرجات ، بين خط الأساس لكل حرف والمحور السيني للجهاز . |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد دقة الإخراج. تحدد دقة الإخراج مدى قرب الخط المطلوب لمطابقة الارتفاع المطلوب ، والعرض ، واتجاه الحرف ، والتخطي ، والخطوة ، ونوع الخط. يجب أن تكون قيمة من WMF OutPrecision enumeration |
| [Padding](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/padding) { get; set; } | الحصول على أو تعيين حقل موجود فقط لضمان محاذاة 32 بت لهذه البنية. يجب تجاهله |
| [Panose](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/panose) { get; set; } | الحصول على كائن Panose أو تعيينه (القسم 2.2.21) الذي يحدد خصائص PANOSE للخط المنطقي. إذا كانت جميع حقول هذا الكائن صفراً ، فيجب تجاهله. |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | الحصول على أو تعيين كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) الذي يحدد درجة الخط وعائلة الخط. تصف عائلات الخطوط مظهر الخط بطريقة عامة. الغرض منها هو تحديد الخط عندما لا يكون المحرف المحدد متاحًا. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد جودة الإخراج. تحدد جودة الإخراج مدى قرب محاولة مطابقة سمات الخط المنطقي لتلك الخاصة بالخط الفعلي . يجب أن تكون إحدى القيم في تعداد جودة الخط في WMF ([MS-WMF] القسم 2.1.1.10) . |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد خط إضراب إذا تم تعيينه إلى 0x01 ؛ وإلا ، يجب تعيينه على 0x00. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/style) { get; set; } | الحصول على أو تعيين سلسلة من 32 حرفًا من أحرف Unicode تحدد نمط الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا ، فيجب أن يكون هناك إنهاء NULL ، وبعد ذلك يجب تجاهل باقي هذا الحقل. |
| [StyleSize](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/stylesize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد حجم النقطة التي يتم عندها تنفيذ تلميح الخط . إذا تم التعيين على الصفر ، فسيتم تنفيذ تلميح الخط بحجم النقطة المطابق لحقل الارتفاع في كائن LogFont في حقل LogFont |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 8 بت يحدد خطًا تحته خط إذا تم تعيينه على 0x01 ؛ وإلا ، يجب تعيينه على 0x00. |
| [VendorId](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/vendorid) { get; set; } | الحصول على هذا الحقل أو تعيينه يجب تجاهلها. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/version) { get; set; } | يحصل أو يعيّن يجب تجاهل هذا الحقل. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد وزن الخط في النطاق من صفر إلى 1000. على سبيل المثال ، 400 عادي و 700 غامق. إذا كانت هذه القيمة صفراً ، فيمكن استخدام وزن افتراضي . |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد متوسط العرض ، بالوحدات المنطقية ، من حرفًا في الخط. إذا كانت قيمة حقل العرض تساوي صفرًا ، فيجب أن تكون القيمة المناسبة محسوبة من قيم LogFont الأخرى للعثور على الخط الذي يقصده المصمم نسبة العرض إلى الارتفاع |

### أنظر أيضا

* class [EmfLogFont](../emflogfont)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
