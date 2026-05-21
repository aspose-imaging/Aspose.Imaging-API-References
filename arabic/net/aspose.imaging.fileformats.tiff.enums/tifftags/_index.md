---
title: "تعداد TiffTags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Tiff.Enums.TiffTags enum. تعداد وسوم tiff"
type: docs
weight: 7850
url: /ar/net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

تعداد وسم tiff.

```csharp
public enum TiffTags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| SubFileType | `254` | وصف بيانات الملف الفرعي. |
| OsubfileType | `255` | [تم إهماله بواسطة TIFF rev. 5.0] نوع البيانات في الملف الفرعي. |
| ImageWidth | `256` | عرض الصورة بالبكسل. |
| ImageLength | `257` | ارتفاع الصورة بالبكسل. |
| BitsPerSample | `258` | بتات لكل قناة (عينة). |
| Compression | `259` | تقنية ضغط البيانات. |
| Photometric | `262` | تفسير فوتومتري. |
| Thresholding | `263` | [تم إهماله بواسطة TIFF rev. 5.0] العتبة المستخدمة على البيانات. |
| CellWidth | `264` | [تم إهماله بواسطة TIFF rev. 5.0] عرض مصفوفة التمويه. |
| CellLength | `265` | [تم إهماله بواسطة TIFF rev. 5.0] ارتفاع مصفوفة التمويه. |
| FillOrder | `266` | ترتيب البيانات داخل بايت. |
| DocumentName | `269` | اسم المستند الذي يحمل الصورة. |
| ImageDescription | `270` | معلومات عن الصورة. |
| Make | `271` | اسم شركة صانع الماسح الضوئي. |
| Model | `272` | اسم/رقم طراز الماسح الضوئي. |
| StripOffsets | `273` | إزاحات إلى شرائط البيانات. |
| Orientation | `274` | [تم إهماله بواسطة TIFF rev. 5.0] اتجاه الصورة. |
| SamplesPerPixel | `277` | عينات لكل بكسل. |
| RowsPerStrip | `278` | صفوف لكل شريط من البيانات. |
| StripByteCounts | `279` | عدد البايتات للشرائط. |
| MinSampleValue | `280` | [تم إهماله بواسطة TIFF rev. 5.0] الحد الأدنى لقيمة العينة. |
| MaxSampleValue | `281` | [تم إهماله بواسطة TIFF rev. 5.0] الحد الأقصى لقيمة العينة. |
| Xresolution | `282` | بكسلات/دقة في x. |
| Yresolution | `283` | البكسلات/الدقة في y. |
| PlanarConfig | `284` | تنظيم التخزين. |
| PageName | `285` | اسم الصفحة التي يأتي منها الصورة. |
| Xposition | `286` | إزاحة الصفحة X للصورة على اليسار. |
| Yposition | `287` | إزاحة الصفحة Y للصورة على اليسار. |
| FreeOffsets | `288` | [obsoleted by TIFF rev. 5.0] إزاحة البايت إلى الكتلة الحرة. |
| FreeByteCounts | `289` | [obsoleted by TIFF rev. 5.0] أحجام الكتل الحرة. |
| GrayResponseUnit | `290` | [obsoleted by TIFF rev. 6.0] دقة منحنى التدرج الرمادي. |
| GrayResponseCurve | `291` | [obsoleted by TIFF rev. 6.0] منحنى استجابة التدرج الرمادي. |
| T4Options | `292` | TIFF 6.0 الاسم المناسب المستعار لـ GROUP3OPTIONS. خيارات ترميز الفاكس CCITT Group 3. 32 بت علم. |
| T6Options | `293` | خيارات ترميز الفاكس CCITT Group 4. 32 بت علم. TIFF 6.0 الاسم المناسب المستعار لـ GROUP4OPTIONS. |
| ResolutionUnit | `296` | وحدات الدقة. |
| PageNumber | `297` | أرقام الصفحات في المستند متعدد الصفحات. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] دقة منحنى اللون. |
| TransferFunction | `301` | معلومات قياس الألوان. |
| Software | `305` | الاسم والإصدار. |
| DateTime | `306` | تاريخ ووقت الإنشاء. |
| Artist | `315` | منشئ الصورة. |
| HostComputer | `316` | الجهاز الذي تم الإنشاء عليه. |
| Predictor | `317` | نظام التنبؤ باستخدام LZW. |
| WhitePoint | `318` | نقطة بيضاء الصورة. |
| PrimaryChromaticities | `319` | الألوان الأولية. |
| ColorMap | `320` | خريطة RGB لصورة اللوحة. |
| HalftoneHints | `321` | معلومات الإبراز والظل. |
| TileWidth | `322` | عرض البلاط بالبكسل. |
| TileLength | `323` | ارتفاع البلاطة بالبكسل. |
| TileOffsets | `324` | الإزاحات إلى بلاطات البيانات. |
| TileByteCounts | `325` | عدد البايتات للبلاطات. |
| BadFaxLines | `326` | السطور ذات عدد بكسلات غير صحيح. |
| CleanFaxData | `327` | معلومات السطر المعاد توليده. |
| ConsecutiveBadFaxLines | `328` | الحد الأقصى للسطور السيئة المتتالية. |
| SubIfd | `330` | واصفات الصورة الفرعية. |
| InkSet | `332` | الأحبار في الصورة المفصولة. |
| InkNames | `333` | أسماء الأحبار بنظام ASCII. |
| NumberOfInks | `334` | عدد الأحبار. |
| DotRange | `336` | رموز النقاط 0% و 100%. |
| TargetPrinter | `337` | هدف الفصل. |
| ExtraSamples | `338` | معلومات حول العينات الإضافية. |
| SampleFormat | `339` | تنسيق عينة البيانات. |
| SminSampleValue | `340` | المتغير MinSampleValue. |
| SmaxSampleValue | `341` | المتغير MaxSampleValue. |
| TransferRange | `342` | المتغير TransferRange |
| ClipPath | `343` | ClipPath. تم تقديمه بعد إصدار TIFF 6.0 بواسطة ملاحظة تقنية Adobe TIFF رقم 2. |
| Xclippathunits | `344` | XClipPathUnits. تم تقديمه بعد إصدار TIFF 6.0 بواسطة ملاحظة تقنية Adobe TIFF رقم 2. |
| Yclippathunits | `345` | YClipPathUnits. تم تقديمه بعد إصدار TIFF 6.0 بواسطة ملاحظة تقنية Adobe TIFF رقم 2. |
| Indexed | `346` | Indexed. تم تقديمه بعد إصدار TIFF 6.0 بواسطة ملاحظة تقنية Adobe TIFF رقم 3. |
| JpegTables | `347` | دفق جدول JPEG. تم تقديمه بعد إصدار TIFF 6.0. |
| OpiProxy | `351` | OPI Proxy. تم تقديمه بعد إصدار TIFF 6.0 بواسطة ملاحظة تقنية Adobe TIFF. |
| JpegProc | `512` | [تم إهماله بملاحظة تقنية #2 التي تحدد مخطط JPEG في TIFF المعدل] خوارزمية معالجة JPEG. |
| JpegInerchangeFormat | `513` | [تم إهماله بملاحظة تقنية #2 التي تحدد مخطط JPEG في TIFF المعدل] مؤشر إلى علامة SOI. |
| JpegInterchangeFormatLength | `514` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] طول تدفق JFIF |
| JpegRestartInterval | `515` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] طول فترة إعادة التشغيل. |
| JpegLosslessPredictors | `517` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] متنبئ proc غير مضغوط. |
| JpegPointTransform | `518` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] تحويل نقطة غير مضغوط. |
| JpegQTables | `519` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] إزاحات مصفوفة Q. |
| JpegDCtables | `520` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] إزاحات جدول DCT. |
| JpegACtables | `521` | [تم إهماله بواسطة الملاحظة التقنية #2 التي تحدد مخطط JPEG-in-TIFF المعدل] إزاحات معامل AC. |
| YcbcrCoefficients | `529` | تحويل RGB -&gt; YCbCr. |
| YcbcrSubSampling | `530` | عوامل أخذ العينات الفرعية YCbCr. |
| YcbcrPositioning | `531` | موضع العينة الفرعية. |
| ReferenceBlackWhite | `532` | معلومات قياس الألوان. |
| XmlPacket | `700` | حزمة XML. تم تقديمها بعد TIFF الإصدار 6.0 بواسطة مواصفة Adobe XMP، يناير 2004. |
| OpiImageid | `32781` | معرف OPI ImageID. تم تقديمه بعد TIFF الإصدار 6.0 بواسطة ملاحظة تقنية Adobe TIFF. |
| Refpts | `32953` | نقاط مرجعية الصورة. علامة خاصة مسجلة لدى Island Graphics. |
| Copyright | `33432` | سلسلة حقوق النشر. هذه العلامة مدرجة في TIFF الإصدار 6.0 مع ملكية غير معروفة. |
| PhotoshopResources | `34377` | موارد صورة Photoshop. |
| IccProfile | `34675` | ملف تعريف الجهاز المدمج ICC |
| ExifIfdPointer | `34665` | مؤشر إلى Exif IFD. |
| XPTitle | `40091` | معلومات حول الصورة، تُستخدم بواسطة Windows Explorer. يتم تجاهل XPTitle من قبل Windows Explorer إذا كانت علامة ImageDescription موجودة. |
| XPComment | `40092` | تعليق على الصورة، يُستخدم بواسطة Windows Explorer. |
| XPAuthor | `40093` | مؤلف الصورة، يُستخدم بواسطة Windows Explorer. يتم تجاهل XPAuthor من قبل Windows Explorer إذا كانت علامة Artist موجودة. |
| XPKeywords | `40094` | كلمات مفتاحية للصورة، تُستخدم بواسطة Windows Explorer. |
| XPSubject | `40095` | صورة الموضوع، تُستخدم بواسطة Windows Explorer. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums/)
* assembly [Aspose.Imaging](../../)


