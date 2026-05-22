---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /ar/python-net/aspose.imaging.fileformats.bmp/
---


الوحدة تتعامل مع معالجة تنسيق ملف Bmp.

## **Classes**
| **فئة** | **الوصف** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | الأبعاد وتنسيق اللون لـ DIB.<br/>            اسم الرأس BITMAPCOREHEADER المعروف أيضًا باسم OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | يحدد BITMAPINFOHEADER. <br/>                دعم نظام التشغيل: Windows NT، 3.1x أو أحدث.<br/>                الميزات: يضيف تنسيقات 16 بت و32 بت. يضيف ضغط RLE. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | هيكل BitmapV4Header هو ملف رأس معلومات البت ماب. وهو نسخة موسعة من هيكل BITMAPINFOHEADER.<br/>            <br/>تم توسيع هيكل BitmapV4Header للسماح بتمرير صورة JPEG أو PNG كصورة مصدر إلى StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | هيكل BitmapV5Header هو ملف رأس معلومات البت ماب. وهو نسخة موسعة من هيكل BITMAPINFOHEADER.<br/>            <br/>إذا كانت قيمة bV5Height سالبة، مما يدل على DIB من الأعلى إلى الأسفل، يجب أن يكون bV5Compression إما BI_RGB أو BI_BITFIELDS. لا يمكن ضغط DIBs من الأعلى إلى الأسفل.<br/>            تسمح واجهة إدارة اللون المستقلة (ICM) 2.0 بربط أو تضمين ملفات تعريف الألوان الخاصة بـ International Color Consortium (ICC) في DIBs (DIBs). <br/>            راجع Using Structures لمزيد من المعلومات. عندما يتم تحميل DIB في الذاكرة، يجب أن تتبع بيانات الملف التعريفي (إن وجدت) جدول الألوان، <br/>            ويجب أن يوفر bV5ProfileData إزاحة بيانات الملف التعريفي من بداية هيكل BITMAPV5HEADER. <br/>            القيمة المخزنة في bV5ProfileData ستكون مختلفة عن القيمة التي يعيدها عامل sizeof للمعامل BITMAPV5HEADER، <br/>            لأن bV5ProfileData هو الإزاحة بالبايتات من بداية هيكل BITMAPV5HEADER إلى بداية بيانات الملف التعريفي. <br/>            (بتات البت ماب لا تتبع جدول الألوان في الذاكرة). يجب على التطبيقات تعديل عضو bV5ProfileData بعد تحميل DIB في الذاكرة.<br/>            بالنسبة لـ DIBs المعبأة، يجب أن تتبع بيانات الملف التعريفي بتات البت ماب مشابهة لتنسيق الملف. <br/>            يجب أن يظل عضو bV5ProfileData يعطي إزاحة بيانات الملف التعريفي من بداية BITMAPV5HEADER.<br/>            يجب على التطبيقات الوصول إلى بيانات الملف التعريفي فقط عندما يكون bV5Size مساويًا لحجم BITMAPV5HEADER وbV5CSType يساوي PROFILE_EMBEDDED أو PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | يمكنك بسهولة التعامل مع ملفات Bitmap (BMP) وDevice Independent Bitmap<br/>            (DIB)، مما يسهل المعالجة الفعّالة للصور النقطية<br/>            . من خلال تنفيذ عمليات مختلفة على الصور، تبسط هذه API<br/>            سير العمل، وتوفر للمطورين مجموعة أدوات موثوقة للعمل مع صيغ BMP و<br/>            DIB في تطبيقاتهم البرمجية. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | OS/2 2.x OS22XBITMAPHEADER المعروف أيضًا باسم BITMAPCOREHEADER2. |
## **Enumerations**
| **تعداد** | **الوصف** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | يحدد طرق ضغط البت ماب المختلفة. |
