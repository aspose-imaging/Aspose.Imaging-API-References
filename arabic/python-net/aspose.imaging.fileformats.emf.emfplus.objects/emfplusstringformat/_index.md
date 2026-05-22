---
title: "EmfPlusStringFormat Class"
type: docs
weight: 650
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | ينشئ نسخة جديدة من الفئة EmfPlusStringFormat |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | يحصل أو يعيّن كائن EmfPlusLanguageIdentifier الذي يحدد<br/>            اللغة المستخدمة للأرقام الرقمية في السلسلة.<br/>            على سبيل المثال، إذا كانت هذه السلسلة تحتوي على أرقام عربية،<br/>            يجب أن يحتوي هذا الحقل على معرف لغة يحدد<br/>            لغة عربية. |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية استبدال<br/>            الأرقام الرقمية في السلسلة وفقًا للمنطقة أو اللغة.<br/>            يجب أن تكون هذه القيمة معرفة في تعداد StringDigitSubstitution<br/>            (القسم 2.1.1.30). |
| first_tab_offset | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عدد<br/>            المسافات بين بداية سطر النص و<br/>            أول موضع تبويب |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | يحصل أو يعيّن عددًا صحيحًا 32‑بت يحدد نوع<br/>            المعالجة التي تُجرى على سلسلة عندما يُصادف بادئة اختصار لوحة المفاتيح (أي علامة العطف).<br/>            أساسًا، يحدد هذا الحقل ما إذا كان سيتم عرض<br/>            بادئات اختصارات لوحة المفاتيح المتعلقة بالنص.<br/>            يجب أن تكون القيمة معرفة في تعداد HotkeyPrefix<br/>            (القسم 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | يحصل أو يعيّن كائن EmfPlusLanguageIdentifier (القسم 2.2.2.23)<br/>            الذي يحدد اللغة المستخدمة للسلسلة |
| leading_margin | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد طول<br/>            المسافة التي تُضاف إلى الموضع الابتدائي لسلسلة.<br/>            القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية،<br/>            القيمة الافتراضية هي 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد كيفية<br/>            محاذاة السلسلة عموديًا في مستطيل التخطيط.<br/>            يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment. |
| range_count | int | r/w | يحصل أو يعيّن عددًا صحيحًا 32‑بت يحدد عدد كائنات EmfPlusCharacterRange<br/>            (القسم 2.2.2.8) المعرفة في حقل StringFormatData. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد كيفية<br/>            محاذاة السلسلة أفقيًا في مستطيل التخطيط.<br/>            يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment<br/>            (القسم 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | يحصل أو يعيّن كائن EmfPlusStringFormatData (القسم 2.2.2.44)<br/>            الذي يحدد بيانات تخطيط النص الاختيارية. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات تخطيط النص<br/>            للتنسيق والقص ومعالجة الخط.<br/>            يجب أن تتكون هذه القيمة من أعلام StringFormat<br/>            (القسم 2.1.2.8). |
| tabstop_count | int | r/w | يحصل أو يعيّن عددًا صحيحًا 32‑بت يحدد عدد مواضع التبويب<br/>            المعرفة في حقل StringFormatData. |
| tracking | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد النسبة<br/>            بين المسافة الأفقية المخصصة لكل حرف في<br/>            سلسلة محددة وعرض الحرف المحدد بالخط.<br/>            القيم الكبيرة لهذه الخاصية تحدد مساحة وفيرة<br/>            بين الأحرف؛ القيم الأقل من 1 قد تُنتج تداخلًا بين الأحرف.<br/>            القيمة الافتراضية هي 1.03؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 1.00. |
| trailing_margin | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد طول<br/>            المسافة التي تُترك بعد سلسلة. القيمة الافتراضية<br/>            هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | يحصل أو يعيّن ما يحدد كيفية قص الأحرف من سلسلة تكون<br/>            كبيرة جدًا لتناسب مستطيل التخطيط. يجب أن تكون هذه القيمة<br/>            معرفة في تعداد StringTrimming (القسم 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | يحصل أو يضبط الإصدار. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

ينشئ نسخة جديدة من الفئة EmfPlusStringFormat

