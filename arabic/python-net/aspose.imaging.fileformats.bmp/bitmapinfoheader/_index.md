---
title: "BitmapInfoHeader فئة"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

**Summary:** Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Inheritance:** BitmapCoreHeader

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | حجم رأس BITMAPCOREHEADER المعروف أيضًا باسم OS21XBITMAPHEADER |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | حجم رأس معلومات bitmap الإصدار 3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | حجم رأس معلومات bitmap الإصدار 2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | حجم رأس معلومات bitmap الإصدار 3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | حجم رأس معلومات bitmap الإصدار 4 |
| BITMAP_INFO_HEADER_SIZE_V5 [ثابت] | int | r | حجم رأس معلومات bitmap v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [ثابت] | int | r | حجم bitmap core header2 |
| OS_22X_BITMAP_HEADER_SIZE [ثابت] | int | r | حجم bitmap core header2 |
| bitmap_colors_important | int | r/w | يحصل أو يعيّن عدد ألوان اللوحة المهمة. |
| bitmap_colors_used | int | r/w | يحصل أو يعيّن عدد ألوان اللوحة المستخدمة. |
| bitmap_compression | int | r/w | يحصل أو يعيّن ضغط bitmap. |
| bitmap_height | int | r/w | يحصل أو يعيّن ارتفاع bitmap. |
| bitmap_image_size | int | r/w | يحصل أو يعيّن حجم البيانات الخام للـ bitmap بالبايت. |
| bitmap_planes | int | r/w | يحصل أو يعيّن عدد المستويات. |
| bitmap_width | int | r/w | يحصل أو يعيّن عرض bitmap. |
| bitmap_x_pels_per_meter | int | r/w | يحصل أو يعيّن دقة البكسلات الأفقية. |
| bitmap_y_pels_per_meter | int | r/w | يحصل أو يعيّن دقة البكسلات العمودية. |
| bits_per_pixel | int | r/w | يحصل أو يضبط عدد البتات لكل بكسل. |
| extra_bit_masks | int[] | r/w | يحصل أو يضبط أقنعة البت الإضافية.<br/>            تظهر فقط في حالة أن رأس DIB هو BITMAPINFOHEADER وأن [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) تم تعيينه إما إلى [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) أو [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | int | r/w | يحصل أو يضبط حجم هذا الهيكل بالبايت. |


