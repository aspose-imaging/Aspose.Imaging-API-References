---
title: "فئة EmfText"
type: docs
weight: 260
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfText()](#EmfText__1) | ينشئ مثلاً جديداً من فئة EmfText |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| chars | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع بحجم 32‑بت يحدد عدد الأحرف في السلسلة |
| dx_buffer | int[] | r/w | يحصل أو يضبط مخزن تباعد الأحرف الاختياري<br/>            UndefinedSpace2 (متغير): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع الحقل OutputDx <br/>            مباشرة الجزء السابق من هذه البنية.<br/>            OutputDx (متغير): مصفوفة من الأعداد الصحيحة غير الموقعة بحجم 32‑بت تحدد تباعد الإخراج بين <br/>            أصول خلايا الأحرف المتجاورة بوحدات منطقية. يتم تحديد موقع هذا الحقل بقيمة offDx بالبايتات من بداية هذا السجل. إذا تم تعريف التباعد، يحتوي هذا الحقل على <br/>            نفس عدد القيم كعدد الأحرف في سلسلة الإخراج. إذا كان حقل Options لكائن EmrText <br/>            يحتوي على العلامة ETO_PDY، فإن هذا المخزن يحتوي على ضعف عدد القيم مقارنةً بعدد الأحرف في <br/>            سلسلة الإخراج، إزاحة أفقية وإزاحة رأسية لكل حرف، بهذا الترتيب. إذا تم تحديد ETO_RTLREADING، <br/>            تُرتب الأحرف من اليمين إلى اليسار بدلاً من اليسار إلى اليمين. لا تؤثر أي خيارات أخرى على تفسير هذا الحقل. |
| glyph_index_buffer | int[] | r/w | يحصل أو يضبط مخزن فهرس القوالب الاختياري.<br/>            إذا كان للخيارات علامة ETO_GLYPH_INDEX فإن رموز الأحرف في سلسلة النص المُخرجة هي في الواقع فهارس<br/>            لقوالب الأحرف في خط TrueType (تعداد ExtTextOutOptions القسم 2.1.11). فهارس القوالب خاصة بالخط،<br/>            لذا لعرض الأحرف الصحيحة عند التشغيل، يجب أن يكون الخط المستخدم مطابِقاً تماماً للخط المستخدم في<br/>            توليد الفهارس. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع بحجم 32‑بت يحدد طريقة استخدام المستطيل المحدد في حقل <br/>            Rectangle. يمكن أن يكون هذا الحقل مزيجًا من أكثر من قيمة لتعداد ExtTextOutOptions <br/>            (القسم 2.1.11). |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يضبط كائن WMF RectL اختياري ([MS-WMF] القسم 2.2.2.19) يحدد مستطيل قص <br/>            و/أو تعتيم بوحدات منطقية. يُطبّق هذا المستطيل على إخراج النص <br/>            الذي يتم بواسطة السجل الحاوي. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) يحدد إحداثيات <br/>            نقطة المرجع المستخدمة لتحديد موضع السلسلة. تُعرّف نقطة المرجع بواسطة سجل EMR_SETTEXTALIGN الأخير (القسم 2.3.11.25). إذا لم يتم تعيين مثل هذا السجل، <br/>            يكون المحاذاة الافتراضية هي TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | يحصل أو يضبط مخزن سلسلة الأحرف<br/>            UndefinedSpace1 (متغير): عدد اختياري من البايتات غير المستخدمة. <br/>            لا يُشترط أن يتبع الحقل OutputString مباشرة الجزء السابق من هذه البنية.<br/>            OutputString (متغير): مصفوفة من الأحرف تحدد السلسلة المراد إخراجها. <br/>            يتم تحديد موقع هذا الحقل بقيمة offString بالبايتات من بداية هذا السجل. <br/>            يُحدد عدد الأحرف بقيمة Chars. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

ينشئ مثلاً جديداً من فئة EmfText

