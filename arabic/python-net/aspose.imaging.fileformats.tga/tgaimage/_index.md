---
title: "TgaImage Class"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.tga/tgaimage/
---

**Summary:** Manipulate TGA raster image files with our API, tailored for the TARGA<br/>            (Truevision Advanced Raster Adapter) format, enabling seamless loading and<br/>            customization. Easily update public properties such as author, timestamp,<br/>            image ID, and software version, while using various bits per pixel settings,<br/>            alpha channel and color transparency. Additionally, you can export TGA images<br/>            to other popular raster formats, ensuring compatibility for your projects.

**Module:** [aspose.imaging.fileformats.tga](/imaging/python-net/aspose.imaging.fileformats.tga/)

**Full Name:** aspose.imaging.fileformats.tga.TgaImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TgaImage(path)](#TgaImage_path_1) | يقوم بتهيئة كائن جديد من [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) باستخدام مسار الملف المقدم لـ <br/>            تحميل محتوى الصورة. يقوم هذا المُنشئ بتهيئة نسخة الصورة بكفاءة <br/>            مما يسمح بالوصول السلس إلى ملفات صور TGA، مبسطًا عملية التكامل <br/>            في سير عمل تطبيقك. |
| [TgaImage(raster_image)](#TgaImage_raster_image_2) | إنشاء نسخة جديدة من فئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) عن طريق توفير كائن صورة نقطية <br/>            . يسهّل هذا المُنشئ التكامل المباشر للصور النقطية الموجودة في تنسيق صورة TGA، مما يبسط عملية التحويل لتحقيق <br/>            توافقية محسّنة داخل أنظمة البرمجيات الخاصة بك. |
| [TgaImage(stream)](#TgaImage_stream_3) | تهيئة نسخة جديدة من فئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) باستخدام تدفق <br/>            لتحميل الصورة. يتيح هذا المُنشئ التكامل السلس لبيانات الصورة <br/>            من التدفقات، مما يُسهل المعالجة الفعّالة للصور بصيغة TGA داخل <br/>            تطبيقات البرمجيات الخاصة بك. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| author_comments | string | r/w | يقوم باسترجاع أو تعيين التعليقات التي قدمها مؤلف الصورة. غالبًا ما تحتوي هذه التعليقات <br/>            على معلومات قيّمة، مثل الأوصاف، التعليقات التوضيحية، أو <br/>            سياق إضافي حول الصورة. من خلال الوصول إلى خاصية تعليقات المؤلف (Author Comments) أو تعديلها، يمكن للمطورين تحسين البيانات الوصفية المرتبطة بالصورة، وتزويد المستخدمين برؤى قيمة وسياق حول محتواها أو إنشائها.<br/>            هذا حقل ASCII يتألف من 324 بايتًا مُنظمًا كأربع أسطر<br/>            كل سطر يحتوي على 80 حرفًا، يتبع كل سطر مُنهيًا بصفر. |
| author_name | string | r/w | يقوم باسترجاع أو تعيين اسم المؤلف المرتبط بالصورة. تسمح هذه الخاصية <br/>            للمطورين بالوصول إلى بيانات اسم المؤلف أو تعديلها، مما يوفر <br/>            معلومات قيّمة حول صانع الصورة. باستخدام خاصية اسم المؤلف (Author Name)، يمكن للمستخدمين بسهولة التعرف على الفرد المسؤول عن إنشاء أو <br/>            المساهمة في الصورة، مما يعزز البيانات الوصفية العامة لها ويقدم سياقًا قيمًا للمشاهدين.<br/>            هذا الحقل يتألف من 40 حرفًا ASCII للاسم. إذا تم استخدام الحقل،<br/>            يجب أن يحتوي على اسم الشخص الذي أنشأ الصورة (المؤلف). |
| auto_adjust_palette | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تعديل لوحة الألوان تلقائيًا. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يقوم باسترجاع أو تعيين لون خلفية الصورة. تسمح هذه الخاصية <br/>            لك بتحديد اللون المستخدم لخلفية الصورة، مما يضمن التناسق و <br/>            تحسين العرض البصري. إنها مفيدة بشكل خاص في السيناريوهات التي تكون فيها <br/>            الصورة معروضة على خلفية بلون مختلف أو عند عرض الصورة على لوحة أخرى. |
| bits_per_pixel | int | r | استرجاع قيمة البتات لكل بكسل، مما يوفر معلومات أساسية حول <br/>            عمق ألوان الصورة. تُعد هذه الخاصية مقياسًا حاسمًا لفهم <br/>            مستوى التفاصيل وغنى الألوان الموجود في الصورة، مما يساعد المطورين على <br/>            تحسين خوارزميات المعالجة وتخصيص الموارد للمعالجة الفعّالة للصور <br/>            ومهام العرض. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود الكائن. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| bytes_per_pixel | int | r | الحصول على قيمة البايتات لكل بكسل، التي تُظهر مقدار الذاكرة التي يشغلها <br/>            كل بكسل في الصورة. تُعد هذه الخاصية مقياسًا مهمًا لإدارة الذاكرة <br/>            وتحسينها، مما يساعد المطورين على تخصيص الموارد بكفاءة <br/>            ومعالجة بيانات الصورة. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | يحصل على حاوية [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | يحصل على تدفق بيانات الكائن. |
| date_time_stamp | System.Nullable`1[[System.DateTime]] | r/w | يقوم بالحصول على أو تعيين طابع التاريخ/الوقت.<br/>            يحدد هذا الحقل قيمة التاريخ والوقت الذي تم حفظ الصورة فيه. <br/>            على الرغم من أن أنظمة التشغيل عادةً ما تضيف طوابع زمنية وتاريخية للملفات، فإن هذه الميزة <br/>            مُقدمة لأن نظام التشغيل قد يغيّر طابع الوقت والتاريخ إذا تم <br/>            نسخ الملف. باستخدام هذه المنطقة، تضمن وجود منطقة غير معدلة لتسجيل التاريخ والوقت. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن كائن Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | احصل على معلومات حيوية حول تنسيق ملف الصورة الممثلة بهذه <br/>            النسخة من [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). فهم تنسيق الملف أمر أساسي لـ <br/>            فحص التوافق وضمان التكامل السلس داخل أنظمة البرمجيات، <br/>            مما يتيح معالجة فعّالة وتعديل الصور. |
| gamma_value_denominator | int | r | يقوم باسترجاع الجزء المقام من قيمة جاما، وهو عامل أساسي في <br/>            تحديد تمثيل الألوان داخل الصور. بالنسبة للصور التي تفتقر إلى تصحيح جاما، يجب أن تكون هذه القيمة 1.0، لضمان عرض ألوان دقيق. <br/>            تقدير واستخدام هذه المعلمة أساسي للحفاظ على دقة الألوان وتحقيق تصور صورة دقيق. |
| gamma_value_numerator | int | r | يقوم بالحصول على الجزء البسط من قيمة الجاما، وهو ضروري لتمثيل ألوان دقيق في الصور. في الصور بدون تصحيح جاما، يجب أن تكون هذه القيمة 1.0. فهم واستخدام هذه القيمة أمر حاسم للحفاظ على دقة الألوان وضمان عرض صورة صحيح. |
| has_alpha | bool | r | استرجاع قيمة منطقية تشير إلى ما إذا كانت [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) تشمل <br/>            قناة ألفا، مما يُسهل تأثيرات الشفافية. توفر هذه الخاصية معلومات أساسية <br/>            لمعالجة تركيب الصورة وعرضها، وتساعد المطورين على <br/>            تنفيذ تأثيرات بصرية متنوعة وعمليات تركيب. |
| has_background_color | bool | r/w | يقوم باسترجاع أو تعيين قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة لتحديد ما إذا كانت الصورة تشمل <br/>            لون خلفية مميز منفصل عن محتوى المقدمة. تمكّنك من تخصيص معالجة الصورة أو عرضها بناءً على وجود أو عدم وجود <br/>            لون خلفية. |
| has_color_map | bool | r | استرجاع ما إذا كانت هذه النسخة من [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) تحتوي على خريطة ألوان. <br/>            فهم وجود خريطة الألوان أمر حاسم للتفسير الدقيق <br/>            ومعالجة بيانات ألوان الصورة. |
| has_transparent_color | bool | r/w | يقوم باسترجاع أو تعيين قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على <br/>            لون شفاف. هذه الخاصية أساسية لتحديد ما إذا كانت الصورة <br/>            تدعم الشفافية، مما يساعدك على تنفيذ معالجة مناسبة للعمليات المتعلقة بالشفافية مثل الدمج، التركيب، أو القناع. |
| height | int | r | احصل على ارتفاع الصورة المغلفة بهذا [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            المثيل. توفر هذه الخاصية للمطورين تفاصيل حيوية حول الأبعاد الرأسية للصورة، مما يتيح دمجًا سلسًا ومعالجة الصور ضمن حلولهم البرمجية. |
| horizontal_resolution | float | r/w | يحصل أو يعيّن الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_id | string | r/w | يحصل أو يعيّن المعرف الفريد المرتبط بالصورة. يعمل هذا المعرف كنقطة مرجعية لتحديد وتمييز الصورة عن غيرها داخل نظام أو تطبيق. من خلال تعيين أو استرجاع معرف الصورة، يمكنك إدارة وتتبع الصور بفعالية، مما يسهل عمليات إدارة واسترجاع الصور المنظمة.<br/>            <br/>هذا الحقل الاختياري يحتوي على معلومات تعريفية حول الصورة. الحد الأقصى لطول هذا الحقل هو 255 بايت.<br/> |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | يحصل أو يعيّن مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتاً حالياً. |
| is_gray_scale | bool | r | احصل على قيمة منطقية تشير إلى ما إذا كان [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) يمثل صورة ذات تدرج رمادي. هذه الخاصية حاسمة للتمييز بين الصور الملونة وصور التدرج الرمادي، مما يساعد المطورين على تطبيق تقنيات المعالجة والعرض المناسبة بناءً على خصائص اللون في الصورة. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| job_name_or_id | string | r/w | يحصل أو يعيّن اسم المهمة أو المعرف المرتبط بالصورة. تتيح هذه الخاصية لك الوصول إلى بيانات التعريف المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة أو تعديلها. باستخدام خاصية اسم/معرف المهمة، يمكن للمستخدمين بسهولة تحديد المشروع أو المهمة التي تتعلق بها الصورة، مما يسهل تنظيم وإدارة أصول الصورة ضمن سير عمل أو مشاريع أكبر. |
| job_time | System.Nullable`1[[System.TimeSpan]] | r/w | يحصل أو يعيّن الطابع الزمني الذي يشير إلى وقت المهمة المرتبط بالصورة. تتيح هذه الخاصية للمطورين الوصول إلى بيانات التعريف الزمنية المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة أو تعديلها. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | يحصل على بيانات التعريف الخاصة بالصورة. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| pixel_aspect_ratio_denominator | int | r | يحصل على الجزء المقام من نسبة أبعاد البكسل، وهو عامل حاسم في تحديد المظهر البصري للبكسلات داخل الصورة. هذه القيمة أساسية للحفاظ على تمثيل دقيق للبكسل ونسب الأبعاد عبر عمليات عرض ومعالجة الصور المختلفة، مما يضمن مخرجات بصرية عالية الجودة. |
| pixel_aspect_ratio_numerator | int | r | يحصل على الجزء البسط من نسبة أبعاد البكسل، الذي يؤثر على المظهر البصري للبكسلات داخل الصورة. فهم هذه القيمة وتعديلها أمر أساسي لتحقيق تمثيل دقيق للبكسل ونسب الأبعاد في عرض ومعالجة الصور. |
| premultiply_components | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | يحصل أو يضبط محول الألوان المخصص |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على تنسيق البيانات الخام. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | يحصل أو يضبط محول الألوان المفهرسة |
| raw_line_size | int | r | يحصل على حجم السطر الخام بالبايت. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | يحصل على حجم الكائن. |
| software_id | string | r/w | يدير تعريف البرنامج (المعرف) المرتبط بالصورة، مع السماح بما يصل إلى 40 حرفًا ASCII. تُستخدم هذه الخاصية لتحديد البرنامج المستخدم في إنشاء أو معالجة الصورة بشكل فريد، وتوفر بيانات تعريفية قيمة لأغراض التنظيم والمعلومات. |
| software_version | string | r/w | يحصل أو يعيّن إصدار البرنامج المرتبط بالصورة. عادةً ما يكون طول سلسلة الإصدار المقبول من 3 إلى 4 أحرف. هذه الخاصية مفيدة لتتبع البرنامج المستخدم لإنشاء أو تعديل الصورة ويمكن أن توفر سياقًا قيمًا لمعالجة الصور وفحوصات التوافق. |
| software_version_letter | System.Char | r/w | يحصل أو يعيّن الحرف المكوّن لإصدار البرنامج المرتبط بالصورة. تمثل هذه الخاصية تفصيلًا إضافيًا داخل سلسلة إصدار البرنامج ويمكن أن تكون مفيدة للتمييز الدقيق بين الإصدارات. |
| software_version_number | int | r/w | يحصل أو يعيّن المكوّن الرقمي لإصدار البرنامج المرتبط بالصورة. تمثل هذه الخاصية الجزء الرقمي من سلسلة إصدار البرنامج، وتوفر معلومات هامة حول نسخة البرنامج المستخدمة لإنشاء أو تعديل الصورة. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن اللون المفتاح المرتبط بالصورة. تتيح هذه الخاصية لك الوصول إلى اللون المحدد كلون مفتاح لمهام أو تأثيرات معالجة الصورة المحددة أو تعديلها. يتيح استخدام خاصية اللون المفتاح للمستخدمين تطبيق عمليات تعتمد على اللون مثل إزالة الخلفية (chroma key) أو استبدال اللون، مما يعزز قدرات تعديل الصورة وإمكانيات الإبداع.<br/>            <br/>يمكن اعتبار اللون المفتاح كـ ‘لون الخلفية’ أو ‘اللون الشفاف’.<br/>            هذا هو لون المنطقة ‘غير الصورة’ على الشاشة، وهو نفس اللون الذي ستُمسح إليه الشاشة إذا تم مسحها في التطبيق. |
| update_xmp_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| use_raw_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| vertical_resolution | float | r/w | يحصل أو يضبط الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | احصل على عرض الصورة التي يمثلها هذا [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            المثيل. توفر هذه الخاصية للمطورين معلومات أساسية حول أبعاد الصورة، مما يسهل مهام معالجة وتعديل الصور المختلفة ضمن تطبيقاتهم البرمجية. |
| x_origin | int | r/w | يحصل أو يضبط الإحداثي الأفقي المطلق للزاوية السفلية اليسرى للصورة<br/>            كما يتم وضعها على جهاز عرض يكون أصله في الزاوية السفلية اليسرى لل<br/>            الشاشة (مثال، سلسلة TARGA). |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
| y_origin | int | r/w | يحصل أو يضبط الإحداثي الرأسي المطلق للزاوية السفلية اليسرى للصورة<br/>            كما يتم وضعها على جهاز عرض يكون أصله في الزاوية السفلية اليسرى لل<br/>            الشاشة (مثال، سلسلة TARGA). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | ضبط سطوع الصورة. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | تباين الصورة |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | تصحيح جاما لصورة. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | تصحيح جاما لصورة. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| auto_brightness_contrast() | ينفّذ تطبيعًا تلقائيًا متكيفًا للسطوع والتباين لكامل الصورة. |
| auto_rotate() | يدور الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من Exif <br/>            metadata. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح،<br/>            مما يعزز تجربة المستخدم ويزيل الحاجة إلى التعديلات اليدوية. من خلال <br/>            تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، موفرًا تجربة مشاهدة سلسة <br/>            عبر منصات وأجهزة مختلفة. تُبسّط عملية الدوران الآلية التعامل مع الصور وتُحسّن القابلية العامة للاستخدام، خاصةً عند <br/>            التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| binarize_otsu() | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | يمزج هذه النسخة من الصورة مع الصورة _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | يمزج هذه النسخة من الصورة مع الصورة _overlay_. |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل أي بيانات إضافية من [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_11) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_load(stream)](#can_load_stream_13) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_save(options)](#can_save_options_18) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [clone()](#clone__19) | ينتج نسخة مكررة من الكائن الحالي، مُنشئًا كائنًا جديدًا ينسخ <br/>            جميع السمات والخصائص للنسخة الأصلية. تُسهل هذه الطريقة <br/>            إنشاء نسخ مطابقة، مما يضمن سلامة البيانات ويحافظ على حالة <br/>            الكائن الحالي دون التأثير على الكائن الأصلي. |
| [clone(tga_image)](#clone_tga_image_20) | تكرار خصائص كائن [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) آخر، وإنشاء <br/>            نسخة جديدة ذات سمات مطابقة. يضمن هذا الإجراء الحفاظ على <br/>            سلامة البيانات ويسهل تكرار خصائص الصورة دون <br/>            تعديل الكائن المصدر. |
| [create(files)](#create_files_21) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | ينشئ مثيلًا من [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) من مصفوفة البكسل المقدمة.<br/>            <br/>            يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل.<br/>            لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص. |
| [create(images)](#create_images_25) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(images, dispose_images)](#create_images_dispose_images_26) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | ينشئ خيارات الإنشاء المتعددة الصفحات المحددة. |
| [create_from_files(files)](#create_from_files_files_28) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_image(raster_image)](#create_from_image_raster_image_30) | يُهيئ نسخة جديدة من الفئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). |
| [create_from_images(images)](#create_from_images_images_31) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | يُهيئ نسخة جديدة من الفئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_34) | قم بقص الصورة بتحديد إزاحات للحدود اليسرى، اليمنى، العليا والسفلى <br/>            . تتيح لك هذه الطريقة تقليم الصورة عن طريق تحريك حدودها <br/>            بشكل مستقل على المحاور الأفقية والرأسية. من خلال ضبط هذه الإزاحات، <br/>            يمكنك التحكم بدقة في الأجزاء التي تريد الاحتفاظ بها، وبالتالي <br/>            قصها إلى الأبعاد المطلوبة. |
| [crop(rectangle)](#crop_rectangle_35) | قم بقص الصورة إلى منطقة محددة. تتيح لك هذه الطريقة تحديد <br/>            مساحة مستطيلة داخل الصورة للاحتفاظ بها، مع حذف البقية. هذه العملية <br/>            مفيدة للتركيز على محتوى معين داخل الصورة أو إزالة الأجزاء غير المرغوب فيها. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | يُجري تمويهًا على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | يُجري تمويهًا على الصورة الحالية. |
| [embed_digital_signature(password)](#embed_digital_signature_password_38) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التستغنوجرافيا. |
| [filter(rectangle, options)](#filter_rectangle_options_39) | يفلتر المستطيل المحدد. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_40) | يحصل على بكسل صورة 32-بت ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_41) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_42) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_43) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_45) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_46) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_47) | يحصل على تنسيق الملف. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_48) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_49) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_50) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_51) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [get_original_options()](#get_original_options__52) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_53) | يحصل على بكسل صورة. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_54) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_55) | يحصل على عرض نسبي. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_56) | يحوّل إلى aps. |
| [get_skew_angle()](#get_skew_angle__57) | يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح. |
| grayscale() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_58) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |
| [load(file_path)](#load_file_path_59) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(file_path, load_options)](#load_file_path_load_options_60) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(stream)](#load_stream_61) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_62) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_63) | يحمّل بكسلات ARGB 32‑بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_64) | يحمّل بكسلات ARGB 64‑بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_65) | يحمّل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_66) | يحمّل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67) | يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68) | يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_69) | يحمّل بكسلات جزئيًا حسب الحزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_70) | يحمّل بكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71) | يحمّل بيانات خام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72) | يحمّل بيانات خام. |
| [load_stream(stream)](#load_stream_stream_73) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_74) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_75) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| normalize_angle() | يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) . |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_76) | يضبط الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من الانحراف في المسح.<br/>            تستخدم هذه الطريقة أساليب [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | يُعَدِّل مدرج الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_77) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_78) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| remove_metadata() | يزيل بيانات التعريف لهذه الصورة عن طريق تعيين قيمة [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) إلى **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | يضبط حجم الصورة باستخدام نوع تغيير حجم محدد، والذي يحدد كيفية <br/>            تنفيذ عملية تغيير الحجم. توفر هذه الطريقة مرونة في تعديل حجم <br/>            الصور وفقًا لخوارزميات أو تقنيات مختلفة. باختيار نوع تغيير الحجم <br/>            المناسب، يمكنك تحقيق التوازن المطلوب بين جودة الصورة <br/>            وكفاءة الحوسبة بناءً على المتطلبات أو التفضيلات المحددة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | غيّر حجم الصورة مع تطبيق إعدادات محددة للحفاظ على الأبعاد المطلوبة <br/>            ونسبة العرض إلى الارتفاع. من خلال تخصيص إعدادات الصورة، يمكنك بفعالية <br/>            تعديل حجم الصورة مع ضمان جودة بصرية مثالية وتوافق مع <br/>            أجهزة العرض أو التطبيقات المختلفة. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | يقوم بتغيير حجم الصورة. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | يقوم بتغيير حجم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_93) | يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_94) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_95) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_96) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [rotate(angle)](#rotate_angle_97) | تدوير الصورة حول المركز. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_98) | يدور الصورة حول مركزها بزاوية محددة مع الحفاظ على تناسب تغيير الحجم <br/>            وحفظ لون الخلفية. تتيح هذه الطريقة <br/>            تعديلًا دقيقًا للصورة، مع ضمان أن يدور الصورة بشكل متوازن بصريًا <br/>            ويتماشى مع لون الخلفية المحدد. إنها مثالية للمهام التي تتطلب <br/>            دورانًا دقيقًا حول المركز، مثل تصحيح الاتجاه <br/>            أو التعديلات الفنية. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_99) | تتيح طريقة "RotateFlip" إجراء عمليات الدوران والقلب على الصورة. فهي <br/>            توفر وظائف متعددة لتعديل اتجاه الصورة، مما يسمح للمستخدمين <br/>            بأداء الدورانات والقلب وفقًا لمتطلباتهم، مما يسهل <br/>            مهام معالجة الصور بكفاءة داخل تطبيقات البرمجيات. |
| save() | يقوم بحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_100) | يقوم بحفظ الصورة إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_101) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_102) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_103) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_104) | بيانات الحفظ. |
| [save(stream, options_base)](#save_stream_options_base_105) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_106) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_107) | يقوم بحفظ بكسلات ARGB 32‑بت. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_108) | يقوم بحفظ البكسلات. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_109) | يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_110) | يقوم بحفظ البكسلات (طريقة خاصة بالتنسيق). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_111) | يحفظ البيانات الخام. |
| [save_to_stream(stream)](#save_to_stream_stream_112) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_113) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_115) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_116) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_117) | يضبط بكسل صورة 32-بت ARGB للموقع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_118) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_119) | يضبط بكسل صورة للموقع المحدد. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_120) | يضبط الدقة لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_121) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_123) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |


### Constructor: TgaImage(path) {#TgaImage_path_1}


```
 TgaImage(path) 
```

يقوم بتهيئة كائن جديد من [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) باستخدام مسار الملف المقدم لـ <br/>            تحميل محتوى الصورة. يقوم هذا المُنشئ بتهيئة نسخة الصورة بكفاءة <br/>            مما يسمح بالوصول السلس إلى ملفات صور TGA، مبسطًا عملية التكامل <br/>            في سير عمل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار لتحميل صورة. |

### Constructor: TgaImage(raster_image) {#TgaImage_raster_image_2}


```
 TgaImage(raster_image) 
```

إنشاء نسخة جديدة من فئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) عن طريق توفير كائن صورة نقطية <br/>            . يسهّل هذا المُنشئ التكامل المباشر للصور النقطية الموجودة في تنسيق صورة TGA، مما يبسط عملية التحويل لتحقيق <br/>            توافقية محسّنة داخل أنظمة البرمجيات الخاصة بك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |


**See also:**

**[Example # 1](#example_216)**: Loading of the PNG image, conversion of it to the TgaImage and saving as a TG...


### Constructor: TgaImage(stream) {#TgaImage_stream_3}


```
 TgaImage(stream) 
```

تهيئة نسخة جديدة من فئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) باستخدام تدفق <br/>            لتحميل الصورة. يتيح هذا المُنشئ التكامل السلس لبيانات الصورة <br/>            من التدفقات، مما يُسهل المعالجة الفعّالة للصور بصيغة TGA داخل <br/>            تطبيقات البرمجيات الخاصة بك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | تيار البيانات لتحميل صورة. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

ضبط سطوع الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| السطوع | int | قيمة السطوع. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

تباين الصورة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

تصحيح جاما لصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| جاما | float | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

تصحيح جاما لصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| gamma_red | float | معامل جاما للقناة الحمراء |
| gamma_green | float | معامل جاما للقناة الخضراء |
| gamma_blue | float | معامل جاما للقناة الزرقاء |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


```
 analyze_percentage_digital_signature(password) 
```

يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور المستخدمة لاستخراج البيانات المدمجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة نسبة التشابه. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brightness_difference | float | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات التي تتمركز حول هذا البكسل. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brightness_difference | float | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات التي تتمركز حول هذا البكسل. |
| window_size | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحدّ | System.Byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


```
 blend(origin, overlay, overlay_alpha) 
```

يمزج هذه النسخة من الصورة مع الصورة _overlay_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | مصدر دمج صورة الخلفية. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة التراكب. |
| overlay_alpha | System.Byte | قيمة ألفا للتراكب. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

يمزج هذه النسخة من الصورة مع الصورة _overlay_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | مصدر دمج صورة الخلفية. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة التراكب. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | منطقة التراكب. |
| overlay_alpha | System.Byte | قيمة ألفا للتراكب. |

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


```
 can_load(file_path) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


```
 can_load(file_path, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_13}


```
 can_load(stream) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق للتحميل منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


```
 can_load(stream, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق للتحميل منه. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


```
 can_load_stream(stream) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق للتحميل منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


```
 can_load_stream_with_options(stream, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق للتحميل منه. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


```
 can_load_with_options(file_path, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_save(options) {#can_save_options_18}


```
 can_save(options) 
```

يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة؛ وإلا، <c>false</c>. |


### Method: clone() {#clone__19}


```
 clone() 
```

ينتج نسخة مكررة من الكائن الحالي، مُنشئًا كائنًا جديدًا ينسخ <br/>            جميع السمات والخصائص للنسخة الأصلية. تُسهل هذه الطريقة <br/>            إنشاء نسخ مطابقة، مما يضمن سلامة البيانات ويحافظ على حالة <br/>            الكائن الحالي دون التأثير على الكائن الأصلي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | يرجع كائنًا جديدًا يكون نسخة من الكائن الحالي. |


### Method: clone(tga_image) {#clone_tga_image_20}


```
 clone(tga_image) 
```

تكرار خصائص كائن [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) آخر، وإنشاء <br/>            نسخة جديدة ذات سمات مطابقة. يضمن هذا الإجراء الحفاظ على <br/>            سلامة البيانات ويسهل تكرار خصائص الصورة دون <br/>            تعديل الكائن المصدر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tga_image | [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | أخرى [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |

### Method: create(files)  [static] {#create_files_21}


```
 create(files) 
```

ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| ملفات | string[] | الملفات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة متعددة الصفحات |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


```
 create(files, throw_exception_on_load_error) 
```

ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| ملفات | string[] | الملفات. |
| throw_exception_on_load_error | bool | إذا تم الضبط على <c>true</c> [إلقاء استثناء عند خطأ التحميل]. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة متعددة الصفحات |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


```
 create(image_options, width, height) 
```

ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الصورة. |
| width | int | العرض. |
| height | int | الارتفاع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي تم إنشاؤها حديثًا. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


```
 create(image_options, width, height, pixels) 
```

ينشئ مثيلًا من [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) من مصفوفة البكسل المقدمة.<br/>            <br/>            يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل.<br/>            لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستخدمة لإنشاء الـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | عرض الـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | ارتفاع الـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| البكسلات | int[] | المصفوفة من قيم البكسل المستخدمة لملء الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | صورة [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) مملوءة ببيانات البكسل المقدمة. |


### Method: create(images)  [static] {#create_images_25}


```
 create(images) 
```

ينشئ صورة جديدة باستخدام الصور المحددة كصفحات

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | الصور. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة كـ IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


```
 create(images, dispose_images) 
```

ينشئ صورة جديدة باستخدام الصور المحددة كصفحات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | الصور. |
| dispose_images | bool | إذا تم الضبط على <c>true</c> [إزالة الصور]. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة كـ IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


```
 create(multipage_create_options) 
```

ينشئ خيارات الإنشاء المتعددة الصفحات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | خيارات إنشاء متعدد الصفحات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة متعددة الصفحات |


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


```
 create_from_files(files) 
```

ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| ملفات | string[] | الملفات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة متعددة الصفحات |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


```
 create_from_files(files, throw_exception_on_load_error) 
```

ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| ملفات | string[] | الملفات. |
| throw_exception_on_load_error | bool | إذا تم الضبط على <c>true</c> إلقاء استثناء عند خطأ التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة متعددة الصفحات |


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_30}


```
 create_from_image(raster_image) 
```

يُهيئ نسخة جديدة من الفئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


```
 create_from_images(images) 
```

ينشئ صورة جديدة باستخدام الصور المحددة كصفحات

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | الصور. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة كـ IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


```
 create_from_images(images, dispose_images) 
```

ينشئ صورة جديدة باستخدام الصور المحددة كصفحات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | الصور. |
| dispose_images | bool | إذا تم الضبط على <c>true</c> [إزالة الصور]. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة كـ IMultipageImage |


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

يُهيئ نسخة جديدة من الفئة [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | تيار البيانات لتحميل صورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_34}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

قم بقص الصورة بتحديد إزاحات للحدود اليسرى، اليمنى، العليا والسفلى <br/>            . تتيح لك هذه الطريقة تقليم الصورة عن طريق تحريك حدودها <br/>            بشكل مستقل على المحاور الأفقية والرأسية. من خلال ضبط هذه الإزاحات، <br/>            يمكنك التحكم بدقة في الأجزاء التي تريد الاحتفاظ بها، وبالتالي <br/>            قصها إلى الأبعاد المطلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| left_shift | int | الإزاحة اليسرى. |
| right_shift | int | الإزاحة اليمنى. |
| top_shift | int | الإزاحة العلوية. |
| bottom_shift | int | الإزاحة السفلية. |

### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

قم بقص الصورة إلى منطقة محددة. تتيح لك هذه الطريقة تحديد <br/>            مساحة مستطيلة داخل الصورة للاحتفاظ بها، مع حذف البقية. هذه العملية <br/>            مفيدة للتركيز على محتوى معين داخل الصورة أو إزالة الأجزاء غير المرغوب فيها.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

يُجري تمويهًا على الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

يُجري تمويهًا على الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان المخصصة للتدرج. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_38}


```
 embed_digital_signature(password) 
```

إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التستغنوجرافيا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور المستخدمة لإنشاء بيانات التوقيع الرقمي |

### Method: filter(rectangle, options) {#filter_rectangle_options_39}


```
 filter(rectangle, options) 
```

يفلتر المستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | الخيارات. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_40}


```
 get_argb_32_pixel(x, y) 
```

يحصل على بكسل صورة 32-بت ARGB.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | موقع البكسل x. |
| y | int | موقع البكسل y. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | بكسل ARGB 32-بت للموقع المحدد. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_41}


```
 get_default_argb_32_pixels(rectangle) 
```

يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة البكسلات الافتراضية. |


### Method: get_default_options(args) {#get_default_options_args_42}


```
 get_default_options(args) 
```

يحصل على الخيارات الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| args | System.Object | المعلمات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات الافتراضية |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_43}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | محمل البيانات الخام الجزئي. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | إعدادات البيانات الخام. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_45}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

يحصل على مصفوفة البيانات الخام الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البيانات الخام. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | إعدادات البيانات الخام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | مصفوفة البيانات الخام الافتراضية. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_46}


```
 get_file_format(file_path) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | تنسيق الملف المحدد. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_47}


```
 get_file_format(stream) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | تنسيق الملف المحدد. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_48}


```
 get_file_format_of_stream(stream) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | تنسيق الملف المحدد. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_49}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

يحصل على المستطيل الذي يناسب الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على المستطيل المناسب. |
| البكسلات | int[] | بكسلات ARGB 32-بت. |
| width | int | عرض الكائن. |
| height | int | ارتفاع الكائن. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المناسب أو استثناء إذا لم يتم العثور على مستطيل مناسب. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_50}


```
 get_fitting_rectangle(rectangle, width, height) 
```

يحصل على المستطيل الذي يناسب الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على المستطيل المناسب. |
| width | int | عرض الكائن. |
| height | int | ارتفاع الكائن. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المناسب أو استثناء إذا لم يتم العثور على مستطيل مناسب. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_51}


```
 get_modify_date(use_default) 
```

يحصل على تاريخ ووقت آخر تعديل لصورة المورد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| use_default | bool | إذا تم تعيينه إلى <c>true</c> يستخدم المعلومات من FileInfo كقيمة افتراضية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.DateTime | التاريخ والوقت الذي تم تعديل صورة المورد فيه آخر مرة. |


### Method: get_original_options() {#get_original_options__52}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستندة إلى إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_53}


```
 get_pixel(x, y) 
```

يحصل على بكسل صورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | موقع البكسل x. |
| y | int | موقع البكسل y. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | لون البكسل للموقع المحدد. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_54}


```
 get_proportional_height(width, height, new_width) 
```

يحصل على ارتفاع نسبي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | العرض. |
| height | int | الارتفاع. |
| new_width | int | العرض الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | الارتفاع النسبي. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_55}


```
 get_proportional_width(width, height, new_height) 
```

يحصل على عرض نسبي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | العرض. |
| height | int | الارتفاع. |
| new_height | int | الارتفاع الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | العرض النسبي. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_56}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

يحوّل إلى aps.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الصورة. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل القص. |
| page_number | int[] | رقم الصفحة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | التدفق المتسلسل |


### Method: get_skew_angle() {#get_skew_angle__57}


```
 get_skew_angle() 
```

يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح.

**Returns**

| نوع | الوصف |
| :- | :- |
| float | زاوية الانحراف، بالدرجات. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_58}


```
 is_digital_signed(password, percentage_threshold) 
```

يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور للتحقق من التوقيع. |
| percentage_threshold | int | الحد (بالنسبة المئوية)[0-100] الذي يحدد ما إذا كانت الصورة تعتبر موقعة.<br/>            إذا لم يتم تحديده، سيتم تطبيق حد افتراضي (<c>75</c>). |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح إذا كانت الصورة موقعة، وإلا خاطئ. |


### Method: load(file_path)  [static] {#load_file_path_59}


```
 load(file_path) 
```

يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف أو URL لتحميل الصورة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_60}


```
 load(file_path, load_options) 
```

يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف أو URL لتحميل الصورة منه. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: load(stream)  [static] {#load_stream_61}


```
 load(stream) 
```

يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_62}


```
 load(stream, load_options) 
```

يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_63}


```
 load_argb_32_pixels(rectangle) 
```

يحمّل بكسلات ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة البكسلات ARGB 32-بت المحملة. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_64}


```
 load_argb_64_pixels(rectangle) 
```

يحمّل بكسلات ARGB 64‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة بكسلات ARGB 64-بت المحملة. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_65}


```
 load_cmyk_32_pixels(rectangle) 
```

يحمّل بكسلات بتنسيق CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة بكسلات CMYK المحملة كقيم صحيحة 32-بت. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_66}


```
 load_cmyk_pixels(rectangle) 
```

يحمّل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | مصفوفة بكسلات CMYK المحملة. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | محمل بكسلات ARGB 64-بت. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_69}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يحمّل بكسلات جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_70}


```
 load_pixels(rectangle) 
```

يحمّل بكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | مصفوفة البكسلات المحملة. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

يحمّل بيانات خام.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البيانات الخام منه. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود الصورة الوجهة. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | إعدادات البيانات الخام لاستخدامها مع البيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل البيانات. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | محمل البيانات الخام. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

يحمّل بيانات خام.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البيانات الخام منه. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | إعدادات البيانات الخام لاستخدامها مع البيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل البيانات. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | محمل البيانات الخام. |

### Method: load_stream(stream)  [static] {#load_stream_stream_73}


```
 load_stream(stream) 
```

يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_74}


```
 load_stream_with_options(stream, load_options) 
```

يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_75}


```
 load_with_options(file_path, load_options) 
```

يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف أو URL لتحميل الصورة منه. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المحملة. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_76}


```
 normalize_angle(resize_proportionally, background_color) 
```

يضبط الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من الانحراف في المسح.<br/>            تستخدم هذه الطريقة أساليب [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_77}


```
 read_argb_32_scan_line(scan_line_index) 
```

يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة قيم ألوان ARGB 32-بت لصف المسح. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_78}


```
 read_scan_line(scan_line_index) 
```

يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | مصفوفة قيم ألوان بكسلات صف المسح. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| old_color_argb | int | قيمة ARGB للون القديم التي سيتم استبدالها. |
| old_color_diff | System.Byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم بها. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


```
 replace_color(old_color, old_color_diff, new_color) 
```

يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون القديم الذي سيتم استبداله. |
| old_color_diff | System.Byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون الجديد لاستبدال اللون القديم به. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| old_color_argb | int | قيمة ARGB للون القديم التي سيتم استبدالها. |
| old_color_diff | System.Byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم بها. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون الجديد لاستبدال الألوان غير الشفافة به. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

يضبط حجم الصورة باستخدام نوع تغيير حجم محدد، والذي يحدد كيفية <br/>            تنفيذ عملية تغيير الحجم. توفر هذه الطريقة مرونة في تعديل حجم <br/>            الصور وفقًا لخوارزميات أو تقنيات مختلفة. باختيار نوع تغيير الحجم <br/>            المناسب، يمكنك تحقيق التوازن المطلوب بين جودة الصورة <br/>            وكفاءة الحوسبة بناءً على المتطلبات أو التفضيلات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

غيّر حجم الصورة مع تطبيق إعدادات محددة للحفاظ على الأبعاد المطلوبة <br/>            ونسبة العرض إلى الارتفاع. من خلال تخصيص إعدادات الصورة، يمكنك بفعالية <br/>            تعديل حجم الصورة مع ضمان جودة بصرية مثالية وتوافق مع <br/>            أجهزة العرض أو التطبيقات المختلفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات التحجيم. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


```
 resize_by_settings(new_width, new_height, settings) 
```

يقوم بتغيير حجم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات التحجيم. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


```
 resize_by_type(new_width, new_height, resize_type) 
```

يقوم بتغيير حجم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_93}


```
 resize_width_proportionally(new_width) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_94}


```
 resize_width_proportionally(new_width, resize_type) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_95}


```
 resize_width_proportionally(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_96}


```
 resize_width_proportionally_settings(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_97}


```
 rotate(angle) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_98}


```
 rotate(angle, resize_proportionally, background_color) 
```

يدور الصورة حول مركزها بزاوية محددة مع الحفاظ على تناسب تغيير الحجم <br/>            وحفظ لون الخلفية. تتيح هذه الطريقة <br/>            تعديلًا دقيقًا للصورة، مع ضمان أن يدور الصورة بشكل متوازن بصريًا <br/>            ويتماشى مع لون الخلفية المحدد. إنها مثالية للمهام التي تتطلب <br/>            دورانًا دقيقًا حول المركز، مثل تصحيح الاتجاه <br/>            أو التعديلات الفنية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة<br/>            وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) في الحالة الأخرى يترك الأبعاد دون تغيير وتُدوَّر محتويات الصورة __internal__ فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_99}


```
 rotate_flip(rotate_flip_type) 
```

تتيح طريقة "RotateFlip" إجراء عمليات الدوران والقلب على الصورة. فهي <br/>            توفر وظائف متعددة لتعديل اتجاه الصورة، مما يسمح للمستخدمين <br/>            بأداء الدورانات والقلب وفقًا لمتطلباتهم، مما يسهل <br/>            مهام معالجة الصور بكفاءة داخل تطبيقات البرمجيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | نوع دوران الانعكاس. |

### Method: save(file_path) {#save_file_path_100}


```
 save(file_path) 
```

يقوم بحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ الصورة فيه. |

### Method: save(file_path, options) {#save_file_path_options_101}


```
 save(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_102}


```
 save(file_path, options, bounds_rectangle) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: save(file_path, over_write) {#save_file_path_over_write_103}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_104}


```
 save(stream) 
```

بيانات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

### Method: save(stream, options_base) {#save_stream_options_base_105}


```
 save(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_106}


```
 save(stream, options_base, bounds_rectangle) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_107}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يقوم بحفظ بكسلات ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_108}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | بكسلات CMYK معروضة كقيم صحيحة 32‑بت. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_109}


```
 save_cmyk_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | مصفوفة بكسلات CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_110}


```
 save_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات (طريقة خاصة بالتنسيق).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_111}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

يحفظ البيانات الخام.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البيانات | System.Byte | البيانات الخام. |
| data_offset | int | إزاحة البيانات الخام الابتدائية. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل البيانات الخام. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | إعدادات البيانات الخام التي توجد فيها البيانات. |

### Method: save_to_stream(stream) {#save_to_stream_stream_112}


```
 save_to_stream(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_113}


```
 save_to_stream_with_options(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_115}


```
 save_with_options(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_116}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_117}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

يضبط بكسل صورة 32-بت ARGB للموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | موقع البكسل x. |
| y | int | موقع البكسل y. |
| argb_32_color | int | بكسل ARGB 32‑بت للموقع المحدد. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_118}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة التي يجب ضبطها. |
| update_colors | bool | إذا تم ضبطه على <c>true</c> سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. لاحظ أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات مطابقة في اللوحة. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_119}


```
 set_pixel(x, y, color) 
```

يضبط بكسل صورة للموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | موقع البكسل x. |
| y | int | موقع البكسل y. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | لون البكسل للموقع المحدد. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_120}


```
 set_resolution(dpi_x, dpi_y) 
```

يضبط الدقة لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dpi_x | float | الدقة الأفقية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | الدقة العمودية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_121}


```
 try_set_metadata(metadata) 
```

يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | البيانات الوصفية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح إذا كان _metadata_ غير فارغ وكانت نسخة [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            تدعم و/أو تنفذ نسخة [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); وإلا، خطأ. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |
| argb_32_pixels | int[] | مصفوفة ألوان ARGB 32‑بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_123}


```
 write_scan_line(scan_line_index, pixels) 
```

يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | مصفوفة ألوان البكسل للكتابة. |

## **Examples**
### Saving of the JPG image as a TGA image. {#example_215}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import TgaOptions

with Image.load("test.jpg") as image:
	image.save("test.tga"", TgaOptions())
	

```

### Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image. {#example_216}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.fileformats.tga import TgaImage

with as_of(Image.load("test.png"), RasterImage) as image:
	with TgaImage(image) as tgaImage:
		tgaImage.save("test.tga")


```

