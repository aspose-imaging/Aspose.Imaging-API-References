---
title: "الفئة EmfPlusTextureBrushData"
type: docs
weight: 680
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | يقوم بتهيئة نسخة جديدة من الفئة EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد البيانات في حقل OptionalData. <br/>            يجب أن تتكون هذه القيمة من أعلام BrushData (القسم 2.1.2.1). <br/>            الأعلام التالية ذات صلة بفرشاة النسيج<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | يحصل أو يعيّن كائن EmfPlusTextureBrushOptionalData اختياري (القسم 2.2.2.46) الذي <br/>            يحدد بيانات إضافية لفرشاة النسيج. المحتويات المحددة لهذا الحقل يتم تحديدها بقيمة حقل BrushDataFlags |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت من تعداد WrapMode (القسم 2.1.1.34) <br/>            الذي يحدد كيفية تكرار صورة النسيج عبر الشكل، عندما تكون <br/>            الصورة أصغر من المنطقة التي يتم ملؤها. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

يقوم بتهيئة نسخة جديدة من الفئة EmfPlusTextureBrushData

