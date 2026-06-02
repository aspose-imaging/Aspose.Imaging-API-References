---
title: "فئة EmfPlusSetTsGraphics"
type: docs
weight: 580
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | يُنشئ مثيلاً جديدًا للفئة [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 8-بت يحدد جودة رسم الخطوط،<br/>            بما في ذلك نوع مضاد التعرج للخط. يجب أن يكون معرفًا في تعداد SmoothingMode<br/>            (القسم 2.1.1.28). |
| basic_vga_colors | bool | r | يحصل على قيمة تشير إلى ما إذا كان [basic vga colors].<br/>            إذا تم التعيين، فإن لوحة الألوان تحتوي فقط على ألوان VGA الأساسية. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 8-بت يحدد كيفية دمج ألوان المصدر<br/>            مع ألوان الخلفية. يجب أن تكون قيمة في تعداد CompositingMode<br/>            (القسم 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 8-بت يحدد درجة<br/>            التنعيم التي تُطبق على الخطوط والمنحنيات وحواف المناطق المملوءة لجعلها تبدو أكثر<br/>            استمرارية أو تعريفًا حادًا. يجب أن تكون قيمة في تعداد CompositingQuality (القسم 2.1.1.6). |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 8-بت يحدد كيفية تنفيذ التحجيم، بما في ذلك التمدد<br/>            والانكماش. يجب أن تكون قيمة في تعداد FilterType (القسم 2.1.1.11). |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| have_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كان [have palette].<br/>            إذا تم التعيين، يحتوي هذا السجل على كائن EmfPlusPalette (القسم 2.2.2.28) في<br/>            حقل Palette بعد بيانات حالة الرسومات. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | يحصل أو يعيّن كائن EmfPlusPalette اختياري. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 8-بت يحدد الجودة العامة للصورة<br/>            وعملية رسم النص. يجب أن تكون قيمة في تعداد PixelOffsetMode (القسم 2.1.1.26). |
| render_origin_x | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 16-بت، وهو الإحداثي الأفقي لـ<br/>            أصل رسم نصف التظليل ومصفوفات التدرج. |
| render_origin_y | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 16-بت، وهو الإحداثي العمودي لأصل<br/>            رسم نصف التظليل ومصفوفات التدرج. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| text_contrast | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16-بت يحدد قيمة تصحيح غاما<br/>            المستخدمة في رسم النص المضاد للتعرج ونص ClearType. يجب أن تكون هذه القيمة في النطاق من 0 إلى 12، شاملًا. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 8-بت يحدد جودة رسم النص<br/>            بما في ذلك نوع مضاد التعرج للنص. يجب أن يكون معرفًا في تعداد TextRenderingHint<br/>            (القسم 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | الحصول أو تعيين كائن EmfPlusTransformMatrix بحجم 192 بت (القسم 2.2.2.47) الذي<br/> يحدد التحويلات من مساحة العالم إلى مساحة الجهاز. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

يُنشئ مثيلاً جديدًا للفئة [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

