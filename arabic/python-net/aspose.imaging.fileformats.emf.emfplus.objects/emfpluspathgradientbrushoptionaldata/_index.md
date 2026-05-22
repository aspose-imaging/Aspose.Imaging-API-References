---
title: "فئة EmfPlusPathGradientBrushOptionalData"
type: docs
weight: 510
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | ينشئ مثيلًا جديدًا من فئة EmfPlusPathGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | يحصل أو يعيّن نمط دمج اختياري لفرشاة التدرج المساري. إذا كان هذا الحقل<br/>            موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، <br/>            أو على كائن EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. <br/>            يوضح الجدول أدناه التركيبات الصالحة لعلامات EmfPlusPathGradientBrushData<br/>            BrushData والأنماط المقابلة للدمج. |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | يحصل أو يعيّن كائن EmfPlusFocusScaleData اختياري (القسم 2.2.2.18) يحدد <br/>            مقاييس التركيز لفرشاة التدرج المساري. يجب أن يكون هذا الحقل موجودًا إذا كان<br/>            علم BrushDataFocusScales مُحددًا في حقل BrushDataFlags الخاص بـ <br/>            كائن EmfPlusPathGradientBrushData. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز لفرشاة التدرج المساري. <br/>            يجب أن يكون هذا الحقل موجودًا إذا كان علم BrushDataTransform مُحددًا في حقل BrushDataFlags الخاص بكائن EmfPlusPathGradientBrushData. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

ينشئ مثيلًا جديدًا من فئة EmfPlusPathGradientBrushOptionalData

