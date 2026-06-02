---
title: "فئة EmfPlusPathGradientBrushData"
type: docs
weight: 500
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | ينشئ مثيلًا جديدًا من فئة EmfPlusPathGradientBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | يحصل أو يضبط حد فرشاة تدرج المسار، الذي يُحدد إما بمسار أو بمنحنى كاردينال مغلق. <br/>            إذا تم تعيين علامة BrushDataPath في حقل BrushDataFlags، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6)؛ <br/>            وإلا، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد البيانات في الحقل OptionalData.<br/>            يجب أن يتكون هذه القيمة من علامات BrushData (القسم 2.1.2.1). العلامات التالية ذات صلة بفرشاة تدرج المسار: |
| center_argb_32_color | int | r/w | يحصل أو يضبط كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز ل<br/>            فرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. <br/>            يتغير لون الفرشاة تدريجيًا من لون الحد <br/>            إلى لون المركز كلما انتقل من الحد إلى نقطة المركز. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يضبط كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، <br/>            وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون<br/>            الفرشاة تدريجيًا من لون الحد إلى لون المركز كلما انتقل<br/>            من الحد إلى نقطة المركز. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | يحصل أو يضبط كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي <br/>            يحدد بيانات إضافية لفرشاة تدرج المسار. <br/>            يتم تحديد محتويات هذا الحقل بناءً على قيمة حقل BrushDataFlags. |
| surrounding_argb_32_colors | int[] | r/w | يحصل أو يضبط مصفوفة من كائنات EmfPlusARGB عددها SurroundingColorCount <br/>            التي تحدد الألوان للنقاط المتقطعة على حد الفرشاة. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | يحصل أو يضبط عددًا صحيحًا 32 بت من تعداد WrapMode (القسم 2.1.1.34) يحدد<br/>            ما إذا كان سيتم رسم المنطقة خارج حد الفرشاة. عند الرسم <br/>            خارج الحد، يحدد وضع الالتفاف كيفية تكرار تدرج اللون |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

ينشئ مثيلًا جديدًا من فئة EmfPlusPathGradientBrushData

