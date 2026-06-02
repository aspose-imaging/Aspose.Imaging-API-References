---
title: "فئة EmfPlusDrawImagePoints"
type: docs
weight: 140
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [applying an effect].<br/>            هذه البتة تشير إلى أن عرض الصورة يتضمن تطبيق تأثير.<br/>            إذا تم الضبط، يجب أن يكون كائن من الفئة Effect قد تم تحديده في سجل EmfPlusSerializableObject سابق (القسم 2.3.5.2). |
| مضغوط | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان PointData مضغوطاً.<br/>            هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة.<br/>            إذا تم الضبط، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت.<br/>            إذا تم إلغاء الضبط، يحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت.<br/>            ملاحظة: إذا تم تعيين علم P (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| image_attributes_id | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحتوي على فهرس<br/>            كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| object_id | System.Byte | r/w | يحصل أو يضبط معرف الكائن.<br/>            فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+<br/>            الذي يحدد الصورة التي سيتم عرضها. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يضبط مصفوفة من نقاط Count التي تحدد ثلاث نقاط لمتوازي الأضلاع.<br/>            تمثل النقاط الثلاث الزاوية العليا اليسرى، العليا اليمنى، والسفلى اليسرى لـ<br/>            متوازي الأضلاع. يتم استنتاج النقطة الرابعة لمتوازي الأضلاع من الثلاث نقاط الأولى.<br/>            الجزء من الصورة المحدد بحقل SrcRect SHOULD يُطبق عليه تحويلات التكبير والقص إذا لزم الأمر لتناسب داخل متوازي الأضلاع. |
| relative | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) نسبيًا.<br/>            هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة.<br/>            إذا تم الضبط، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون<br/>            نسبياً للموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم إلغاء الضبط،<br/>            يحدد PointData المواقع المطلقة وفقًا لعلم C.<br/>            ملاحظة: إذا تم تعيين هذه العلامة، يكون علم C (أعلاه) غير معرف ويجب تجاهله. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد جزءًا من الصورة ليتم عرضه. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد وحدات حقل SrcRect. يجب أن يكون<br/>            قيمة UnitPixel من تعداد UnitType (القسم 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

