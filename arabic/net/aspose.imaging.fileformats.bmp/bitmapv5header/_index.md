---
title: "الفئة BitmapV5Header"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Bmp.BitmapV5Header. بنية BitmapV5Header هي ملف رأس معلومات البت ماب. وهي نسخة موسعة من بنية BITMAPINFOHEADER. إذا كان bV5Height سالبًا مما يدل على DIB من الأعلى إلى الأسفل، يجب أن يكون bV5Compression إما BI_RGB أو BI_BITFIELDS. لا يمكن ضغط DIBs من الأعلى إلى الأسفل. تسمح واجهة إدارة الألوان المستقلة ICM 2.0 بربط أو تضمين ملفات تعريف الألوان ICC الخاصة بـ International Color Consortium في DIBs. راجع Using Structures لمزيد من المعلومات. عند تحميل DIB إلى الذاكرة، يجب أن تتبع بيانات الملف الشخصي (إن وجدت) جدول الألوان ويجب أن يوفر bV5ProfileData إزاحة بيانات الملف الشخصي من بداية بنية BITMAPV5HEADER. القيمة المخزنة في bV5ProfileData ستكون مختلفة عن القيمة التي يُرجعها عامل sizeof للمعامل BITMAPV5HEADER لأن bV5ProfileData هو الإزاحة بالبايتات من بداية بنية BITMAPV5HEADER إلى بداية بيانات الملف الشخصي. لا تتبع بتات البت ماب جدول الألوان في الذاكرة. يجب على التطبيقات تعديل عضو bV5ProfileData بعد تحميل DIB إلى الذاكرة. بالنسبة لـ DIBs المعبأة، يجب أن تتبع بيانات الملف الشخصي بتات البت ماب مشابهة لتنسيق الملف. يجب أن يظل عضو bV5ProfileData يعطي إزاحة بيانات الملف الشخصي من بداية BITMAPV5HEADER. يجب على التطبيقات الوصول إلى بيانات الملف الشخصي فقط عندما يكون bV5Size يساوي حجم BITMAPV5HEADER و bV5CSType يساوي PROFILE_EMBEDDED أو PROFILE_LINKED."
type: docs
weight: 1420
url: /ar/net/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

هيكل BitmapV5Header هو ملف رأس معلومات البت ماب. وهو نسخة موسعة من هيكل BITMAPINFOHEADER. إذا كان bV5Height سالبًا، مما يدل على DIB من الأعلى إلى الأسفل، يجب أن يكون bV5Compression إما BI_RGB أو BI_BITFIELDS. لا يمكن ضغط DIBs من الأعلى إلى الأسفل. تسمح واجهة إدارة الألوان المستقلة (ICM) 2.0 بربط أو تضمين ملفات تعريف الألوان الخاصة بـ International Color Consortium (ICC) في DIBs (DIBs). راجع Using Structures لمزيد من المعلومات. عندما يتم تحميل DIB إلى الذاكرة، يجب أن تتبع بيانات الملف الشخصي (إن وجدت) جدول الألوان، ويجب أن يوفر bV5ProfileData إزاحة بيانات الملف الشخصي من بداية هيكل BITMAPV5HEADER. القيمة المخزنة في bV5ProfileData ستكون مختلفة عن القيمة التي يعيدها عامل sizeof عند تمرير BITMAPV5HEADER كمعامل، لأن bV5ProfileData هي الإزاحة بالبايتات من بداية هيكل BITMAPV5HEADER إلى بداية بيانات الملف الشخصي. (بتات البت ماب لا تتبع جدول الألوان في الذاكرة). يجب على التطبيقات تعديل عضو bV5ProfileData بعد تحميل DIB إلى الذاكرة. بالنسبة لـ DIBs المعبأة، يجب أن تتبع بيانات الملف الشخصي بتات البت ماب مشابهة لتنسيق الملف. يجب أن يظل عضو bV5ProfileData يعطي إزاحة بيانات الملف الشخصي من بداية BITMAPV5HEADER. يجب على التطبيقات الوصول إلى بيانات الملف الشخصي فقط عندما يكون bV5Size مساويًا لحجم BITMAPV5HEADER و bV5CSType يساوي PROFILE_EMBEDDED أو PROFILE_LINKED.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask/) { get; set; } | الحصول أو تعيين قناع اللون الذي يحدد مكوّن ألفا لكل بكسل. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant/) { get; set; } | الحصول أو تعيين عدد ألوان اللوحة المهمة. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused/) { get; set; } | الحصول أو تعيين عدد ألوان اللوحة المستخدمة. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression/) { get; set; } | الحصول أو تعيين ضغط البت ماب. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight/) { get; set; } | الحصول أو تعيين ارتفاع البت ماب. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize/) { get; set; } | الحصول أو تعيين حجم البيانات الخام للبت ماب بالبايت. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes/) { get; set; } | الحصول أو تعيين عدد المستويات. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth/) { get; set; } | الحصول أو تعيين عرض البت ماب. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter/) { get; set; } | الحصول أو تعيين دقة البكسلات الأفقية. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter/) { get; set; } | الحصول أو تعيين دقة البكسلات العمودية. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel/) { get; set; } | الحصول أو تعيين عدد البتات لكل بكسل. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask/) { get; set; } | الحصول أو تعيين قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype/) { get; set; } | الحصول أو تعيين مساحة اللون لـ DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints/) { get; set; } | الحصول أو تعيين فئة CoordinatesTriple. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks/) { get; set; } | الحصول أو تعيين أقنعة البت الإضافية. تظهر فقط في حالة كان رأس DIB هو BITMAPINFOHEADER وتم تعيين [`BitmapCompression`](../bitmapinfoheader/bitmapcompression/) إلى إما Bitfields (RGB) أو AlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue/) { get; set; } | الحصول أو تعيين غاما الأزرق. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen/) { get; set; } | يحصل أو يضبط قيمة gamma green. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared/) { get; set; } | يحصل أو يضبط قيمة gamma red. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask/) { get; set; } | يحصل أو يضبط قناع اللون الذي يحدد المكون الأخضر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize/) { get; set; } | يحصل أو يضبط حجم هذا الهيكل بالبايت. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent/) { get; set; } | يحصل أو يضبط نية العرض للصور النقطية. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata/) { get; set; } | يحصل أو يضبط بيانات الملف الشخصي. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize/) { get; set; } | يحصل أو يضبط حجم الملف الشخصي. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask/) { get; set; } | يحصل أو يضبط قناع اللون الذي يحدد المكون الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved/) { get; set; } | يحصل أو يضبط العضو المحجوز. |

### انظر أيضًا

* class [BitmapV4Header](../bitmapv4header/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


