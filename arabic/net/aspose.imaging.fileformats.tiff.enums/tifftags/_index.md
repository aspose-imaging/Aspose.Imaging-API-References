---
title: TiffTags
second_title: Aspose.Imaging لمرجع NET API
description: تعداد علامة tiff .
type: docs
weight: 7740
url: /ar/net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

تعداد علامة tiff .

```csharp
public enum TiffTags
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| SubFileType | `254` | واصف بيانات الملف الفرعي . |
| OsubfileType | `255` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] نوع البيانات في الملف الفرعي. |
| ImageWidth | `256` | عرض الصورة بالبكسل . |
| ImageLength | `257` | ارتفاع الصورة بالبكسل . |
| BitsPerSample | `258` | بت لكل قناة (عينة) . |
| Compression | `259` | تقنية ضغط البيانات . |
| Photometric | `262` | تفسير ضوئي . |
| Thresholding | `263` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] العتبة المستخدمة في البيانات. |
| CellWidth | `264` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] عرض مصفوفة التردد . |
| CellLength | `265` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] ارتفاع مصفوفة التردد . |
| FillOrder | `266` | ترتيب البيانات داخل بايت . |
| DocumentName | `269` | اسم المستند الذي يحمل الصورة . |
| ImageDescription | `270` | معلومات حول الصورة . |
| Make | `271` | اسم الشركة المصنعة للماسح الضوئي . |
| Model | `272` | اسم / رقم طراز الماسح. |
| StripOffsets | `273` | إزاحة لشرائط البيانات. |
| Orientation | `274` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] اتجاه الصورة. |
| SamplesPerPixel | `277` | عينات لكل بكسل . |
| RowsPerStrip | `278` | صفوف لكل شريط بيانات . |
| StripByteCounts | `279` | عدد البايت للشرائط . |
| MinSampleValue | `280` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] أدنى قيمة للعينة . |
| MaxSampleValue | `281` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] الحد الأقصى لقيمة العينة . |
| Xresolution | `282` | بكسل / دقة x. |
| Yresolution | `283` | بكسل / الدقة في y. |
| PlanarConfig | `284` | منظمة التخزين . |
| PageName | `285` | صورة اسم الصفحة من . |
| Xposition | `286` | إزاحة صفحة X للصورة lhs. |
| Yposition | `287` | إزاحة صفحة Y للصورة lhs. |
| FreeOffsets | `288` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] إزاحة البايت للكتلة الحرة . |
| FreeByteCounts | `289` | [عفا عليها الزمن بواسطة TIFF rev. 5.0] أحجام الكتل المجانية. |
| GrayResponseUnit | `290` | [عفا عليها الزمن بواسطة TIFF rev. 6.0] دقة منحنى المقياس الرمادي. |
| GrayResponseCurve | `291` | [عفا عليها الزمن بواسطة TIFF rev. 6.0] منحنى استجابة المقياس الرمادي. |
| T4Options | `292` | TIFF 6.0 الاسم المستعار لمجموعة GROUP3OPTIONS. خيارات لتشفير الفاكس CCITT Group 3. 32 بت العلم. |
| T6Options | `293` | خيارات لتشفير الفاكس CCITT Group 4. 32 بت علم . TIFF 6.0 الاسم المستعار للاسم لمجموعة GROUP4OPTIONS. |
| ResolutionUnit | `296` | وحدات القرارات . |
| PageNumber | `297` | أرقام الصفحات متعددة الصفحات. |
| ColorResponseUnit | `300` | [عفا عليها الزمن بواسطة TIFF rev. 6.0] دقة منحنى اللون. |
| TransferFunction | `301` | معلومات قياس الألوان . |
| Software | `305` | الاسم والإصدار . |
| DateTime | `306` | تاريخ الإنشاء ووقته . |
| Artist | `315` | منشئ الصورة . |
| HostComputer | `316` | الجهاز حيث تم إنشاؤه . |
| Predictor | `317` | مخطط التنبؤ ث / LZW. |
| WhitePoint | `318` | النقطة البيضاء للصورة . |
| PrimaryChromaticities | `319` | اللونية الأولية . |
| ColorMap | `320` | خريطة RGB لصورة لوحة. |
| HalftoneHints | `321` | تسليط الضوء + معلومات الظل . |
| TileWidth | `322` | عرض البلاط بالبكسل . |
| TileLength | `323` | ارتفاع البلاط بالبكسل . |
| TileOffsets | `324` | إزاحة لمربعات البيانات . |
| TileByteCounts | `325` | عدد البايت للبلاط . |
| BadFaxLines | `326` | الخطوط ذات عدد وحدات البكسل الخطأ . |
| CleanFaxData | `327` | معلومات الخط المعاد إنشاؤه . |
| ConsecutiveBadFaxLines | `328` | الحد الأقصى للخطوط السيئة المتتالية . |
| SubIfd | `330` | واصفات الصورة الفرعية . |
| InkSet | `332` | أحبار في صورة منفصلة. |
| InkNames | `333` | أسماء أحبار ASCII . |
| NumberOfInks | `334` | عدد الأحبار . |
| DotRange | `336` | 0٪ و 100٪ رموز نقطية . |
| TargetPrinter | `337` | هدف الفصل . |
| ExtraSamples | `338` | معلومات حول العينات الإضافية . |
| SampleFormat | `339` | تنسيق نموذج البيانات . |
| SminSampleValue | `340` | قيمة MinSampleVari المتغيرة. |
| SmaxSampleValue | `341` | الحد الأقصى لقيمة المتغير. |
| TransferRange | `342` | نطاق النقل المتغير |
| ClipPath | `343` | ClipPath. تم تقديم المنشور TIFF rev 6.0 بواسطة Adobe TIFF technote 2. |
| Xclippathunits | `344` | وحدات XClipPath. تم تقديم المنشور TIFF rev 6.0 بواسطة Adobe TIFF technote 2. |
| Yclippathunits | `345` | وحدات YClipPath. تم تقديم المنشور TIFF rev 6.0 بواسطة Adobe TIFF technote 2. |
| Indexed | `346` | مفهرسة. المنشور المقدم TIFF rev 6.0 بواسطة Adobe TIFF Technote 3. |
| JpegTables | `347` | جدول تيار JPEG. المقدمة بعد TIFF rev 6.0. |
| OpiProxy | `351` | وكيل OPI. تم تقديم المنشور TIFF rev 6.0 بواسطة Adobe TIFF technote . |
| JpegProc | `512` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] خوارزمية معالجة JPEG . |
| JpegInerchangeFormat | `513` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] المؤشر إلى علامة SOI . |
| JpegInterchangeFormatLength | `514` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] طول دفق JFIF |
| JpegRestartInterval | `515` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] طول الفاصل الزمني لإعادة التشغيل . |
| JpegLosslessPredictors | `517` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] توقع proc بدون فقد . |
| JpegPointTransform | `518` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] تحويل النقطة بلا خسارة . |
| JpegQTables | `519` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] تعويضات Q matrice . |
| JpegDCtables | `520` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] إزاحة جدول DCT . |
| JpegACtables | `521` | [عفا عليه الزمن بواسطة الملاحظة الفنية رقم 2 التي تحدد مخطط JPEG-in-TIFF المنقح] تعويضات معامل التيار المتردد . |
| YcbcrCoefficients | `529` | RGB -&gt; تحويل YCbCr . |
| YcbcrSubSampling | `530` | عوامل أخذ العينات الفرعية من YCbCr. |
| YcbcrPositioning | `531` | تحديد المواقع للعينة الفرعية . |
| ReferenceBlackWhite | `532` | معلومات قياس الألوان . |
| XmlPacket | `700` | حزمة XML. المنشور المقدم TIFF rev 6.0 بواسطة Adobe XMP Specification ، يناير 2004. |
| OpiImageid | `32781` | OPI ImageID. تم تقديم المنشور TIFF rev 6.0 بواسطة Adobe TIFF technote . |
| Refpts | `32953` | النقاط المرجعية للصورة. علامة خاصة مسجلة في Island Graphics . |
| Copyright | `33432` | سلسلة حقوق النشر. تم سرد هذه العلامة في TIFF rev. 6.0 مع ملكية غير معروفة. |
| PhotoshopResources | `34377` | موارد صور Photoshop . |
| IccProfile | `34675` | ملف تعريف جهاز ICC المضمن |
| ExifIfdPointer | `34665` | مؤشر إلى Exif IFD . |
| XPTitle | `40091` | معلومات حول الصورة ، يستخدمها مستكشف Windows . ملفXPTitle يتم تجاهله بواسطة مستكشف Windows إذا كان ملفImageDescription العلامة موجودة . |
| XPComment | `40092` | تعليق على الصورة ، مستخدم بواسطة مستكشف Windows . |
| XPAuthor | `40093` | مؤلف الصورة ، المستخدم بواسطة مستكشف Windows . ملفXPAuthor يتم تجاهله بواسطة مستكشف Windows إذا كان ملفArtist العلامة موجودة . |
| XPKeywords | `40094` | الكلمات الأساسية للصورة ، المستخدمة بواسطة مستكشف Windows . |
| XPSubject | `40095` | صورة الموضوع ، مستخدمة بواسطة مستكشف Windows . |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
