---
title: "فئة EmfPlusFillPie"
type: docs
weight: 260
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

**Summary:** The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillPie(source)](#EmfPlusFillPie_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | يحصل أو يعيّن معرف الفرشاة<br/> عدد صحيح غير موقع 32-بت يحدد الفرشاة، محتواها يُحدّد ببت S في حقل Flags. |
| مضغوط | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData مضغوطة.<br/> إذا تم الضبط، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38).<br/> إذا لم يتم الضبط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل لونيًا.<br/>            إذا تم تعيينه، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). <br/>            إذا لم يتم تعيينه، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يضبط بيانات المستطيل<br/>Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the <br/>ellipse that contains the pie wedge. This rectangle defines the position, size, <br/>and shape of the pie. The type of object in this field is specified by the value <br/>of the Flags field. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| start_angle | float | r/w | يحصل أو يضبط زاوية البداية<br/>A 32-bit, non-negative floating-point value that specifies the angle between the <br/>x-axis and the starting point of the pie wedge. Any value is acceptable, but it <br/>MUST be interpreted modulo 360, with the result that is used being in the range <br/>0.0 inclusive to 360.0 exclusive. |
| sweep_angle | float | r/w | يحصل أو يضبط زاوية المسح<br/>A 32-bit floating-point value that specifies the extent of the arc that defines <br/>the pie wedge to draw, as an angle in degrees measured from the starting point <br/>defined by the StartAngle value. Any value is acceptable, but it MUST be clamped <br/>to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined <br/>in a clockwise direction, and a negative value indicates that the sweep is defined <br/>in a counter-clockwise direction. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusFillPie(source) {#EmfPlusFillPie_source_1}


```
 EmfPlusFillPie(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

