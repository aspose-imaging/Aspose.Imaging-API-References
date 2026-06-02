---
title: "الفئة EmfLogBrushEx"
type: docs
weight: 120
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | يُنشئ نسخة جديدة من الفئة EmfLogBrushEx |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | يحصل أو يعيّن كائن WMF ColorRef 32‑بت ([MS-WMF] القسم 2.2.2.8) يحدد <br/>            لونًا. تفسير هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في <br/>            الجدول التالي. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | يحصل أو يعيّن حقلًا غير موقع 32‑بت يحتوي على بيانات نمط الفرشاة. تفسيره <br/>            يعتمد على قيمة BrushStyle، |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نمط الفرشاة. يجب أن تكون القيمة <br/>            من تعداد WMF BrushStyle enumeration ([MS-WMF] القسم 2.1.1.4). قيم الأنماط <br/>            المدعومة في هذه البنية مُدرجة لاحقًا في هذا القسم. يجب استخدام نمط BS_NULL <br/>            لتحديد فرشاة لا تُحدث أي تأثير. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

يُنشئ نسخة جديدة من الفئة EmfLogBrushEx

