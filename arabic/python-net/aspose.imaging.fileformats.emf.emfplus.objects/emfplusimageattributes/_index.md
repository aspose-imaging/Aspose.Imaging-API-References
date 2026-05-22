---
title: "فئة EmfPlusImageAttributes"
type: docs
weight: 390
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | ينشئ مثلاً جديداً من فئة EmfPlusImageAttributes |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون الحافة للاستخدام <br/>            عندما تكون قيمة WrapMode هي WrapModeClamp. هذا اللون يظهر عندما يكون <br/>            المستطيل المصدر الذي تعالجه سجل EmfPlusDrawImage (القسم 2.3.4.8) <br/>            أكبر من الصورة نفسها. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | يحصل أو يعيّن عدد صحيح موقع 32‑بت يحدد سلوك تثبيت الكائن.<br/>            لا يُستخدم إلا بعد تطبيق هذا الكائن على صورة يتم <br/>            رسمها. يجب أن تكون هذه القيمة واحدة من القيم المعرفة في <br/>            الجدول التالي. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | يحصل أو يضبط الإصدار. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32‑بت يحدد كيفية معالجة ظروف الحافة باستخدام <br/>            قيمة من تعداد WrapMode (القسم 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

ينشئ مثلاً جديداً من فئة EmfPlusImageAttributes

