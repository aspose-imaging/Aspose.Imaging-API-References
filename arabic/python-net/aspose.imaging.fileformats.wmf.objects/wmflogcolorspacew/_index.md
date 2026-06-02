---
title: "فئة WmfLogColorSpaceW"
type: docs
weight: 390
url: /ar/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

**Summary:** The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW__1) | يُنشئ مثيلًا جديدًا من الفئة WmfLogColorSpaceW |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد نوع مساحة اللون<br/>                . يجب أن يكون معرفًا في تعداد LogicalColorSpace<br/>                (القسم 2.1.1.14). إذا كانت هذه القيمة LCS_sRGB أو<br/>                LCS_WINDOWS_COLOR_SPACE، يجب استخدام مساحة اللون sRGB. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) الذي يحدد<br/>                إحداثيات اللون CIE x و y و z للثلاثة ألوان<br/>                التي تتCorrespond إلى RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) للمساحة اللونية المنطقية<br/>                المرتبطة بصورة البت. إذا كان حقل<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) لا يحدد<br/>                LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| filename | string | r/w | يحصل أو يعيّن سلسلة أحرف Unicode UTF16-LE منتهية بصفر اختيارية، والتي تحدد اسم ملف يحتوي على ملف تعريف لون.<br/>                إذا تم تحديد اسم ملف، وكان حقل<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) مضبوطًا على LCS_CALIBRATED_RGB، يجب أن تُهمل الحقول الأخرى لهذا الهيكل. |
| gamma_blue | int | r/w | يحصل أو يعيّن قيمة ثابتة 32 بت تحدد منحنى الاستجابة المظللة للون الأزرق. إذا كان حقل [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| gamma_green | int | r/w | يحصل أو يعيّن قيمة ثابتة 32 بت تحدد منحنى الاستجابة المظللة للون الأخضر. إذا كان حقل [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| gamma_red | int | r/w | يحصل أو يعيّن قيمة ثابتة 32 بت تحدد منحنى الاستجابة المظللة للون الأحمر. إذا كان حقل [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد نية تعيين النطاق اللوني.<br/>                يجب أن يكون معرفًا في تعداد GamutMappingIntent<br/>                (القسم 2.1.1.11). |
| signature | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) لكائنات مساحة اللون؛ يجب تعيينه إلى<br/>                القيمة 0x50534F43، وهي الترميز ASCII للسلسلة<br/>                "PSOC". |
| size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) لهذا الكائن، بالبايت. |
| version | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رقمًا<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/)؛ يجب أن يكون 0x00000400. |


### Constructor: WmfLogColorSpaceW() {#WmfLogColorSpaceW__1}


```
 WmfLogColorSpaceW() 
```

يُنشئ مثيلًا جديدًا من الفئة WmfLogColorSpaceW

