---
title: "فئة EmfPlusBitmap"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | ينشئ مثلاً جديداً من فئة EmfPlusBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | يحصل أو يعيّن بيانات البت ماب<br/>            BitmapData (متغيّر): بيانات بطول متغيّر تُعرّف كائن بيانات البت ماب المحدد في حقل Type. يمكن أن يكون المحتوى<br/>            وتنسيق البيانات مختلفين لكل نوع من أنواع البت ماب. |
| height | int | r/w | يحصل أو يعيّن ارتفاع البت ماب<br/>            Height (4 بايت): عدد صحيح موقع 32‑بت يحدد الارتفاع بالبكسل للمنطقة التي يشغلها البت ماب.<br/>            إذا كانت الصورة مضغوطة، وفقاً لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | يحصل أو يعيّن تنسيق البكسل<br/>            PixelFormat (4 بايت): عدد صحيح غير موقع 32‑بت يحدد تنسيق البكسلات التي تُكوّن صورة البت ماب.<br/>            تنسيقات البكسل المدعومة مُحددة في تعداد [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (القسم 2.1.1.25).<br/>            إذا كانت الصورة مضغوطة، وفقاً لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |
| stride | int | r/w | يحصل أو يعيّن خطوة الصورة<br/>            Stride (4 بايت): عدد صحيح موقع 32‑بت يحدد إزاحة البايت بين بداية سطر مسح وآخر. هذه القيمة هي عدد البايتات لكل بكسل، المحدد في حقل PixelFormat، مضروباً في العرض بالبكسل المحدد في حقل Width. يجب أن تكون قيمة هذا الحقل مضاعفة للعدد أربعة.<br/>            إذا كانت الصورة مضغوطة، وفقاً لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | يحصل أو يعيّن نوع الصورة<br/>            Type (4 بايت): عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل BitmapData. يجب أن تكون هذه القيمة مُعرفة في تعداد [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (القسم 2.1.1.2). |
| width | int | r/w | يحصل أو يعيّن عرض الصورة<br/>            Width (4 بايت): عدد صحيح موقع 32‑بت يحدد العرض بالبكسل للمنطقة التي يشغلها البت ماب.<br/>            إذا كانت الصورة مضغوطة، وفقاً لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

ينشئ مثلاً جديداً من فئة EmfPlusBitmap

