---
title: "فئة EmfPlusDrawDriverString"
type: docs
weight: 110
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | يحصل أو يضبط معرف الفرشاة<br/>A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush,<br/>depending on the value of the S flag in the Flags |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | يحصل أو يضبط أعلام خيارات سلسلة السائق<br/>A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| glyph_count | int | r/w | يحصل أو يضبط عدد الرموز<br/>A 32-bit unsigned integer that specifies number of glyphs in the string |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يضبط مصفوفة مواضع الرموز<br/>An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph.<br/>There MUST be GlyphCount elements, which have a one-to-one correspondence with the elements in the Glyphs array.<br/>Glyph positions are calculated from the position of the first glyph if the DriverStringOptionsRealizedAdvance<br/>flag in DriverStringOptions flags is set. In this case, GlyphPos specifies the position of the first glyph only. |
| glyphs | int[] | r/w | يحصل أو يضبط مصفوفة الرموز<br/>An array of 16-bit values that define the text string to draw.<br/>If the DriverStringOptionsCmapLookup flag in the DriverStringOptionsFlags field is set, each value in this<br/>array specifies a Unicode character. Otherwise, each value specifies an index to a<br/>character glyph in the EmfPlusFont object specified by the ObjectId value in Flags field. |
| is_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل لونيًا.<br/>This bit indicates the type of data in the BrushId field.<br/>If set, BrushId specifies the color value in an EmfPlusARGB object<br/>(section 2.2.2.1). If clear, BrushId contains the EMF+ Object<br/>Table index of an EmfPlusBrush object (section 2.1.1). |
| matrix_present | int | r/w | يحصل أو يضبط ما إذا كان علم وجود المصفوفة مفعلاً<br/>A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field<br/>0 - no matrix present. 1 - transform matrix is in TransformMatrix field |
| object_id | System.Byte | r/w | يحصل أو يضبط معرف الكائن.<br/>The EMF+ Object Table index of an ***EmfPlusFont*** object (section<br/>2.2.1.3) to render the text. The value MUST be zero to 63, inclusive. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يضبط مصفوفة التحويل<br/>An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to<br/>each value in the text array. The presence of this data is determined from the MatrixPresent field. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) class.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

