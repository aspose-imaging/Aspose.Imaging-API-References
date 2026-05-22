---
title: "EmfPlusBlurEffect Class"
type: docs
weight: 100
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | ينشئ مثلاً جديداً من الفئة EmfPlusBlurEffect. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | الحصول أو تعيين عدد عائم 32‑بت يحدد نصف قطر الضبابية بالبكسل،<br/>            والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين.<br/>            يجب أن تكون هذه القيمة في النطاق من 0.0 إلى 255.0. |
| expand_edge | bool | r/w | الحصول أو تعيين قيمة منطقية 32‑بت تحدد ما إذا كانت الصورة النقطية تتوسع بمقدار يساوي قيمة BlurRadius لإنتاج حواف ناعمة. يجب أن تكون هذه القيمة أحد التالي:<br/>            FALSE<br/>            0x00000000<br/>            يجب ألا يتغير حجم الصورة النقطية، ويجب قص حوافها الناعمة إلى حجم BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            يجب أن يتوسع حجم الصورة النقطية بمقدار يساوي BlurRadius لإنتاج حواف ناعمة. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

ينشئ مثلاً جديداً من الفئة EmfPlusBlurEffect.

