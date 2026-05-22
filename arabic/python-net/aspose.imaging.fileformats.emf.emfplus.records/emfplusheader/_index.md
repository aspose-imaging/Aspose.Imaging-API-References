---
title: "فئة EmfPlusHeader"
type: docs
weight: 310
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | يُنشئ مثلاً جديداً من الفئة [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| dual_mode | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode].<br/>            إذا تم تعيينها، فإن هذا العلم يشير إلى أن ملف الميتا هذا "ثنائي الوضع"، مما يعني<br/>            أنه يحتوي على مجموعتين من السجلات، كل واحدة منهما تحدد محتوى الرسومات بالكامل.<br/>            إذا لم يتم تعيينه، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+ <br/>            وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC.<br/>            إذا تم تعيين هذا العلم، يجب أن تكون سجلات EMF وحدها كافية لتحديد <br/>            محتوى الرسومات. لاحظ أنه سواء تم تعيين علم "ثنائي الوضع" أم لا، فإن بعض <br/>            سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي <br/>            تحتوي على سجلات EMF+.<br/>            سجلات التحكم في EMF موصوفة في [MS-EMF] <br/>            القسم 2.3.4. |
| emf_plus_flags | int | r/w | يحصل أو يعيّن أعلام EMF plus.<br/>            عدد صحيح غير موقع 32‑بت يحتوي على معلومات حول كيفية تسجيل ملف الميتا هذا.<br/>            إذا تم تعيين البت الـ31 من الحقل، فإن هذا العلم يشير إلى أن ملف الميتا تم تسجيله باستخدام <br/>            سياق جهاز مرجعي لعرض الفيديو. إذا لم يتم تعيينه، تم تسجيل ملف الميتا باستخدام<br/>            سياق جهاز مرجعي للطابعة. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل صالحًا. |
| logical_dpi_x | int | r/w | يحصل أو يعيّن قيمة dpi المنطقي x.<br/>            عدد صحيح غير موقع 32‑بت يحدد الدقة الأفقية التي سُجّل من أجلها ملف الميتا <br/>            بوحدات البكسل لكل بوصة. |
| logical_dpi_y | int | r/w | يحصل أو يعيّن قيمة dpi المنطقي y.<br/>            عدد صحيح غير موقع 32‑بت يحدد الدقة العمودية التي سُجّل من أجلها ملف الميتا <br/>            بوحدات الخطوط لكل بوصة. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | يحصل أو يعيّن الإصدار.<br/>            كائن EmfPlusGraphicsVersion (القسم 2.2.2.19) يحدد نسخة رسومات نظام التشغيل التي تم استخدامها لإنشاء ملف الميتا هذا. |
| video_display | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو.<br/>            إذا تم تعيينه، فإن هذا العلم يشير إلى أن ملف الميتا تم تسجيله باستخدام سياق جهاز مرجعي لعرض الفيديو. إذا لم يتم تعيينه، تم تسجيل ملف الميتا باستخدام سياق جهاز مرجعي للطابعة. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

يُنشئ مثلاً جديداً من الفئة [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

