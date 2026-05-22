---
title: "فئة WmfLogColorSpace"
type: docs
weight: 380
url: /ar/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | يُنشئ مثيلًا جديدًا من الفئة WmfLogColorSpace |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد نوع مساحة اللون<br/>                . يجب أن يكون معرفًا في تعداد LogicalColorSpace<br/>                (القسم 2.1.1.14). إذا كانت هذه القيمة LCS_sRGB أو<br/>                LCS_WINDOWS_COLOR_SPACE، يجب استخدام مساحة اللون sRGB. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) الذي يحدد<br/>                إحداثيات اللون CIE x و y و z للثلاثة ألوان<br/>                التي تتCorrespond إلى RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) للمساحة اللونية المنطقية<br/>                المرتبطة بصورة البت. إذا كان حقل<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) لا يحدد<br/>                LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| filename | string | r/w | يحصل أو يعيّن سلسلة أحرف ASCII اختيارية تحدد اسم ملف يحتوي على ملف تعريف لون. إذا تم تحديد اسم ملف، وكان حقل [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) مضبوطًا على LCS_CALIBRATED_RGB، يجب أن تُهمل الحقول الأخرى لهذا الهيكل. |
| gamma_blue | int | r/w | يحصل أو يعيّن قيمة ثابتة 32 بت تحدد منحنى الاستجابة المظللة للون الأزرق. إذا كان حقل [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| gamma_green | int | r/w | يحصل أو يعيّن قيمة ثابتة 32 بت تحدد منحنى الاستجابة المظللة للون الأخضر. إذا كان حقل [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| gamma_red | int | r/w | يحصل أو يعيّن قيمة ثابتة 32 بت تحدد منحنى الاستجابة المظللة للون الأحمر. إذا كان حقل [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد نية تعيين النطاق اللوني.<br/>                يجب أن يكون معرفًا في تعداد GamutMappingIntent<br/>                (القسم 2.1.1.11). |
| signature | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) لكائنات مساحة اللون؛ يجب تعيينه إلى<br/>                القيمة 0x50534F43، وهي الترميز ASCII للسلسلة<br/>                "PSOC". |
| size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) لهذا الكائن، بالبايت. |
| version | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رقمًا<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)؛ يجب أن يكون 0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

يُنشئ مثيلًا جديدًا من الفئة WmfLogColorSpace

