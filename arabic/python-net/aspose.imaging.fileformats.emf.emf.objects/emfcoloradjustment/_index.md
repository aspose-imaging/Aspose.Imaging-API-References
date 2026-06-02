---
title: "فئة EmfColorAdjustment"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | يُنشئ مثيلاً جديدًا من فئة EmfColorAdjustment |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح غاما للقوة n للون الأساسي الأزرق للألوان المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. <br/>            قيمة 10,000 تعني أنه لا يجب إجراء تصحيح غاما. |
| السطوع | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 16 بت يحدد مقدار السطوع الذي سيُطبق على الكائن المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من –100 إلى 100.<br/>            قيمة الصفر تعني أنه لا يجب إجراء تعديل السطوع. |
| colorfullness | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 16 بت يحدد مقدار الإشباع اللوني الذي سيُطبق على الكائن المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. <br/>            قيمة الصفر تعني أنه لا يجب إجراء تعديل الإشباع اللوني |
| التباين | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 16 بت يحدد مقدار التباين الذي سيُطبق على الكائن المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجب إجراء تعديل التباين. |
| green_gamma | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح غاما للقوة n للون الأساسي الأخضر للألوان المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. <br/>            قيمة 10,000 تعني أنه لا يجب إجراء تصحيح غاما. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد نوع مصدر الضوء القياسي الذي تُعرض تحته الصورة، من تعداد Illuminant (القسم 2.1.19). |
| red_gamma | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح غاما للقوة n للون الأساسي الأحمر للألوان المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000.<br/>            قيمة 10,000 تعني أنه لا يجب إجراء تصحيح غاما. |
| red_green_tint | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 16 بت يحدد مقدار تعديل الصبغة الحمراء أو الخضراء الذي سيُطبق على الكائن المصدر.<br/>            يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. <br/>            الأعداد الموجبة تضبط الصبغة نحو الأحمر والأعداد السالبة تضبطها نحو الأخضر. <br/>            قيمة الصفر تعني أنه لا يجب إجراء تعديل الصبغة. |
| reference_black | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد المرجع الأسود للألوان المصدر.<br/>            أي ألوان أغمق من ذلك تُعامل كأنها سوداء. <br/>            يجب أن تكون هذه القيمة في النطاق من صفر إلى 4,000 |
| reference_white | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد المرجع الأبيض للألوان المصدر.<br/>            أي ألوان أفتح من ذلك تُعامل كأنها بيضاء. <br/>            يجب أن تكون هذه القيمة في النطاق من 6,000 إلى 10,000. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد الحجم بالبايت لهذا الكائن. يجب أن يكون هذا 0x0018. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد طريقة إعداد الصورة الناتجة. يمكن أن يكون <br/>            تعيينه إلى NULL أو إلى أي تركيبة من القيم في تعداد ColorAdjustment (القسم 2.1.5). |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

يُنشئ مثيلاً جديدًا من فئة EmfColorAdjustment

