---
title: "فئة RasterImage"
type: docs
weight: 7060
url: /ar/python-net/aspose.imaging/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RasterImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تعديل لوحة الألوان تلقائيًا. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| bits_per_pixel | int | r | يحصل على عدد البتات في الصورة لكل بكسل. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود الصورة. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | يحصل على حاوية [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | يحصل على تدفق بيانات الكائن. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | يحصل على قيمة تنسيق الملف |
| [has_alpha](#has_alpha1) | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على قناة ألفا. |
| has_background_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| has_transparent_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) يحتوي على لون شفاف. |
| height | int | r | يحصل على ارتفاع الصورة. |
| horizontal_resolution | float | r/w | يحصل أو يعيّن الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | يحصل على شفافية هذه الصورة. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | يحصل أو يعيّن مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| is_raw_data_available | bool | r | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | يحصل على بيانات التعريف الخاصة بالصورة. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [premultiply_components](#premultiply_components2) | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | يحصل أو يضبط محول الألوان المخصص |
| [raw_data_format](#raw_data_format3) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على تنسيق البيانات الخام. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| raw_fallback_index | int | r/w | يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | يحصل أو يضبط محول الألوان المفهرسة |
| raw_line_size | int | r | يحصل على حجم السطر الخام بالبايت. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | يحصل على حجم الصورة. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل على لون شفافية الصورة. |
| update_xmp_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| use_raw_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| vertical_resolution | float | r/w | يحصل أو يضبط الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | يحصل على عرض الصورة. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يعيّن بيانات Xmp. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | ضبط سطوع الصورة. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | تباين الصورة |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | تصحيح جاما لصورة. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | تصحيح جاما لصورة. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| auto_brightness_contrast() | تطبيع تلقائي متكيف للسطوع والتباين لكامل الصورة. |
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
| [create_from_files(files)](#create_from_files_files_26) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_images(images)](#create_from_images_images_28) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | قص الصورة مع إزاحات. |
| [crop(rectangle)](#crop_rectangle_31) | يقص المستطيل المحدد. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | يُجري تمويهًا على الصورة الحالية. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | يُجري تمويهًا على الصورة الحالية. |
| [embed_digital_signature(password)](#embed_digital_signature_password_34) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التستغنوجرافيا. |
| [filter(rectangle, options)](#filter_rectangle_options_35) | يفلتر المستطيل المحدد. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_36) | يحصل على بكسل صورة 32-بت ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_37) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [get_default_options(args)](#get_default_options_args_38) | يحصل على الخيارات الافتراضية. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_39) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_41) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_42) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_43) | يحصل على تنسيق الملف. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_44) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_45) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_46) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_modify_date(use_default)](#get_modify_date_use_default_47) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [get_original_options()](#get_original_options__48) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ. |
| [get_pixel(x, y)](#get_pixel_x_y_49) | يحصل على بكسل صورة. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_50) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_51) | يحصل على عرض نسبي. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_52) | يحوّل إلى aps. |
| [get_skew_angle()](#get_skew_angle__53) | يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح. |
| grayscale() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_54) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |
| [load(file_path)](#load_file_path_55) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(stream)](#load_stream_57) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_58) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | يحمّل بكسلات ARGB 32‑بت. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | يحمّل بكسلات ARGB 64‑بت. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | يحمّل بكسلات بتنسيق CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | يحمّل بكسلات بتنسيق CMYK.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | يحمّل بكسلات ARGB 32-بت جزئيًا عن طريق الحزم. |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64) | يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_65) | يحمّل بكسلات جزئيًا حسب الحزم. |
| [load_pixels(rectangle)](#load_pixels_rectangle_66) | يحمّل بكسلات. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67) | يحمّل بيانات خام. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68) | يحمّل بيانات خام. |
| [load_stream(stream)](#load_stream_stream_69) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_70) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_71) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| normalize_angle() | يُعَدِّل الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف.<br/>            تستخدم هذه الطريقة [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) . |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_72) | يضبط الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من الانحراف في المسح.<br/>            تستخدم هذه الطريقة أساليب [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | يُعَدِّل مدرج الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_73) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_74) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| remove_metadata() | يزيل بيانات التعريف لهذه الصورة عن طريق تعيين قيمة [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) إلى **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_75) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_76) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_77) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_78) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_79) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_80) | يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_81) | يقوم بتغيير حجم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_82) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_83) | يقوم بتغيير حجم الصورة. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_84) | يقوم بتغيير حجم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_85) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_86) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_87) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_88) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_89) | يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_90) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_91) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_92) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [rotate(angle)](#rotate_angle_93) | تدوير الصورة حول المركز. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_94) | تدوير الصورة حول المركز. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_95) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يقوم بحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_96) | يقوم بحفظ الصورة إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_97) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_98) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_99) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_100) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_101) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_102) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_103) | يقوم بحفظ بكسلات ARGB 32‑بت. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_104) | يقوم بحفظ البكسلات. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_105) | يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_106) | يقوم بحفظ البكسلات. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_107) | يحفظ البيانات الخام. |
| [save_to_stream(stream)](#save_to_stream_stream_108) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_109) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_111) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_112) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_113) | يضبط بكسل صورة 32-بت ARGB للموقع المحدد. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_114) | يضبط لوحة ألوان الصورة. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_115) | يضبط بكسل صورة للموقع المحدد. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_116) | يضبط الدقة لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_117) | يحاول تعيين مثيل _metadata_، إذا كان مثيل [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق النوع [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_119) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |


### Property: has_alpha {#has_alpha1}

يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على قناة ألفا.

**See also:**

**[Example # 1](#example_38)**: The following example loads raster images and prints information about raw da...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: premultiply_components {#premultiply_components2}

يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا.

**See also:**

**[Example # 1](#example_37)**: The following example creates a new raster image, saves the specified semi-tr...


### Property: raw_data_format {#raw_data_format3}

يحصل على تنسيق البيانات الخام.

**See also:**

**[Example # 1](#example_38)**: The following example loads raster images and prints information about raw da...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

ضبط سطوع الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| السطوع | int | قيمة السطوع. |


**See also:**

**[Example # 1](#example_57)**: The following example performs brightness correction of an image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

تباين الصورة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |


**See also:**

**[Example # 1](#example_58)**: The following example performs contrast correction of an image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

تصحيح جاما لصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| جاما | float | معامل جاما للقنوات الحمراء والخضراء والزرقاء |


**See also:**

**[Example # 1](#example_55)**: The following example performs gamma-correction of an image.


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


**See also:**

**[Example # 1](#example_56)**: The following example performs gamma-correction of an image applying differen...


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



**See also:**

**[Example # 1](#example_234)**: The example illustrates how to determine the probability (from 0% to 100%) th...


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


**See also:**

**[Example # 1](#example_53)**: The following example binarizes a raster image with Bradley's adaptive thresh...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحدّ | System.Byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |


**See also:**

**[Example # 1](#example_51)**: The following example binarizes a raster image with the predefined threshold....


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


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


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


**See also:**

**[Example # 1](#example_50)**: The following example crops a raster image. The cropping area is specified vi...


### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

يقص المستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |


**See also:**

**[Example # 1](#example_49)**: The following example crops a raster image. The cropping area is be specified...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

يُجري تمويهًا على الصورة الحالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | طريقة التمويه. |
| bits_count | int | عدد البتات النهائي للتدرج. |


**See also:**

**[Example # 1](#example_39)**: The following example loads a raster image and performs threshold and Floyd d...


### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_34}


```
 embed_digital_signature(password) 
```

إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التستغنوجرافيا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | string | كلمة المرور المستخدمة لإنشاء بيانات التوقيع الرقمي |


**See also:**

**[Example # 1](#example_232)**: The example shows how to embed digital signature based on provided password i...


### Method: filter(rectangle, options) {#filter_rectangle_options_35}


```
 filter(rectangle, options) 
```

يفلتر المستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | الخيارات. |


**See also:**

**[Example # 1](#example_59)**: The following example applies various types of filters to a raster image.


### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_36}


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



**See also:**

**[Example # 1](#example_36)**: The following example shows how image caching affects performance. In general...

**[Example # 2](#example_40)**: The following example loads a raster image and obtains the color of an arbitr...


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_37}


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


### Method: get_default_options(args) {#get_default_options_args_38}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_39}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للحصول على البكسلات. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل البكسل الجزئي. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_41}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_42}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_43}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_44}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_45}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_46}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_47}


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


### Method: get_original_options() {#get_original_options__48}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستندة إلى إعدادات الملف الأصلي. |


### Method: get_pixel(x, y) {#get_pixel_x_y_49}


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



**See also:**

**[Example # 1](#example_41)**: The following example loads a raster image and obtains the color of an arbitr...


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_50}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_51}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_52}


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


### Method: get_skew_angle() {#get_skew_angle__53}


```
 get_skew_angle() 
```

يحصل على زاوية الانحراف.<br/> هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف أثناء المسح.

**Returns**

| نوع | الوصف |
| :- | :- |
| float | زاوية الانحراف، بالدرجات. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_54}


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



**See also:**

**[Example # 1](#example_231)**: The example shows how to validate that the embedded digital signature matches...

**[Example # 2](#example_233)**: The example demonstrates how to verify that the embedded digital signature ma...


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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



**See also:**

**[Example # 1](#example_43)**: The following example shows how to load and process pixels of a raster image....


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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



**See also:**

**[Example # 1](#example_44)**: The following example shows how to load and process pixels of a raster image....


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 32-بت جزئيًا عن طريق الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | محمل بكسلات ARGB 32-بت. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | محمل بكسلات ARGB 64-بت. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_65}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

يحمّل بكسلات جزئيًا حسب الحزم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المطلوب. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | محمل البكسلات. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_66}


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



**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...

**[Example # 2](#example_45)**: The following example shows how to load and process pixels of a raster image....


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_69}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_70}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_71}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_72}


```
 normalize_angle(resize_proportionally, background_color) 
```

يضبط الزاوية.<br/>            هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من الانحراف في المسح.<br/>            تستخدم هذه الطريقة أساليب [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) و [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| resize_proportionally | bool | إذا تم تعيينه إلى <c>true</c> سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى سيبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الخلفية. |


**See also:**

**[Example # 1](#example_184)**: Skew is an artifact that might appear during document scanning process when t...


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_73}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_74}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_75}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_76}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_77}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_78}


```
 replace_non_transparent_colors(new_color) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون الجديد لاستبدال الألوان غير الشفافة به. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_79}


```
 replace_non_transparent_colors(new_color_argb) 
```

يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.<br/>            ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_color_argb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_80}


```
 resize(new_width, new_height) 
```

يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_81}


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


**See also:**

**[Example # 1](#example_61)**: This example loads a raster image and resizes it using various resizing methods.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_82}


```
 resize(new_width, new_height, settings) 
```

يعيد تحجيم الصورة باستخدام خيارات موسعة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات التحجيم. |


**See also:**

**[Example # 1](#example_62)**: This example loads a raster image and resizes it using various resizing setti...


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_83}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_84}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_85}


```
 resize_height_proportionally(new_height) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_86}


```
 resize_height_proportionally(new_height, resize_type) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_87}


```
 resize_height_proportionally(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_88}


```
 resize_height_proportionally_settings(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_89}


```
 resize_width_proportionally(new_width) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_90}


```
 resize_width_proportionally(new_width, resize_type) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_91}


```
 resize_width_proportionally(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_92}


```
 resize_width_proportionally_settings(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_93}


```
 rotate(angle) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_94}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_95}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | نوع تدوير/قلب الصورة. |

### Method: save(file_path) {#save_file_path_96}


```
 save(file_path) 
```

يقوم بحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ الصورة فيه. |

### Method: save(file_path, options) {#save_file_path_options_97}


```
 save(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_98}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_99}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_100}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_101}


```
 save(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_102}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_103}


```
 save_argb_32_pixels(rectangle, pixels) 
```

يقوم بحفظ بكسلات ARGB 32‑بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | مصفوفة بكسلات ARGB 32‑بت. |


**See also:**

**[Example # 1](#example_46)**: The following example fills the central area of a raster image with black pix...


### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_104}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| البكسلات | int[] | بكسلات CMYK معروضة كقيم صحيحة 32‑بت. |


**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_105}


```
 save_cmyk_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.<br/>            هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | مصفوفة بكسلات CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_106}


```
 save_pixels(rectangle, pixels) 
```

يقوم بحفظ البكسلات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | مصفوفة البكسلات. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...

**[Example # 2](#example_47)**: The following example fills the central area of a raster image with black pix...


### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_107}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_108}


```
 save_to_stream(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_109}


```
 save_to_stream_with_options(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_111}


```
 save_with_options(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_112}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_113}


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


**See also:**

**[Example # 1](#example_42)**: The following example loads a raster image, and sets the color of an arbitrar...


### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_114}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة التي يجب ضبطها. |
| update_colors | bool | إذا تم ضبطه على <c>true</c> سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. لاحظ أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات مطابقة في اللوحة. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_115}


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


**See also:**

**[Example # 1](#example_42)**: The following example loads a raster image, and sets the color of an arbitrar...


### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_116}


```
 set_resolution(dpi_x, dpi_y) 
```

يضبط الدقة لهذه [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dpi_x | float | الدقة الأفقية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | الدقة العمودية، بالنقاط لكل بوصة، لـ [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_117}


```
 try_set_metadata(metadata) 
```

يحاول تعيين مثيل _metadata_، إذا كان مثيل [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق النوع [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | البيانات الوصفية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح، إذا كان مثيل [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق النوع [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); وإلا، خطأ. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| scan_line_index | int | فهرس الصف الماسح يبدأ من الصفر. |
| argb_32_pixels | int[] | مصفوفة ألوان ARGB 32‑بت للكتابة. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_119}


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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# إنشاء نسخة من MemoryStream
with strm_ext.create_memory_stream() as stream:
	#أنشئ مثيلًا من GifOptions واضبط خصائصه المتنوعة بما في ذلك خاصية Source.
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# إنشاء نسخة من Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# احصل على بكسلات الصورة بتحديد المنطقة كحدود الصورة.
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#تكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل.
			for index in range(pixel.length):
				if index % 2 == 0:
					#عيّن لون البكسل المفهرس إلى الأصفر.
					pixels[index] = yellow_color
				else:
					#عيّن لون البكسل المفهرس إلى الأزرق.
					pixels[index] = blue_color

			#طبق تغييرات البكسل على الصورة.
			image.save_pixels(image.bounds, pixels)

			# احفظ جميع التغييرات.
			image.save()

	# اكتب MemoryStream إلى ملف.
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

### The following example shows how image caching affects performance. In general case, reading cached data is performed faster than reading non-cached data. {#example_36}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

# حمّل صورة من ملف PNG.
with Image.load(path_join(directory, "sample.png")) as image:
	# قم بتخزين جميع بيانات البكسل في الذاكرة المؤقتة بحيث لا يتم تحميل أي بيانات إضافية من تدفق البيانات الأساسي
	image.cache_daata()

	start_time = timedelta()

	# قراءة جميع البكسلات سريعة إلى حد ما.
	rasterImage = as_of(image, RasterImage)
	for y in range(image.height):
		for x in range(image.width):
			color = rasterImage.get_argb_32_pixel(x, y)
			
	end_time = timedelta()
	time = (end_time.microseconds - start_time.microseconds) / 1000000
	print(f"Reading all cached pixels took {time} ms.")


# تحميل صورة من ملف PNG
with Image.load(path_join(directory, "sample.png")) as image:
	start_time = timedelta()

	# قراءة جميع البكسلات ليست سريعة كما هي عند التخزين المؤقت
	rasterImage = as_of(image, RasterImage)
	for y in range(image.height):
		for x in range(image.width):
			color = rasterImage.get_argb_32_pixel(x, y)

	end_time = timedelta()
	time = (end_time.microseconds - start_time.microseconds) / 1000000
	print(f"Reading all pixels without preliminary caching took {time} ms.")

# قد يبدو الإخراج هكذا:
# استغرق قراءة جميع البكسلات المخزنة مؤقتًا 1500 مللي ثانية.
# استغرق قراءة جميع البكسلات دون تخزين مؤقت تمهيدي 150000 مللي ثانية.


```

### The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form. {#example_37}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging.fileformats.png import PngColorType

image_width = 3
image_height = 2

colors = [
	Color.from_argb(127, 255, 0, 0),
	Color.from_argb(127, 0, 255, 0),
	Color.from_argb(127, 0, 0, 255),
	Color.from_argb(127, 255, 255, 0),
	Color.from_argb(127, 255, 0, 255),
	Color.from_argb(127, 0, 255, 255)
]

create_options = PngOptions()
create_options.source = StreamSource()
create_options.color_type = PngColorType.TRUECOLOR_WITH_ALPHA

with Image.create(create_options, image_width, image_height) as image:
	raster_image = as_of(image, RasterImage)

	# حفظ البكسلات لكامل الصورة.
	raster_image.save_pixels(raster_image.bounds, colors)

	# يتم تخزين البكسلات في الصورة الأصلية بصيغة غير مضاعفة مسبقًا.
	# يجب تحديد الخيار المقابل صراحةً للحصول على مكونات اللون المضاعفة مسبقًا.
	# يتم حساب مكونات اللون المضاعفة مسبقًا باستخدام الصيغ التالية:
	# red = original_red * alpha / 255;
	# green = original_green * alpha / 255;
	# blue = original_blue * alpha / 255;
	raster_image.premultiply_components = True
	premultiplied_colors = raster_image.load_pixels(raster_image.bounds)
	for i in range(len(colors)):
		print(f"Original color: {colors[i]}")
		print(f"Premultiplied color: {premultiplied_colors[i]}")


```

### The following example loads raster images and prints information about raw data format and alpha channel. {#example_38}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

# ملفات الصورة للتحميل.
fileNames = (r"c:\temp\sample.bmp", r"c:\temp\alpha.png")

for fileName in fileNames:
	with Image.load(fileName) as image:
		raster_image = as_of(image, RasterImage)
		print(f"ImageFile={fileName}, FileFormat={raster_image.raw_data_format}, HasAlpha={raster_image.has_alpha}")

# قد يبدو الإخراج هكذا:
# ImageFile=c:\temp\sample.bmp, FileFormat=Rgb24Bpp, القنوات المستخدمة: 8,8,8, HasAlpha=False
# ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, القنوات المستخدمة: 8,8,8,8, HasAlpha=True

```

### The following example loads a raster image and performs threshold and Floyd dithering using different palette depth. {#example_39}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, DitheringMethod
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تنفيذ تمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
	# كلما زاد عدد البتات المحددة، ارتفعت جودة الصورة وحجم الصورة الناتجة.
	# لاحظ أن لوحات الألوان ذات 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
	rasterImage.dither(DitheringMethod.THRESHOLD_DITHERING, 4)

	rasterImage.save(join_path(directory, "sample.ThresholdDithering4.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)

	# تنفيذ تمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
	# كلما زاد عدد البتات المحددة، ارتفعت جودة الصورة وحجم الصورة الناتجة.
	# لاحظ أن لوحات الألوان ذات 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
	rasterImage.dither(DitheringMethod.FLOYD_STEINBERG_DITHERING, 1)
	rasterImage.save(join_path(directory, "sample.FloydSteinbergDithering1.png"))


```

### The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value. {#example_40}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)

	# احصل على تمثيل عدد صحيح للون البكسل العلوي الأيسر في الصورة.
	color = rasterImage.get_argb_32_pixel(0, 0)

	# للحصول على قيم مكونات اللون الفردية، قم بإزاحة قيمة اللون بعدد البتات المقابل.
	alpha = (color >> 24) & 0xff
	red = (color >> 16) & 0xff
	green = (color >> 8) & 0xff
	blue = (color >> 0) & 0xff

	print(f"The color of the pixel(0,0) is A={alpha},R={red},G={green},B={blue}")


```

### The following example loads a raster image and obtains the color of an arbitrary pixel. {#example_41}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)
	# احصل على لون البكسل العلوي الأيسر في الصورة.
	color = rasterImage.get_pixel(0, 0)

	# احصل على قيم مكونات اللون الفردية
	alpha = color.a
	red = color.r
	green = color.g
	blue = color.b

	print(f"The color of the pixel(0,0) is A={alpha},R={red},G={green},B={blue}")


```

### The following example loads a raster image, and sets the color of an arbitrary pixel. {#example_42}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)
	# يضبط لون البكسل العلوي الأيسر.
	rasterImage.set_argb_32_pixel(0, 0, Color.aqua.to_argb())
	# طريقة أخرى هي تمرير مثيل من aspose.imaging.Color مباشرةً
	rasterImage.set_pixel(0, 0, Color.aqua)


```

### The following example shows how to load and process pixels of a raster image. The pixels are represented as 32-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image. {#example_43}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("alpha.png") as image:
	rasterImage = as_of(image, RasterImage)

	# تحميل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة aspose.imaging.RasterImage.load_argb_32_pixels(rectangle).
	pixels = rasterImage.load_argb_32_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		alpha = (pixel >> 24) & 0xff
		if alpha == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example shows how to load and process pixels of a raster image. The pixels are represented as 64-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image. {#example_44}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("16rgba.png") as image:
	rasterImage = as_of(image, RasterImage)
	# تحميل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة aspose.imaging.RasterImage.load_argb_64_pixels.
	# لاحظ أن الصورة نفسها يجب أن تكون 16 بت لكل عينة، لأن aspose.imaging.RasterImage.load_argb_64_pixels لا تعمل مع 8 بت لكل عينة.
	# للعمل مع 8 بت لكل عينة يرجى استخدام الطريقة القديمة الجيدة aspose.imaging.RasterImage.load_argb_64_pixels.
	pixels = rasterImage.load_argb_64_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		# لاحظ أن جميع مكونات اللون بما في ذلك ألفا ممثلة بقيم 16‑بت، لذا فإن القيم المسموح بها تقع في النطاق [0, 63535].
		alpha = (pixel >> 48) & 0xffff
		if alpha == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example shows how to load and process pixels of a raster image. For example, consider a problem of counting of fully transparent pixels of an image. {#example_45}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("alpha.png") as image:
	rasterImage = as_of(image, RasterImage)
	# تحميل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة aspose.imaging.RasterImage.load_pixels.
	pixels = rasterImage.load_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		if pixel.a == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_argb_32_pixels method. {#example_46}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# المربع الأسود
	pixel_count = ((rasterImage.width // 2) * (rasterImage.height // 2))
	black_color = Color.black.to_argb()
	pixels = [black_color] * pixel_count

	# ارسم المربع الأسود في مركز الصورة.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_argb_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveArgb32Pixels.png"))


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_pixels method. {#example_47}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# المربع الأسود
	pixel_count = ((rasterImage.width // 2) * (rasterImage.height // 2))
	black_color = Color.black
	pixels = [black_color] * pixel_count

	# ارسم المربع الأسود في مركز الصورة.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SavePixels.png"))


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# احصل على تمثيل صحيح للون الأسود في مساحة ألوان CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# المربع الأسود.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# ارسم المربع الأسود في مركز الصورة.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_cmyk_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveCmyk32Pixels.png"))


```

### The following example crops a raster image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_49}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية للصورة.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.crop(area)
	# حفظ الصورة المقصوصة إلى PNG
	rasterImage.save(join_path(directory, "sample.Crop.png"))


```

### The following example crops a raster image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_50}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# قم بالقص مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
	horizontalMargin = rasterImage.width // 10
	verticalMargin = rasterImage.height // 10
	rasterImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin)
	# احفظ الصورة المقصوصة بصيغة PNG.
	rasterImage.save(join_path(directory, "sample.Crop.png"))


```

### The following example binarizes a raster image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_51}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# حوّل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
	# إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
	rasterImage.binarize_fixed(127)
	rasterImage.save(join_path(directory, "sample.BinarizeFixed.png"))


```

### The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_53}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# حوّل الصورة إلى ثنائية بفارق سطوع قدره 5. السطوع هو الفرق بين البكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
	rasterImage.binarize_bradley(5, 10)
	rasterImage.save(join_path(directory, "sample.BinarizeBradley5_10x10.png"))


```

### The following example performs gamma-correction of an image. {#example_55}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# اضبط معامل غاما للقنوات الحمراء والخضراء والزرقاء.
	rasterImage.adjust_gamma(2.5f)
	rasterImage.save(join_path(directory, "sample.AdjustGamma.png"))


```

### The following example performs gamma-correction of an image applying different coefficients for color components. {#example_56}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# اضبط معامل غاما للقنوات الحمراء والخضراء والزرقاء.
	rasterImage.adjust_gamma(1.5f, 2.5f, 3.5f)
	rasterImage.save(join_path(directory, "sample.AdjustGamma.png"))


```

### The following example performs brightness correction of an image. {#example_57}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# اضبط قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255، 255].
	rasterImage.adjust_brightness(50)
	rasterImage.save(join_path(directory, "sample.AdjustBrightness.png"))


```

### The following example performs contrast correction of an image. {#example_58}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# اضبط قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f، 100f].
	rasterImage.adjust_contrast(50)
	rasterImage.save(join_path(directory, "sample.AdjustContrast.png"))


```

### The following example applies various types of filters to a raster image. {#example_59}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.imagefilters.filteroptions import *
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح غاوس-وينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح حركة وينر بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# تطبيق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

### This example loads a raster image and resizes it using various resizing methods. {#example_61}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, ResizeType
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
	rasterImage.resize(image.width * 2, image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(join_path(directory, "upsample.nearestneighbour.gif"))

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
	rasterImage.resize(image.width // 2, image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE);
	image.Save(dir + "downsample.nearestneighbour.gif");

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخط.
	rasterImage.resize(image.width * 2, image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(join_path(directory, "upsample.bilinear.gif"))

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخط.
	rasterImage.resize(image.width // 2, image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.Save(dir + "downsample.bilinear.gif");


```

### This example loads a raster image and resizes it using various resizing settings. {#example_62}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, ImageResizeSettings, ResizeType,\
	ImageFilterType, ColorQuantizationMethod, ColorCompareMethod
from os.path import join as join_path

directory = r"c:\temp"

resizeSettings = ImageResizeSettings()
# الخوارزمية التكيفية المستندة إلى الدالة النسبية الموزونة والممزجة وتداخل lanczos3.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# المرشح المستطيل الصغير.
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# عدد الألوان في لوحة الألوان.
resizeSettings.entries_count = 256
# تكميم اللون غير مستخدم.
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE
# طريقة إقليدية.
resizeSettings.color_compare_method = ColorCompareMethod.EUCLIDIAN

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
	rasterImage.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(join_path(directory, "downsample.adaptive.gif"))


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

### Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle. It can have various causes but the most common is that the paper get misplaced during a scan. Therefore, deskew is the process of detecting and fixing this issue on scanned files(i.e. bitmap) so deskewed documents will have the text/images correctly and horizontally adjusted. {#example_184}
``` python
from aspose.imaging import Image, RasterImage, Color
from aspose.pycore import as_of

dir_: str = "c:\\3567\\"
input_file_path: str = dir_ + "skewed.png"
output_file_path: str = dir_ + "skewed.out.png"
# التخلص من المسح المائل باستخدام المعلمات الافتراضية
with as_of(Image.load(input_file_path), RasterImage) as image:
	# إزالة الميل
	image.normalize_angle(False, Color.light_gray)
	image.save(output_file_path)


```

### The example shows how to validate that the embedded digital signature matches the provided password. {#example_231}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, -1)


```

### The example shows how to embed digital signature based on provided password into image pixel data. {#example_232}
``` python

from aspose.imaging import Image

image_file_path = "ball.png"
password = "veryStr0ngPassword"
with Image.load(image_file_path) as image:
	image.embed_digital_signature(password)
	image.save(output_path)


```

### The example demonstrates how to verify that the embedded digital signature matches the provided password against the specified probability threshold. {#example_233}
``` python

from aspose.imaging import Image
  
threshold = 100
with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, threshold)


```

### The example illustrates how to determine the probability (from 0% to 100%) that an image contains a digital signature created with the specified password. {#example_234}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	signed_percentage = image.analyze_percentage_digital_signature(password)


```

