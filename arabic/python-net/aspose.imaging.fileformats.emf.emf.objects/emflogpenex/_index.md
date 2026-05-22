---
title: "فئة EmfLogPenEx"
type: docs
weight: 190
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | ينشئ مثيلًا جديدًا من فئة EmfLogPenEx |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8). يعتمد تفسير هذا<br/>            الحقل على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن نمط الفرشاة dib. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | يحصل أو يعيّن نمط تظليل الفرشاة. يعتمد تعريف هذا الحقل على قيمة <br/>            BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نمط فرشاة للقلم من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). <br/>            إذا كان نوع القلم في حقل PenStyle هو PS_GEOMETRIC، يجب أن تكون هذه القيمة إما <br/>            BS_SOLID أو BS_HATCHED. يمكن أن تكون قيمة هذا الحقل BS_NULL، ولكن فقط إذا كان <br/>            نمط الخط المحدد في PenStyle هو PS_NULL. يجب استخدام نمط BS_NULL <br/>            لتحديد فرشاة لا تؤثر. |
| num_style_entities | int | r | يحصل على عدد العناصر في المصفوفة المحددة في حقل StyleEntry. <br/>            يجب أن تكون هذه القيمة صفرًا إذا لم يحدد PenStyle قيمة PS_USERSTYLE. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | يحصل أو يعيّن نمط القلم |
| style_entry | int[] | r/w | يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة غير الموقعة 32‑بت التي تحدد أطوال <br/>            الشرطات والفواصل في الخط المرسوم بهذا القلم، عندما تكون قيمة PenStyle <br/>            هي نمط الخط PS_USERSTYLE للقلم. تحتوي المصفوفة على عدد من <br/>            الإدخالات المحددة بواسطة NumStyleEntries، لكنها تُستعمل كما لو أنها تتكرر إلى ما لا نهاية <br/>            الإدخال الأول في المصفوفة يحدد طول الشرط الأول. الإدخال الثاني <br/>            يحدد طول الفاصل الأول. بعد ذلك، تتناوب أطوال الشرطات والفواصل.<br/>            إذا كان نوع القلم في حقل PenStyle هو PS_GEOMETRIC، فإن الأطوال تُحدد بوحدات منطقية؛ وإلا تُحدد بوحدات الجهاز. |
| width | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عرض الخط المرسوم بالقلم.<br/>            إذا كان نوع القلم في حقل PenStyle هو PS_GEOMETRIC، فإن هذه القيمة هي العرض بوحدات<br/>            منطقية؛ وإلا يُحدد العرض بوحدات الجهاز. <br/>            إذا كان نوع القلم في حقل PenStyle هو PS_COSMETIC، يجب أن تكون هذه القيمة 0x00000001. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

ينشئ مثيلًا جديدًا من فئة EmfLogPenEx

