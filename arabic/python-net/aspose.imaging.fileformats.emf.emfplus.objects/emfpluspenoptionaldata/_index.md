---
title: "الفئة EmfPlusPenOptionalData"
type: docs
weight: 560
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | يقوم بإنشاء نسخة جديدة من الفئة EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | يحصل أو يحدد كائن EmfPlusCompoundLineData اختياري (section 2.2.2.9) <br/>            يحدد مصفوفة من القيم العائمة التي تُعرّف <br/>            الخط المركب للقلم، والذي يتكوّن من خطوط موازية <br/>            ومسافات. يجب أن يكون هذا الحقل موجودًا إذا كان <br/>            علم PenDataCompoundLine مُحددًا في حقل PenDataFlags <br/>            لكائن EmfPlusPenData |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | يحصل أو يحدد كائن EmfPlusCustomEndCapData اختياري (section 2.2.11) <br/>            يعرّف شكل النهاية المخصّصة، وهو الشكل المستخدم <br/>            في نهاية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا من <br/>            الأشكال المتنوعة، مثل مربع أو دائرة أو ماسي. يجب أن يكون هذا <br/>            الحقل موجودًا إذا كان علم PenDataCustomEndCap <br/>            مُحددًا في حقل PenDataFlags لكائن EmfPlusPenData |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | يحصل أو يحدد كائن EmfPlusCustomStartCapData اختياري (section 2.2.2.15) <br/>            يعرّف شكل البداية المخصّصة، وهو الشكل المستخدم <br/>            في بداية الخط المرسوم بهذا القلم. يمكن أن يكون أيًا <br/>            من الأشكال المتنوعة، مثل مربع أو دائرة أو ماسي. <br/>            يجب أن يكون هذا الحقل موجودًا إذا كان علم PenDataCustomStartCap <br/>            مُحددًا في حقل PenDataFlags لكائن EmfPlusPenData |
| dash_offset | float | r/w | يحصل أو يحدد قيمة عائمة 32-بت اختيارية تحدد <br/>            المسافة من بداية الخط إلى بداية <br/>            الفراغ الأول في نمط الخط المتقطّع. يجب أن يكون هذا الحقل <br/>            موجودًا إذا كان علم PenDataDashedLineOffset مُحددًا في <br/>            حقل PenDataFlags لكائن EmfPlusPenData. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | يحصل أو يحدد عددًا صحيحًا موقعًا 32-بت اختياري يحدد الشكل <br/>            لكلا طرفي كل شَرطَة في خط متقطّع. يجب أن يكون هذا الحقل <br/>            موجودًا إذا كان علم PenDataDashedLineCap مُحددًا في <br/>            حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون <br/>            القيمة معرفة في تعداد DashedLineCapType <br/>            (section 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | يحصل أو يحدد كائن EmfPlusDashedLineData اختياري (section 2.2.2.16) <br/>            يحدد أطوال الشرطات والمسافات في خط متقطّع مخصّص. يجب أن يكون هذا الحقل موجودًا إذا كان علم PenDataDashedLine <br/>            مُحددًا في حقل PenDataFlags لكائن EmfPlusPenData<br/>            . |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | يحصل أو يحدد عددًا صحيحًا موقعًا 32-بت اختياري يحدد الشكل<br/>             لنهاية الخط في حقل CustomEndCapData. يجب أن يكون هذا <br/>            الحقل موجودًا إذا كان علم PenDataEndCap مُحددًا في <br/>            حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة <br/>            معرفة في تعداد LineCapType |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | يحصل أو يحدد عددًا صحيحًا موقعًا 32-بت اختياري يحدد كيفية ربط<br/>             خطين يتم رسمهما بنفس القلم وتلتقي نهايتهما. يجب أن يكون هذا الحقل موجودًا إذا كان علم PenDataJoin مُحددًا في <br/>            حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineJoinType <br/>            (section 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | يحصل أو يحدد عددًا صحيحًا موقعًا 32-بت اختياري يحدد النمط <br/>            المستخدم للخطوط المرسومة بهذا القلم. يجب أن يكون هذا الحقل <br/>            موجودًا إذا كان علم PenDataLineStyle مُحددًا في <br/>            حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineStyle <br/>            (section 2.1.1.20). |
| miter_limit | float | r/w | يحصل أو يضبط قيمة اختيارية عائمة 32-بت تحدد حد الميتر <br/>            وهو النسبة القصوى المسموح بها لطول الميتر إلى<br/>            عرض الخط. طول الميتر هو المسافة من<br/>            تقاطع جدران الخط من داخل الوصلة إلى <br/>            تقاطع جدران الخط من خارج الوصلة. <br/>            يمكن أن يكون طول الميتر كبيرًا عندما تكون الزاوية بين خطين <br/>            صغيرة. يجب أن يكون هذا الحقل موجودًا إذا كان<br/>            علم PenDataMiterLimit مضبوطًا في حقل PenDataFlags <br/>            لكائن EmfPlusPenData. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت اختياريًا يحدد <br/>            توزيع عرض القلم بالنسبة إلى<br/>            إحداثيات الخط المرسوم. يجب أن يكون هذا الحقل موجودًا إذا كان علم PenDataNonCenter مضبوطًا في <br/>            حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد PenAlignment (القسم 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت اختياريًا يحدد الشكل لبداية الخط في حقل CustomStartCapData. يجب أن يكون هذا الحقل موجودًا إذا كان علم PenDataStartCap مضبوطًا في حقل PenDataFlags لكائن EmfPlusPenData، ويجب أن تكون القيمة معرفة في تعداد LineCapType (القسم 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) <br/>            يحدد تحويل الفضاء العالمي إلى فضاء الجهاز للقلم. يجب أن يكون هذا الحقل موجودًا إذا كان علم PenDataTransform مضبوطًا في حقل PenDataFlags لكائن EmfPlusPenData. |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

يقوم بإنشاء نسخة جديدة من الفئة EmfPlusPenOptionalData

