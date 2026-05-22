---
title: "فئة TiffImage"
type: docs
weight: 200
url: /ar/python-net/aspose.imaging.fileformats.tiff/tiffimage/
---

**Summary:** Process Tagged Image File Format (TIFF) raster images with our API, offering<br/>            comprehensive support for various resolutions and advanced editing capabilities<br/>            like EXIF data manipulation and alpha channels. Normalize angles for scanned images,<br/>            resize, transform to grayscale, and apply filters, gamma corrections and image<br/>            parameters adjustments with ease. Seamlessly handle multi-frame TIFF files,<br/>            create graphics paths, add shapes, and effortlessly save images to different formats.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffImage(frame)](#TiffImage_frame_1) | قم بتهيئة كائن جديد من الفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/)، مع تحديد معلمة <br/>            الإطار. يُسهل هذا المُنشئ إنشاء مثيل TiffImage <br/>            ، مما يسمح للمطورين بتحديد الإطار الذي سيتم تحميله أو معالجته، <br/>            مما يبسط مهام معالجة صور Tiff داخل تطبيقاتهم. |
| [TiffImage(frames)](#TiffImage_frames_2) | أنشئ مثيلاً جديدًا للفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/)، مع توفير قائمة بـ <br/>            الإطارات كمعامل. يتيح هذا المُنشئ تهيئة كائن TiffImage <br/>            بعدة إطارات، مما يُسهل التعامل الفعال ومعالجة <br/>            تسلسلات صور TIFF داخل تطبيقات البرمجيات. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| active_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r/w | قم بإدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي و<br/>            التلاعب داخل السياق المحدد. مكن تطبيقك من التفاعل<br/>            بكفاءة مع محتوى الوسائط المتعددة، مما يعزز تفاعل المستخدم والإنتاجية. |
| auto_adjust_palette | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تعديل لوحة الألوان تلقائيًا. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| bits_per_pixel | int | r | يحصل على عدد البتات في الصورة لكل بكسل. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود الكائن. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | بدّل ترتيب البايت لملفات TIFF بسلاسة، مما يضمن تحكمًا دقيقًا في<br/>            تفسير البيانات. مكن تطبيقاتك من المرونة للتكيف مع<br/>            مواصفات الملفات المتنوعة، مما يعزز التوافق والكفاءة في معالجة البيانات. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | يحصل على حاوية [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | يحصل على تدفق بيانات الكائن. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن كائن Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | استرجع قيمة تنسيق الملف المرتبط بالصورة. تُعد هذه الخاصية <br/>            جانبًا حاسمًا في استرجاع بيانات تعريف الصورة، مما يسمح لتطبيقات البرمجيات <br/>            بتحديد وتفسير تنسيق بيانات الصورة بكفاءة. |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r | استرجع مصفوفة من مثيلات [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/)، مما يتيح وصولًا شاملاً و<br/>            تلاعبًا بالإطارات الفردية داخل صورة TIFF. استغل قوة هذه المصفوفة لتبسيط سير عمل معالجة الصور، مما يضمن تحكمًا دقيقًا<br/>            وتحسين المحتوى البصري. |
| [has_alpha](#has_alpha1) | bool | r | حدد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حاسمة<br/>            للتصوير وعمليات التركيب. دمج هذه الميزة لتحسين سير عمل المعالجة البصرية، مما يضمن تمثيلًا دقيقًا وتلاعبًا بالعناصر الشفافة. |
| has_background_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparent_color | bool | r/w | يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون شفاف. |
| height | int | r | يحصل على ارتفاع الصورة. |
| horizontal_resolution | float | r/w | استرجع الدقة الأفقية للصورة المحددة [Image](/imaging/python-net/aspose.imaging/image/) بوحدات البكسل<br/>            لكل بوصة، مما يسهل الضبط الدقيق وقدرات العرض. احصل على<br/>            بيانات التعريف الأساسية للصورة بسهولة، مما يمكّن سير عمل معالجة الصور المبسط<br/>            لتجارب مستخدم محسّنة. |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | يحصل أو يعيّن مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتاً حالياً. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | يحصل أو يعيّن بيانات XMP من الإطار. |
| page_count | int | r | استرجاع العدد الكلي للصفحات داخل المستند المحدد، مما يسهل <br/> التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه <br/> الوظيفة لتعزيز تجربة المستخدم، وتمكين الوصول السلس إلى <br/> هياكل المستند الشاملة. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | الوصول إلى صفحات المستند بسلاسة، مما يتيح تنقلًا ديناميكيًا و<br/>            تلاعبًا داخل هيكل المحتوى. مكن تطبيقك من وصول فعال إلى الصفحات الفردية، مما يسهل معالجة المستندات المبسطة<br/>            وتعزيز تفاعل المستخدم. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| premultiply_components | bool | r/w | أشر إذا كانت المكونات تحتاج إلى الضرب المسبق، مما يضمن معالجة فعّالة<br/>            للعناصر البصرية. حسّن عمليات العرض بتبديل هذه الخاصية،<br/>            مما يبسط سير عمل الرسومات لأداء محسن. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | يحصل أو يضبط محول الألوان المخصص |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على تنسيق البيانات الخام. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | يحصل أو يضبط محول الألوان المفهرسة |
| raw_line_size | int | r | يحصل على حجم السطر الخام بالبايت. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | يحصل على حجم الكائن. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل على لون شفافية الصورة. |
| update_xmp_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| use_raw_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| vertical_resolution | float | r/w | الوصول إلى الدقة العمودية للصورة المحددة [Image](/imaging/python-net/aspose.imaging/image/) بوحدات البكسل لكل<br/>            بوصة، مما يتيح ضبطًا دقيقًا وتحسينات في العرض. استخدم بيانات الصورة الأساسية بسهولة لتبسيط سير عمل معالجة الصور، مما يضمن جودة وأداءً فائقين في تطبيقاتك. |
| width | int | r | يحصل على عرض الصورة. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(image)](#add_image_1) | أضف الإطارات من الصورة المحددة بسلاسة إلى الإطار الحالي،<br/>            موحدًا محتواها ومعززًا مرونة التركيب. دمج هذه الطريقة لتبسيط إدارة الإطارات وتلاعبها داخل تطبيقك، مما يسهل معالجة فعّالة للصور متعددة الإطارات. |
| [add_frame(frame)](#add_frame_frame_2) | دمج الإطار المحدد بسلاسة في الصورة، موسعًا محتواها<br/>            وتنوعها. استخدم هذه الطريقة لتعزيز تركيب الصورة وإدارتها،<br/>            مما يمكّن من معالجة فعّالة للصور متعددة الإطارات داخل تطبيقك. |
| [add_frames(frames)](#add_frames_frames_3) | دمج مصفوفة الإطارات بسلاسة في الصورة، مُغنيًا محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تركيب الصورة وإدارتها،<br/>            مما يتيح معالجة فعّالة للصور متعددة الإطارات داخل تطبيقك. |
| [add_page(page)](#add_page_page_4) | أدمج صفحة جديدة في الصورة الحالية بسلاسة، موسعًا محتواها <br/>            وتنوعها. استخدم هذه الطريقة لتعزيز تكوين المستندات و <br/>            إدارتها، مما يتيح التعامل الفعال مع الصور متعددة الصفحات داخل تطبيقك. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | نفّذ تعديل _السطوع_ للصورة، مما يسمح<br/>            بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور الخاصة بك لتعزيز الرؤية وتحسين جودة الصورة البصرية<br/>            للصور داخل تطبيقك. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | عزز التباين في مثيل [Image](/imaging/python-net/aspose.imaging/image/) ،<br/>            مضخمًا الفروق بين المناطق الفاتحة والداكنة. دمج هذه<br/>            الوظيفة لتحسين وضوح الصورة البصري والجودة العامة للصورة<br/>            داخل تطبيقك. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | طبق تصحيح غاما على الصورة، مع تعديل شدة البكسلات لتحقيق توازن اللون المطلوب.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز جودة الصورة وتحسين دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | قم بتطبيق تصحيح غاما على الصورة باستخدام معاملات فردية للقنوات الحمراء، الخضراء، والزرقاء، مما يسمح بتعديلات دقيقة لتوازن اللون والتباين.<br/>            دمج هذه الطريقة في خط أنابيب معالجة الصور الخاص بك لتحقيق تحكم دقيق في عرض الألوان وتعزيز دقة الصورة داخل تطبيقك. |
| align_resolutions() | نفّذ طريقة المساعدة AlignResolutions لمزامنة الدقة الأفقية والعمودية، مما يضمن توحيد أبعاد الصورة.<br/>            تُسهل هذه الوظيفة سير عمل معالجة الصور بسلاسة عن طريق توحيد معلمات الدقة، وتحسين جودة الصورة واتساقها عبر مختلف المنصات والأجهزة. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| auto_brightness_contrast() | ينفّذ تطبيعًا تلقائيًا متكيفًا للسطوع والتباين لكامل الصورة. |
| auto_rotate() | يدور الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من Exif <br/>            metadata. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح،<br/>            مما يعزز تجربة المستخدم ويزيل الحاجة إلى التعديلات اليدوية. من خلال <br/>            تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، موفرًا تجربة مشاهدة سلسة <br/>            عبر منصات وأجهزة مختلفة. تُبسّط عملية الدوران الآلية التعامل مع الصور وتُحسّن القابلية العامة للاستخدام، خاصةً عند <br/>            التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | نفّذ تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة.<br/>            هذه الطريقة تحسب عتبات محلية ديناميكياً بناءً على جوار الصورة، مما يعزز التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام اللاحقة داخل تطبيقك. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | طبق التثن binary على الصورة باستخدام عتبة محددة مسبقاً، محولاً إياها إلى صورة ثنائية ذات مناطق أمامية وخلفية متميزة.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التجزئة واستخراج الميزات، مما يعزز دقة وكفاءة تحليل الصورة داخل تطبيقك. |
| binarize_otsu() | استخدم عتبة أوتسو لإجراء التثن binary على الصورة، مع تحديد القيمة المثلى للعتبة تلقائياً بناءً على هيستوغرام الصورة.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة فعّالة واستخراج ميزات، مما يعزز دقة وموثوقية تحليل الصورة داخل تطبيقك. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_13) | يمزج هذه النسخة من الصورة مع الصورة _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_14) | يمزج هذه النسخة من الصورة مع الصورة _overlay_. |
| cache_data() | يقوم بتخزين البيانات بشكل خاص. |
| [can_load(file_path)](#can_load_file_path_15) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_16) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_load(stream)](#can_load_stream_17) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_18) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_stream(stream)](#can_load_stream_stream_19) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_20) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_21) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_save(options)](#can_save_options_22) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [create(files)](#create_files_23) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_24) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(image_options, width, height)](#create_image_options_width_height_25) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_26) | ينشئ مثيلًا من [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) من مصفوفة البكسل المقدمة.<br/>            <br/>            يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل.<br/>            لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص. |
| [create(images)](#create_images_27) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(images, dispose_images)](#create_images_dispose_images_28) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create(multipage_create_options)](#create_multipage_create_options_29) | ينشئ خيارات الإنشاء المتعددة الصفحات المحددة. |
| [create_from_files(files)](#create_from_files_files_30) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_31) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_images(images)](#create_from_images_images_32) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_33) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create_with_frame(frame)](#create_with_frame_frame_34) | يُنشئ مثيلاً جديدًا للفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/). |
| [create_with_frames(frames)](#create_with_frames_frames_35) | يُنشئ مثيلاً جديدًا للفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_36) | قم بقص الصورة عن طريق تحديد إزاحات في الاتجاهات اليسرى، اليمنى، العليا، والسفلى.<br/>            تتيح هذه الطريقة اختيار الجزء المطلوب من الصورة بدقة، مما يسهل إزالة المناطق غير المرغوبة والتركيز على المحتوى الأساسي.<br/>            دمج هذه الوظيفة في خط أنابيب معالجة الصور لتعزيز الوضوح والتركيب حسب الحاجة داخل تطبيقك. |
| [crop(rectangle)](#crop_rectangle_37) | قص الصورة باستخدام منطقة مستطيلة محددة، مما يتيح اختيار المحتوى المطلوب بدقة.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لإزالة المناطق غير المرغوبة والتركيز على التفاصيل الأساسية، مما يعزز الوضوح والتركيب العام للصورة. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_38) | يُجري تمويهًا على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_39) | نفّذ التدرج (dithering) على الصورة الحالية لتعزيز جودتها البصرية وتقليل آثار تدرج اللون.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لضمان انتقالات ألوان أكثر سلاسة، مما ينتج مظهرًا بصريًا محسّنًا ووضوحًا أفضل للصورة. |
| [embed_digital_signature(password)](#embed_digital_signature_password_40) | أدمج توقيعًا رقميًا يعتمد على كلمة المرور المقدمة في كل صفحة من الصورة. |
| [filter(rectangle, options)](#filter_rectangle_options_41) | قم بتصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صور مخصص لتحسين أو تعديل المنطقة المختارة. دمج هذه الطريقة <br/>            في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات مستهدفة أو <br/>            تحويلات داخل تطبيقك. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_42) | يحصل على بكسل صورة 32-بت ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_43) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_44) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_45) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_47) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_48) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_49) | يحصل على تنسيق الملف. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_50) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_51) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_52) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_53) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [get_original_options()](#get_original_options__54) | استرجع الخيارات المستمدة من إعدادات الملف الأصلي، مما يسهل الحفاظ السلس على المعلمات الرئيسية مثل عمق البت وغيرها من السمات الأساسية للصورة الأصلية.<br/>            استخدم هذه الطريقة للحفاظ على الدقة والاتساق في مهام معالجة الصور، وضمان نتائج مثالية دون تعديلات غير ضرورية.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_55) | يحصل على بكسل صورة. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_56) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_57) | يحصل على عرض نسبي. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_58) | يحوّل إلى aps. |
| [get_skew_angle()](#get_skew_angle__59) | يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح. |
| grayscale() | حوّل الصورة إلى تمثيلها الرمادي، محولاً إياها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل شدة الإضاءة.<br/>            دمج هذه الطريقة في خط أنابيب معالجة الصور لتبسيط التحليل وتعزيز التوافق مع الخوارزميات القائمة على التدرج الرمادي، مما يسهل مهام الرؤية الحاسوبية وتحليل الصور داخل تطبيقك. |
| [insert_frame(index, frame)](#insert_frame_index_frame_60) | أدرج الإطار الجديد في الفهرس المحدد داخل تسلسل الإطارات، مما يضمن تحكمًا دقيقًا في ترتيب الإطارات.<br/>            استخدم هذه الطريقة لإدارة تسلسلات الإطارات بفعالية، مما يسهل التلاعب الديناميكي وتنظيم محتوى الصورة داخل تطبيقك. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |
| [load(file_path)](#load_file_path_62) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(stream)](#load_stream_64) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_65) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | يحمّل بكسلات ARGB 32‑بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | يحمّل بكسلات ARGB 64‑بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | يحمّل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | يحمّل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | يحمّل بكسلات جزئيًا حسب الحزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | يحمّل بكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | يحمّل بيانات خام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | يحمّل بيانات خام. |
| [load_stream(stream)](#load_stream_stream_76) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| normalize_angle() | يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) . |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | استخدم طريقة **NormalizeAngle** المصممة خصيصًا لمستندات النص الممسوحة ضوئياً لتصحيح الانحرافات، مما يضمن محاذاة دقيقة.<br/>            دمج هذه الوظيفة بسلاسة في سير عمل معالجة النص لتحسين قابلية القراءة وجودة المستند، مما يعزز الكفاءة العامة في مهام التعرف على النص وتحليلها.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و[TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/). |
| normalize_histogram() | يُعَدِّل مدرج الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [remove_frame(frame)](#remove_frame_frame_82) | أزل الإطار المحدد بفعالية من تسلسل الصور، مما يسهل إدارة الإطارات بسلاسة داخل تطبيقك.<br/>            دمج هذه الوظيفة لتعزيز الدقة والمرونة في التلاعب بالإطارات، وضمان تنظيم وعرض محتوى الصورة بسلاسة. |
| [remove_frame(index)](#remove_frame_index_83) | يزيل الإطار وفقًا لموقعه. |
| [remove_frame_by_index(index)](#remove_frame_by_index_index_84) | يزيل الإطار وفقًا لموقعه. |
| remove_metadata() | يزيل بيانات التعريف لهذا المثيل الصورة عن طريق تعيين قيم [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) و [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) إلى **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_85) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_86) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_87) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_frame(index, new_frame)](#replace_frame_index_new_frame_88) | استبدل الإطار في الموضع المحدد بإطار آخر بسلاسة، مما يسهل إدارة الإطارات الديناميكية داخل تسلسل الصور.<br/>            دمج هذه الطريقة لتعزيز المرونة والدقة في التلاعب بالإطارات، وضمان تنظيم وعرض محتوى الصورة بشكل أمثل داخل تطبيقك. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_89) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_90) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_91) | يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_92) | قم بإجراء عملية تغيير حجم متناسبة على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها.<br/>            استخدم هذه الطريقة لتوسيع الصور ديناميكيًا داخل تطبيقك، مما يضمن تمثيلًا بصريًا متسقًا للمحتوى وسلامة التكامل.<br/>            سيقوم تغيير الحجم المتناسب بتغيير حجم كل إطار وفقًا لنسبة _newWidth_/العرض و _newHeight_/الارتفاع. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_93) | اضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تغيير حجم مخصصة تتناسب مع المتطلبات الخاصة لتطبيقك. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_94) | يقوم بتغيير حجم الصورة. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_95) | يقوم بتغيير حجم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_96) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_97) | قم بتعديل ارتفاع الصورة بشكل متناسب، مع الحفاظ على نسبة العرض إلى الارتفاع لضمان تكامل بصري ثابت.<br/>            استخدم هذه الطريقة لتغيير حجم الصور ديناميكيًا داخل تطبيقك، مما يضمن عرضًا مثاليًا عبر منصات وأجهزة متعددة دون الإضرار بجودة المحتوى. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_98) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_99) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_100) | قم بإجراء عملية تغيير حجم متناسبة على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها.<br/>            استخدم هذه الطريقة لتوسيع الصور ديناميكيًا داخل تطبيقك، مما يضمن تمثيلًا بصريًا متسقًا للمحتوى وسلامة التكامل.<br/>            سيقوم تغيير الحجم المتناسب بتغيير حجم كل إطار وفقًا لنسبة _newWidth_/العرض و _newHeight_/الارتفاع. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_101) | يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_102) | اضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع، مما يضمن تغيير حجم متناسب لتقديم عرض بصري أمثل.<br/>            استخدم هذه الطريقة لتوسيع الصور ديناميكيًا داخل تطبيقك، مما يسهل تقديم عرض متسق وجذاب عبر مختلف سياقات العرض. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_103) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_104) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [rotate(angle)](#rotate_angle_105) | تدوير الصورة حول المركز. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_106) | دوّر الصورة حول نقطة مركزها بزاوية محددة، مما يتيح تعديلات دقيقة في الاتجاه.<br/>            دمج هذه الوظيفة في خط أنابيب معالجة الصور لتسهيل التحويلات الدقيقة، وضمان محاذاة وعرض محتوى بصري مثالي داخل تطبيقك. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_107) | نفّذ دورانًا أو انعكاسًا أو مزيجًا من كلا العمليتين حصريًا على الإطار النشط. تتيح هذه الطريقة تعديلًا دقيقًا لإطارات فردية داخل تسلسل الصورة، مما يعزز المرونة في تحرير الصورة وتكوينها داخل تطبيقك. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_108) | يقوم بتدوير جميع القلب. |
| save() | يقوم بحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_109) | يقوم بحفظ الصورة إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_110) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_111) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_112) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_113) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_114) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_115) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_116) | يقوم بحفظ بكسلات ARGB 32‑بت. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_117) | يقوم بحفظ البكسلات. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_118) | يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_119) | يحفظ البكسلات الداخلية الرئيسية. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_120) | يحفظ البيانات الخام. |
| [save_to_stream(stream)](#save_to_stream_stream_121) | يحفظ الصورة إلى تدفق. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_122) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_124) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_125) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_126) | يضبط بكسل صورة 32-بت ARGB للموقع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_127) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_128) | يضبط بكسل صورة للموقع المحدد. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_129) | يحدد الدقة للصورة [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحددة، مما يتيح <br/>            تحكمًا دقيقًا في عرض الصورة وخصائص العرض. دمج هذه <br/>            الوظيفة لتحسين المخرجات البصرية وضمان التوافق مع أجهزة ومواقع إخراج متنوعة <br/>            ، مما يعزز تجربة المستخدم العامة. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_130) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_132) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |


### Constructor: TiffImage(frame) {#TiffImage_frame_1}


```
 TiffImage(frame) 
```

قم بتهيئة كائن جديد من الفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/)، مع تحديد معلمة <br/>            الإطار. يُسهل هذا المُنشئ إنشاء مثيل TiffImage <br/>            ، مما يسمح للمطورين بتحديد الإطار الذي سيتم تحميله أو معالجته، <br/>            مما يبسط مهام معالجة صور Tiff داخل تطبيقاتهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | إطار TIFF لبدء الصورة به. |

### Constructor: TiffImage(frames) {#TiffImage_frames_2}


```
 TiffImage(frames) 
```

أنشئ مثيلاً جديدًا للفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/)، مع توفير قائمة بـ <br/>            الإطارات كمعامل. يتيح هذا المُنشئ تهيئة كائن TiffImage <br/>            بعدة إطارات، مما يُسهل التعامل الفعال ومعالجة <br/>            تسلسلات صور TIFF داخل تطبيقات البرمجيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطارات. |

### Property: has_alpha {#has_alpha1}

حدد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حاسمة<br/>            للتصوير وعمليات التركيب. دمج هذه الميزة لتحسين سير عمل المعالجة البصرية، مما يضمن تمثيلًا دقيقًا وتلاعبًا بالعناصر الشفافة.

**See also:**

**[Example # 1](#example_119)**: The following example loads a TIFF image and prints information about raw dat...


### Method: add(image) {#add_image_1}


```
 add(image) 
```

أضف الإطارات من الصورة المحددة بسلاسة إلى الإطار الحالي،<br/>            موحدًا محتواها ومعززًا مرونة التركيب. دمج هذه الطريقة لتبسيط إدارة الإطارات وتلاعبها داخل تطبيقك، مما يسهل معالجة فعّالة للصور متعددة الإطارات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) | صورة المصدر. |

### Method: add_frame(frame) {#add_frame_frame_2}


```
 add_frame(frame) 
```

دمج الإطار المحدد بسلاسة في الصورة، موسعًا محتواها<br/>            وتنوعها. استخدم هذه الطريقة لتعزيز تركيب الصورة وإدارتها،<br/>            مما يمكّن من معالجة فعّالة للصور متعددة الإطارات داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار للإضافة. |

### Method: add_frames(frames) {#add_frames_frames_3}


```
 add_frames(frames) 
```

دمج مصفوفة الإطارات بسلاسة في الصورة، مُغنيًا محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تركيب الصورة وإدارتها،<br/>            مما يتيح معالجة فعّالة للصور متعددة الإطارات داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | مصفوفة الإطارات للإضافة |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

أدمج صفحة جديدة في الصورة الحالية بسلاسة، موسعًا محتواها <br/>            وتنوعها. استخدم هذه الطريقة لتعزيز تكوين المستندات و <br/>            إدارتها، مما يتيح التعامل الفعال مع الصور متعددة الصفحات داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصفحة للإضافة. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

نفّذ تعديل _السطوع_ للصورة، مما يسمح<br/>            بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور الخاصة بك لتعزيز الرؤية وتحسين جودة الصورة البصرية<br/>            للصور داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| السطوع | int | قيمة السطوع. |


**See also:**

**[Example # 1](#example_128)**: The following example performs brightness correction of a TIFF image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

عزز التباين في مثيل [Image](/imaging/python-net/aspose.imaging/image/) ،<br/>            مضخمًا الفروق بين المناطق الفاتحة والداكنة. دمج هذه<br/>            الوظيفة لتحسين وضوح الصورة البصري والجودة العامة للصورة<br/>            داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |


**See also:**

**[Example # 1](#example_129)**: The following example performs contrast correction of a TIFF image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

طبق تصحيح غاما على الصورة، مع تعديل شدة البكسلات لتحقيق توازن اللون المطلوب.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز جودة الصورة وتحسين دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| جاما | float | معامل جاما للقنوات الحمراء والخضراء والزرقاء |


**See also:**

**[Example # 1](#example_126)**: The following example performs gamma-correction of a TIFF image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

قم بتطبيق تصحيح غاما على الصورة باستخدام معاملات فردية للقنوات الحمراء، الخضراء، والزرقاء، مما يسمح بتعديلات دقيقة لتوازن اللون والتباين.<br/>            دمج هذه الطريقة في خط أنابيب معالجة الصور الخاص بك لتحقيق تحكم دقيق في عرض الألوان وتعزيز دقة الصورة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| gamma_red | float | معامل جاما للقناة الحمراء |
| gamma_green | float | معامل جاما للقناة الخضراء |
| gamma_blue | float | معامل جاما للقناة الزرقاء |


**See also:**

**[Example # 1](#example_127)**: The following example performs gamma-correction of a TIFF image applying diff...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_9}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_10}


```
 binarize_bradley(brightness_difference) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brightness_difference | float | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات<br/>                المتمركزة حول هذا البكسل. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_11}


```
 binarize_bradley(brightness_difference, window_size) 
```

نفّذ تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة.<br/>            هذه الطريقة تحسب عتبات محلية ديناميكياً بناءً على جوار الصورة، مما يعزز التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام اللاحقة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brightness_difference | float | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات<br/>            المتمركزة حول هذا البكسل. |
| window_size | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |


**See also:**

**[Example # 1](#example_124)**: The following example binarizes a TIFF image with Bradley's adaptive threshol...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

طبق التثن binary على الصورة باستخدام عتبة محددة مسبقاً، محولاً إياها إلى صورة ثنائية ذات مناطق أمامية وخلفية متميزة.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التجزئة واستخراج الميزات، مما يعزز دقة وكفاءة تحليل الصورة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحدّ | System.Byte | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة<br/>            255 له، وإلا 0. |


**See also:**

**[Example # 1](#example_122)**: The following example binarizes a TIFF image with the predefined threshold. B...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_13}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_14}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_15}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_16}


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


### Method: can_load(stream)  [static] {#can_load_stream_17}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_18}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_19}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_20}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_21}


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


### Method: can_save(options) {#can_save_options_22}


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


### Method: create(files)  [static] {#create_files_23}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_24}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_25}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_26}


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


### Method: create(images)  [static] {#create_images_27}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_28}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_29}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_30}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_31}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_32}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_33}


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


### Method: create_with_frame(frame)  [static] {#create_with_frame_frame_34}


```
 create_with_frame(frame) 
```

يُنشئ مثيلاً جديدًا للفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | إطار TIFF لبدء الصورة به. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) |  |


### Method: create_with_frames(frames)  [static] {#create_with_frames_frames_35}


```
 create_with_frames(frames) 
```

يُنشئ مثيلاً جديدًا للفئة [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطارات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_36}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

قم بقص الصورة عن طريق تحديد إزاحات في الاتجاهات اليسرى، اليمنى، العليا، والسفلى.<br/>            تتيح هذه الطريقة اختيار الجزء المطلوب من الصورة بدقة، مما يسهل إزالة المناطق غير المرغوبة والتركيز على المحتوى الأساسي.<br/>            دمج هذه الوظيفة في خط أنابيب معالجة الصور لتعزيز الوضوح والتركيب حسب الحاجة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| left_shift | int | الإزاحة اليسرى. |
| right_shift | int | الإزاحة اليمنى. |
| top_shift | int | الإزاحة العلوية. |
| bottom_shift | int | الإزاحة السفلية. |


**See also:**

**[Example # 1](#example_121)**: The following example crops a TIFF image. The cropping area is specified via ...


### Method: crop(rectangle) {#crop_rectangle_37}


```
 crop(rectangle) 
```

قص الصورة باستخدام منطقة مستطيلة محددة، مما يتيح اختيار المحتوى المطلوب بدقة.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لإزالة المناطق غير المرغوبة والتركيز على التفاصيل الأساسية، مما يعزز الوضوح والتركيب العام للصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |


**See also:**

**[Example # 1](#example_120)**: The following example crops a TIFF image. The cropping area is be specified v...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_38}


```
 dither(dithering_method, bits_count) 
```

يُجري تمويهًا على الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_39}


```
 dither(dithering_method, bits_count, custom_palette) 
```

نفّذ التدرج (dithering) على الصورة الحالية لتعزيز جودتها البصرية وتقليل آثار تدرج اللون.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لضمان انتقالات ألوان أكثر سلاسة، مما ينتج مظهرًا بصريًا محسّنًا ووضوحًا أفضل للصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان المخصصة للتدرج. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_40}


```
 embed_digital_signature(password) 
```

أدمج توقيعًا رقميًا يعتمد على كلمة المرور المقدمة في كل صفحة من الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور المستخدمة لإنشاء بيانات التوقيع الرقمي |

### Method: filter(rectangle, options) {#filter_rectangle_options_41}


```
 filter(rectangle, options) 
```

قم بتصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صور مخصص لتحسين أو تعديل المنطقة المختارة. دمج هذه الطريقة <br/>            في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات مستهدفة أو <br/>            تحويلات داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | الخيارات. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_42}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_43}


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


### Method: get_default_options(args) {#get_default_options_args_44}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_45}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_47}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_48}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_49}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_50}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_51}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_52}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_53}


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


### Method: get_original_options() {#get_original_options__54}


```
 get_original_options() 
```

استرجع الخيارات المستمدة من إعدادات الملف الأصلي، مما يسهل الحفاظ السلس على المعلمات الرئيسية مثل عمق البت وغيرها من السمات الأساسية للصورة الأصلية.<br/>            استخدم هذه الطريقة للحفاظ على الدقة والاتساق في مهام معالجة الصور، وضمان نتائج مثالية دون تعديلات غير ضرورية.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستندة إلى إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_55}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_56}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_57}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_58}


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


### Method: get_skew_angle() {#get_skew_angle__59}


```
 get_skew_angle() 
```

يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح.

**Returns**

| نوع | الوصف |
| :- | :- |
| float | زاوية الانحراف، بالدرجات. |


### Method: insert_frame(index, frame) {#insert_frame_index_frame_60}


```
 insert_frame(index, frame) 
```

أدرج الإطار الجديد في الفهرس المحدد داخل تسلسل الإطارات، مما يضمن تحكمًا دقيقًا في ترتيب الإطارات.<br/>            استخدم هذه الطريقة لإدارة تسلسلات الإطارات بفعالية، مما يسهل التلاعب الديناميكي وتنظيم محتوى الصورة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس _frame_. |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار للإدراج. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


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


### Method: load(file_path)  [static] {#load_file_path_62}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


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


### Method: load(stream)  [static] {#load_stream_64}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | محمل بكسلات ARGB 64-بت. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يحمّل بكسلات جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

استخدم طريقة **NormalizeAngle** المصممة خصيصًا لمستندات النص الممسوحة ضوئياً لتصحيح الانحرافات، مما يضمن محاذاة دقيقة.<br/>            دمج هذه الوظيفة بسلاسة في سير عمل معالجة النص لتحسين قابلية القراءة وجودة المستند، مما يعزز الكفاءة العامة في مهام التعرف على النص وتحليلها.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و[TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


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


### Method: remove_frame(frame) {#remove_frame_frame_82}


```
 remove_frame(frame) 
```

أزل الإطار المحدد بفعالية من تسلسل الصور، مما يسهل إدارة الإطارات بسلاسة داخل تطبيقك.<br/>            دمج هذه الوظيفة لتعزيز الدقة والمرونة في التلاعب بالإطارات، وضمان تنظيم وعرض محتوى الصورة بسلاسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار للإزالة. |

### Method: remove_frame(index) {#remove_frame_index_83}


```
 remove_frame(index) 
```

يزيل الإطار وفقًا لموقعه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس الإطار الذي سيُزال. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار المُزال. |


### Method: remove_frame_by_index(index) {#remove_frame_by_index_index_84}


```
 remove_frame_by_index(index) 
```

يزيل الإطار وفقًا لموقعه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس الإطار الذي سيُزال. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار المُزال. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_85}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_86}


```
 replace_color(old_color, old_color_diff, new_color) 
```

يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_87}


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

### Method: replace_frame(index, new_frame) {#replace_frame_index_new_frame_88}


```
 replace_frame(index, new_frame) 
```

استبدل الإطار في الموضع المحدد بإطار آخر بسلاسة، مما يسهل إدارة الإطارات الديناميكية داخل تسلسل الصور.<br/>            دمج هذه الطريقة لتعزيز المرونة والدقة في التلاعب بالإطارات، وضمان تنظيم وعرض محتوى الصورة بشكل أمثل داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | موضع الإطار بدءًا من الصفر. |
| new_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار لاستبدال الإطار الموجود في _index_ المحدد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | الإطار المُزال. |


### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_89}


```
 replace_non_transparent_colors(new_color) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_90}


```
 replace_non_transparent_colors(new_color_argb) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_91}


```
 resize(new_width, new_height) 
```

يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_92}


```
 resize(new_width, new_height, resize_type) 
```

قم بإجراء عملية تغيير حجم متناسبة على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها.<br/>            استخدم هذه الطريقة لتوسيع الصور ديناميكيًا داخل تطبيقك، مما يضمن تمثيلًا بصريًا متسقًا للمحتوى وسلامة التكامل.<br/>            سيقوم تغيير الحجم المتناسب بتغيير حجم كل إطار وفقًا لنسبة _newWidth_/العرض و _newHeight_/الارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_93}


```
 resize(new_width, new_height, settings) 
```

اضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم.<br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تغيير حجم مخصصة تتناسب مع المتطلبات الخاصة لتطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات التحجيم. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_94}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_95}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_96}


```
 resize_height_proportionally(new_height) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_97}


```
 resize_height_proportionally(new_height, resize_type) 
```

قم بتعديل ارتفاع الصورة بشكل متناسب، مع الحفاظ على نسبة العرض إلى الارتفاع لضمان تكامل بصري ثابت.<br/>            استخدم هذه الطريقة لتغيير حجم الصور ديناميكيًا داخل تطبيقك، مما يضمن عرضًا مثاليًا عبر منصات وأجهزة متعددة دون الإضرار بجودة المحتوى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_98}


```
 resize_height_proportionally(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_99}


```
 resize_height_proportionally_settings(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_100}


```
 resize_proportional(new_width, new_height, resize_type) 
```

قم بإجراء عملية تغيير حجم متناسبة على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها.<br/>            استخدم هذه الطريقة لتوسيع الصور ديناميكيًا داخل تطبيقك، مما يضمن تمثيلًا بصريًا متسقًا للمحتوى وسلامة التكامل.<br/>            سيقوم تغيير الحجم المتناسب بتغيير حجم كل إطار وفقًا لنسبة _newWidth_/العرض و _newHeight_/الارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_101}


```
 resize_width_proportionally(new_width) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_102}


```
 resize_width_proportionally(new_width, resize_type) 
```

اضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع، مما يضمن تغيير حجم متناسب لتقديم عرض بصري أمثل.<br/>            استخدم هذه الطريقة لتوسيع الصور ديناميكيًا داخل تطبيقك، مما يسهل تقديم عرض متسق وجذاب عبر مختلف سياقات العرض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_103}


```
 resize_width_proportionally(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_104}


```
 resize_width_proportionally_settings(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_105}


```
 rotate(angle) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_106}


```
 rotate(angle, resize_proportionally, background_color) 
```

دوّر الصورة حول نقطة مركزها بزاوية محددة، مما يتيح تعديلات دقيقة في الاتجاه.<br/>            دمج هذه الوظيفة في خط أنابيب معالجة الصور لتسهيل التحويلات الدقيقة، وضمان محاذاة وعرض محتوى بصري مثالي داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_107}


```
 rotate_flip(rotate_flip_type) 
```

نفّذ دورانًا أو انعكاسًا أو مزيجًا من كلا العمليتين حصريًا على الإطار النشط. تتيح هذه الطريقة تعديلًا دقيقًا لإطارات فردية داخل تسلسل الصورة، مما يعزز المرونة في تحرير الصورة وتكوينها داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | نوع دوران الانعكاس. |


**See also:**

**[Example # 1](#example_118)**: This example loads a TIFF image, rotates it by 90 degrees clockwise and optio...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_108}


```
 rotate_flip_all(rotate_flip) 
```

يقوم بتدوير جميع القلب.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | دوران الانعكاس. |

### Method: save(file_path) {#save_file_path_109}


```
 save(file_path) 
```

يقوم بحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ الصورة فيه. |

### Method: save(file_path, options) {#save_file_path_options_110}


```
 save(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_111}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_112}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_113}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_114}


```
 save(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_115}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_116}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يقوم بحفظ بكسلات ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_117}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | بكسلات CMYK معروضة كقيم صحيحة 32‑بت. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_118}


```
 save_cmyk_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | مصفوفة بكسلات CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_119}


```
 save_pixels(rectangle, pixels) 
```

يحفظ البكسلات الداخلية الرئيسية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | البكسلات. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_120}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_121}


```
 save_to_stream(stream) 
```

يحفظ الصورة إلى تدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom |  |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_122}


```
 save_to_stream_with_options(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_124}


```
 save_with_options(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_125}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_126}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_127}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة التي يجب ضبطها. |
| update_colors | bool | إذا تم ضبطه على <c>true</c> سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. لاحظ أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات مطابقة في اللوحة. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_128}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_129}


```
 set_resolution(dpi_x, dpi_y) 
```

يحدد الدقة للصورة [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحددة، مما يتيح <br/>            تحكمًا دقيقًا في عرض الصورة وخصائص العرض. دمج هذه <br/>            الوظيفة لتحسين المخرجات البصرية وضمان التوافق مع أجهزة ومواقع إخراج متنوعة <br/>            ، مما يعزز تجربة المستخدم العامة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dpi_x | float | الدقة الأفقية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | الدقة العمودية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_130}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |
| argb_32_pixels | int[] | مصفوفة ألوان ARGB 32‑بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_132}


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
### This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_118}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# تدوير، انعكاس وحفظ إلى ملف الإخراج.
	with aspycore.as_of(Image.load(join(dir_, "sample.tif")), TiffImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a TIFF image and prints information about raw data format and alpha channel. {#example_119}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from os.path import join as path_join


dir_ = "c:\\temp"
file_name = path_join(dir_, "sample.tif")
with Image.load(file_name) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# إذا كان لإطار TIFF النشط قناة ألفا، فسيُعتبر أن صورة TIFF بأكملها تحتوي على قناة ألفا.
	print("ImageFile={0}, FileFormat={1}, HasAlpha={2}".format(file_name, tiff_image.raw_data_format, tiff_image.has_alpha))
	i = 1
	for frame in tiff_image.frames:
		print("Frame={0}, FileFormat={1}, HasAlpha={2}".format(i, frame.raw_data_format, frame.has_alpha))
		i += 1

# قد يبدو الإخراج هكذا:
# ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False


```

### The following example crops a TIFF image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_120}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.tiff import TiffImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية للصورة.
	area = Rectangle(tiff_image.width // 4, tiff_image.height // 4, tiff_image.width // 2,
					 tiff_image.height // 2)
	tiff_image.crop(area)
	# حفظ الصورة المقصوصة إلى PNG
	tiff_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a TIFF image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_121}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image       
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# قم بالقص مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
	horizontal_margin: int = tiff_image.width // 10
	vertical_margin: int = tiff_image.height // 10
	tiff_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# احفظ الصورة المقصوصة بصيغة PNG.
	tiff_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a TIFF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_122}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# حوّل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
	# إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
	tiff_image.binarize_fixed(127)
	tiff_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_124}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# حوّل الصورة إلى ثنائية بفارق سطوع قدره 5. السطوع هو الفرق بين البكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
	tiff_image.binarize_bradley(5, 10)
	tiff_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a TIFF image. {#example_126}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# اضبط معامل غاما للقنوات الحمراء والخضراء والزرقاء.
	tiff_image.adjust_gamma(2.5)
	tiff_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a TIFF image applying different coefficients for color components. {#example_127}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# اضبط معاملات غاما الفردية للقنوات الحمراء والخضراء والزرقاء.
	tiff_image.adjust_gamma(1.5, 2.5, 3.5)
	tiff_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a TIFF image. {#example_128}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# اضبط قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255، 255].
	tiff_image.adjust_brightness(50)
	tiff_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a TIFF image. {#example_129}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# اضبط قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f، 100f].
	tiff_image.adjust_contrast(50.0)
	tiff_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# إنشاء GraphicsPath باستخدام PathResources من صورة TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# ارسم خطًا أحمر واحفظ الصورة
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

