---
title: EmfPlusStringFormat
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن EmfPlusStringFormat تخطيط النص  التلاعب بالعرض  وتعريف اللغة
type: docs
weight: 5780
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

يحدد كائن EmfPlusStringFormat تخطيط النص ، التلاعب بالعرض ، وتعريف اللغة

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | الحصول على كائن EmfPlusLanguageIdentifier أو تعيينه والذي يحدد لغة لاستخدامها للأرقام الرقمية في السلسلة. |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد كيفية استبدال الأرقام الرقمية في السلسلة وفقًا للإعدادات المحلية أو اللغة . يجب تحديد هذه القيمة في StringDigitSubstitution التعداد (القسم 2.1.1.30) . |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | الحصول على أو تعيين قيمة النقطة العائمة 32 بت التي تحدد عدد المسافات بين بداية سطر النص و علامة التبويب الأولى توقف |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | الحصول على أو تعيين عدد صحيح موقعة 32 بت يحدد نوع المعالجة التي يتم إجراؤها على سلسلة عند مصادفة بادئة اختصار keyboard (أي علامة العطف) . بشكل أساسي ، يحدد هذا الحقل ما إذا كان سيتم عرض اختصارات لوحة المفاتيح التي تتعلق بالنص. يجب تحديد القيمة في تعداد HotkeyPrefix (القسم 2.1.1.14) . |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | الحصول على كائن EmfPlusLanguageIdentifier أو تعيينه (القسم 2.2.2.23) الذي يحدد اللغة المراد استخدامها للسلسلة |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | الحصول على أو تعيين قيمة النقطة العائمة 32 بت التي تحدد length للمساحة المراد إضافتها إلى موضع البداية لسلسلة . الافتراضي هو 1/6 بوصة ؛ بالنسبة للخطوط المطبعية ، فإن القيمة الافتراضية هي 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد كيفية محاذاة السلسلة عموديًا في مستطيل التخطيط. يجب تحديد هذه القيمة في تعداد StringAlignment. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | الحصول على أو تعيين عدد صحيح موقعة 32 بت يحدد عدد كائنات EmfPlusCharacterRange (القسم 2.2.2.8) المحددة في حقل StringFormatData. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد كيفية محاذاة السلسلة أفقياً في مستطيل التخطيط. يجب تحديد هذه القيمة في تعداد StringAlignment (القسم 2.1.1.29) . |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | الحصول على أو تعيين كائن EmfPlusStringFormatData (القسم 2.2.2.44) الذي يحدد بيانات تخطيط النص الاختياري. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد تخطيط النص خيارات التنسيق والقص ومعالجة الخط. يجب أن تتكون هذه القيمة من StringFormat flags (القسم 2.1.2.8) . |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | الحصول على أو تعيين عدد صحيح موقعة 32 بت يحدد عدد علامات الجدولة المحددة في حقل StringFormatData . |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | الحصول على أو تعيين قيمة النقطة العائمة 32 بت التي تحدد نسبة للمسافة الأفقية المخصصة لكل حرف في سلسلة محددة للعرض المحدد بواسطة الخط للحرف . تحدد القيم الكبيرة لهذه الخاصية مسافة ample بين الأحرف ؛ يمكن أن تنتج القيم الأقل من 1 تداخلًا في الأحرف. الافتراضي هو 1.03 ؛ بالنسبة لخطوط typographic ، فإن القيمة الافتراضية هي 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | الحصول على أو تعيين قيمة النقطة العائمة 32 بت التي تحدد length للمساحة التي يجب تركها بعد سلسلة. الافتراضي هو 1/6 بوصة ؛ بالنسبة للخطوط المطبعية ، القيمة الافتراضية هي 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Gets أو المجموعات تحدد كيفية اقتطاع الأحرف من سلسلة كبيرة جدًا لتناسب مستطيل التخطيط. يجب تعريف هذه value في تعداد StringTrimming (القسم 2.1.1.31) . |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | الحصول على الإصدار أو تعيينه. |

### أنظر أيضا

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
