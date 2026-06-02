---
title: "الفئة EmfPlusLinearGradientBrushOptionalData"
type: docs
weight: 450
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | يقوم بتهيئة نسخة جديدة من الفئة EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | يحصل أو يعيّن نمط مزج اختياري لفرشاة التدرج الخطي. إذا كان هذا الحقل موجودًا، <br/>            يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، <br/>            أو على كائن أو كائنين EmfPlusBlendFactors (القسم 2.2.2.5)، <br/>            ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لـ <br/>            أعلام BrushData في EmfPlusLinearGradientBrushData والأنماط المقابلة للمزج:<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | يحصل على نمط المزج كعوامل مزج h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | يحصل على نمط المزج كعوامل مزج v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | يحصل على نمط المزج كلون مسبق. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد<br/>            تحويل مساحة العالم إلى مساحة الجهاز لفرشاة التدرج الخطي. <br/>            يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة BrushDataTransform في<br/>            حقل BrushDataFlags لكائن EmfPlusLinearGradientBrushData. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

يقوم بتهيئة نسخة جديدة من الفئة EmfPlusLinearGradientBrushOptionalData

