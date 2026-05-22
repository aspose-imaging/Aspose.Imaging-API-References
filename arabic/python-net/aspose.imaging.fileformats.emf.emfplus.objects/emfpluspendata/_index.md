---
title: "الفئة EmfPlusPenData"
type: docs
weight: 550
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | يُنشئ مثيلاً جديدًا من الفئة EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | يحصل أو يعيّن كائن EmfPlusPenOptionalData اختياري (القسم 2.2.2.34) <br/>            الذي يحدد بيانات إضافية لكائن القلم. المحتويات المحددة لهذا الحقل تُحدد بقيمة حقل <br/>            PenDataFlags. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل <br/>            OptionalData. يجب أن تكون هذه القيمة مكوّنة من أعلام PenData <br/>            (القسم 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وحدات القياس <br/>            للقلم. يجب أن تكون القيمة من تعداد UnitType <br/>            (القسم 2.1.1.33). |
| pen_width | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عرض <br/>            الخط المرسوم بالقلم بالوحدات المحددة في حقل PenUnit <br/>           . إذا تم تحديد عرض صفر، تُستخدم قيمة دنيا، <br/>            التي تُحدد حسب الوحدات. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

يُنشئ مثيلاً جديدًا من الفئة EmfPlusPenData

