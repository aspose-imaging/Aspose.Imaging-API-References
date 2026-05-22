---
title: "EmfEpsData Class"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | ينشئ مثيلًا جديدًا من الفئة EmfEpsData. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | يحصل أو يعيّن مصفوفة من ثلاثة كائنات Point28_4 (القسم 2.2.23) التي تحدد <br/>            إحداثيات المتوازي المستطيل الناتج باستخدام تدوين FIX بدقة 28.4 بت |
| post_script_data | System.Byte | r/w | يحصل أو يعيّن مصفوفة من بايتات بيانات PostScript. يمكن حساب طول هذه المصفوفة <br/>            من حقل SizeData. قد يتم استخدام هذه البيانات لتصيير صورة. |
| size_data | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد الحجم الكلي لهذا الكائن، بالبايت. |
| الإصدار | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد مستوى لغة PostScript. يجب أن تكون هذه <br/>            القيمة 0x00000001. |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

ينشئ مثيلًا جديدًا من الفئة EmfEpsData.

