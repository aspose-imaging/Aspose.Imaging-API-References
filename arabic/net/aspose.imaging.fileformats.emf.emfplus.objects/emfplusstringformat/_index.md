---
title: "الفئة EmfPlusStringFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusStringFormat. كائن EmfPlusStringFormat يحدد عمليات تعديل عرض تخطيط النص وتحديد اللغة"
type: docs
weight: 5900
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

كائن EmfPlusStringFormat يحدد تخطيط النص، وتعديلات العرض، وتحديد اللغة

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage/) { get; set; } | يحصل أو يعيّن كائن EmfPlusLanguageIdentifier الذي يحدد اللغة المستخدمة للأرقام الرقمية في السلسلة. على سبيل المثال، إذا كانت هذه السلسلة تحتوي على أرقام عربية، يجب أن يحتوي هذا الحقل على معرف لغة يحدد لغة عربية |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32‑بت يحدد طريقة استبدال الأرقام الرقمية في السلسلة وفقاً للمنطقة أو اللغة. يجب أن تكون هذه القيمة معرفة في تعداد StringDigitSubstitution (القسم 2.1.1.30). |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عدد المسافات بين بداية سطر النص وأول موضع تبويب |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix/) { get; set; } | يحصل أو يعيّن عدد صحيح موقع 32‑بت يحدد نوع المعالجة التي تُجرى على السلسلة عندما يُصادف بادئة اختصار لوحة المفاتيح (أي علامة العطف). أساساً، يحدد هذا الحقل ما إذا كان سيتم عرض بادئات اختصارات لوحة المفاتيح المتعلقة بالنص. يجب أن تكون القيمة معرفة في تعداد HotkeyPrefix (القسم 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language/) { get; set; } | يحصل أو يعيّن كائن EmfPlusLanguageIdentifier (القسم 2.2.2.23) الذي يحدد اللغة المستخدمة للسلسلة |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد طول الفراغ الذي يضاف إلى الموضع الابتدائي للسلسلة. القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32‑بت يحدد طريقة محاذاة السلسلة عمودياً في مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount/) { get; set; } | يحصل أو يعيّن عدد صحيح موقع 32‑بت يحدد عدد كائنات EmfPlusCharacterRange (القسم 2.2.2.8) المعرفة في حقل StringFormatData. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية محاذاة السلسلة أفقياً في مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment (القسم 2.1.1.29). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata/) { get; set; } | يحصل أو يضبط كائن EmfPlusStringFormatData (القسم 2.2.2.44) الذي يحدد بيانات تخطيط النص الاختيارية. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد خيارات تخطيط النص للتنسيق والقص ومعالجة الخطوط. يجب أن تتكون هذه القيمة من أعلام StringFormat (القسم 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount/) { get; set; } | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد عدد نقاط التبويب المعرفة في حقل StringFormatData. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking/) { get; set; } | يحصل أو يضبط قيمة عائمة 32‑بت تحدد نسبة المسافة الأفقية المخصصة لكل حرف في سلسلة محددة إلى عرض الحرف المحدد بالخط. القيم الكبيرة لهذه الخاصية تشير إلى مساحة واسعة بين الأحرف؛ القيم الأقل من 1 قد تتسبب في تداخل الأحرف. القيمة الافتراضية هي 1.03؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin/) { get; set; } | يحصل أو يضبط قيمة عائمة 32‑بت تحدد طول الفراغ الذي يُترك بعد سلسلة. القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming/) { get; set; } | يحصل أو يضبط طريقة تقليم الأحرف من سلسلة كبيرة جدًا بحيث لا تتناسب مع مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringTrimming (القسم 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | الحصول أو تعيين الإصدار. |

### انظر أيضًا

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


