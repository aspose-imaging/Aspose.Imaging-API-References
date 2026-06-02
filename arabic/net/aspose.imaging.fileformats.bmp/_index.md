---
title: "Aspose.Imaging.FileFormats.Bmp"
second_title: "Aspose.Imaging for .NET API Reference"
description: "المساحة الاسمية تتعامل مع معالجة تنسيق ملف Bmp"
type: docs
weight: 170
url: /ar/net/aspose.imaging.fileformats.bmp/
---
مساحة الاسم تتعامل مع معالجة صيغة ملف Bmp.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [BitmapCoreHeader](./bitmapcoreheader/) | الأبعاد وتنسيق اللون لـ DIB. اسم الرأس BITMAPCOREHEADER المعروف أيضًا باسم OS21XBITMAPHEADER. |
| [BitmapInfoHeader](./bitmapinfoheader/) | يحدد BITMAPINFOHEADER. دعم نظام التشغيل: Windows NT، 3.1x أو أحدث. الميزات: يضيف صيغ 16 بت و 32 بت لكل بكسل. يضيف ضغط RLE. |
| [BitmapV4Header](./bitmapv4header/) | هيكل BitmapV4Header هو ملف رأس معلومات البت ماب. وهو نسخة موسعة من هيكل BITMAPINFOHEADER. تم توسيع هيكل BitmapV4Header للسماح بتمرير صورة JPEG أو PNG كصورة مصدر إلى StretchDIBits. |
| [BitmapV5Header](./bitmapv5header/) | هيكل BitmapV5Header هو ملف رأس معلومات البت ماب. وهو نسخة موسعة من هيكل BITMAPINFOHEADER. إذا كان bV5Height سالبًا، مما يدل على DIB من الأعلى إلى الأسفل، يجب أن يكون bV5Compression إما BI_RGB أو BI_BITFIELDS. لا يمكن ضغط DIBs من الأعلى إلى الأسفل. تسمح واجهة إدارة الألوان المستقلة (ICM) 2.0 بربط أو تضمين ملفات تعريف الألوان الخاصة بـ International Color Consortium (ICC) في DIBs (DIBs). راجع Using Structures لمزيد من المعلومات. عندما يتم تحميل DIB إلى الذاكرة، يجب أن تتبع بيانات الملف الشخصي (إن وجدت) جدول الألوان، ويجب أن يوفر bV5ProfileData إزاحة بيانات الملف الشخصي من بداية هيكل BITMAPV5HEADER. القيمة المخزنة في bV5ProfileData ستكون مختلفة عن القيمة التي يعيدها عامل sizeof عند تمرير BITMAPV5HEADER كمعامل، لأن bV5ProfileData هي الإزاحة بالبايتات من بداية هيكل BITMAPV5HEADER إلى بداية بيانات الملف الشخصي. (بتات البت ماب لا تتبع جدول الألوان في الذاكرة). يجب على التطبيقات تعديل عضو bV5ProfileData بعد تحميل DIB إلى الذاكرة. بالنسبة لـ DIBs المعبأة، يجب أن تتبع بيانات الملف الشخصي بتات البت ماب مشابهة لتنسيق الملف. يجب أن يظل عضو bV5ProfileData يعطي إزاحة بيانات الملف الشخصي من بداية BITMAPV5HEADER. يجب على التطبيقات الوصول إلى بيانات الملف الشخصي فقط عندما يكون bV5Size مساويًا لحجم BITMAPV5HEADER و bV5CSType يساوي PROFILE_EMBEDDED أو PROFILE_LINKED. |
| [BmpImage](./bmpimage/) | يمكنك التعامل بسهولة مع ملفات Bitmap (BMP) وDevice Independent Bitmap (DIB)، مما يسهل التلاعب الفعال ومعالجة الصور النقطية. من خلال تنفيذ عمليات مختلفة على الصور، يبسط هذا API سير العمل، ويقدم للمطورين مجموعة أدوات موثوقة للعمل مع صيغ BMP و DIB في تطبيقاتهم البرمجية. |
| [Os22XBitmapHeader](./os22xbitmapheader/) | هيكل OS/2 2.x OS22XBITMAPHEADER المعروف أيضًا باسم BITMAPCOREHEADER2. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [BitmapCompression](./bitmapcompression/) | يحدد طرق ضغط البت ماب المختلفة. |


