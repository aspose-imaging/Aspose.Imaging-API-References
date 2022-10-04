---
title: WmfBitmapInfoHeader
second_title: Aspose.Imaging لمرجع NET API
description: يحتوي كائن BitmapInfoHeader على معلومات حول الأبعاد وتنسيق الألوان لصورة نقطية DIB مستقلة عن الجهاز .
type: docs
weight: 8470
url: /ar/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

يحتوي كائن BitmapInfoHeader على معلومات حول الأبعاد وتنسيق الألوان لصورة نقطية (DIB) مستقلة عن الجهاز .

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد تنسيق لكل بكسل ، والحد الأقصى لعدد الألوان في DIB. يجب أن تكون هذه value في ملف[`BitCount`](../wmfbitmapbaseheader/bitcount) التعداد (القسم 2.1.1.3) . |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد فهارس الألوان المطلوبة لعرض DIB. إذا كانت هذه القيمة صفرًا ، تكون جميع فهارس الألوان مطلوبة |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد الفهارس في جدول الألوان المستخدم بواسطة DIB ، كما يلي: إذا كانت هذه القيمة صفرًا ، يستخدم DIB الحد الأقصى لعدد الألوان التي تتوافق مع قيمة BitCount. إذا كانت هذه القيمة غير صفرية وقيمة BitCount أقل من 16 ، تحدد هذه القيمة عدد الألوان المستخدمة بواسطة DIB. إذا كانت هذه القيمة غير صفرية وقيمة BitCount هي 16 أو أكبر ، تحدد هذه القيمة حجم اللون table يُستخدم لتحسين أداء لوحة النظام . ملاحظة إذا كانت هذه القيمة غير صفرية وأكبر من الحد الأقصى للحجم الممكن لجدول الألوان استنادًا إلى قيمة BitCount ، فيجب افتراض الحد الأقصى لحجم جدول الألوان. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد وضع ضغط DIB. يجب أن تكون هذه القيمة في تعداد الضغط (القسم 2.1.1.7) . يجب ألا تحدد هذه القيمة تنسيقًا مضغوطًا إذا كان DIB عبارة عن صورة نقطية من أعلى إلى أسفل ، كما هو موضح بواسطة قيمة الارتفاع. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد حجم هذا الكائن ، بالبايت. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد ارتفاع DIB بالبكسل. يجب ألا تكون هذه القيمة صفراً. إذا كانت هذه القيمة موجبة ، فإن DIB عبارة عن صورة نقطية من أسفل إلى أعلى ، وأصلها هو الركن الأيسر السفلي. أصله هو الزاوية العلوية اليسرى. الصور النقطية من أعلى لأسفل لا تدعم الضغط . يجب أن يحدد هذا الحقل ارتفاع ملف الصورة التي تم فك ضغطها ، إذا كانت قيمة الضغط تحدد تنسيق JPEG أو PNG . |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد حجم الصورة بالبايت. إذا كانت قيمة الضغط BI_RGB ، فيجب أن تكون هذه القيمة صفرية ويجب تجاهلها. إذا كانت قيمة الضغط هي BI_JPEG أو BI_PNG ، يجب أن تحدد هذه القيمة حجم المخزن المؤقت للصور JPEG أو PNG ، على التوالي. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد عدد planes للجهاز المستهدف. يجب أن تكون هذه القيمة 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | الحصول على أو تعيين عدد صحيح موقعة 32 بت يحدد عرض DIB بالبكسل. يجب أن تكون هذه القيمة موجبة. يجب أن يحدد هذا الحقل عرض ملف الصورة التي تم فك ضغطها ، إذا كانت قيمة الضغط تحدد تنسيق JPEG أو PNG . |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد الدقة الأفقية ، بالبكسل لكل متر ، لجهاز target لجهاز DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | الحصول على أو تعيين عدد صحيح موقعة 32 بت يحدد الدقة الرأسية ، بالبكسل لكل متر ، لجهاز target لجهاز DIB |

## مجالات

| اسم | وصف |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | حجم الهيكل |

### أنظر أيضا

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* مساحة الاسم [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->