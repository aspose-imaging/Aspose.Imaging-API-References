---
title: "الفئة WmfLogColorSpace"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Wmf.Objects.WmfLogColorSpace. يحدد كائن LogColorSpace مساحة لون منطقية لسياق جهاز التشغيل يمكن أن تكون اسم ملف تعريف لون بأحرف ASCII."
type: docs
weight: 8930
url: /ar/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

كائن LogColorSpace يحدد مساحة ألوان منطقية لسياق جهاز التشغيل، والتي يمكن أن تكون اسم ملف تعريف لون بأحرف ASCII.

```csharp
public class WmfLogColorSpace : MetaObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد نوع مساحة اللون. يجب أن يكون معرفًا في تعداد LogicalColorSpace (القسم 2.1.1.14). إذا كانت هذه القيمة LCS_sRGB أو LCS_WINDOWS_COLOR_SPACE، يجب استخدام مساحة اللون sRGB. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints/) { get; set; } | يحصل أو يعيّن كائن CIEXYZTriple (القسم 2.2.2.7) الذي يحدد إحداثيات اللون CIE x, y, z للثلاثة ألوان التي تتطابق مع نقاط النهاية RGB لمساحة اللون المنطقية المرتبطة بالبت ماب. إذا كان الحقل [`ColorSpaceType`](./colorspacetype/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename/) { get; set; } | يسترجع أو يعيّن سلسلة اختيارية من أحرف ASCII تحدد اسم ملف يحتوي على ملف تعريف لون. إذا تم تحديد اسم ملف، وكان حقل [`ColorSpaceType`](./colorspacetype/) مضبوطًا على LCS_CALIBRATED_RGB، يجب تجاهل الحقول الأخرى في هذه البنية. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue/) { get; set; } | يحصل أو يعيّن قيمة ثابتة 32‑بت تحدد منحنى الاستجابة للون الأزرق. إذا كان الحقل [`ColorSpaceType`](./colorspacetype/) لا يحدد LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen/) { get; set; } | يسترجع أو يعيّن قيمة ثابتة بنقطة عائمة 32‑بت تُعرّف منحنى الاستجابة الملون للأخضر. إذا لم يُحدد حقل [`ColorSpaceType`](./colorspacetype/) القيمة LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared/) { get; set; } | يسترجع أو يعيّن قيمة ثابتة بنقطة عائمة 32‑بت تُعرّف منحنى الاستجابة الملون للأحمر. إذا لم يُحدد حقل [`ColorSpaceType`](./colorspacetype/) القيمة LCS_CALIBRATED_RGB، يجب تجاهل هذا الحقل. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent/) { get; set; } | يسترجع أو يعيّن عددًا صحيحًا موقعًا 32‑بت يُعرّف نية تخطيط النطاق اللوني. يجب أن يكون مُعرّفًا في تعداد GamutMappingIntent (القسم 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature/) { get; set; } | يسترجع أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدّد توقيع كائنات مساحة اللون؛ يجب تعيينه إلى القيمة 0x50534F43، وهي ترميز ASCII للسلسلة "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايتات. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version/) { get; set; } | يسترجع أو يعيّن عددًا صحيحًا غير موقع 32‑بت يُعرّف رقم الإصدار؛ يجب أن يكون 0x00000400. |

## ملاحظات

تُستخدم حقول Endpoints و GammaRed و GammaGreen و GammaBlue لتحديد مساحة لون منطقية. حقل Endpoints هو كائن CIEXYZTriple يحتوي على قيم x و y و z لنقطة النهاية RGB لمساحة اللون. تُعبّر العلاقة بين قيم الثلاثية X,Y,Z وقيم الإشعاعية x,y,z كما يلي. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) تحتوي حقول GammaRed و GammaGreen و GammaBlue على قيم بتنسيق "8.8 fixed point"، وهو أسلوب لتمثيل الأعداد غير الصحيحة. كل قيمة تتكوّن من مقدار 8‑بت ممتد بالصفر يليه جزء كسر 8‑بت، مع إزاحة الـ 16‑بت المدمجة إلى اليسار بمقدار 8‑بت. وبالتالي، في 32‑بت، القيمة الحقيقية N.F هي 00000000nnnnnnnnffffffff00000000، حيث "nnnnnnnn" و "ffffffff" تمثيلات ثنائية لـ N و F على التوالي. على سبيل المثال، للعدد الحقيقي 10.5، سيكون nnnnnnnn هو 00001010 (ثنائي 10) و ffffffff هو 00000101 (ثنائي 5)، وستكون القيمة الثنائية الكاملة 32‑بت هي 00000000000010100000010100000000، وهي القيمة السداسية عشرية 0x0A50.

### انظر أيضًا

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


