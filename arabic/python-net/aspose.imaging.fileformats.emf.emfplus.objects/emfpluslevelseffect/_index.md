---
title: "فئة EmfPlusLevelsEffect"
type: docs
weight: 420
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | يقوم بإنشاء نسخة جديدة من الفئة EmfPlusLevelsEffect |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| تمييز | int | r/w | يحصل أو يضبط يحدد مقدار إضاءة الإبرازات في الصورة. قيم قناة اللون<br/>            في الطرف العالي من نطاق الشدة تُعدل أكثر من القيم القريبة من<br/>            الوسط أو الطرف المنخفض، مما يعني أنه يمكن إضاءة الصورة دون فقدان التباين<br/>            بين الأجزاء الداكنة من الصورة.<br/>            0 ≤ value &lt; يحدد أن الإبرازات التي تتجاوز نسبة الشدة هذا العتبة SHOULD<br/>            100 تُزاد.<br/>            100 يحدد أن الإبرازات MUST NOT تتغير. |
| mid_tone | int | r/w | يحصل أو يضبط يحدد مقدار إضاءة أو تعتيم النغمات المتوسطة في الصورة. قيم قناة اللون<br/>            في وسط نطاق الشدة تُعدل أكثر من القيم القريبة من الطرف العالي<br/>            أو المنخفض، مما يعني أنه يمكن إضاءة أو تعتيم الصورة دون فقدان التباين<br/>            بين أقسام الصورة الأكثر ظلامًا وإضاءة.<br/>            -100 ≤ value &lt; 0 يحدد أن النغمات المتوسطة تُصبح أغمق.<br/>            0 يحدد أن النغمات المتوسطة MUST NOT تتغير.<br/>            0 &lt; value ≤ 100 يحدد أن النغمات المتوسطة تُصبح أفتح. |
| shadow | int | r/w | يحصل أو يضبط يحدد مقدار تعتيم الظلال في الصورة. قيم قناة اللون<br/>            في الطرف المنخفض من نطاق الشدة تُعدل أكثر من القيم القريبة من الوسط أو<br/>            الطرف العالي، مما يعني أنه يمكن تعتيم الصورة دون فقدان التباين بين الأجزاء<br/>            الأكثر إضاءة في الصورة.<br/>            0 يحدد أن الظلال MUST NOT تتغير.<br/>            0 &lt; value ≤ 100<br/>            يحدد أن الظلال التي تكون نسبتها من الشدة أقل من هذا العتبة تُصبح<br/>            أغمق. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

يقوم بإنشاء نسخة جديدة من الفئة EmfPlusLevelsEffect

