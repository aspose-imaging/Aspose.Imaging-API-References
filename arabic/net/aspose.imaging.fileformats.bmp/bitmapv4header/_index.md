---
title: "فئة BitmapV4Header"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Bmp.BitmapV4Header. بنية BitmapV4Header هي ملف رأس معلومات الصورة النقطية. إنها نسخة موسعة من بنية BITMAPINFOHEADER. تم توسيع بنية BitmapV4Header للسماح بتمرير صورة JPEG أو PNG كصورة مصدر إلى StretchDIBits"
type: docs
weight: 1410
url: /ar/net/aspose.imaging.fileformats.bmp/bitmapv4header/
---
## BitmapV4Header class

هيكل BitmapV4Header هو ملف رأس معلومات البت ماب. وهو نسخة موسعة من هيكل BITMAPINFOHEADER. تم توسيع هيكل BitmapV4Header للسماح بتمرير صورة JPEG أو PNG كصورة مصدر إلى StretchDIBits.

```csharp
public class BitmapV4Header : BitmapInfoHeader
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
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask/) { get; set; } | يحصل أو يضبط قناع اللون الذي يحدد المكون الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |

### انظر أيضًا

* class [BitmapInfoHeader](../bitmapinfoheader/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


