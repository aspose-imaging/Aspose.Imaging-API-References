---
title: "فئة EmfLogFontEx"
type: docs
weight: 140
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---

**Summary:** The LogFontEx object specifies the extended attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfLogFontEx(emf_log_font)](#EmfLogFontEx_emf_log_font_1) | ينشئ مثيلًا جديدًا من الفئة [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 8‑بت يحدد مجموعة رموز الحروف. يجب أن تكون <br/>            قيمةً في تعداد WMF CharacterSet ([MS-WMF] القسم 2.1.1.5). إذا كان مجموعة الأحرف غير معروفة، يجب ألا تحاول معالجة ملف الميتا ترجمة أو تفسير <br/>            السلاسل التي تُعرض بهذه الخط. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 8‑بت يحدد دقة القطع. <br/>            تحدد دقة القطع كيفية قطع الأحرف التي هي جزئيًا خارج منطقة القطع. <br/>            يمكن أن تكون واحدة أو أكثر من أعلام WMF ClipPrecision. |
| escapement | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد الزاوية، بعشرات الدرجات، <br/>            بين متجه الـ escapement ومحور x للجهاز. متجه الـ escapement <br/>            موازٍ لخط الأساس لسطر النص. |
| اسم الخط | string | r/w | يحصل أو يضبط Facename (64 بايت): سلسلة لا تتجاوز 32 حرف يونيكود تحدد <br/>            اسم الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، <br/>            وبعده يجب تجاهل باقي هذا الحقل. |
| full_name | string | r/w | يحصل أو يضبط سلسلة مكونة من 64 حرف يونيكود تحتوي على الاسم الكامل للخط. إذا <br/>            كان طول هذه السلسلة أقل من 64 حرفًا، يجب أن يكون هناك NULL نهائي، بعد <br/>            ذلك يجب تجاهل باقي هذا الحقل. |
| height | int | r/w | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد الارتفاع، بوحدات منطقية، لخلية الحرف أو الحرف في الخط <br/>            . قيمة ارتفاع الحرف، المعروفة أيضًا بحجم الـ em، هي قيمة ارتفاع خلية الحرف مطروحًا منها قيمة المسافة الداخلية. يجب على مُطابِق الخط أن يفسّر القيمة المحددة في حقل Height بالطريقة التالية. |
| مائل | System.Byte | r/w | يحصل أو يضبط عددًا صحيحًا غير موقّع 8-بت يحدد خطًا مائلًا إذا تم تعيينه إلى 0x01؛ وإلا، <br/>            يجب تعيينه إلى 0x00. |
| الاتجاه | int | r/w | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد الزاوية، بعشرات الدرجات، <br/>            بين خط أساس كل حرف ومحور x للجهاز. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقّع 8-بت يحدد دقة الإخراج. <br/>            تحدد دقة الإخراج مدى قرب مطابقة الخط للارتفاع والعرض والاتجاه والحرف والهروب والدرجة ونوع الخط المطلوب. يجب أن تكون قيمة من تعداد WMF OutPrecision <br/>            . |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | يحصل أو يضبط كائن WMF PitchAndFamily ([MS-WMF] القسم 2.2.2.14) الذي <br/>            يحدد درجة الخط وعائلة الخط. تصف عائلات الخط مظهر الخط بشكل عام. تُستخدم لتحديد خط عندما لا يكون نوع الخط المحدد متاحًا. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقّع 8-بت يحدد جودة الإخراج. جودة الإخراج <br/>            تحدد مدى محاولة مطابقة خصائص الخط المنطقي مع خصائص خط فعلي مادي. يجب أن تكون إحدى القيم في تعداد WMF FontQuality ([MS-WMF] <br/>            القسم 2.1.1.10). |
| النص | string | r/w | يحصل أو يضبط سلسلة من 32 حرف يونيكود تحدد مجموعة الأحرف للخط. <br/>            إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، <br/>            وبعد ذلك يجب تجاهل باقي هذا الحقل. |
| شطب | System.Byte | r/w | يحصل أو يضبط عددًا صحيحًا غير موقّع 8-بت يحدد خطًا مشطوبًا إذا تم تعيينه إلى 0x01؛ <br/>            وإلا، يجب تعيينه إلى 0x00. |
| النمط | string | r/w | يحصل أو يضبط سلسلة من 32 حرف يونيكود تحدد نمط الخط. إذا كان طول هذه السلسلة أقل من 32 حرفًا، يجب أن يكون هناك NULL نهائي، <br/>            بعد ذلك يجب تجاهل باقي هذا الحقل. |
| تحته خط | System.Byte | r/w | يحصل أو يضبط عددًا صحيحًا غير موقّع 8-بت يحدد خطًا تحته خط إذا تم تعيينه إلى 0x01؛ <br/>            وإلا، يجب تعيينه إلى 0x00. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد وزن الخط في النطاق من صفر إلى 1000. على سبيل المثال، 400 هو عادي و700 هو عريض. إذا كانت هذه القيمة صفرًا، يمكن استخدام وزن افتراضي. |
| width | int | r/w | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد العرض المتوسط، بوحدات منطقية، <br/>            للأحرف في الخط. إذا كانت قيمة حقل Width صفرًا، يجب حساب قيمة مناسبة <br/>            من قيم LogFont الأخرى للعثور على خط يطابق النسبة المطلوبة للمصمم <br/>             |


### Constructor: EmfLogFontEx(emf_log_font) {#EmfLogFontEx_emf_log_font_1}


```
 EmfLogFontEx(emf_log_font) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | خط سجل EMF. |

