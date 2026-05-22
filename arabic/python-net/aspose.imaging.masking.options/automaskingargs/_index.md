---
title: "فئة AutoMaskingArgs"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | يُنشئ نسخة جديدة من فئة AutoMaskingArgs |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | يحصل أو يعيّن الحد الأقصى لعدد التكرارات. |
| number_of_objects | int | r/w | يحصل أو يعيّن عدد الكائنات<br/>            لتقسيم الصورة الأولية إلى (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | يحصل أو يعيّن النقاط التي تنتمي إلى الكائنات المفصولة (اختياري)<br/>            إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية.<br/>            يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري).<br/>            يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن النقاط التي لم تعد تنتمي إلى أي كائن (اختياري).<br/>            يُستخدم هذا المعامل فقط في حالة إعادة التجزئة. |
| precision | float | r/w | يحصل أو يعيّن دقة طريقة التجزئة (اختياري). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

يُنشئ نسخة جديدة من فئة AutoMaskingArgs

