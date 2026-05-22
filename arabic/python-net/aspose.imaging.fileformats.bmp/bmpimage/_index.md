---
title: "BmpImage فئة"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.bmp/bmpimage/
---

**Summary:** You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap<br/>            (DIB) files, facilitating efficient manipulation and processing of raster<br/>            images. Performing various operations on images, this API streamlines the<br/>            workflow, offering developers a reliable toolkit for working with BMP and<br/>            DIB formats in their software applications.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BmpImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BmpImage(path)](#BmpImage_path_1) | ابدأ باستخدام فئة BmpImage بسهولة مع هذا المُنشئ الذي<br/>            يهيئ نسخة جديدة. مثالي للمطورين الذين يرغبون في البدء و<br/>            تشغيل كائنات [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسرعة وكفاءة. |
| [BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2) | أنشئ نسخة جديدة من فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة باستخدام هذا المُنشئ,<br/>            مع تحديد المعلمات مثل path و bitsPerPixel و compression. مثالي للمطورين<br/>            الذين يرغبون في تهيئة كائنات BmpImage بسرعة وكفاءة، مع تحكم دقيق<br/>            في خصائص الصورة. |
| [BmpImage(raster_image)](#BmpImage_raster_image_3) | أنشئ نسخة جديدة من فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة<br/>            عن طريق تهيئتها باستخدام كائن RasterImage. مثالي للمطورين الذين يرغبون<br/>            في تحويل الصور النقطية الحالية إلى تنسيق BmpImage بسلاسة، مما يضمن<br/>            التوافق وسهولة التكامل في مشاريعهم. |
| [BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4) | ابدأ العمل مع فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسلاسة عن طريق إنشاء نسخة جديدة<br/>            باستخدام rasterImage مع المعلمات المحددة مثل bitsPerPixel و compression.<br/>            مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage،<br/>            مما يضمن المرونة والكفاءة في مشاريعهم. |
| [BmpImage(stream)](#BmpImage_stream_5) | ابدأ باستخدام فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة عن طريق تهيئة نسخة جديدة<br/>            باستخدام هذا المُنشئ، مع استعمال stream كمدخل. مثالي للمطورين الذين يبحثون<br/>            عن طريقة مريحة للعمل مع كائنات BmpImage من مصادر بيانات مختلفة،<br/>            مما يضمن المرونة وسهولة التكامل. |
| [BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6) | ابدأ العمل مع فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسلاسة عن طريق إنشاء<br/>            نسخة جديدة باستخدام stream، مع المعلمات المحددة مثل bitsPerPixel<br/>            و compression. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع<br/>            كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم. |
| [BmpImage(width, height)](#BmpImage_width_height_7) | ابدأ باستخدام فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة عن طريق إنشاء نسخة جديدة<br/>            مع معلمات العرض والارتفاع المحددة. مثالي للمطورين الذين يبحثون<br/>            عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة، مما يضمن<br/>            المرونة وسهولة التكامل في مشاريعهم. |
| [BmpImage(width, height, bits_per_pixel, palette)](#BmpImage_width_height_bits_per_pixel_palette_8) | ابدأ باستخدام فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسلاسة عن طريق تهيئة نسخة جديدة<br/>            مع معلمات مثل العرض، الارتفاع، عمق البت، واللوحة. مثالي للمطورين<br/>            الذين يبحثون عن طريقة مباشرة لإنشاء كائنات BmpImage بأبعاد مخصصة<br/>            وتكوينات لونية، مما يضمن المرونة والكفاءة في مشاريعهم. |
| [BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution)](#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9) | أنشئ نسخة جديدة من فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة باستخدام هذا المُنشئ,<br/>            مع تحديد المعلمات مثل العرض، الارتفاع، bitsPerPixel، واللوحة. مثالي للمطورين<br/>            الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة<br/>            وتكوينات لونية، مما يضمن المرونة وسهولة التكامل في مشاريعهم. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تعديل لوحة الألوان تلقائيًا. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| [bitmap_info_header](#bitmap_info_header1) | [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | r | احصل بسرعة على التفاصيل الأساسية حول صورة bitmap الخاصة بك باستخدام هذه الدالة البسيطة.<br/>            مثالي للمطورين الذين يحتاجون إلى استرجاع معلومات الرأس لصورهم. |
| [bits_per_pixel](#bits_per_pixel2) | int | r | الوصول بسهولة إلى عدد البتات لكل بكسل في الصورة باستخدام هذه الخاصية.<br/>            مثالي للمطورين الذين يبحثون عن معلومات سريعة حول جودة الصورة وعمقها. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود الكائن. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [compression](#compression3) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r | استرجع نوع الضغط المستخدم للصورة بسهولة باستخدام هذه الخاصية.<br/>            مثالي للمطورين الذين يحتاجون إلى الوصول السريع إلى معلومات حول ضغط الصورة. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | يحصل على حاوية [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | يحصل على تدفق بيانات الكائن. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن كائن Exif. |
| [file_format](#file_format4) | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية الصديقة للمستخدم.<br/>            مثالي للمطورين الذين يسعون إلى الوصول السريع إلى معلومات حول تنسيق الملف. |
| has_alpha | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على قناة ألفا. |
| has_background_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparent_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) يحتوي على لون شفاف. |
| [height](#height5) | int | r | استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين<br/>            الذين يحتاجون إلى الوصول السريع إلى معلومات حول أبعاد الصورة. |
| [horizontal_resolution](#horizontal_resolution6) | float | r/w | تتيح لك هذه الخاصية بسهولة الحصول على أو تعيين الدقة الأفقية،<br/>            المقاسة بوحدات البكسل لكل بوصة، لكائن [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). مثالي لـ<br/>            المطورين الذين يحتاجون إلى تحكم دقيق في دقة الصورة لتطبيقاتهم. |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | يحصل أو يعيّن مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتاً حالياً. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | يحصل على بيانات التعريف الخاصة بالصورة. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| premultiply_components | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | يحصل أو يضبط محول الألوان المخصص |
| [raw_data_format](#raw_data_format7) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | احصل بسهولة على تنسيق بياناتك الخام باستخدام هذه الدالة الصديقة للمستخدم.<br/>            مثالي للمطورين الذين يرغبون في الوصول السريع إلى معلومات حيوية حول تنسيق بياناتهم. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | يحصل أو يضبط محول الألوان المفهرسة |
| [raw_line_size](#raw_line_size8) | int | r | الوصول السريع إلى حجم كل سطر خام بالبايت باستخدام هذه الخاصية البسيطة.<br/>            مثالي للمطورين الذين يحتاجون إلى التعامل بكفاءة مع بيانات الصورة الخام. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | يحصل على حجم الكائن. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل على لون شفافية الصورة. |
| update_xmp_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| use_raw_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [vertical_resolution](#vertical_resolution9) | float | r/w | استرجع أو عيّن بسهولة الدقة العمودية، المقاسة بوحدات البكسل لكل بوصة،<br/>            لهذا الكائن [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) باستخدام هذه الخاصية. مثالي للمطورين الذين يتطلبون<br/>            تحكمًا دقيقًا في دقة الصورة في تطبيقاتهم. |
| [width](#width10) | int | r | الوصول إلى عرض الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين<br/>            الذين يبحثون عن معلومات سريعة حول أبعاد الصورة. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
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
| [create(files)](#create_files_19) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | ينشئ مثيلًا من [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) من مصفوفة البكسل المقدمة.<br/>            <br/>            يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل.<br/>            لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص. |
| [create(images)](#create_images_23) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(images, dispose_images)](#create_images_dispose_images_24) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | ينشئ خيارات الإنشاء المتعددة الصفحات المحددة. |
| [create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26) | ابدأ بسهولة باستخدام فئة BmpImage مع هذا المُنشئ، مما يبسط<br/>            عملية إنشاء نسخة جديدة. مثالي للمطورين الذين يبحثون عن<br/>            طريقة سريعة وفعّالة لإدراج كائنات [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) في مشاريعهم. |
| [create_from_files(files)](#create_from_files_files_27) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_image(raster_image)](#create_from_image_raster_image_29) | ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30) | ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_images(images)](#create_from_images_images_31) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34) | ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_35) | قص الصورة مع إزاحات. |
| [crop(rectangle)](#crop_rectangle_36) | قص الصورة. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_37) | يُجري تمويهًا على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_38) | يُجري تمويهًا على الصورة الحالية. |
| [embed_digital_signature(password)](#embed_digital_signature_password_39) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التستغنوجرافيا. |
| [filter(rectangle, options)](#filter_rectangle_options_40) | يفلتر المستطيل المحدد. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_41) | يحصل على بكسل صورة 32-بت ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_42) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_43) | استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة البسيطة.<br/>            مثالي للمطورين الذين يسعون إلى الوصول السريع إلى إعدادات أو تكوينات الصورة الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_44) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_46) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_47) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_48) | يحصل على تنسيق الملف. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_49) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_50) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_51) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_52) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [get_original_options()](#get_original_options__53) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_54) | يحصل على بكسل صورة. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_55) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_56) | يحصل على عرض نسبي. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_57) | يحوّل إلى aps. |
| [get_skew_angle()](#get_skew_angle__58) | يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح. |
| grayscale() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_59) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |
| [load(file_path)](#load_file_path_60) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(file_path, load_options)](#load_file_path_load_options_61) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(stream)](#load_stream_62) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_63) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_64) | يحمّل بكسلات ARGB 32‑بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_65) | يحمّل بكسلات ARGB 64‑بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_66) | يحمّل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_67) | يحمّل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68) | يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69) | يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_70) | يحمّل بكسلات جزئيًا حسب الحزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_71) | يحمّل بكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72) | يحمّل بيانات خام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73) | يحمّل بيانات خام. |
| [load_stream(stream)](#load_stream_stream_74) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_75) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_76) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| normalize_angle() | يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) . |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_77) | يضبط الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من الانحراف في المسح.<br/>            تستخدم هذه الطريقة أساليب [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | يُعَدِّل مدرج الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_78) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_79) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| remove_metadata() | يزيل بيانات التعريف لهذه الصورة عن طريق تعيين قيمة [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) إلى **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_80) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_81) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_82) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_83) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_84) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_85) | يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_86) | يقوم بتغيير حجم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_87) | يقوم بتغيير حجم الصورة. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_88) | يقوم بتغيير حجم الصورة. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_89) | يقوم بتغيير حجم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [rotate(angle)](#rotate_angle_98) | تدوير الصورة حول المركز. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | تدوير الصورة حول المركز. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يقوم بحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_101) | يقوم بحفظ الصورة إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_102) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_103) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_104) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_105) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_106) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_107) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_108) | يقوم بحفظ بكسلات ARGB 32‑بت. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_109) | يقوم بحفظ البكسلات. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_110) | يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_111) | يقوم بحفظ البكسلات (طريقة خاصة بالتنسيق). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_112) | يحفظ البيانات الخام. |
| [save_to_stream(stream)](#save_to_stream_stream_113) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_114) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_116) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_117) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_118) | يضبط بكسل صورة 32-بت ARGB للموقع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_119) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_120) | يضبط بكسل صورة للموقع المحدد. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_121) | قم بضبط دقة الـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) الخاصة بك بسهولة باستخدام هذه<br/>            الطريقة الصديقة للمستخدم. مثالي للمطورين الذين يسعون إلى تحكم دقيق في<br/>            دقة الصورة في تطبيقاتهم. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_122) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_124) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |


### Constructor: BmpImage(path) {#BmpImage_path_1}


```
 BmpImage(path) 
```

ابدأ باستخدام فئة BmpImage بسهولة مع هذا المُنشئ الذي<br/>            يهيئ نسخة جديدة. مثالي للمطورين الذين يرغبون في البدء و<br/>            تشغيل كائنات [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسرعة وكفاءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار لتحميل الصورة منه وتهيئة بيانات البكسل ولوحة الألوان. |


**See also:**

**[Example # 1](#example_77)**: The example shows how to load a BmpImage from a file.


### Constructor: BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2}


```
 BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

أنشئ نسخة جديدة من فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة باستخدام هذا المُنشئ,<br/>            مع تحديد المعلمات مثل path و bitsPerPixel و compression. مثالي للمطورين<br/>            الذين يرغبون في تهيئة كائنات BmpImage بسرعة وكفاءة، مع تحكم دقيق<br/>            في خصائص الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار لتحميل الصورة منه وتهيئة بيانات البكسل ولوحة الألوان. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |


**See also:**

**[Example # 1](#example_78)**: The example shows how to load a BmpImage from a file with the specified bit d...


### Constructor: BmpImage(raster_image) {#BmpImage_raster_image_3}


```
 BmpImage(raster_image) 
```

أنشئ نسخة جديدة من فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة<br/>            عن طريق تهيئتها باستخدام كائن RasterImage. مثالي للمطورين الذين يرغبون<br/>            في تحويل الصور النقطية الحالية إلى تنسيق BmpImage بسلاسة، مما يضمن<br/>            التوافق وسهولة التكامل في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة لتهيئة بيانات البكسل ولوحة الألوان معها. |


**See also:**

**[Example # 1](#example_81)**: The example shows how to load a BmpImage from another instance of RasterImage.


### Constructor: BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4}


```
 BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

ابدأ العمل مع فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسلاسة عن طريق إنشاء نسخة جديدة<br/>            باستخدام rasterImage مع المعلمات المحددة مثل bitsPerPixel و compression.<br/>            مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage،<br/>            مما يضمن المرونة والكفاءة في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة لتهيئة بيانات البكسل ولوحة الألوان معها. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |


**See also:**

**[Example # 1](#example_82)**: The example shows how to load a BmpImage from another instance of RasterImage...


### Constructor: BmpImage(stream) {#BmpImage_stream_5}


```
 BmpImage(stream) 
```

ابدأ باستخدام فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة عن طريق تهيئة نسخة جديدة<br/>            باستخدام هذا المُنشئ، مع استعمال stream كمدخل. مثالي للمطورين الذين يبحثون<br/>            عن طريقة مريحة للعمل مع كائنات BmpImage من مصادر بيانات مختلفة،<br/>            مما يضمن المرونة وسهولة التكامل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق التحميل للصور منه وتهيئة بيانات البكسل ولوحة الألوان. |


**See also:**

**[Example # 1](#example_79)**: The example shows how to load a BmpImage from a file stream.


### Constructor: BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6}


```
 BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

ابدأ العمل مع فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسلاسة عن طريق إنشاء<br/>            نسخة جديدة باستخدام stream، مع المعلمات المحددة مثل bitsPerPixel<br/>            و compression. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع<br/>            كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق التحميل للصور منه وتهيئة بيانات البكسل ولوحة الألوان. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |


**See also:**

**[Example # 1](#example_80)**: The example shows how to load a BmpImage from a file stream with the specifie...


### Constructor: BmpImage(width, height) {#BmpImage_width_height_7}


```
 BmpImage(width, height) 
```

ابدأ باستخدام فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة عن طريق إنشاء نسخة جديدة<br/>            مع معلمات العرض والارتفاع المحددة. مثالي للمطورين الذين يبحثون<br/>            عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة، مما يضمن<br/>            المرونة وسهولة التكامل في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |


**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_83)**: The example shows how to create a BmpImage of the specified size.


### Constructor: BmpImage(width, height, bits_per_pixel, palette) {#BmpImage_width_height_bits_per_pixel_palette_8}


```
 BmpImage(width, height, bits_per_pixel, palette) 
```

ابدأ باستخدام فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسلاسة عن طريق تهيئة نسخة جديدة<br/>            مع معلمات مثل العرض، الارتفاع، عمق البت، واللوحة. مثالي للمطورين<br/>            الذين يبحثون عن طريقة مباشرة لإنشاء كائنات BmpImage بأبعاد مخصصة<br/>            وتكوينات لونية، مما يضمن المرونة والكفاءة في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان. |


**See also:**

**[Example # 1](#example_84)**: The example shows how to create a BmpImage of the specified size with the spe...


### Constructor: BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) {#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9}


```
 BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) 
```

أنشئ نسخة جديدة من فئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) بسهولة باستخدام هذا المُنشئ,<br/>            مع تحديد المعلمات مثل العرض، الارتفاع، bitsPerPixel، واللوحة. مثالي للمطورين<br/>            الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة<br/>            وتكوينات لونية، مما يضمن المرونة وسهولة التكامل في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة الألوان. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |


**See also:**

**[Example # 1](#example_85)**: The example shows how to create a BmpImage using various options.


### Property: bitmap_info_header {#bitmap_info_header1}

احصل بسرعة على التفاصيل الأساسية حول صورة bitmap الخاصة بك باستخدام هذه الدالة البسيطة.<br/>            مثالي للمطورين الذين يحتاجون إلى استرجاع معلومات الرأس لصورهم.

**See also:**

**[Example # 1](#example_89)**: The following example gets the information from the BMP header and prints it ...


### Property: bits_per_pixel {#bits_per_pixel2}

الوصول بسهولة إلى عدد البتات لكل بكسل في الصورة باستخدام هذه الخاصية.<br/>            مثالي للمطورين الذين يبحثون عن معلومات سريعة حول جودة الصورة وعمقها.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: compression {#compression3}

استرجع نوع الضغط المستخدم للصورة بسهولة باستخدام هذه الخاصية.<br/>            مثالي للمطورين الذين يحتاجون إلى الوصول السريع إلى معلومات حول ضغط الصورة.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: file_format {#file_format4}

استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية الصديقة للمستخدم.<br/>            مثالي للمطورين الذين يسعون إلى الوصول السريع إلى معلومات حول تنسيق الملف.

**See also:**

**[Example # 1](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: height {#height5}

استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين<br/>            الذين يحتاجون إلى الوصول السريع إلى معلومات حول أبعاد الصورة.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: horizontal_resolution {#horizontal_resolution6}

تتيح لك هذه الخاصية بسهولة الحصول على أو تعيين الدقة الأفقية،<br/>            المقاسة بوحدات البكسل لكل بوصة، لكائن [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). مثالي لـ<br/>            المطورين الذين يحتاجون إلى تحكم دقيق في دقة الصورة لتطبيقاتهم.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: raw_data_format {#raw_data_format7}

احصل بسهولة على تنسيق بياناتك الخام باستخدام هذه الدالة الصديقة للمستخدم.<br/>            مثالي للمطورين الذين يرغبون في الوصول السريع إلى معلومات حيوية حول تنسيق بياناتهم.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: raw_line_size {#raw_line_size8}

الوصول السريع إلى حجم كل سطر خام بالبايت باستخدام هذه الخاصية البسيطة.<br/>            مثالي للمطورين الذين يحتاجون إلى التعامل بكفاءة مع بيانات الصورة الخام.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: vertical_resolution {#vertical_resolution9}

استرجع أو عيّن بسهولة الدقة العمودية، المقاسة بوحدات البكسل لكل بوصة،<br/>            لهذا الكائن [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) باستخدام هذه الخاصية. مثالي للمطورين الذين يتطلبون<br/>            تحكمًا دقيقًا في دقة الصورة في تطبيقاتهم.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: width {#width10}

الوصول إلى عرض الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين<br/>            الذين يبحثون عن معلومات سريعة حول أبعاد الصورة.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


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


### Method: create(files)  [static] {#create_files_19}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


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


### Method: create(images)  [static] {#create_images_23}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


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


### Method: create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26}


```
 create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

ابدأ بسهولة باستخدام فئة BmpImage مع هذا المُنشئ، مما يبسط<br/>            عملية إنشاء نسخة جديدة. مثالي للمطورين الذين يبحثون عن<br/>            طريقة سريعة وفعّالة لإدراج كائنات [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) في مشاريعهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار لتحميل الصورة منه وتهيئة بيانات البكسل ولوحة الألوان. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_29}


```
 create_from_image(raster_image) 
```

ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة لتهيئة بيانات البكسل ولوحة الألوان معها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30}


```
 create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة لتهيئة بيانات البكسل ولوحة الألوان معها. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


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

ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق التحميل للصور منه وتهيئة بيانات البكسل ولوحة الألوان. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34}


```
 create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

ينشئ نسخة جديدة من الفئة [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق التحميل للصور منه وتهيئة بيانات البكسل ولوحة الألوان. |
| bits_per_pixel | int | عدد البتات لكل بكسل. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | ضغط الاستخدام. |
| horizontal_resolution | float | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |
| vertical_resolution | float | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المدخلة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_35}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

قص الصورة مع إزاحات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| left_shift | int | الإزاحة اليسرى. |
| right_shift | int | الإزاحة اليمنى. |
| top_shift | int | الإزاحة العلوية. |
| bottom_shift | int | الإزاحة السفلية. |

### Method: crop(rectangle) {#crop_rectangle_36}


```
 crop(rectangle) 
```

قص الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_37}


```
 dither(dithering_method, bits_count) 
```

يُجري تمويهًا على الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_38}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_39}


```
 embed_digital_signature(password) 
```

إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التستغنوجرافيا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور المستخدمة لإنشاء بيانات التوقيع الرقمي |

### Method: filter(rectangle, options) {#filter_rectangle_options_40}


```
 filter(rectangle, options) 
```

يفلتر المستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | الخيارات. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_41}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_42}


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


### Method: get_default_options(args) {#get_default_options_args_43}


```
 get_default_options(args) 
```

استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة البسيطة.<br/>            مثالي للمطورين الذين يسعون إلى الوصول السريع إلى إعدادات أو تكوينات الصورة الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| args | System.Object | المعلمات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات الافتراضية |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_44}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_46}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_47}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_48}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_49}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_50}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_51}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_52}


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


### Method: get_original_options() {#get_original_options__53}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستندة إلى إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_54}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_55}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_56}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_57}


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


### Method: get_skew_angle() {#get_skew_angle__58}


```
 get_skew_angle() 
```

يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح.

**Returns**

| نوع | الوصف |
| :- | :- |
| float | زاوية الانحراف، بالدرجات. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_59}


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


### Method: load(file_path)  [static] {#load_file_path_60}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_61}


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


### Method: load(stream)  [static] {#load_stream_62}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_63}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_64}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_65}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_66}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_67}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32‑بت جزئيًا (حسب الكتل).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لتحميل البكسلات منه. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | محمل بكسلات ARGB 64-بت. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_70}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يحمّل بكسلات جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_71}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_74}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_75}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_76}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_77}


```
 normalize_angle(resize_proportionally, background_color) 
```

يضبط الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من الانحراف في المسح.<br/>            تستخدم هذه الطريقة أساليب [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_78}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_79}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_80}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_81}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_82}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_83}


```
 replace_non_transparent_colors(new_color) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون الجديد لاستبدال الألوان غير الشفافة به. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_84}


```
 replace_non_transparent_colors(new_color_argb) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_85}


```
 resize(new_width, new_height) 
```

يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_86}


```
 resize(new_width, new_height, resize_type) 
```

يقوم بتغيير حجم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_87}


```
 resize(new_width, new_height, settings) 
```

يقوم بتغيير حجم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات التحجيم. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_88}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_89}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_90}


```
 resize_height_proportionally(new_height) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_91}


```
 resize_height_proportionally(new_height, resize_type) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_92}


```
 resize_height_proportionally(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_93}


```
 resize_height_proportionally_settings(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | نوع دوران الانعكاس. |

### Method: save(file_path) {#save_file_path_101}


```
 save(file_path) 
```

يقوم بحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ الصورة فيه. |

### Method: save(file_path, options) {#save_file_path_options_102}


```
 save(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_103}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_104}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_105}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_106}


```
 save(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_107}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_108}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يقوم بحفظ بكسلات ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_109}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | بكسلات CMYK معروضة كقيم صحيحة 32‑بت. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_110}


```
 save_cmyk_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | مصفوفة بكسلات CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_111}


```
 save_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات (طريقة خاصة بالتنسيق).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | مصفوفة بكسلات ARGB 32‑بت. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_112}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_113}


```
 save_to_stream(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_114}


```
 save_to_stream_with_options(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_116}


```
 save_with_options(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_117}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_118}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_119}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة التي يجب ضبطها. |
| update_colors | bool | إذا تم ضبطه على <c>true</c> سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. لاحظ أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات مطابقة في اللوحة. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_120}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_121}


```
 set_resolution(dpi_x, dpi_y) 
```

قم بضبط دقة الـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) الخاصة بك بسهولة باستخدام هذه<br/>            الطريقة الصديقة للمستخدم. مثالي للمطورين الذين يسعون إلى تحكم دقيق في<br/>            دقة الصورة في تطبيقاتهم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dpi_x | float | الدقة الأفقية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | الدقة العمودية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_122}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |
| argb_32_pixels | int[] | مصفوفة ألوان ARGB 32‑بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_124}


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
### The following example shows how to create a BMP image of the specified size. {#example_18}
``` python
from aspose.imaging import Color
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join

directory = "c:\\temp\\"

# إنشاء صورة BMP بحجم 100 × 100 بكسل.
with BmpImage(100, 100) as bmpImage:
	# املأ الصورة بتدرج خطي بسيط من الأحمر إلى الأسود.
	width = bmpImage.width
	height = bmpImage.height
	for y in range(height):
		for x in range(width):
			hue = (255 * x) // width
			bmpImage.set_pixel(x, y, Color.from_argb(255, hue, 0, 0))

	with open(path_join(directory, "output.bmp"), "w+b") as stream:
		bmpImage.save(stream)


```

### The following example gets the general information about the image including pixel format, image size, resolution, compression etc. {#example_19}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join


with Image.load(r"c:\temp\sample.bmp") as image:
	bmpImage = as_of(image, BmpImage)    

	print("The pixel format:", bmpImage.raw_data_format)
	print("The raw line size in bytes:", bmpImage.raw_line_size)
	print("The bitmap compression:", bmpImage.compression)
	print("The bitmap width", bmpImage.width)
	print("The bitmap height", bmpImage.height)
	print("The number of bits per pixel", bmpImage.bits_per_pixel)

	hres = bmpImage.horizontal_resolution
	vres = bmpImage.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", hres)
	print("The vertical resolution, in pixels per inch:", vres)

	if hres != 96.0 or vres != 96.0:
		# قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
		print("Set resolution values to 96 dpi")
		bmpImage.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch: {0}", bmpImage.horizontal_resolution);
		print("The vertical resolution, in pixels per inch: {0}", bmpImage.vertical_resolution);

	#قد يبدو الإخراج هكذا:
	#تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
	#حجم السطر الخام بالبايت: 1500
	#ضغط البت ماب: Rgb
	#عرض البت ماب: 500
	#ارتفاع البت ماب: 375
	#عدد البتات لكل بكسل: 24
	#الدقة الأفقية، بوحدات البكسل لكل بوصة: 0
	#الدقة العمودية، بوحدات البكسل لكل بوصة: 0
	#تعيين قيم الدقة إلى 96 نقطة في البوصة
	#الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.012
	#الدقة العمودية، بوحدات البكسل لكل بوصة: 96.012


```

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# إنشاء صورة BMP بحجم 100 × 100 بكسل.
with BmpImage(100, 100) as bmpImage:
	# التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# املأ الصورة بالكامل بفرشاة التدرج الخطي.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملونة باللوحة
	# تقريبًا لا يمكن تمييزها بصريًا عن صورة BMP بدون لوحة ألوان
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# لوحة ألوان 8‑بت تحتوي على حد أقصى 256 لونًا.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# المخرجات تبدو هكذا:
# حجم الصورة مع اللوحة هو 11078 بايت.
# حجم الصورة بدون لوحة هو 40054 بايت.

```

### The example shows how to load a BmpImage from a file. {#example_77}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# تحميل صورة BMP من ملف.
# سيتم تحويل بكسلات المصدر إلى تنسيق 32-ببت إذا لزم الأمر.
with BmpImage(os.path.join(directory, "sample.bmp")) as bmp_image:
	# إجراء بعض معالجة الصور.
	# حفظ إلى ملف BMP آخر.
	bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file with the specified bit depth and resolution. {#example_78}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# تحميل صورة BMP من ملف.
# سيتم تحويل بكسلات المصدر إلى تنسيق 24-ببت إذا لزم الأمر.
# سيتم تعيين الدقة إلى 96 نقطة في البوصة.
with BmpImage(os.path.join(directory, "sample.bmp"), 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	# إجراء بعض معالجة الصور.
	# حفظ إلى ملف BMP آخر.
	bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))


```

### The example shows how to load a BmpImage from a file stream. {#example_79}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# تحميل صورة BMP من تدفق ملف.
# سيتم تحويل بكسلات المصدر إلى تنسيق 32-ببت إذا لزم الأمر.
with open(os.path.join(directory, "sample.bmp"), "rb+") as stream:
	with BmpImage(stream) as bmp_image:
		# إجراء بعض معالجة الصور.
		# حفظ إلى ملف BMP آخر.
		bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file stream with the specified bit depth and resolution. {#example_80}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# تحميل صورة BMP من تدفق ملف.
# سيتم تحويل بكسلات المصدر إلى تنسيق 24-ببت إذا لزم الأمر.
# سيتم تعيين الدقة إلى 96 نقطة في البوصة.
with open(os.path.join(directory, "sample.bmp"), "rb") as stream:
	with BmpImage(stream, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
		# إجراء بعض معالجة الصور.
		# حفظ إلى ملف BMP آخر.
		bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))

```

### The example shows how to load a BmpImage from another instance of RasterImage. {#example_81}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging import Image, RasterImage, Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os
import aspose.pycore as aspycore

directory = r"c:\temp"

# إنشاء صورة PNG جديدة.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# املأ صورة PNG بالكامل باللون الأحمر.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# إنشاء صورة BMP بناءً على صورة PNG.
		# سيتم تحويل بكسلات المصدر إلى تنسيق 32-ببت إذا لزم الأمر.
		with BmpImage(raster_image) as bmp_image:
			# حفظ إلى ملف BMP
			bmp_image.save(os.path.join(directory, "output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from another instance of RasterImage with the specified bit depth and compression. {#example_82}
``` python

from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging import Image, RasterImage, Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os
import aspose.pycore as aspycore

directory = r"c:\temp"

# إنشاء صورة PNG جديدة.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# املأ صورة PNG بالكامل باللون الأحمر.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# إنشاء صورة BMP بناءً على صورة PNG.
		# سيتم تحويل بكسلات المصدر إلى تنسيق 24-ببت إذا لزم الأمر.
		# سيتم تعيين الدقة إلى 96 نقطة في البوصة.
		with BmpImage(raster_image, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
			# حفظ إلى ملف BMP
			bmp_image.save(os.path.join(directory, "output.24bpp.96dpi.bmp"))

```

### The example shows how to create a BmpImage of the specified size. {#example_83}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

# إنشاء صورة BMP بدقة 32‑bpp بحجم 100 × 100 بكسل.
with BmpImage(100, 100) as bmp_image:
	# ملء الصورة بالكامل باللون الأحمر.
	Graphics gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	# حفظ إلى ملف BMP
	bmp_image.save(os.path.join(directory, "output.bmp"))


```

### The example shows how to create a BmpImage of the specified size with the specified palette. {#example_84}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color, ColorPalette, Rectangle
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

paletterColors = [Color.red, Color.green]

# إنشاء لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
palette = ColorPalette.create_with_colors(paletterColors)

# إنشاء صورة BMP أحادية اللون بدقة 1-ببت بحجم 100 × 100 بكسل.
with BmpImage(100, 100, 1, palette) as bmp_image:
	gr = Graphics(bmp_image)

	# ملء النصف العلوي من الصورة باللون الأحمر.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# ملء النصف السفلي من الصورة باللون الأخضر.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# حفظ إلى BMP
	bmp_image.save(os.path.join(directory, "output.monochrome.bmp"))


```

### The example shows how to create a BmpImage using various options. {#example_85}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging import Graphics, Color, ColorPalette, Rectangle
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

paletterColors = [Color.red, Color.green]

# إنشاء لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
palette = ColorPalette.create_with_colors(paletterColors)

# إنشاء صورة BMP أحادية اللون بدقة 1-ببت بحجم 100 × 100 بكسل.
with BmpImage(100, 100, 1, palette, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	gr = Graphics(bmp_image)

	# ملء النصف العلوي من الصورة باللون الأحمر.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# ملء النصف السفلي من الصورة باللون الأخضر.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# حفظ إلى BMP
	bmp_image.save(os.path.join(directory, "output.monochrome.96dpi.bmp"))


```

### The following example shows how to extract information about raw data format and alpha channel from a BMP image. {#example_86}
``` python
from aspose.imaging.fileformats.bmp import BmpImage

# إنشاء صورة BMP بدقة 32‑bpp بحجم 100 × 100 بكسل.
with BmpImage(100, 100, 32, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))


# إنشاء صورة BMP بدقة 24‑bpp بحجم 100 × 100 بكسل.
with BmpImage(100, 100, 24, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))

# عمومًا، لا يدعم BMP قناة ألفا لذا سيظهر الناتج هكذا:
# FileFormat = BMP, RawDataFormat = Rgb32Bpp, القنوات المستخدمة: 8,8,8,8, HasAlpha = False
# FileFormat = BMP, RawDataFormat = Rgb24Bpp, القنوات المستخدمة: 8,8,8, HasAlpha = False

```

### The following example shows how the bitmap compression affects the output image size. {#example_87}
``` python

from aspose.imaging import Color, ColorPalette, Graphics
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.extensions import StreamExtensions as strm_ext

compressions = (BitmapCompression.RGB, BitmapCompression.RLE8)

paletterColors = (Color.red, Color.green)

# إنشاء لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
palette = ColorPalette.create_with_colors(paletterColors)

for compression in compressions:
	# إنشاء صورة BMP بدقة 8-ببت بحجم 100 × 100 بكسل.
	with BmpImage(100, 100, 8, palette, compression, 0.0, 0.0) as bmp_image:
		gr = Graphics(bmp_image)
		# ملء الصورة بالكامل باللون الأحمر.
		red_brush = SolidBrush(Color.red)
		gr.fill_rectangle(red_brush, bmp_image.bounds)
		# حفظ الصورة إلى تدفق الذاكرة للحصول على حجم الصورة الناتج.
		with strm_ext.create_memory_stream() as stream:
			bmp_image.save(stream)
			print("---------------------------------------------")
			print("The compression =", bmp_image.compression.name)
			print("The number of bits per pixel =", bmp_image.bits_per_pixel)
			print(f"The image dimensions = {bmp_image.width} x {bmp_image.height}")
			print("The raw line size =", bmp_image.raw_line_size)
			print("The output size in bytes =", stream.tell())

# المخرجات تبدو هكذا:
# ---------------------------------------------
# الضغط = RGB
# عدد البتات لكل بكسل = 8
# أبعاد الصورة =100 × 100
# حجم السطر الخام = 100
# حجم الإخراج بالبايت = 1178
# ---------------------------------------------
# الضغط = RLE8
# عدد البتات لكل بكسل = 8
# أبعاد الصورة =100 × 100
# حجم السطر الخام = 100
# حجم الإخراج بالبايت = 856

```

### The following example shows how to set horizontal/vertical resolution of a BMP image. {#example_88}
``` python

import os
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage

directory = r"c:\temp"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	bmp_image = aspycore.as_of(image, BmpImage)
	# احصل على الدقة الأفقية والعمودية لصورة BmpImage
	horizontal_resolution = bmp_image.horizontal_resolution
	vertical_resolution = bmp_image.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", horizontal_resolution)
	print("The vertical resolution, in pixels per inch:", vertical_resolution)

	if (horizontal_resolution != 96.0 || vertical_resolution != 96.0)
	{
		# استخدم طريقة set_resolution لتحديث قيمتي الدقة معًا في استدعاء واحد.
		print("Set resolution values to 96 dpi")
		bmp_image.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch:", bmp_image.horizontal_resolution);
		print("The vertical resolution, in pixels per inch:", bmp_image.vertical_resolution);
	}

	# قد يبدو الإخراج هكذا:
	# الدقة الأفقية، بوحدات البكسل لكل بوصة: 0
	# الدقة العمودية، بوحدات البكسل لكل بوصة: 0
	# تعيين قيم الدقة إلى 96 نقطة في البوصة
	# الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.0
	# الدقة العمودية، بوحدة بكسل لكل بوصة: 96.0

```

### The following example gets the information from the BMP header and prints it to the console. {#example_89}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage

with Image.load(r"c:\temp\sample.bmp") as image:
	bmp_image = aspycore.as_of(image, BmpImage)
	header = bmp_image.bitmap_info_header

	print("The number of palette colors that are required for displaying the bitmap:", header.bitmap_colors_important)
	print("The number of palette colors used in the bitmap:", header.bitmap_colors_used)
	print("The bitmap compression:", header.bitmap_compression)
	print("The bitmap height:", header.bitmap_height)
	print("The bitmap width:", header.bitmap_width)
	print("The bitmap raw data size in bytes:", header.bitmap_image_size)
	print("The number of planes:", header.bitmap_planes)
	print("The horizontal resolution of the bitmap, in pixels-per-meter:", header.bitmap_x_pels_per_meter)
	print("The vertical resolution of the bitmap, in pixels-per-meter:", header.bitmap_y_pels_per_meter)
	print("The number of bits per pixel:", header.bits_per_pixel)
	print("The extra bits masks:", header.extra_bit_masks)
	print("The header size in bytes:", header.header_size)

#قد يبدو الإخراج هكذا:
#عدد ألوان لوحة الألوان المطلوبة لعرض الصورة النقطية: 0
#عدد ألوان لوحة الألوان المستخدمة في الصورة النقطية: 0
#ضغط الصورة النقطية: 0
#ارتفاع البت ماب: 375
#عرض البت ماب: 500
#حجم البيانات الخام للصورة النقطية بالبايت: 562500
#عدد المستويات: 1
#الدقة الأفقية للصورة النقطية، بوحدة بكسل لكل متر: 0
#الدقة العمودية للصورة النقطية، بوحدة بكسل لكل متر: 0
#عدد البتات لكل بكسل: 24
#قناع البتات الإضافية: 
#حجم الرأس بالبايت: 40

```

### Compress BMP image using DXT1 compression algorithm. {#example_207}
``` python
#cxFor:aspose.imaging.imageoptions.BmpOptions.compression

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression

with Image.load("Tiger.bmp") as image:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.DXT1
	image.save("CompressedTiger.bmp", bmp_options)

```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

