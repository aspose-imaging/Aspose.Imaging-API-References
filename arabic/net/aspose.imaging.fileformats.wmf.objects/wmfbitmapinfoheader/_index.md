---
title: "الفئة WmfBitmapInfoHeader"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Wmf.Objects.WmfBitmapInfoHeader. كائن BitmapInfoHeader يحتوي على معلومات حول الأبعاد وتنسيق اللون لملف bitmap مستقل عن الجهاز DIB"
type: docs
weight: 8650
url: /ar/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

كائن BitmapInfoHeader يحتوي على معلومات حول الأبعاد وتنسيق اللون لملف bitmap المستقل عن الجهاز (DIB).

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في الـ DIB. يجب أن تكون هذه القيمة ضمن تعداد [`BitCount`](../wmfbitmapbaseheader/bitcount/) (القسم 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد مؤشرات الألوان المطلوبة لعرض DIB. إذا كانت هذه القيمة صفرًا، فإن جميع مؤشرات الألوان مطلوبة. |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الفهارس في جدول الألوان الذي يستخدمه DIB، كما يلي: إذا كانت هذه القيمة صفرًا، يستخدم DIB الحد الأقصى لعدد الألوان التي تتطابق مع قيمة BitCount. إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount أقل من 16، تحدد هذه القيمة عدد الألوان المستخدمة بواسطة DIB. إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount 16 أو أكثر، تحدد هذه القيمة حجم جدول الألوان المستخدم لتحسين أداء لوحة النظام. ملاحظة: إذا كانت هذه القيمة غير صفرية وأكبر من الحد الأقصى الممكن لحجم جدول الألوان بناءً على قيمة BitCount، يجب افتراض الحد الأقصى لحجم جدول الألوان. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد وضع الضغط لـ DIB. يجب أن تكون هذه القيمة ضمن تعداد Compression (القسم 2.1.1.7). يجب ألا تحدد هذه القيمة تنسيقًا مضغوطًا إذا كان DIB صورة bitmap من الأعلى إلى الأسفل، كما يشير إليه قيمة Height. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايتات. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع DIB بالبكسل. يجب ألا تكون هذه القيمة صفرًا. إذا كانت هذه القيمة موجبة، يكون DIB صورة bitmap من الأسفل إلى الأعلى، وأصلها هو الزاوية السفلية اليسرى. إذا كانت هذه القيمة سالبة، يكون DIB صورة bitmap من الأعلى إلى الأسفل، وأصلها هو الزاوية العلوية اليسرى. لا تدعم صور bitmap من الأعلى إلى الأسفل الضغط. يجب أن يحدد هذا الحقل ارتفاع ملف الصورة غير المضغوط إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG. |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم الصورة بالبايت. إذا كانت قيمة Compression هي BI_RGB، يجب أن تكون هذه القيمة صفرًا ويجب تجاهلها. إذا كانت قيمة Compression هي BI_JPEG أو BI_PNG، يجب أن تحدد هذه القيمة حجم مخزن صورة JPEG أو PNG على التوالي. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 16‑بت يحدد عدد المستويات للجهاز المستهدف. يجب أن تكون هذه القيمة 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد عرض DIB بالبكسل. يجب أن تكون هذه القيمة موجبة. يجب أن يحدد هذا الحقل عرض ملف الصورة غير المضغوط إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG. |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة الأفقية، بوحدة بكسل لكل متر، للجهاز الهدف لـ DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة العمودية، بوحدة بكسل لكل متر، للجهاز الهدف لـ DIB |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize/) | حجم البنية |

### انظر أيضًا

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


