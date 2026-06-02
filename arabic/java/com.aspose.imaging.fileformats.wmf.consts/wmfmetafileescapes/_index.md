---
title: "WmfMetafileEscapes"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد MetafileEscapes وظائف برنامج تشغيل الطابعة التي قد لا تكون قابلة للوصول مباشرةً من خلال سجلات WMF المعرفة في تعداد RecordType القسم 2.1.1.1."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

تحدد تعداد MetafileEscapes وظائف برنامج تشغيل الطابعة التي قد لا تكون متاحة مباشرةً من خلال سجلات WMF المعرفة في تعداد RecordType (القسم 2.1.1.1).
## الحقول

| حقل | الوصف |
| --- | --- |
| [Newframe](#Newframe) | يُخطر برنامج تشغيل الطابعة أن التطبيق قد انتهى من الكتابة إلى صفحة. |
| [Abortdoc](#Abortdoc) | يوقف معالجة المستند الحالي. |
| [Nextband](#Nextband) | يُخطر برنامج تشغيل الطابعة أن التطبيق قد انتهى من الكتابة إلى شريط. |
| [Setcolortable](#Setcolortable) | يضبط قيم جدول الألوان. |
| [Getcolortable](#Getcolortable) | يحصل على قيم جدول الألوان. |
| [Flushout](#Flushout) | يتسبب في تفريغ جميع المخرجات المعلقة إلى جهاز الإخراج. |
| [Draftmode](#Draftmode) | يشير إلى أن برنامج تشغيل الطابعة يجب أن يطبع النص فقط، دون رسومات. |
| [Queryescsupport](#Queryescsupport) | يستعلم برنامج تشغيل الطابعة لتحديد ما إذا كانت وظيفة escape محددة مدعومة على جهاز الإخراج الذي يتحكم فيه. |
| [Setabortproc](#Setabortproc) | يضبط الوظيفة المعرفة من قبل التطبيق التي تسمح بإلغاء مهمة الطباعة أثناء الطباعة. |
| [Startdoc](#Startdoc) | يُخطر برنامج تشغيل الطابعة بأن مهمة طباعة جديدة تبدأ. |
| [Enddoc](#Enddoc) | يُخطر برنامج تشغيل الطابعة بأن مهمة الطباعة الحالية تنتهي. |
| [Getphyspagesize](#Getphyspagesize) | يسترجع حجم الصفحة الفعلية المحدد حاليًا على جهاز الإخراج. |
| [Getprintingoffset](#Getprintingoffset) | يسترجع الإزاحة من الزاوية العليا اليسرى للصفحة الفعلية حيث يبدأ الطباعة أو الرسم الفعلي. |
| [Getscalingfactor](#Getscalingfactor) | يسترجع عوامل التحجيم لمحوري x و y للطابعة. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | يُستخدم لتضمين ملف ميتافايل محسّن (EMF) داخل ملف ميتافايل WMF. |
| [Setpenwidth](#Setpenwidth) | يضبط عرض القلم بالبكسل. |
| [Setcopycount](#Setcopycount) | يضبط عدد النسخ. |
| [Setpapersource](#Setpapersource) | يضبط المصدر، مثل درج ورق معين أو حاوية على الطابعة، للنماذج المخرجة. |
| [Passthrough](#Passthrough) | هذا السجل يمر ببيانات عشوائية. |
| [Gettechnology](#Gettechnology) | يحصل على معلومات حول تقنية الرسومات المدعومة على الجهاز. |
| [Setlinecap](#Setlinecap) | يحدد وضع رسم الخطوط لاستخدامه في الإخراج إلى جهاز. |
| [Setlinejoin](#Setlinejoin) | يحدد وضع ربط الخطوط لاستخدامه في الإخراج إلى جهاز. |
| [Setmiterlimit](#Setmiterlimit) | يضبط الحد لطول وصلات الميتر لاستخدامها في الإخراج إلى جهاز. |
| [Bandinfo](#Bandinfo) | يسترجع أو يحدد الإعدادات المتعلقة بالتقسيط على الجهاز، مثل عدد الشرائح. |
| [Drawpatternrect](#Drawpatternrect) | يرسم مستطيلًا بنمط محدد. |
| [Getvectorpensize](#Getvectorpensize) | يسترجع حجم القلم الفعلي المحدد حاليًا على الجهاز. |
| [Getvectorbrushsize](#Getvectorbrushsize) | يسترجع حجم الفرشاة الفعلي المحدد حاليًا على الجهاز. |
| [Enableduplex](#Enableduplex) | يفعل أو يعطل الطباعة ذات الوجهين (duplex) على الجهاز. |
| [Getsetpaperbins](#Getsetpaperbins) | يسترجع أو يحدد مصدر نماذج الإخراج على الجهاز. |
| [Getsetprintorient](#Getsetprintorient) | يسترجع أو يحدد اتجاه الورق على الجهاز. |
| [Enumpaperbins](#Enumpaperbins) | يسترجع معلومات حول مصادر النماذج المختلفة على جهاز الإخراج. |
| [Setdibscaling](#Setdibscaling) | يحدد مقياس صور البت المستقلة عن الجهاز (DIBs). |
| [Epsprinting](#Epsprinting) | يشير إلى بداية ونهاية قسم PostScript المغلف (EPS). |
| [Enumpapermetrics](#Enumpapermetrics) | يستعلم برنامج تشغيل الطابعة عن أبعاد الورق وبيانات النماذج الأخرى. |
| [Getsetpapermetrics](#Getsetpapermetrics) | يسترجع أو يحدد أبعاد الورق وبيانات النماذج الأخرى على جهاز الإخراج. |
| [PostscriptData](#PostscriptData) | يرسل بيانات PostScript عشوائية إلى جهاز الإخراج. |
| [PostscriptIgnore](#PostscriptIgnore) | يُخطر جهاز الإخراج بتجاهل بيانات PostScript. |
| [Getdeviceunits](#Getdeviceunits) | يحصل على وحدات الجهاز المكوَّنة حاليًا على جهاز الإخراج. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | يحصل على مقاييس النص الموسعة المكوَّنة حاليًا على جهاز الإخراج. |
| [Getpairkerntable](#Getpairkerntable) | يحصل على جدول الترصيع للخط (kern) المحدد حاليًا على جهاز الإخراج. |
| [Exttextout](#Exttextout) | يرسم النص باستخدام الخط المحدد حاليًا، ولون الخلفية، ولون النص. |
| [Getfacename](#Getfacename) | يحصل على اسم عائلة الخط المكوَّن حاليًا على الجهاز. |
| [Downloadface](#Downloadface) | يضبط اسم عائلة الخط على الجهاز. |
| [MetafileDriver](#MetafileDriver) | يستعلم برنامج تشغيل الطابعة عن دعم ملفات الميتا على جهاز الإخراج. |
| [Querydibsupport](#Querydibsupport) | يستعلم برنامج تشغيل الطابعة عن دعمه لملفات DIBs على جهاز الإخراج. |
| [BeginPath](#BeginPath) | يفتح مسارًا. |
| [ClipToPath](#ClipToPath) | يحدد منطقة قص محصورة بمسار. |
| [EndPath](#EndPath) | ينهي مسارًا. |
| [OpenChannel](#OpenChannel) | نفس ما هو STARTDOC المحدد بوثيقة NULL واسم ملف الإخراج، والبيانات في وضع raw، ونوع صفر. |
| [Downloadheader](#Downloadheader) | يُعطي برنامج تشغيل الطابعة تعليمات لتنزيل مجموعات من إجراءات PostScript. |
| [CloseChannel](#CloseChannel) | نفس ما هو ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | يرسل بيانات عشوائية مباشرة إلى برنامج تشغيل الطابعة، والذي من المتوقع أن يعالج هذه البيانات فقط عندما يكون في وضع PostScript. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | يرسل بيانات عشوائية مباشرة إلى برنامج تشغيل الطابعة. |
| [PostscriptIdentify](#PostscriptIdentify) | يضبط برنامج تشغيل الطابعة على وضع PostScript أو GDI. |
| [PostscriptInjection](#PostscriptInjection) | يدرج كتلة من البيانات الخام في تدفق PostScript. |
| [Checkjpegformat](#Checkjpegformat) | يتحقق مما إذا كانت الطابعة تدعم صورة JPEG. |
| [Checkpngformat](#Checkpngformat) | يتحقق مما إذا كانت الطابعة تدعم صورة PNG. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | يحصل على معلومات حول إعداد ميزة محدد لبرنامج تشغيل طابعة PostScript. |
| [MxdcEscape](#MxdcEscape) | يُمكّن التطبيقات من كتابة المستندات إلى ملف أو إلى طابعة بصيغة XML Paper Specification (XPS). |
| [Spclpassthrough2](#Spclpassthrough2) | يُمكّن التطبيقات من تضمين إجراءات خاصة وبيانات عشوائية أخرى في المستندات. |
### Newframe {#Newframe}
```
public static final int Newframe
```


يُخطر برنامج تشغيل الطابعة أن التطبيق قد انتهى من الكتابة إلى صفحة.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


يوقف معالجة المستند الحالي.

### Nextband {#Nextband}
```
public static final int Nextband
```


يُخطر برنامج تشغيل الطابعة أن التطبيق قد انتهى من الكتابة إلى شريط.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


يضبط قيم جدول الألوان.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


يحصل على قيم جدول الألوان.

### Flushout {#Flushout}
```
public static final int Flushout
```


يتسبب في تفريغ جميع المخرجات المعلقة إلى جهاز الإخراج.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


يشير إلى أن برنامج تشغيل الطابعة يجب أن يطبع النص فقط، دون رسومات.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


يستعلم برنامج تشغيل الطابعة لتحديد ما إذا كانت وظيفة escape محددة مدعومة على جهاز الإخراج الذي يتحكم فيه.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


يضبط الوظيفة المعرفة من قبل التطبيق التي تسمح بإلغاء مهمة الطباعة أثناء الطباعة.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


يُخطر برنامج تشغيل الطابعة بأن مهمة طباعة جديدة تبدأ.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


يُخطر برنامج تشغيل الطابعة بأن مهمة الطباعة الحالية تنتهي.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


يسترجع حجم الصفحة الفعلية المحدد حاليًا على جهاز الإخراج.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


يسترجع الإزاحة من الزاوية العليا اليسرى للصفحة الفعلية حيث يبدأ الطباعة أو الرسم الفعلي.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


يسترجع عوامل التحجيم لمحوري x و y للطابعة.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


يُستخدم لتضمين ملف ميتافايل محسّن (EMF) داخل ملف ميتافايل WMF.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


يضبط عرض القلم بالبكسل.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


يضبط عدد النسخ.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


يضبط المصدر، مثل درج ورق معين أو حاوية على الطابعة، للنماذج المخرجة.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


هذا السجل يمر ببيانات عشوائية.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


يحصل على معلومات حول تقنية الرسومات المدعومة على الجهاز.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


يحدد وضع رسم الخطوط لاستخدامه في الإخراج إلى جهاز.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


يحدد وضع ربط الخطوط لاستخدامه في الإخراج إلى جهاز.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


يضبط الحد لطول وصلات الميتر لاستخدامها في الإخراج إلى جهاز.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


يسترجع أو يحدد الإعدادات المتعلقة بالتقسيط على الجهاز، مثل عدد الشرائح.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


يرسم مستطيلًا بنمط محدد.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


يسترجع حجم القلم الفعلي المحدد حاليًا على الجهاز.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


يسترجع حجم الفرشاة الفعلي المحدد حاليًا على الجهاز.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


يفعل أو يعطل الطباعة ذات الوجهين (duplex) على الجهاز.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


يسترجع أو يحدد مصدر نماذج الإخراج على الجهاز.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


يسترجع أو يحدد اتجاه الورق على الجهاز.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


يسترجع معلومات حول مصادر النماذج المختلفة على جهاز الإخراج.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


يحدد مقياس صور البت المستقلة عن الجهاز (DIBs).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


يشير إلى بداية ونهاية قسم PostScript المغلف (EPS).

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


يستعلم برنامج تشغيل الطابعة عن أبعاد الورق وبيانات النماذج الأخرى.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


يسترجع أو يحدد أبعاد الورق وبيانات النماذج الأخرى على جهاز الإخراج.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


يرسل بيانات PostScript عشوائية إلى جهاز الإخراج.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


يُخطر جهاز الإخراج بتجاهل بيانات PostScript.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


يحصل على وحدات الجهاز المكوَّنة حاليًا على جهاز الإخراج.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


يحصل على مقاييس النص الموسعة المكوَّنة حاليًا على جهاز الإخراج.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


يحصل على جدول الترصيع للخط (kern) المحدد حاليًا على جهاز الإخراج.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


يرسم النص باستخدام الخط المحدد حاليًا، ولون الخلفية، ولون النص.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


يحصل على اسم عائلة الخط المكوَّن حاليًا على الجهاز.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


يضبط اسم عائلة الخط على الجهاز.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


يستعلم برنامج تشغيل الطابعة عن دعم ملفات الميتا على جهاز الإخراج.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


يستعلم برنامج تشغيل الطابعة عن دعمه لملفات DIBs على جهاز الإخراج.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


يفتح مسارًا.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


يحدد منطقة قص محاطة بمسار. يجب أن يكون الإدخال كمية 16‑بت تحدد الإجراء المتخذ.

### EndPath {#EndPath}
```
public static final int EndPath
```


ينهي مسارًا.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


نفس ما هو STARTDOC المحدد بوثيقة NULL واسم ملف الإخراج، والبيانات في وضع raw، ونوع صفر.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


يُعطي برنامج تشغيل الطابعة تعليمات لتنزيل مجموعات من إجراءات PostScript.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


نفس ما هو ENDDOC. راجع OPEN\\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


يرسل بيانات عشوائية مباشرة إلى برنامج تشغيل الطابعة، والذي من المتوقع أن يعالج هذه البيانات فقط عندما يكون في وضع PostScript. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


يرسل بيانات عشوائية مباشرة إلى برنامج تشغيل الطابعة.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


يضبط برنامج تشغيل الطابعة على وضع PostScript أو GDI.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


يدرج كتلة من البيانات الخام في تدفق PostScript. يجب أن يكون الإدخال كمية 32‑بت تحدد عدد البايتات التي سيتم حقنها، وكمية 16‑بت تحدد نقطة الحقن، وكمية 16‑بت تحدد رقم الصفحة، تليها البايتات التي سيتم حقنها.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


يتحقق مما إذا كانت الطابعة تدعم صورة JPEG.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


يتحقق مما إذا كانت الطابعة تدعم صورة PNG.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


يحصل على معلومات حول إعداد ميزة محدد لبرنامج تشغيل طابعة PostScript.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


يُمكّن التطبيقات من كتابة المستندات إلى ملف أو إلى طابعة بصيغة XML Paper Specification (XPS).

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


يُمكّن التطبيقات من تضمين إجراءات خاصة وبيانات عشوائية أخرى في المستندات.

