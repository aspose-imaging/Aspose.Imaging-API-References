---
title: "فئة BitmapV5Header"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/
---

**Summary:** The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed.<br/>            The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). <br/>            See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, <br/>            and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. <br/>            The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, <br/>            because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. <br/>            (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory.<br/>            For packed DIBs, the profile data should follow the bitmap bits similar to the file format. <br/>            The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER.<br/>            Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV5Header

**Inheritance:** BitmapV4Header

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
| alpha_mask | int | r/w | يحصل أو يعيّن قناع اللون الذي يحدد مكوّن ألفا لكل بكسل. |
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
| blue_mask | int | r/w | يحصل أو يضبط قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |
| cs_type | int | r/w | يحصل أو يضبط مساحة اللون لـ DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | يحصل أو يضبط فئة CoordinatesTriple. |
| extra_bit_masks | int[] | r/w | يحصل أو يضبط أقنعة البت الإضافية.<br/>            تظهر فقط في حالة أن رأس DIB هو BITMAPINFOHEADER وأن [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) تم تعيينه إما إلى [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) أو [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | يحصل أو يضبط غاما الأزرق. |
| gamma_green | int | r/w | يحصل أو يضبط غاما الأخضر. |
| gamma_red | int | r/w | يحصل أو يضبط غاما الأحمر. |
| green_mask | int | r/w | يحصل أو يضبط قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |
| header_size | int | r/w | يحصل أو يضبط حجم هذا الهيكل بالبايت. |
| intent | int | r/w | يحصل أو يضبط نية العرض للصور النقطية. |
| profile_data | int | r/w | يحصل أو يضبط بيانات الملف الشخصي. |
| profile_size | int | r/w | يحصل أو يضبط حجم الملف الشخصي. |
| red_mask | int | r/w | يحصل أو يضبط قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI_BITFIELDS. |
| محجوز | int | r/w | يحصل أو يضبط العضو المحجوز. |


