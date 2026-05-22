---
title: "فئة EmfPlusCustomLineCapData"
type: docs
weight: 270
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | يقوم بإنشاء نسخة جديدة من الفئة EmfPlusCustomLineCapData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) <br/>            الذي تستند إليه قبضة الخط المخصصة. |
| base_inset | float | r/w | يحصل أو يعيّن قيمة عائمة 32-بت تحدد المسافة بين بداية <br/>            قبضة الخط ونهاية الخط. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن كائن EmfPlusPointF غير مستخدم حاليًا. يجب تعيينه إلى {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | يحصل أو يعيّن كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14)<br/>             الذي يحدد بيانات إضافية لقبضة الخط الرسومية المخصصة. T<br/>            المحتويات المحددة لهذا الحقل تُحدد <br/>            بقيمة حقل CustomLineCapDataFlags. |
| stroke_end_cap | int | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى <br/>            قبضة الخط التي ستُستخدم في نهاية الخط المراد رسمه. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن كائن EmfPlusPointF غير مستخدم حاليًا. يجب تعيينه إلى {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineJoin <br/>            (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بـ<br/>            نفس القلم وتلتقي نهاياتهما. عند تقاطع نهايتي الخطين، <br/>            يجعل ربط الخط الاتصال يبدو أكثر استمرارية. |
| stroke_miter_limit | float | r/w | يحصل أو يعيّن قيمة عائمة 32-بت تحتوي على حد سمك<br/>             الوصلة عند زاوية ميتة عن طريق ضبط النسبة القصوى المسموح بها<br/>             لطول الوصلة إلى عرض الخط. |
| stroke_start_cap | int | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى <br/>            قبضة الخط المستخدمة في بداية الخط المراد رسمه |
| width_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32-بت تحدد مقدار ما يجب <br/>             تعديل قبضة الخط المخصصة بالنسبة إلى عرض كائن EmfPlusPen <br/>            (القسم 2.2.1.7) المستخدم لرسم الخطوط. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

يقوم بإنشاء نسخة جديدة من الفئة EmfPlusCustomLineCapData

