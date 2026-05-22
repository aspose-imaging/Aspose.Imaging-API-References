---
title: "EmfPlusTextureBrushOptionalData Class"
type: docs
weight: 690
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | ينشئ مثلاً جديداً من الفئة EmfPlusTextureBrushOptionalData. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | الحصول أو تعيين كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد<br/>            نسيج الفرشاة. يجب أن يكون هذا الحقل موجوداً إذا كان حجم<br/>            سجل EmfPlusObject (القسم 2.3.5.1) الذي يحدد هذا النسيج<br/>            الفرشاة كبيراً بما يكفي لاستيعاب كائن EmfPlusImage<br/>            بالإضافة إلى الحقول المطلوبة لكائن EmfPlusTextureBrushData<br/>            وربما كائن EmfPlusTransformMatrix. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | الحصول أو تعيين كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47)<br/>            يحدد تحويل من مساحة العالم إلى مساحة الجهاز للفرشاة<br/>            النسيجية. يجب أن يكون هذا الحقل موجوداً إذا تم تعيين علم BrushDataTransform<br/>            في حقل BrushDataFlags لكائن EmfPlusTextureBrushData. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

ينشئ مثلاً جديداً من الفئة EmfPlusTextureBrushOptionalData.

