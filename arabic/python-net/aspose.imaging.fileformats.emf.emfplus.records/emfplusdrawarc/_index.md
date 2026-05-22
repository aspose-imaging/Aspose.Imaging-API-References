---
title: "فئة EmfPlusDrawArc"
type: docs
weight: 70
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | إنشاء نسخة جديدة من الفئة [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | الحصول أو تعيين حجم البيانات.<br/> عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المحاذاة على 32‑بت للبيانات الخاصة بالسجل التي تلي.<br/> بالنسبة لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من القيم التالية:<br/> 0x00000010 إذا كان بت C مفعلاً في حقل Flags.<br/> 0x00000018 إذا كان بت C غير مفعّل في حقل Flags. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| object_id | System.Byte | r/w | الحصول أو تعيين معرف الكائن.<br/> فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لت رسم القوس. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| rect_float | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كانت البيانات تحتوي على <br/> سجلات EmfPlusRectF أو EmfPlusRect<br/> هذا البت يحدد ما إذا كانت البيانات في حقل RectData مضغوطة.<br/> إذا كان مفعلاً، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38).<br/> إذا كان غير مفعّل، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | الحصول أو تعيين بيانات المستطيل<br/> إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للقطع الناقص المتوازي مع القوس. يحدد هذا المستطيل موضع القوس وحجمه وشكله. نوع الكائن في هذا الحقل يحدد بواسطة قيمة حقل Flags. |
| الحجم | int | r/w | الحصول أو تعيين الحجم.<br/> عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المحاذاة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل بطول 12 بايتًا وبيانات السجل الخاصة. بالنسبة لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من القيم التالية:<br/> 0x0000001C إذا كان بت C مفعلاً في حقل Flags.<br/> 0x00000024 إذا كان بت C غير مفعّل في حقل Flags. |
| start_angle | float | r/w | الحصول أو تعيين زاوية البدء<br/> قيمة عائمة 32‑بت غير سالبة تحدد الزاوية بين محور x ونقطة بدء القوس. أي قيمة مقبولة، لكن يجب تفسيرها modulo 360، بحيث يكون الناتج في النطاق من 0.0 شاملًا إلى 360.0 حصريًا. |
| sweep_angle | float | r/w | الحصول أو تعيين زاوية القوس<br/> قيمة عائمة 32‑بت تحدد مدى القوس المراد رسمه، كزاوية بالدرجات مقاسة من نقطة البدء المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، لكن يجب حصرها بين -360.0 و 360.0 شاملًا. القيمة الموجبة تشير إلى أن القوس يُعرّف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرّف باتجاه عكس عقارب الساعة. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

إنشاء نسخة جديدة من الفئة [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

