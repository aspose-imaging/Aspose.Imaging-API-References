---
title: "الفئة WmfLogColorSpaceW"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Wmf.Objects.WmfLogColorSpaceW. كائن LogColorSpaceW يحدد مساحة لون منطقية يمكن تعريفها بملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode 16‑بت."
type: docs
weight: 8940
url: /ar/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
## WmfLogColorSpaceW class

كائن LogColorSpaceW يحدد مساحة ألوان منطقية، ويمكن تعريفها بملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode 16-بت.

```csharp
public class WmfLogColorSpaceW : MetaObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfLogColorSpaceW](wmflogcolorspacew/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/colorspacetype/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد نوع مساحة اللون. يجب أن يكون معرفًا في تعداد LogicalColorSpace (القسم 2.1.1.14). إذا كانت هذه القيمة LCS_sRGB أو LCS_WINDOWS_COLOR_SPACE، يجب استخدام مساحة اللون sRGB. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/endpoints/) { get; set; } | يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) الذي يحدد إحداثيات اللون CIE x, y, z للثلاثة ألوان التي تتطابق مع نقاط النهاية RGB لمساحة اللون المنطقية المرتبطة بالبت ماب. إذا كان الحقل [`ColorSpaceType`](./colorspacetype/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/filename/) { get; set; } | يحصل أو يعيّن سلسلة أحرف Unicode UTF16-LE منتهية بصفر اختيارية، والتي تحدد اسم ملف يحتوي على ملف تعريف لون. إذا تم تحديد اسم ملف، وكان الحقل [`ColorSpaceType`](./colorspacetype/) مضبوطًا على LCS_CALIBRATED_RGB، يجب تجاهل الحقول الأخرى في هذه البنية. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammablue/) { get; set; } | يحصل أو يعيّن قيمة ثابتة 32‑بت تحدد منحنى الاستجابة للون الأزرق. إذا كان الحقل [`ColorSpaceType`](./colorspacetype/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammagreen/) { get; set; } | يسترجع أو يعيّن قيمة ثابتة بنقطة عائمة 32‑بت تُعرّف منحنى الاستجابة الملون للأخضر. إذا لم يُحدد حقل [`ColorSpaceType`](./colorspacetype/) القيمة LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammared/) { get; set; } | يسترجع أو يعيّن قيمة ثابتة بنقطة عائمة 32‑بت تُعرّف منحنى الاستجابة الملون للأحمر. إذا لم يُحدد حقل [`ColorSpaceType`](./colorspacetype/) القيمة LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/intent/) { get; set; } | يسترجع أو يعيّن عددًا صحيحًا موقعًا 32‑بت يُعرّف نية تخطيط النطاق اللوني. يجب أن يكون مُعرّفًا في تعداد GamutMappingIntent (القسم 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/signature/) { get; set; } | يسترجع أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدّد توقيع كائنات مساحة اللون؛ يجب تعيينه إلى القيمة 0x50534F43، وهي ترميز ASCII للسلسلة "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايتات. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/version/) { get; set; } | يسترجع أو يعيّن عددًا صحيحًا غير موقع 32‑بت يُعرّف رقم الإصدار؛ يجب أن يكون 0x00000400. |

## ملاحظات

انظر كائن [`WmfLogColorSpace`](../wmflogcolorspace/) (القسم 2.2.2.11) للحصول على تفاصيل إضافية حول تفسير قيم الحقول لهذا الكائن.

### انظر أيضًا

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


