---
title: "فئة EmfBlendFunction"
type: docs
weight: 90
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | ينشئ نسخة جديدة من الفئة EmfBlendFunction |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | ينشئ نسخة جديدة من الفئة [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | يحصل على بنية تحدد كيفية تفسير بكسلات المصدر والوجهة <br/>            بالنسبة للشفافية الألفا. |
| blend_flags | System.Byte | r | يحصل على علامات الدمج.<br/>            يجب أن تكون هذه القيمة 0x00 ويجب تجاهلها. |
| blend_operation | System.Byte | r | يحصل على رمز عملية الدمج. <br/>            عملية الدمج الوحيدة للمصدر والوجهة التي تم تعريفها هي 0x00، والتي تحدد أن bitmap المصدر <br/>            يجب دمجه مع bitmap الوجهة بناءً على قيم الشفافية ألفا <br/>            لبكسلات المصدر. راجع المعادلات التالية للحصول على التفاصيل. |
| src_constant_alpha | System.Byte | r | يحصل على عدد صحيح غير موقع 8‑bit يحدد شفافية ألفا، <br/>            التي تحدد دمج bitmap المصدر و bitmap الوجهة. يجب أن تُستخدم هذه القيمة <br/>            على كامل bitmap المصدر. قيمة شفافية ألفا الدنيا، الصفر، <br/>            تمثل شفافية تامة، والقيمة القصوى 0xFF تمثل عدم شفافية تامة. عمليًا، قيمة 0xFF تحدد أن قيم ألفا لكل بكسل <br/>            تحدد دمج bitmap المصدر و bitmap الوجهة. راجع المعادلات لاحقًا في <br/>            هذا القسم للحصول على التفاصيل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [to_int()](#to_int__1) | Converts the string representation of a number to an integer. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

ينشئ نسخة جديدة من الفئة EmfBlendFunction

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

ينشئ نسخة جديدة من الفئة [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dword_data | int | بيانات الـ dword. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Converts the string representation of a number to an integer.

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة الـ DWORD للهيكل. |


