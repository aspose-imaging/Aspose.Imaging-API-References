---
title: "الفئة PixelDataFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.PixelDataFormat. تنسيق بيانات البكسل. هذا كائن غير قابل للتغيير."
type: docs
weight: 11290
url: /ar/net/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

تنسيق بيانات البكسل. هذا كائن غير قابل للتغيير.

```csharp
public class PixelDataFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk/) { get; } | يحصل على `PixelDataFormat` المعرفة بـ 32 بت لكل بكسل مع 8 بت لكل من السماوي، الأرجواني، الأصفر والأسود. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka/) { get; } | يحصل على acmyk. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha/) { get; } | يحصل على `PixelDataFormat` المعرفة بـ 16 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في المجال 0-255 ومكوّن ألفا إضافي 8 بت. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555/) { get; } | يحصل على `PixelDataFormat` المعرفة بـ 16 بت لكل بكسل مع 5 بت لكل من الأحمر والأخضر والأزرق، ولا يُعرّف ألفا. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 5 بت للأحمر، 6 بت للأخضر و5 بت للأزرق، ولا يتم تعريف ألفا. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من الألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف الألفا. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من الألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف الألفا. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من الألفا، الأحمر، الأخضر والأزرق. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من الألفا، الأحمر، الأخضر والأزرق. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp/) { get; } | يحصل على `PixelDataFormat` المحدد للون المفهرس ببت واحد لكل لون. تخزين بكسل اللون المفهرس يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان تُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب التحويل من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس. |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp/) { get; } | يحصل على `PixelDataFormat` المحدد للون المفهرس ببتين لكل لون. تخزين بكسل اللون المفهرس يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان تُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب التحويل من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس. |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp/) { get; } | يحصل على `PixelDataFormat` المحدد للون المفهرس بأربع بتات لكل لون. تخزين بكسل اللون المفهرس يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان تُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب التحويل من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس. |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp/) { get; } | يحصل على `PixelDataFormat` المحدد للون المفهرس بثمانية بتات لكل لون. تخزين بكسل اللون المفهرس يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان تُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب التحويل من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس. |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من مكوّنات اللمعان، الفرق الأزرق والفرق الأحمر. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck/) { get; } | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من مكوّنات اللمعان، الفرق الأزرق، الفرق الأحمر ومكوّن اللون الأسود. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel/) { get; } | يحصل على عدد البتات لكل بكسل. |
| [Caption](../../aspose.imaging/pixeldataformat/caption/) { get; } | يحصل على تسمية تنسيق بيانات البكسل. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits/) { get; } | يحصل على عدد البتات لكل قناة. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount/) { get; } | يحصل على عدد القنوات. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat/) { get; } | يحصل على تنسيق البكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr/)(int) | يحصل على لون BGR بعدد محدد من البتات لكل عينة. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra/)(int) | يحصل على لون BGRA بعدد محدد من البتات لكل عينة. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab/)(int, int, int) | يحصل على لون CIE Lab بعدد محدد من البتات لكل عينة. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk/#getcmyk)(int) | يحصل على لون CMYK بعدد محدد من البتات لكل عينة. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | يحصل على لون CMYK بعدد محدد من البتات لكل عينة. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka/)(int, int, int, int, int) | يحصل على لون CMYKA بعدد محدد من البتات لكل عينة. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale/)(int) | يحصل على لون تدرج الرمادي بعدد محدد من البتات لكل عينة. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | يحصل على لون GrayscaleAlpha بعدد محدد من البتات لكل عينة. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | يحصل على لون GrayscaleAlpha بعدد محدد من البتات لكل عينة. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb/#getrgb)(int) | يحصل على لون RGB بعدد محدد من البتات لكل عينة. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | يحصل على لون RGB بعدد محدد من البتات لكل عينة. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba/#getrgba)(int) | يحصل على لون RGBA بعدد محدد من البتات لكل عينة. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | يحصل على لون RGBA بعدد محدد من البتات لكل عينة. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed/)(int) | يحصل على لون BGRA المفهرس بعدد محدد من البتات لكل عينة. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr/#getycbcr)(int) | يحصل على لون YCbCr بعدد محدد من البتات لكل عينة. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | يحصل على لون YCbCr بعدد محدد من البتات لكل عينة. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck/)(int) | يحصل على لون YCCK بعدد محدد من البتات لكل عينة. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals/)(object) | يحدد ما إذا كان الـ Object المحدد يساوي هذه المثيلة. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode/)() | يرجع رمز تجزئة لهذه المثيلة. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality/) | يعيد نتيجة المساواة لفئتين `PixelDataFormat`. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality/) | يعيد نتيجة عدم المساواة لفئتين `PixelDataFormat`. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale/) | يحصل على `PixelDataFormat` المعرف لثمانية بتات لكل بكسل حيث تمثل 8 بتات شدة اللون الرمادي في النطاق 0-255. |
| static readonly [Grayscale16](../../aspose.imaging/pixeldataformat/grayscale16/) | معرف لستة عشر بتًا لكل بكسل مع ما يصل إلى 16 بتًا تمثل شدة اللون الرمادي. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


