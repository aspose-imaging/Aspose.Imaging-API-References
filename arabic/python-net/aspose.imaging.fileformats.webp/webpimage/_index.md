---
title: "فئة WebPImage"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.webp/webpimage/
---

**Summary:** Manipulate WebP raster images with our API, using its modern features for both<br/>            lossless and lossy compression, ensuring optimal image quality with reduced file sizes.<br/>            Seamlessly handle extended file formats, animations, and alpha channels, while easily<br/>            updating dimensions, resizing proportionally, cropping, rotating, applying filters,<br/>            adjusting image parameters, and converting to other image formats for versatile<br/>            web image optimization.

**Module:** [aspose.imaging.fileformats.webp](/imaging/python-net/aspose.imaging.fileformats.webp/)

**Full Name:** aspose.imaging.fileformats.webp.WebPImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WebPImage(path)](#WebPImage_path_1) | أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/)، مهيئًا <br/>            من مصدر ملف مُقدَّم. استخدم هذا المُنشئ لإنشاء كائنات WebP <br/>            مباشرةً من الملفات، مما يُبسّط عملية تحميل و <br/>            معالجة بيانات صورة WebP داخل تطبيقك. |
| [WebPImage(path, load_options)](#WebPImage_path_load_options_2) | أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) باستخدام ملف و <br/>            خيارات تحميل محددة، مما يُسهل التعامل المرن مع بيانات صورة WebP. استخدم <br/>            هذا المُنشئ لتهيئة كائنات صورة WebP مباشرةً من الملفات مع <br/>            تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك. |
| [WebPImage(raster_image)](#WebPImage_raster_image_3) | أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/)، مهيئًا <br/>            من كائن rasterImage مُقدَّم. يتيح هذا المُنشئ تحويل صور raster إلى تنسيق WebP بسلاسة، مما يُمكن من التعامل الفعّال و <br/>            معالجة بيانات الصورة داخل تطبيقك. |
| [WebPImage(raster_image, load_options)](#WebPImage_raster_image_load_options_4) | أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) باستخدام كائن rasterImage و <br/>            خيارات تحميل محددة، مما يُتيح التعامل المرن مع بيانات الصورة. استخدم هذا <br/>            المُنشئ لتهيئة كائنات صورة WebP مباشرةً من صور raster مع <br/>            تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك. |
| [WebPImage(stream)](#WebPImage_stream_5) | إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) ، مبدئًا <br/> من مصدر تدفق مُقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP <br/> مباشرةً من التدفقات، مما يتيح معالجة فعّالة وتعديل <br/> بيانات صورة WebP داخل تطبيقك. |
| [WebPImage(stream, load_options)](#WebPImage_stream_load_options_6) | إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من تدفق، مع دمج خيارات التحميل المحددة وإعدادات إدارة الذاكرة. يوفر هذا المُنشئ مرونة في تحميل صور WebP من التدفقات مع إدارة موارد الذاكرة بفعالية، مما يضمن أداءً مثاليًا واستخدامًا أمثل للموارد داخل تطبيقك. |
| [WebPImage(width, height, options)](#WebPImage_width_height_options_7) | إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) مع صورة فارغة <br/> ذات أبعاد عرض وارتفاع محددة. يتيح هذا المُنشئ <br/> إنشاء صور WebP فارغة، مما يوفر أساسًا للتعديل اللاحق على الصور <br/> وتوليد المحتوى داخل تطبيقك. |
| [WebPImage(width, height, options, load_options)](#WebPImage_width_height_options_load_options_8) | إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) مع صورة فارغة وخيارات تحميل محددة <br/>. يتيح هذا المُنشئ تهيئة صور WebP مع <br/> معلمات تحميل قابلة للتخصيص، مما يوفر مرونة في إنشاء الصور و <br/> تعديلها داخل تطبيقك. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تعديل لوحة الألوان تلقائيًا. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| bits_per_pixel | int | r | يحصل على عدد البتات في الصورة لكل بكسل. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود الكائن. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | يحصل على حاوية [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | يحصل على تدفق بيانات الكائن. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن كائن Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، وتوفير معلومات <br/> حول التنسيق الذي تُخزن به الصورة. استخدم هذه الخاصية لتحديد <br/> تنسيق ملف الصورة، مما يسهل فحوصات التوافق و <br/> المعالجة الخاصة بالتنسيق داخل تطبيقك. |
| [has_alpha](#has_alpha1) | bool | r | استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يدل على وجود <br/> معلومات الشفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة <br/> تشمل شفافية، مما يتيح معالجة مناسبة للعمليات المتعلقة بالألفا <br/> داخل تطبيقك. |
| has_background_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparent_color | bool | r/w | يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون شفاف. |
| height | int | r | يحصل على ارتفاع الصورة. |
| horizontal_resolution | float | r/w | يحصل أو يعيّن الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | يحصل أو يعيّن مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتاً حالياً. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | يحصل أو يعيّن بيانات XMP من الإطار. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | r | استرجاع أو تعديل الخيارات المرتبطة بالخاصية المحددة، مما يتيح <br/> تخصيصًا دقيقًا للسلوك والإعدادات. استخدم هذه الخاصية لـ <br/> الوصول السلس إلى المعلمات القابلة للتكوين وتعديلها، مما يسهل تحكمًا متعدد الاستخدامات <br/> وتحسينًا داخل وظائف تطبيقك. |
| page_count | int | r | استرجاع العدد الكلي للصفحات داخل المستند المحدد، مما يسهل <br/> التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه <br/> الوظيفة لتعزيز تجربة المستخدم، وتمكين الوصول السلس إلى <br/> هياكل المستند الشاملة. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | الوصول إلى كتل WebP داخل الصورة، مما يسمح بفحص مفصل أو <br/> تعديل للهيكل الكتلي الأساسي. استخدم هذه الخاصية لتحليل <br/> أو تعديل الكتل الفردية داخل بيانات صورة WebP، مما يسهل تقنيات معالجة الصور المتقدمة <br/> داخل تطبيقك. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| premultiply_components | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
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
| vertical_resolution | float | r/w | يحصل أو يضبط الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | يحصل على عرض الصورة. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | إدراج كتلة WebP جديدة في الصورة، مما يثري محتواها و <br/> يسهل تعديل الصور المتقدم. دمج هذه الطريقة لتحديث بنية وتعقيد بيانات صورة WebP داخل <br/> تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا في عرض الصورة. |
| [add_page(page)](#add_page_page_2) | إضافة صفحة جديدة إلى الصورة، لتوسيع محتواها واستيعاب عناصر بصرية إضافية <br/>. دمج هذه الطريقة لتسهيل إدارة الصفحات الديناميكية <br/> داخل تطبيقك، مما يتيح إنشاءًا سلسًا وتوسيعًا للمستندات أو الصور متعددة الصفحات <br/>. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | تنفيذ تعديل _السطوع_ للصورة، مما يسمح <br/> بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك <br/> لتعزيز الوضوح وتحسين جودة الصور البصرية <br/> داخل تطبيقك. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | تحسين تباين [Image](/imaging/python-net/aspose.imaging/image/)، مع تضخيم <br/> الفروق بين المناطق الفاتحة والداكنة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك <br/> لتحسين الوضوح البصري وجودة الصورة العامة داخل <br/> تطبيقك. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | تطبيق تصحيح جاما على الصورة، مع تعديل شدة البكسلات لتحقيق <br/> السطوع والتوازن اللوني المطلوبين. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك <br/> لتعزيز الجودة البصرية وتحسين دقة <br/> التحليل أو مهام العرض اللاحقة داخل تطبيقك. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | إجراء تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر، <br/> الأخضر، والأزرق، مما يسمح بتعديلات دقيقة لتوازن الألوان و <br/> التباين. دمج هذه الطريقة في خط معالجة الصور الخاص بك لتحقيق <br/> تحكمًا دقيقًا في عرض الألوان وتعزيز الدقة البصرية داخل <br/> تطبيقك. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| auto_brightness_contrast() | ينفّذ تطبيعًا تلقائيًا متكيفًا للسطوع والتباين لكامل الصورة. |
| auto_rotate() | يدور الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من Exif <br/>            metadata. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح،<br/>            مما يعزز تجربة المستخدم ويزيل الحاجة إلى التعديلات اليدوية. من خلال <br/>            تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، موفرًا تجربة مشاهدة سلسة <br/>            عبر منصات وأجهزة مختلفة. تُبسّط عملية الدوران الآلية التعامل مع الصور وتُحسّن القابلية العامة للاستخدام، خاصةً عند <br/>            التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | تطبيق التثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرايدلي <br/> مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب العتبات المحلية <br/> ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة <br/> ويضمن تجزئة قوية للمهام المعالجة اللاحقة <br/> داخل تطبيقك. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | إجراء التثنائي على الصورة باستخدام قيمة عتبة محددة مسبقًا، وتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة <br/> بناءً على شدتها مقارنةً بالعتبة. دمج هذه الطريقة في <br/> سير عمل معالجة الصور لتسهيل التجزئة واستخراج الميزات <br/>، مما يعزز دقة وكفاءة التحليل اللاحق داخل <br/> تطبيقك. |
| binarize_otsu() | إجراء التثنائي على الصورة باستخدام طريقة عتبة أوتسو، التي تحدد تلقائيًا <br/> قيمة العتبة المثلى بناءً على هيستوجرام الصورة. دمج <br/> هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة فعّالة <br/> واستخراج الميزات، مما يعزز دقة وموثوقية مهام تحليل الصور <br/> داخل تطبيقك. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | يمزج هذه النسخة من الصورة مع الصورة _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | يمزج هذه النسخة من الصورة مع الصورة _overlay_. |
| cache_data() | يقوم بتخزين البيانات بشكل خاص. |
| [can_load(file_path)](#can_load_file_path_13) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_load(stream)](#can_load_stream_15) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_save(options)](#can_save_options_20) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| clear_blocks() | مسح جميع كتل WebP الموجودة من الصورة، مما يتيح مساحة نظيفة لـ <br/> التعديلات أو الإضافات اللاحقة. استخدم هذه الطريقة لإعادة ضبط <br/> بنية الكتل داخل بيانات صورة WebP بفعالية، وضمان إدارة مثالية و <br/> تنظيم محتوى الصورة داخل تطبيقك. |
| [create(files)](#create_files_21) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | ينشئ مثيلًا من [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) من مصفوفة البكسل المقدمة.<br/>            <br/>            يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل.<br/>            لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص. |
| [create(images)](#create_images_25) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(images, dispose_images)](#create_images_dispose_images_26) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | ينشئ خيارات الإنشاء المتعددة الصفحات المحددة. |
| [create_from_file_with_options(path, load_options)](#create_from_file_with_options_path_load_options_28) | يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من ملف. |
| [create_from_files(files)](#create_from_files_files_29) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_30) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_image(raster_image)](#create_from_image_raster_image_31) | يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من rasterImage. |
| [create_from_image_with_options(raster_image, load_options)](#create_from_image_with_options_raster_image_load_options_32) | يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من rasterImage. |
| [create_from_images(images)](#create_from_images_images_33) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_34) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create_from_stream(stream)](#create_from_stream_stream_35) | يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class<br/> من تدفق. |
| [create_from_stream_with_options(stream, load_options)](#create_from_stream_with_options_stream_load_options_36) | يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من تدفق. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | قص الصورة عن طريق تطبيق إزاحات إلى اليسار، اليمين، الأعلى، والأسفل، مما يختار <br/> منطقة اهتمام داخل الصورة. استخدم هذه الطريقة لـ <br/> استخراج الأجزاء المطلوبة من الصورة ديناميكيًا مع تعديل تركيبتها <br/> وتركيزها وفقًا لمتطلبات تطبيقك. |
| [crop(rectangle)](#crop_rectangle_38) | قص الصورة باستخدام منطقة مستطيلة محددة، وإزالة الأجزاء غير المرغوب فيها <br/> مع الحفاظ على المحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور الخاصة بك <br/> لاستخراج وتركيز دقيق على مناطق الاهتمام المحددة داخل الصورة، مما يعزز الوضوح والتركيب لتطبيقات مختلفة. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | يُجري تمويهًا على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | قم بإجراء التدرج على الصورة الحالية لتقليل تدرج الألوان وتحسين الجودة البصرية <br/>            . دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق <br/>            انتقالات أكثر سلاسة بين الألوان وتحسين المظهر العام <br/>            للصورة داخل تطبيقك. |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | أدمج توقيعًا رقميًا يعتمد على كلمة المرور المقدمة في كل صفحة من الصورة. |
| [filter(rectangle, options)](#filter_rectangle_options_42) | قم بتصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صور مخصص لتحسين أو تعديل المنطقة المختارة. دمج هذه الطريقة <br/>            في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات مستهدفة أو <br/>            تحويلات داخل تطبيقك. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_43) | يحصل على بكسل صورة 32-بت ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_44) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_45) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_46) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_48) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_49) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_50) | يحصل على تنسيق الملف. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_51) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_52) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_53) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [get_original_options()](#get_original_options__55) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_56) | يحصل على بكسل صورة. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | يحصل على عرض نسبي. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | يحوّل إلى aps. |
| [get_skew_angle()](#get_skew_angle__60) | يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح. |
| grayscale() | حوّل الصورة إلى تمثيلها بالأبيض والأسود، محولًا إياها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة أو الإضاءة. دمج هذه الطريقة <br/>            في خط أنابيب معالجة الصور الخاص بك لتبسيط التحليل وتعزيز <br/>            التوافق مع الخوارزميات القائمة على الأبيض والأسود، مما يسهل مهام الرؤية الحاسوبية وتحليل الصور المختلفة داخل تطبيقك. |
| [insert_block(index, block)](#insert_block_index_block_61) | أدرج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا <br/>            في تسلسل الكتل. دمج هذه الطريقة لتضمين كتل WebP إضافية بسلاسة في بنية بيانات الصورة، مما يسهل معالجة الصور المتقدمة وتحسينها داخل تطبيقك. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |
| [load(file_path)](#load_file_path_63) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(file_path, load_options)](#load_file_path_load_options_64) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(stream)](#load_stream_65) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_66) | يقوم بتحميل البيانات من الدفق. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_67) | يحمّل بكسلات ARGB 32‑بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_68) | يحمّل بكسلات ARGB 64‑بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_69) | يحمّل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_70) | يحمّل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71) | يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72) | يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_73) | يحمّل بكسلات جزئيًا حسب الحزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_74) | يحمّل بكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75) | يحمّل بيانات خام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76) | يحمّل بيانات خام. |
| [load_stream(stream)](#load_stream_stream_77) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_78) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_79) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| normalize_angle() | يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) . |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) . |
| normalize_histogram() | يُعَدِّل مدرج الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [remove_block(block)](#remove_block_block_83) | إزالة كتلة WebP المحددة من الصورة، مما يسهل إدارة بنية بيانات الصورة بفعالية. <br/>            استخدم هذه الطريقة لتبسيط سير عمل معالجة الصور عن طريق حذف الكتل أو المكونات غير الضرورية داخل تطبيقك. |
| remove_metadata() | يزيل بيانات التعريف لهذه الصورة عن طريق تعيين قيمة [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) إلى **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_87) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_88) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_89) | يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_90) | تغيير حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. <br/>            دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتكبير أو تصغير الصور ديناميكيًا لتتناسب مع متطلبات العرض أو التخزين المختلفة داخل تطبيقك. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_91) | تغيير حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في <br/>            الأبعاد، نسبة العرض إلى الارتفاع، وسلوك التكبير/التصغير. دمج هذه الطريقة في <br/>            سير عمل معالجة الصور لتحقيق عمليات تغيير حجم مخصصة تتناسب مع <br/>            المتطلبات المحددة لتطبيقك. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_92) | يقوم بتغيير حجم الصورة. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_93) | يقوم بتغيير حجم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_94) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_95) | ضبط ارتفاع الصورة بشكل نسبي، مع الحفاظ على نسبة العرض إلى الارتفاع <br/>            لضمان تغيير حجم متسق. دمج هذه الطريقة في سير عمل معالجة الصور <br/>            لتغيير حجم الصور ديناميكيًا بنسب موحدة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل تطبيقك. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_96) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_97) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_98) | يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_99) | ضبط عرض الصورة بشكل نسبي مع الحفاظ على نسبة العرض إلى الارتفاع. <br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتغيير حجم الصور ديناميكيًا <br/>            بنسب متسقة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل <br/>            تطبيقك. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_100) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_101) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [rotate(angle)](#rotate_angle_102) | تدوير الصورة حول المركز. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_103) | دوّر الصورة حول مركزها بزاوية محددة، مع تعديل حجمها نسبيًا <br/>            وتطبيق معلمات لون الخلفية المحددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحويلات دقيقة مع <br/>            ألوان خلفية قابلة للتخصيص، مما يضمن عرضًا بصريًا مثاليًا داخل <br/>            تطبيقك. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_104) | طبق الدوران أو القلب أو كلا العمليتين حصريًا على الإطار النشط <br/>            داخل الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لت <br/>            تحقيق تعديل دقيق للإطارات الفردية، مما يعزز المرونة و <br/>            التحكم في تحويلات الإطارات داخل تطبيقك. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_105) | يقوم بتدوير جميع القلب. |
| save() | يقوم بحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_106) | يقوم بحفظ الصورة إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_107) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_108) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_109) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_110) | يقوم بحفظ البيانات. |
| [save(stream, options_base)](#save_stream_options_base_111) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_112) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_113) | يقوم بحفظ بكسلات ARGB 32‑بت. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_114) | يقوم بحفظ البكسلات. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_115) | يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_116) | يحفظ البكسلات الداخلية الرئيسية. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_117) | يحفظ البيانات الخام. |
| [save_to_stream(stream)](#save_to_stream_stream_118) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_119) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_121) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_122) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_123) | يضبط بكسل صورة 32-بت ARGB للموقع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_124) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_125) | يضبط بكسل صورة للموقع المحدد. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_126) | يضبط الدقة لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_127) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_129) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |


### Constructor: WebPImage(path) {#WebPImage_path_1}


```
 WebPImage(path) 
```

أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/)، مهيئًا <br/>            من مصدر ملف مُقدَّم. استخدم هذا المُنشئ لإنشاء كائنات WebP <br/>            مباشرةً من الملفات، مما يُبسّط عملية تحميل و <br/>            معالجة بيانات صورة WebP داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | مسار ملف صورة WebP |


**See also:**

**[Example # 1](#example_164)**: This example shows how to load a WebP image from a file and save it to PNG.


### Constructor: WebPImage(path, load_options) {#WebPImage_path_load_options_2}


```
 WebPImage(path, load_options) 
```

أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) باستخدام ملف و <br/>            خيارات تحميل محددة، مما يُسهل التعامل المرن مع بيانات صورة WebP. استخدم <br/>            هذا المُنشئ لتهيئة كائنات صورة WebP مباشرةً من الملفات مع <br/>            تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | مسار ملف صورة WebP |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

### Constructor: WebPImage(raster_image) {#WebPImage_raster_image_3}


```
 WebPImage(raster_image) 
```

أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/)، مهيئًا <br/>            من كائن rasterImage مُقدَّم. يتيح هذا المُنشئ تحويل صور raster إلى تنسيق WebP بسلاسة، مما يُمكن من التعامل الفعّال و <br/>            معالجة بيانات الصورة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |


**See also:**

**[Example # 1](#example_166)**: This example shows how to create a WebP image from another raster image.


### Constructor: WebPImage(raster_image, load_options) {#WebPImage_raster_image_load_options_4}


```
 WebPImage(raster_image, load_options) 
```

أنشئ مثيلًا جديدًا من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) باستخدام كائن rasterImage و <br/>            خيارات تحميل محددة، مما يُتيح التعامل المرن مع بيانات الصورة. استخدم هذا <br/>            المُنشئ لتهيئة كائنات صورة WebP مباشرةً من صور raster مع <br/>            تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

### Constructor: WebPImage(stream) {#WebPImage_stream_5}


```
 WebPImage(stream) 
```

إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) ، مبدئًا <br/> من مصدر تدفق مُقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP <br/> مباشرةً من التدفقات، مما يتيح معالجة فعّالة وتعديل <br/> بيانات صورة WebP داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق صورة WebP. |


**See also:**

**[Example # 1](#example_165)**: This example shows how to load a WebP image from a file stream and save it to...


### Constructor: WebPImage(stream, load_options) {#WebPImage_stream_load_options_6}


```
 WebPImage(stream, load_options) 
```

إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من تدفق، مع دمج خيارات التحميل المحددة وإعدادات إدارة الذاكرة. يوفر هذا المُنشئ مرونة في تحميل صور WebP من التدفقات مع إدارة موارد الذاكرة بفعالية، مما يضمن أداءً مثاليًا واستخدامًا أمثل للموارد داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق صورة WebP. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

### Constructor: WebPImage(width, height, options) {#WebPImage_width_height_options_7}


```
 WebPImage(width, height, options) 
```

إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) مع صورة فارغة <br/> ذات أبعاد عرض وارتفاع محددة. يتيح هذا المُنشئ <br/> إنشاء صور WebP فارغة، مما يوفر أساسًا للتعديل اللاحق على الصور <br/> وتوليد المحتوى داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة |
| height | int | ارتفاع الصورة. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | الخيارات. |


**See also:**

**[Example # 1](#example_167)**: This example shows how to create a WebP image with the specified options from...


### Constructor: WebPImage(width, height, options, load_options) {#WebPImage_width_height_options_load_options_8}


```
 WebPImage(width, height, options, load_options) 
```

إنشاء نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) مع صورة فارغة وخيارات تحميل محددة <br/>. يتيح هذا المُنشئ تهيئة صور WebP مع <br/> معلمات تحميل قابلة للتخصيص، مما يوفر مرونة في إنشاء الصور و <br/> تعديلها داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة |
| height | int | ارتفاع الصورة. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | الخيارات. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

### Property: has_alpha {#has_alpha1}

استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يدل على وجود <br/> معلومات الشفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة <br/> تشمل شفافية، مما يتيح معالجة مناسبة للعمليات المتعلقة بالألفا <br/> داخل تطبيقك.

**See also:**

**[Example # 1](#example_168)**: The following example loads a WEBP image and prints information about raw dat...


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

إدراج كتلة WebP جديدة في الصورة، مما يثري محتواها و <br/> يسهل تعديل الصور المتقدم. دمج هذه الطريقة لتحديث بنية وتعقيد بيانات صورة WebP داخل <br/> تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا في عرض الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | كتلة WebP لإضافتها. |

### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

إضافة صفحة جديدة إلى الصورة، لتوسيع محتواها واستيعاب عناصر بصرية إضافية <br/>. دمج هذه الطريقة لتسهيل إدارة الصفحات الديناميكية <br/> داخل تطبيقك، مما يتيح إنشاءًا سلسًا وتوسيعًا للمستندات أو الصور متعددة الصفحات <br/>.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصفحة للإضافة. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

تنفيذ تعديل _السطوع_ للصورة، مما يسمح <br/> بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك <br/> لتعزيز الوضوح وتحسين جودة الصور البصرية <br/> داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| السطوع | int | قيمة السطوع. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

تحسين تباين [Image](/imaging/python-net/aspose.imaging/image/)، مع تضخيم <br/> الفروق بين المناطق الفاتحة والداكنة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك <br/> لتحسين الوضوح البصري وجودة الصورة العامة داخل <br/> تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

تطبيق تصحيح جاما على الصورة، مع تعديل شدة البكسلات لتحقيق <br/> السطوع والتوازن اللوني المطلوبين. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك <br/> لتعزيز الجودة البصرية وتحسين دقة <br/> التحليل أو مهام العرض اللاحقة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| جاما | float | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

إجراء تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر، <br/> الأخضر، والأزرق، مما يسمح بتعديلات دقيقة لتوازن الألوان و <br/> التباين. دمج هذه الطريقة في خط معالجة الصور الخاص بك لتحقيق <br/> تحكمًا دقيقًا في عرض الألوان وتعزيز الدقة البصرية داخل <br/> تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| gamma_red | float | معامل جاما للقناة الحمراء |
| gamma_green | float | معامل جاما للقناة الخضراء |
| gamma_blue | float | معامل جاما للقناة الزرقاء |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brightness_difference | float | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات<br/>                المتمركزة حول هذا البكسل. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

تطبيق التثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرايدلي <br/> مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب العتبات المحلية <br/> ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة <br/> ويضمن تجزئة قوية للمهام المعالجة اللاحقة <br/> داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brightness_difference | float | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات<br/>            المتمركزة حول هذا البكسل. |
| window_size | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

إجراء التثنائي على الصورة باستخدام قيمة عتبة محددة مسبقًا، وتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة <br/> بناءً على شدتها مقارنةً بالعتبة. دمج هذه الطريقة في <br/> سير عمل معالجة الصور لتسهيل التجزئة واستخراج الميزات <br/>، مما يعزز دقة وكفاءة التحليل اللاحق داخل <br/> تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحدّ | System.Byte | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة<br/>            255 له، وإلا 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create_from_file_with_options(path, load_options)  [static] {#create_from_file_with_options_path_load_options_28}


```
 create_from_file_with_options(path, load_options) 
```

يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من ملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | مسار ملف صورة WebP |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_29}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_30}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_31}


```
 create_from_image(raster_image) 
```

يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من rasterImage.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_image_with_options(raster_image, load_options)  [static] {#create_from_image_with_options_raster_image_load_options_32}


```
 create_from_image_with_options(raster_image, load_options) 
```

يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من rasterImage.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة النقطية. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_33}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_34}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_35}


```
 create_from_stream(stream) 
```

يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class<br/> من تدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق صورة WebP. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_stream_with_options(stream, load_options)  [static] {#create_from_stream_with_options_stream_load_options_36}


```
 create_from_stream_with_options(stream, load_options) 
```

يُهيئ نسخة جديدة من الفئة [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) من تدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق صورة WebP. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

قص الصورة عن طريق تطبيق إزاحات إلى اليسار، اليمين، الأعلى، والأسفل، مما يختار <br/> منطقة اهتمام داخل الصورة. استخدم هذه الطريقة لـ <br/> استخراج الأجزاء المطلوبة من الصورة ديناميكيًا مع تعديل تركيبتها <br/> وتركيزها وفقًا لمتطلبات تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| left_shift | int | الإزاحة اليسرى. |
| right_shift | int | الإزاحة اليمنى. |
| top_shift | int | الإزاحة العلوية. |
| bottom_shift | int | الإزاحة السفلية. |

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

قص الصورة باستخدام منطقة مستطيلة محددة، وإزالة الأجزاء غير المرغوب فيها <br/> مع الحفاظ على المحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور الخاصة بك <br/> لاستخراج وتركيز دقيق على مناطق الاهتمام المحددة داخل الصورة، مما يعزز الوضوح والتركيب لتطبيقات مختلفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_39}


```
 dither(dithering_method, bits_count) 
```

يُجري تمويهًا على الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_40}


```
 dither(dithering_method, bits_count, custom_palette) 
```

قم بإجراء التدرج على الصورة الحالية لتقليل تدرج الألوان وتحسين الجودة البصرية <br/>            . دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق <br/>            انتقالات أكثر سلاسة بين الألوان وتحسين المظهر العام <br/>            للصورة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان المخصصة للتدرج. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_41}


```
 embed_digital_signature(password) 
```

أدمج توقيعًا رقميًا يعتمد على كلمة المرور المقدمة في كل صفحة من الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور المستخدمة لإنشاء بيانات التوقيع الرقمي |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

قم بتصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صور مخصص لتحسين أو تعديل المنطقة المختارة. دمج هذه الطريقة <br/>            في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات مستهدفة أو <br/>            تحويلات داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | الخيارات. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_43}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_44}


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


### Method: get_default_options(args) {#get_default_options_args_45}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_46}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_48}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_49}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_50}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_51}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_52}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_53}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_54}


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


### Method: get_original_options() {#get_original_options__55}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستندة إلى إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_56}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_57}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_58}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_59}


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


### Method: get_skew_angle() {#get_skew_angle__60}


```
 get_skew_angle() 
```

يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح.

**Returns**

| نوع | الوصف |
| :- | :- |
| float | زاوية الانحراف، بالدرجات. |


### Method: insert_block(index, block) {#insert_block_index_block_61}


```
 insert_block(index, block) 
```

أدرج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا <br/>            في تسلسل الكتل. دمج هذه الطريقة لتضمين كتل WebP إضافية بسلاسة في بنية بيانات الصورة، مما يسهل معالجة الصور المتقدمة وتحسينها داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | العنصر ذو الفهرس الصفري، حيث سيتم <br/>                إدراج _block_. |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | كتلة WebP لإضافتها. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_62}


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


### Method: load(file_path)  [static] {#load_file_path_63}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_64}


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


### Method: load(stream)  [static] {#load_stream_65}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_66}


```
 load(stream, load_options) 
```

يقوم بتحميل البيانات من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق صورة WebP. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_67}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_68}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_69}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_70}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | محمل بكسلات ARGB 64-بت. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_73}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يحمّل بكسلات جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_74}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_77}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_78}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_79}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_80}


```
 normalize_angle(resize_proportionally, background_color) 
```

يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_81}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_82}


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


### Method: remove_block(block) {#remove_block_block_83}


```
 remove_block(block) 
```

إزالة كتلة WebP المحددة من الصورة، مما يسهل إدارة بنية بيانات الصورة بفعالية. <br/>            استخدم هذه الطريقة لتبسيط سير عمل معالجة الصور عن طريق حذف الكتل أو المكونات غير الضرورية داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | الكتلة المراد إزالتها. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_87}


```
 replace_non_transparent_colors(new_color) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_88}


```
 replace_non_transparent_colors(new_color_argb) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة.<br/>                ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_89}


```
 resize(new_width, new_height) 
```

يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_90}


```
 resize(new_width, new_height, resize_type) 
```

تغيير حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. <br/>            دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتكبير أو تصغير الصور ديناميكيًا لتتناسب مع متطلبات العرض أو التخزين المختلفة داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_91}


```
 resize(new_width, new_height, settings) 
```

تغيير حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في <br/>            الأبعاد، نسبة العرض إلى الارتفاع، وسلوك التكبير/التصغير. دمج هذه الطريقة في <br/>            سير عمل معالجة الصور لتحقيق عمليات تغيير حجم مخصصة تتناسب مع <br/>            المتطلبات المحددة لتطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات التحجيم. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_92}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_93}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_94}


```
 resize_height_proportionally(new_height) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_95}


```
 resize_height_proportionally(new_height, resize_type) 
```

ضبط ارتفاع الصورة بشكل نسبي، مع الحفاظ على نسبة العرض إلى الارتفاع <br/>            لضمان تغيير حجم متسق. دمج هذه الطريقة في سير عمل معالجة الصور <br/>            لتغيير حجم الصور ديناميكيًا بنسب موحدة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_96}


```
 resize_height_proportionally(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_97}


```
 resize_height_proportionally_settings(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_98}


```
 resize_width_proportionally(new_width) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_99}


```
 resize_width_proportionally(new_width, resize_type) 
```

ضبط عرض الصورة بشكل نسبي مع الحفاظ على نسبة العرض إلى الارتفاع. <br/>            دمج هذه الطريقة في سير عمل معالجة الصور لتغيير حجم الصور ديناميكيًا <br/>            بنسب متسقة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل <br/>            تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_100}


```
 resize_width_proportionally(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_101}


```
 resize_width_proportionally_settings(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_102}


```
 rotate(angle) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_103}


```
 rotate(angle, resize_proportionally, background_color) 
```

دوّر الصورة حول مركزها بزاوية محددة، مع تعديل حجمها نسبيًا <br/>            وتطبيق معلمات لون الخلفية المحددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحويلات دقيقة مع <br/>            ألوان خلفية قابلة للتخصيص، مما يضمن عرضًا بصريًا مثاليًا داخل <br/>            تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة<br/>            وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) في الحالة الأخرى يترك الأبعاد دون تغيير وتُدوَّر محتويات الصورة __internal__ فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_104}


```
 rotate_flip(rotate_flip_type) 
```

طبق الدوران أو القلب أو كلا العمليتين حصريًا على الإطار النشط <br/>            داخل الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لت <br/>            تحقيق تعديل دقيق للإطارات الفردية، مما يعزز المرونة و <br/>            التحكم في تحويلات الإطارات داخل تطبيقك.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | نوع دوران الانعكاس. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_105}


```
 rotate_flip_all(rotate_flip) 
```

يقوم بتدوير جميع القلب.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | دوران الانعكاس. |

### Method: save(file_path) {#save_file_path_106}


```
 save(file_path) 
```

يقوم بحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ الصورة فيه. |

### Method: save(file_path, options) {#save_file_path_options_107}


```
 save(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_108}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_109}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_110}


```
 save(stream) 
```

يقوم بحفظ البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_111}


```
 save(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_112}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_113}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يقوم بحفظ بكسلات ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_114}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | بكسلات CMYK معروضة كقيم صحيحة 32‑بت. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_115}


```
 save_cmyk_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | مصفوفة بكسلات CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_116}


```
 save_pixels(rectangle, pixels) 
```

يحفظ البكسلات الداخلية الرئيسية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | البكسلات. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_117}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_118}


```
 save_to_stream(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_119}


```
 save_to_stream_with_options(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_121}


```
 save_with_options(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_122}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_123}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_124}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة التي يجب ضبطها. |
| update_colors | bool | إذا تم ضبطه على <c>true</c> سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. لاحظ أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات مطابقة في اللوحة. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_125}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_126}


```
 set_resolution(dpi_x, dpi_y) 
```

يضبط الدقة لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dpi_x | float | الدقة الأفقية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | الدقة العمودية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_127}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |
| argb_32_pixels | int[] | مصفوفة ألوان ARGB 32‑بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_129}


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
### This example shows how to load a WebP image from a file and save it to PNG. {#example_164}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
# تحميل صورة WebP من ملف.
with WebPImage(join(dir_, "test.webp")) as web_pimage:
	# حفظ كـ PNG
	# لاحظ أن الإطار النشط فقط سيتم تخزينه كـ PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
	web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to load a WebP image from a file stream and save it to PNG. {#example_165}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# تحميل صورة WebP من تدفق ملف.
with open(join(dir_, "test.webp"), "w+b") as stream:
	with WebPImage(stream) as web_pimage:
		# حفظ كـ PNG
		# لاحظ أن الإطار النشط فقط سيتم تخزينه كـ PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
		web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to create a WebP image from another raster image. {#example_166}
``` python
from os.path import join
from aspose.imaging import Graphics, Color
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions      

dir_: str = "c:\\temp"
# تحميل صورة PNG بحجم 100×100 بكسل.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# ملء الصورة بالكامل باللون الأحمر.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# إنشاء صورة WebP بناءً على صورة PNG.
	with WebPImage(png_image) as web_pimage:
		# احفظ إلى ملف WebP باستخدام الخيارات الافتراضية
		web_pimage.save(join(dir_, "output.webp"), WebPOptions())


```

### This example shows how to create a WebP image with the specified options from scratch. {#example_167}
``` python
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions
from os.path import join


dir_: str = "c:\\temp"
create_options = WebPOptions()
create_options.lossless = True
create_options.quality = 100.0

# أنشئ صورة WebP بحجم 100×100 بكسل.
with WebPImage(100, 100, create_options) as web_pimage:
	graphics = Graphics(web_pimage)
	# ملء الصورة بالكامل باللون الأحمر.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, web_pimage.bounds)
	# احفظ إلى ملف WebP
	web_pimage.save(join(dir_, "output.webp"))


```

### The following example loads a WEBP image and prints information about raw data format and alpha channel. {#example_168}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.webp import WebPImage, WebPFrameBlock

dir_ = "c:\\temp"
file_name = dir_ + "sample.webp"
with Image.load(file_name) as image:
	webp_image = aspycore.as_of(image, WebPImage)
	# إذا كان لإطار TIFF النشط قناة ألفا، فسيُعتبر أن صورة TIFF بأكملها تحتوي على قناة ألفا.
	print(f"ImageFile={file_name}, FileFormat={webp_image.raw_data_format}, HasAlpha={webp_image.has_alpha}")
	i: int = 0
	for frame in webp_image.blocks:
		if aspycore.is_assignable(frame, WebPFrameBlock):
			frame_block = aspycore.as_of(frame, WebPFrameBlock)
			print(f"Frame={i}, FileFormat={frame_block.raw_data_format}, HasAlpha={frame_block.has_alpha}")
			i += 1

# قد يبدو الإخراج هكذا:
# ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False


```

