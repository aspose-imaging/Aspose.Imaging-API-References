---
title: BitmapV5Header
second_title: Aspose.Imaging لمرجع NET API
description: بنية BitmapV5Header هي ملف رأس معلومات الصورة النقطية. إنها نسخة موسعة من هيكل BITMAPINFOHEADER.إذا كانت قيمة bV5Height سالبة  فتشير إلى DIB من أعلى إلى أسفل  يجب أن يكون ضغط bV5 إما BI_RGB أو BI_BITFIELDS. لا يمكن ضغط DIBs من أعلى إلى أسفل. تسمح واجهة إدارة الألوان المستقلة ICM 2.0 بربط ملفات تعريف الألوان اتحاد الألوان الدولي ICC أو تضمينها في DIBs DIBs. راجع استخدام الهياكل لمزيد من المعلومات. عند تحميل DIB في الذاكرة  يجب أن تتبع بيانات ملف التعريف إن وجدت جدول الألوان ويجب أن توفر bV5ProfileData إزاحة بيانات ملف التعريف من بداية بنية BITMAPV5HEADER. ستكون القيمة المخزنة في bV5ProfileData مختلفة عن القيمة التي تم إرجاعها بواسطة عامل التشغيل sizeof نظرًا لوسيطة BITMAPV5HEADER  لأن bV5ProfileData هي الإزاحة بالبايت من بداية بنية BITMAPV5HEADER إلى بداية بيانات ملف التعريف. بتات الصور النقطية لا تتبع جدول الألوان في الذاكرة. يجب أن تقوم التطبيقات بتعديل عضو bV5ProfileData بعد تحميل DIB في الذاكرة. بالنسبة لـ DIBs المعبأة  يجب أن تتبع بيانات ملف التعريف بتات الصورة النقطية المشابهة لتنسيق الملف. يجب أن يستمر عضو bV5ProfileData في إعطاء إزاحة بيانات ملف التعريف من بداية BITMAPV5HEADER. يجب أن تصل التطبيقات إلى بيانات ملف التعريف فقط عندما يكون bV5Size مساويًا لحجم BITMAPV5HEADER و bV5CSType يساوي PROFILE_EMBEDDED أو PROFILE_LINK.
type: docs
weight: 1370
url: /ar/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

بنية BitmapV5Header هي ملف رأس معلومات الصورة النقطية. إنها نسخة موسعة من هيكل BITMAPINFOHEADER.إذا كانت قيمة bV5Height سالبة ، فتشير إلى DIB من أعلى إلى أسفل ، يجب أن يكون ضغط bV5 إما BI_RGB أو BI_BITFIELDS. لا يمكن ضغط DIBs من أعلى إلى أسفل. تسمح واجهة إدارة الألوان المستقلة (ICM) 2.0 بربط ملفات تعريف الألوان اتحاد الألوان الدولي (ICC) أو تضمينها في DIBs (DIBs). راجع استخدام الهياكل لمزيد من المعلومات. عند تحميل DIB في الذاكرة ، يجب أن تتبع بيانات ملف التعريف (إن وجدت) جدول الألوان ويجب أن توفر bV5ProfileData إزاحة بيانات ملف التعريف من بداية بنية BITMAPV5HEADER. ستكون القيمة المخزنة في bV5ProfileData مختلفة عن القيمة التي تم إرجاعها بواسطة عامل التشغيل sizeof نظرًا لوسيطة BITMAPV5HEADER ، لأن bV5ProfileData هي الإزاحة بالبايت من بداية بنية BITMAPV5HEADER إلى بداية بيانات ملف التعريف. (بتات الصور النقطية لا تتبع جدول الألوان في الذاكرة). يجب أن تقوم التطبيقات بتعديل عضو bV5ProfileData بعد تحميل DIB في الذاكرة. بالنسبة لـ DIBs المعبأة ، يجب أن تتبع بيانات ملف التعريف بتات الصورة النقطية المشابهة لتنسيق الملف. يجب أن يستمر عضو bV5ProfileData في إعطاء إزاحة بيانات ملف التعريف من بداية BITMAPV5HEADER. يجب أن تصل التطبيقات إلى بيانات ملف التعريف فقط عندما يكون bV5Size مساويًا لحجم BITMAPV5HEADER و bV5CSType يساوي PROFILE_EMBEDDED أو PROFILE_LINK.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | الحصول على أو تعيين قناع اللون الذي يحدد مكون ألفا لكل بكسل. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | الحصول على أو تعيين عدد من ألوان اللوحة المهمة. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | الحصول على أو تعيين عدد ألوان اللوحة المستخدمة. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | الحصول على ضغط الصورة النقطية أو تعيينه. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | الحصول على ارتفاع الصورة النقطية أو تعيينه . |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | الحصول على أو تعيين يحدد حجم البيانات الأولية للصورة النقطية بالبايت. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | الحصول على أو تحديد عدد الطائرات . |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | الحصول على عرض الصورة النقطية أو تعيينه . |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | الحصول على دقة البكسل الأفقية أو تعيينها . |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | الحصول على دقة البكسل العمودية أو تعيينها . |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | الحصول على أو تعيين بت لكل عدد بكسل . |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | الحصول على أو تعيين قناع اللون الذي يحدد المكون الأزرق لكل بكسل ، ويكون صالحًا فقط إذا تم تعيين bV4Compression على BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | الحصول على مساحة اللون الخاصة بـ DIB أو تعيينها. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | الحصول على أو تعيين فئة الإحداثيات الثلاثية. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | الحصول على أقنعة البت الإضافية أو تعيينها. موجودة فقط في حالة كون رأس DIB هو BITMAPINFOHEADER و[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) على أي منهماBitfields (RGB) أوAlphaBitfields (RGBA) . |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | الحصول على أزرق جاما أو تعيينه . |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | الحصول على أو تعيين جاما الأخضر . |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | الحصول على أو تعيين أحمر جاما . |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | الحصول على أو تعيين قناع اللون الذي يحدد المكون الأخضر لكل بكسل ، ويكون صالحًا فقط إذا تم تعيين bV4Compression على BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | الحصول على أو تعيين حجم هذه البنية بالبايت. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | الحصول على أو تعيين هدف العرض للصورة النقطية. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | الحصول على بيانات ملف التعريف أو تعيينها. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | الحصول على أو تحديد حجم ملف التعريف . |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | الحصول على أو تعيين قناع اللون الذي يحدد المكون الأحمر لكل بكسل ، ويكون صالحًا فقط إذا تم تعيين bV4Compression على BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | الحصول على أو تعيين العضو المحجوز. |

### أنظر أيضا

* class [BitmapV4Header](../bitmapv4header)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
