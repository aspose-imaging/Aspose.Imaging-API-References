---
title: "فئة StringFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.StringFormat. تُغلف معلومات تخطيط النص مثل توجيه المحاذاة وإيقافات التبويب وتعديلات العرض مثل إدراج ثلاث نقاط واستبدال الأرقام الوطنية وميزات OpenType. لا يمكن وراثة هذه الفئة."
type: docs
weight: 11750
url: /ar/net/aspose.imaging/stringformat/
---
## StringFormat class

يحتوي على معلومات تخطيط النص (مثل المحاذاة، الاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج الحذف الثلاثي واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class StringFormat : DisposableObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | يُنشئ كائنًا جديدًا من نوع `StringFormat`. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | يُنشئ كائنًا جديدًا من نوع `StringFormat` من الكائن `StringFormat` الموجود المحدد. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | يُنشئ كائنًا جديدًا من نوع `StringFormat` باستخدام تعداد [`StringFormatFlags`](../stringformatflags/) المحدد واللغة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [GenericDefault](../../aspose.imaging/stringformat/genericdefault/) { get; } | يحصل على كائن `StringFormat` افتراضي عام. |
| static [GenericTypographic](../../aspose.imaging/stringformat/generictypographic/) { get; } | يحصل على كائن `StringFormat` طباعي عام. |
| [Alignment](../../aspose.imaging/stringformat/alignment/) { get; set; } | يحصل أو يضبط معلومات محاذاة النص على المستوى العمودي. |
| [CustomCharIdent](../../aspose.imaging/stringformat/customcharident/) { get; set; } | يحصل أو يضبط معرّف الحرف المخصص. |
| [DigitSubstitutionLanguage](../../aspose.imaging/stringformat/digitsubstitutionlanguage/) { get; set; } | يحصل أو يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [DigitSubstitutionMethod](../../aspose.imaging/stringformat/digitsubstitutionmethod/) { get; set; } | يحصل أو يضبط الطريقة المستخدمة لاستبدال الأرقام. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [FirstTabOffset](../../aspose.imaging/stringformat/firsttaboffset/) { get; } | يحصل على عدد المسافات بين بداية سطر النص وأول إيقاف تبويب. |
| [FormatFlags](../../aspose.imaging/stringformat/formatflags/) { get; set; } | يحصل أو يضبط تعداد [`StringFormatFlags`](../stringformatflags/) الذي يحتوي على معلومات التنسيق. |
| [HotkeyPrefix](../../aspose.imaging/stringformat/hotkeyprefix/) { get; set; } | يحصل أو يضبط كائن [`HotkeyPrefix`](../hotkeyprefix/) لهذا الكائن `StringFormat`. |
| [LineAlignment](../../aspose.imaging/stringformat/linealignment/) { get; set; } | يحصل أو يضبط محاذاة السطر على المستوى الأفقي. |
| [TabStops](../../aspose.imaging/stringformat/tabstops/) { get; } | يحصل على مصفوفة من المسافات بين إيقافات التبويب بالوحدات المحددة بواسطة الخاصية [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.imaging/stringformat/trimming/) { get; set; } | يحصل أو يضبط تعداد [`StringTrimming`](../stringtrimming/) لهذا الكائن `StringFormat`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DeepClone](../../aspose.imaging/stringformat/deepclone/)() | ينشئ نسخة عميقة من هذا الكائن `StringFormat`. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Equals](../../aspose.imaging/stringformat/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetHashCode](../../aspose.imaging/stringformat/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [SetTabStops](../../aspose.imaging/stringformat/settabstops/)(float, float[]) | يضبط نقاط التبويب لهذا الكائن `StringFormat`. |
| override [ToString](../../aspose.imaging/stringformat/tostring/)() | يحوّل هذا الكائن `StringFormat` إلى سلسلة قابلة للقراءة من قبل الإنسان. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


