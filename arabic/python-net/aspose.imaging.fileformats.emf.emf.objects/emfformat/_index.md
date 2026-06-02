---
title: "فئة EmfFormat"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | ينشئ مثيلًا جديدًا من فئة EmfFormat |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| off_data | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الإزاحة إلى البيانات من <br/>            بداية حقل المعرف في سجل EMR_COMMENT_PUBLIC (القسم 2.3.3.4). <br/>            يجب أن تكون الإزاحة محاذية إلى 32‑بت. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد تنسيق بيانات الصورة. <br/>            يجب أن تكون هذه القيمة ضمن تعداد FormatSignature (القسم 2.1.14). |
| size_data | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم البيانات بالبايت. |
| الإصدار | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد رقم نسخة التنسيق. <br/>            إذا كان حقل Signature يحدد PostScript المغلف (EPS)، <br/>            يجب أن تكون هذه القيمة 0x00000001؛ وإلا يجب تجاهل هذه القيمة. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

ينشئ مثيلًا جديدًا من فئة EmfFormat

