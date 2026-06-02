---
title: "فئة EmfHeaderExtension2"
type: docs
weight: 100
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---

**Summary:** The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the<br/>            ability to measure device surfaces in micrometers, which enhances the resolution and scalability of EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension2

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfHeaderExtension2()](#EmfHeaderExtension2__1) | يُهيئ نسخة جديدة من فئة EmfHeaderExtension2 |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد الحدود المستطيلة شاملة-شاملة <br/>            بوحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في <br/>            ملف الميتا. |
| بايتات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم ملف الميتا، بالبايت. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | يحصل أو يعيّن كائن WMF SizeL ([MS-WMF] القسم 2.2.2.22) يحدد حجم الجهاز المرجعي، بالبكسل. |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL يحدد أبعاد المستطيل شاملة-شاملة، بوحدات .01 مليمتر <br/>            ، لمستطيل يحيط بالصورة المخزنة في ملف الميتا. |
| handles | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16-بت يحدد عدد كائنات الرسومات التي ستُستخدم أثناء معالجة ملف الميتا. |
| micrometers_x | int | r/w | يحصل أو يعيّن الحجم الأفقي 32-بت لجهاز العرض الذي تم إنشاء صورة ملف الميتا له، بالميكرومتر. |
| micrometers_y | int | r/w | يحصل أو يعيّن الحجم الرأسي 32-بت لجهاز العرض الذي تم إنشاء صورة ملف الميتا له، بالميكرومتر. |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | يحصل أو يعيّن كائن WMF SizeL يحدد حجم الجهاز المرجعي، بالمليمتر. |
| n_desription | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الأحرف في المصفوفة <br/>            التي تحتوي على وصف محتويات ملف الميتا. يكون الصفر إذا لم يكن هناك سلسلة وصف. |
| n_pal_entries | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الإدخالات في لوحة ألوان ملف الميتا <br/>            . تقع لوحة الألوان في سجل EMR_EOF. |
| off_description | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد الإزاحة من بداية هذا <br/>            السجل إلى المصفوفة التي تحتوي على وصف محتويات ملف الميتا. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد توقيع السجل. يجب أن يكون هذا ENHMETA_SIGNATURE، <br/>            من تعداد FormatSignature (القسم 2.1.14). |
| السجلات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد السجلات في ملف الميتا. |
| محجوز | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16-بت يجب أن يكون 0x0000 ويجب تجاهله. |
| valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) صالحًا. |
| الإصدار | int | r/w | يحصل أو يعيّن الإصدار (4 بايت): عدد صحيح غير موقع 32‑بت يحدد توافق ملف EMF. يجب أن يكون هذا 0x00010000. |


### Constructor: EmfHeaderExtension2() {#EmfHeaderExtension2__1}


```
 EmfHeaderExtension2() 
```

يُهيئ نسخة جديدة من فئة EmfHeaderExtension2

