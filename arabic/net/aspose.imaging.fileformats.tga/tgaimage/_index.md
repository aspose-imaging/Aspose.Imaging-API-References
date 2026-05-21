---
title: "الفئة TgaImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Tga.TgaImage class. تحكم في ملفات صور TGA النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا المصممة لتنسيق TARGA Truevision Advanced Raster Adapter مما يتيح تحميلًا وتخصيصًا سلسًا. قم بتحديث الخصائص العامة بسهولة مثل مؤلف الصورة، الطابع الزمني، معرف الصورة وإصدار البرنامج أثناء استخدام إعدادات مختلفة للبتات لكل بكسل، قناة ألفا وشفافية اللون. بالإضافة إلى ذلك، يمكنك تصدير صور TGA إلى تنسيقات نقطية شائعة أخرى لضمان التوافق لمشاريعك."
type: docs
weight: 7690
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

تفاعل مع ملفات الصور النقطية TGA باستخدام واجهة برمجة التطبيقات الخاصة بنا، المصممة لتنسيق TARGA (Truevision Advanced Raster Adapter)، مما يتيح تحميلًا وتخصيصًا سلسًا. قم بتحديث الخصائص العامة بسهولة مثل المؤلف، والطابع الزمني، ومعرّف الصورة، وإصدار البرنامج، مع إمكانية ضبط إعدادات عدد البتات لكل بكسل، وقناة ألفا، وشفافية اللون. بالإضافة إلى ذلك، يمكنك تصدير صور TGA إلى تنسيقات نقطية شائعة أخرى، لضمان التوافق مع مشاريعك.

```csharp
public class TgaImage : RasterCachedImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TgaImage](tgaimage/#constructor)(RasterImage) | إنشاء نسخة جديدة من الفئة `TgaImage` عن طريق توفير كائن صورة نقطية. يسهل هذا المُنشئ دمج الصور النقطية الموجودة مباشرةً في تنسيق صورة TGA، مما يبسط عملية التحويل لتحسين التوافق داخل أنظمة البرمجيات الخاصة بك. |
| [TgaImage](tgaimage/#constructor_1)(Stream) | تهيئة نسخة جديدة من الفئة `TgaImage` باستخدام تدفق لتحميل الصورة. يتيح هذا المُنشئ دمج بيانات الصورة من التدفقات بسلاسة، مما يسهل التعامل الفعال ومعالجة صور TGA داخل تطبيقات البرمجيات الخاصة بك. |
| [TgaImage](tgaimage/#constructor_2)(string) | يُنشئ كائنًا جديدًا من `TgaImage` باستخدام مسار الملف المقدم لتحميل محتوى الصورة. يقوم هذا المُنشئ بتهيئة نسخة الصورة بكفاءة، مما يتيح وصولًا سلسًا إلى ملفات صور TGA، ويسهل دمجها في سير عمل تطبيقك. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments/) { get; set; } | يسترجع أو يعيّن التعليقات التي قدمها مؤلف الصورة. غالبًا ما تحتوي هذه التعليقات على معلومات قيمة، مثل الأوصاف، التعليقات التوضيحية، أو سياق إضافي حول الصورة. من خلال الوصول إلى خاصية Author Comments أو تعديلها، يمكن للمطورين تحسين البيانات الوصفية المرتبطة بالصورة، وتزويد المستخدمين برؤى قيمة وسياق حول محتواها أو إنشاءها. هذا حقل ASCII يتألف من 324 بايتًا مُنظمًا كأربع أسطر كل منها 80 حرفًا، يتبع كل سطر مُنهيًا بصفر. |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname/) { get; set; } | يسترجع أو يعيّن اسم المؤلف المرتبط بالصورة. تتيح هذه الخاصية للمطورين الوصول إلى بيانات اسم المؤلف أو تعديلها، مما يوفر معلومات قيمة حول صانع الصورة. باستخدام خاصية Author Name، يمكن للمستخدمين التعرف بسهولة على الشخص المسؤول عن إنشاء أو المساهمة في الصورة، مما يعزز البيانات الوصفية العامة ويوفر سياقًا قيمًا للمشاهدين. هذا الحقل يتكون من 40 حرفًا ASCII لاسم المؤلف. إذا تم استخدام الحقل، يجب أن يحتوي على اسم الشخص الذي أنشأ الصورة (المؤلف). |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor/) { get; set; } | يسترجع أو يعيّن لون الخلفية للصورة. تتيح هذه الخاصية تحديد اللون المستخدم لخلفية الصورة، مما يضمن الاتساق ويعزز العرض البصري. إنها مفيدة بشكل خاص في السيناريوهات التي تُعرض فيها الصورة على خلفية بلون مختلف أو عند رسم الصورة على لوحة أخرى. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel/) { get; } | استرجاع قيمة البتات لكل بكسل، مما يوفر معلومات أساسية حول عمق ألوان الصورة. تُعد هذه الخاصية مقياسًا حيويًا لفهم مستوى التفاصيل وغنى الألوان في الصورة، وتساعد المطورين على تحسين خوارزميات المعالجة وتخصيص الموارد للمعالجة الفعّالة للصور. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel/) { get; } | الحصول على قيمة البايتات لكل بكسل، التي تشير إلى مقدار الذاكرة التي يشغلها كل بكسل في الصورة. تُعد هذه الخاصية مقياسًا مهمًا لإدارة الذاكرة وتحسينها، وتساعد المطورين على تخصيص الموارد ومعالجة بيانات الصورة بكفاءة. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp/) { get; set; } | الحصول على أو تعيين طابع التاريخ/الوقت. يحدد هذا الحقل قيمة التاريخ والوقت الذي تم حفظ الصورة فيه. على الرغم من أن أنظمة التشغيل عادةً ما تضيف طوابع زمنية للملفات، فإن هذه الميزة مُقدمة لأن نظام التشغيل قد يغيّر طابع التاريخ والوقت إذا تم نسخ الملف. باستخدام هذا الحقل، تضمن وجود منطقة غير معدلة لتسجيل التاريخ والوقت. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat/) { get; } | احصل على معلومات حيوية حول تنسيق ملف الصورة الممثلة بهذه النسخة من `TgaImage`. فهم تنسيق الملف أمر أساسي لفحوصات التوافق وضمان دمج سلس داخل أنظمة البرمجيات، مما يتيح معالجة وتعديل الصور بكفاءة. |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/) { get; } | يسترجع الجزء المقام من قيمة غاما، وهو عامل أساسي في تحديد تمثيل الألوان داخل الصور. بالنسبة للصور التي لا تحتوي على تصحيح غاما، يجب أن تكون القيمة 1.0، لضمان عرض ألوان دقيق. إن فهم واستخدام هذه المعلمة أساسي للحفاظ على دقة الألوان وتحقيق تصور صورة دقيق. |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/) { get; } | يحصل على الجزء البسط من قيمة غاما، وهو أساسي لتمثيل الألوان بدقة في الصور. في الصور بدون تصحيح غاما، يجب أن تكون هذه القيمة 1.0. فهم واستخدام هذه القيمة أمر حاسم للحفاظ على دقة الألوان وضمان عرض الصورة بدقة. |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha/) { get; } | استرجع قيمة منطقية تشير إلى ما إذا كان الـ `TgaImage` يتضمن قناة ألفا، مما يسهل تأثيرات الشفافية. هذه الخاصية توفر معلومات أساسية لمعالجة تركيب الصورة وعرضها، وتساعد المطورين على تنفيذ تأثيرات بصرية متنوعة وعمليات تركيب. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor/) { get; set; } | يسترجع أو يعيّن قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة لتحديد ما إذا كانت الصورة تشمل لون خلفية مميز منفصل عن محتوى المقدمة. تمكنك من تخصيص معالجة الصورة أو عرضها بناءً على وجود أو عدم وجود لون الخلفية. |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap/) { get; } | استرجع ما إذا كان كائن الـ `TgaImage` هذا يحتوي على خريطة ألوان. فهم وجود خريطة الألوان أمر حاسم لتفسير ومعالجة بيانات ألوان الصورة بدقة. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor/) { get; set; } | يسترجع أو يعيّن قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. هذه الخاصية أساسية لتحديد ما إذا كانت الصورة تدعم الشفافية، مما يساعدك على تنفيذ معالجة مناسبة للعمليات المتعلقة بالشفافية مثل الدمج، والتركيب، أو القناع. |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height/) { get; } | احصل على ارتفاع الصورة التي يغلفها كائن الـ `TgaImage` هذا. هذه الخاصية تزود المطورين بتفاصيل حيوية حول الأبعاد العمودية للصورة، مما يتيح دمجًا سلسًا ومعالجة للصور ضمن حلولهم البرمجية. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid/) { get; set; } | يسترجع أو يعيّن المعرف الفريد المرتبط بالصورة. هذا المعرف يعمل كنقطة مرجعية لتحديد وتمييز الصورة عن غيرها ضمن نظام أو تطبيق. من خلال تعيين أو استرجاع معرف الصورة، يمكنك إدارة وتتبع الصور بفعالية، مما يسهل عمليات إدارة الصور واسترجاعها بشكل منظم. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale/) { get; } | احصل على قيمة منطقية تشير إلى ما إذا كان الـ `TgaImage` يمثل صورة رمادية. هذه الخاصية حاسمة للتمييز بين الصور الملونة والرمادية، وتساعد المطورين على تطبيق تقنيات المعالجة والعرض المناسبة بناءً على خصائص ألوان الصورة. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid/) { get; set; } | يسترجع أو يعيّن اسم المهمة أو المعرف المرتبط بالصورة. هذه الخاصية تمكنك من الوصول إلى بيانات التعريف المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة أو تعديلها. باستخدام خاصية اسم/معرف المهمة، يمكن للمستخدمين بسهولة تحديد المشروع أو المهمة التي تتعلق بها الصورة، مما يسهل تنظيم وإدارة أصول الصورة ضمن سير عمل أو مشاريع أكبر. |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime/) { get; set; } | يسترجع أو يعيّن الطابع الزمني الذي يشير إلى وقت المهمة المرتبط بالصورة. هذه الخاصية تسمح للمطورين بالوصول إلى بيانات الوقت المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة أو تعديلها. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator/) { get; } | يسترجع الجزء المقام من نسبة أبعاد البكسل، وهو عامل حاسم في تحديد الشكل البصري للبكسلات داخل الصورة. هذه القيمة أساسية للحفاظ على تمثيل البكسل بدقة ونسب الأبعاد عبر عمليات عرض ومعالجة الصور المختلفة، مما يضمن مخرجات بصرية عالية الجودة. |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator/) { get; } | يسترجع الجزء البسط من نسبة أبعاد البكسل، الذي يؤثر على الشكل البصري للبكسلات داخل الصورة. فهم وتعديل هذه القيمة أمر أساسي لتحقيق تمثيل دقيق للبكسل ونسب الأبعاد في عرض ومعالجة الصور. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المخصص |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الخام. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يعيّن فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق. |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المفهرسة |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid/) { get; set; } | يدير تعريف البرنامج (المعرف) المرتبط بالصورة، مع السماح بما يصل إلى 40 حرفًا ASCII. هذه الخاصية تعمل كوسيلة لتحديد البرنامج المستخدم في إنشاء أو معالجة الصورة بشكل فريد، وتوفر بيانات تعريفية قيمة لأغراض التنظيم والمعلومات. |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion/) { get; set; } | يسترجع أو يعيّن إصدار البرنامج المرتبط بالصورة. الطول المقبول لسلسلة الإصدار عادةً ما يكون من 3 إلى 4 أحرف. هذه الخاصية مفيدة لتتبع البرنامج المستخدم لإنشاء أو تعديل الصورة ويمكن أن توفر سياقًا قيمًا لفحص معالجة الصور وتوافقها. |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter/) { get; set; } | يسترجع أو يعيّن المكوّن الحرفي لإصدار البرنامج المرتبط بالصورة. هذه الخاصية تمثل تفصيلًا إضافيًا ضمن سلسلة إصدار البرنامج ويمكن أن تكون مفيدة للتمييز بين الإصدارات الدقيقة. |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber/) { get; set; } | يسترجع أو يعيّن المكوّن الرقمي لإصدار البرنامج المرتبط بالصورة. هذه الخاصية تمثل الجزء الرقمي من سلسلة إصدار البرنامج، وتوفر معلومات مهمة حول نسخة البرنامج المستخدمة لإنشاء أو تعديل الصورة. |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor/) { get; set; } | يسترجع أو يعيّن اللون المفتاح المرتبط بالصورة. هذه الخاصية تتيح لك الوصول إلى اللون المحدد كلون مفتاح لمهام أو تأثيرات معالجة الصورة المحددة أو تعديلها. استخدام خاصية اللون المفتاح يمكن المستخدمين من تطبيق عمليات قائمة على اللون مثل إزالة الخلفية باللون الأخضر (chroma key) أو استبدال اللون، مما يعزز قدرات تعديل الصورة وإمكانيات الإبداع. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width/) { get; } | استرجع عرض الصورة التي يمثلها كائن الـ `TgaImage` هذا. هذه الخاصية تزود المطورين بمعلومات أساسية حول أبعاد الصورة، مما يسهل مهام معالجة وتعديل الصور المختلفة ضمن تطبيقاتهم البرمجية. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin/) { get; set; } | يسترجع أو يعيّن الإحداثي الأفقي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل يسار الشاشة (مثل سلسلة TARGA). |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin/) { get; set; } | يسترجع أو يعيّن الإحداثي الرأسي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل يسار الشاشة (مثل سلسلة TARGA). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness/)(int) | ضبط السطوع للصورة. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast/)(float) | تباين الصورة |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float) | تصحيح جاما للصورة. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float, float, float) | تصحيح جاما للصورة. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone/#clone)() | ينتج نسخة مكررة من الكائن الحالي، مكوّنًا كائنًا جديدًا ينسخ جميع السمات والخصائص من الأصل. هذه الطريقة تسهل إنشاء نسخ مطابقة، مما يضمن سلامة البيانات ويحافظ على حالة الكائن الحالي دون التأثير على الكائن الأصلي. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone/#clone_1)(TgaImage) | استنسخ خصائص كائن `TgaImage` آخر، مكوّنًا كائنًا جديدًا بسمات مطابقة. هذه العملية تضمن الحفاظ على سلامة البيانات وتسهّل تكرار خصائص الصورة دون تعديل الكائن المصدر. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop/#crop)(Rectangle) | قص الصورة إلى منطقة محددة. تسمح لك هذه الطريقة بتحديد مساحة مستطيلة داخل الصورة للاحتفاظ بها، مع حذف البقية. هذه العملية مفيدة للتركيز على محتوى معين داخل الصورة أو لإزالة أجزاء غير مرغوب فيها. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop/#crop_1)(int, int, int, int) | قص الصورة بتحديد إزاحات للحدود اليسرى، اليمنى، العليا، والسفلى. تسمح لك هذه الطريقة بتقليم الصورة عن طريق تحريك حدودها بشكل مستقل على المحورين الأفقي والرأسي. من خلال ضبط هذه الإزاحات، يمكنك التحكم بدقة في الأجزاء التي تريد الاحتفاظ بها من الصورة، وبالتالي قصها إلى الأبعاد المطلوبة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | يقوم بأداء التمويه على الصورة الحالية. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedimage/embeddigitalsignature/)(string) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة داخل الصورة باستخدام تقنية التضمين. |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals/#equals_1)(object) | تقوم الطريقة بإجراء مقارنة مساواة بين كائن الـ `TgaImage` الحالي وكائن آخر يُمرَّر كمعامل. تحدد بالتحديد ما إذا كانت خصائص الصورة الحالية تطابق خصائص الكائن الثاني، مما يساعد في تحديد تكافئهما لأغراض المقارنة ضمن سير عمل معالجة الصور. |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals/#equals)(TgaImage) | In an equality comparison, the method evaluates whether the current `TgaImage` instance is equal to the second image provided as a parameter. This operation facilitates determining if two TGA images are identical, aiding in image processing and comparison tasks. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | يفلتر المستطيل المحدد. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode/)() | Retrieve the hash code of the current instance. However, it's important to note that this hash code may not be suitable for use as a key, particularly because instances of the TgaImage class are not immutable. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale/)() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedimage/isdigitalsigned/)(string, int) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والحدّ المحدد. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels/)(Rectangle) | يحمّل بكسلات ARGB 32‑بت. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels/)(Rectangle) | يحمّل بكسلات ARGB 64‑بت. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels/)(Rectangle) | يحمّل بكسلات بتنسيق CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | يحمّل بكسلات ARGB 32‑بت جزئيًا عن طريق الحزم. |
| [LoadPartialArgb64Pixels](../../aspose.imaging/rasterimage/loadpartialargb64pixels/)(Rectangle, IPartialArgb64PixelLoader) | يحمّل بكسلات ARGB 64‑بت جزئيًا عن طريق الحزم. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | يحمّل البكسلات جزئيًا عن طريق الحزم. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels/)(Rectangle) | يحمّل البكسلات. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | يحمّل البيانات الخام. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | يحمّل البيانات الخام. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)() | يضبط الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) و[`Rotate`](../../aspose.imaging/rasterimage/rotate/) الطرق. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)(bool, Color) | يضبط الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) و[`Rotate`](../../aspose.imaging/rasterimage/rotate/) الطرق. |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedimage/normalizehistogram/)() | يضبط هيستوجرام الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resize the image while applying specific settings to maintain the desired dimensions and aspect ratio. By customizing image settings, you can effectively resize the image while ensuring optimal visual quality and compatibility with different display devices or applications. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize/#resize_2)(int, int, ResizeType) | Adjusts the size of the image using a specified resize type, which determines how the resizing operation is performed. This method provides flexibility in resizing images according to different algorithms or techniques. By choosing the appropriate resize type, you can achieve the desired balance between image quality and computational efficiency based on specific requirements or preferences. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate/#rotate_1)(float, bool, Color) | Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. This method allows for precise image manipulation, ensuring that the rotation maintains visual balance and consistency with the specified background color. It's ideal for tasks where accurate rotation around the center is necessary, such as orientation correction or artistic adjustments. |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip/)(RotateFlipType) | The \"RotateFlip\" method enables rotating and flipping operations on the image. It offers versatile functionality for manipulating image orientation, allowing users to perform rotations and flips according to their requirements, facilitating efficient image processing tasks within software applications. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.imaging/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32 بت. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32 بت للموقع المحدد. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | يعيّن الدقة لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality/) | Performs an equality comparison between two TGA images, considering both the first and second images involved in the comparison process. This method facilitates straightforward assessment of image equality, ensuring accurate analysis and decision-making within image processing workflows. |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality/) | Conducts a non-equality comparison between two TGA images, evaluating both the first and second images involved in the comparison. This method aids in identifying discrepancies or differences between images, enabling precise analysis and decision-making in image processing tasks. |

## أمثلة

Saving of the JPG image as a TGA image.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

Updating public properties of the loaded TGA image.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Getting values of the public properties of the loaded TGA image.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### انظر أيضًا

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga/)
* assembly [Aspose.Imaging](../../)


