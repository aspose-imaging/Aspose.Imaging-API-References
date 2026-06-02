---
title: "فئة Image"
type: docs
weight: 5650
url: /ar/python-net/aspose.imaging/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DataStreamSupporter

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
| has_background_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| height | int | r | يحصل على ارتفاع الصورة. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | يحصل أو يعيّن مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | يحصل على بيانات التعريف الخاصة بالصورة. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | يحصل على حجم الصورة. |
| [use_palette](#use_palette1) | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| width | int | r | يحصل على عرض الصورة. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يعيّن بيانات Xmp. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل أي بيانات إضافية من [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_load(stream)](#can_load_stream_3) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام _loadOptions_ المحددة اختياريًا. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [can_save(options)](#can_save_options_8) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [create(files)](#create_files_9) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | ينشئ مثيلًا من [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) من مصفوفة البكسل المقدمة.<br/>            <br/>            يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل.<br/>            لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص. |
| [create(images)](#create_images_13) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(images, dispose_images)](#create_images_dispose_images_14) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | ينشئ خيارات الإنشاء المتعددة الصفحات المحددة. |
| [create_from_files(files)](#create_from_files_files_16) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة كصفحات تحميل كسول. |
| [create_from_images(images)](#create_from_images_images_18) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | قص الصورة مع إزاحات. |
| [crop(rectangle)](#crop_rectangle_21) | يقص المستطيل المحدد. |
| [get_default_options(args)](#get_default_options_args_22) | يحصل على الخيارات الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_23) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_24) | يحصل على تنسيق الملف. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_25) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_26) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_27) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [get_original_options()](#get_original_options__28) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_29) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_30) | يحصل على عرض نسبي. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_31) | يحوّل إلى aps. |
| [load(file_path)](#load_file_path_32) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(file_path, load_options)](#load_file_path_load_options_33) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| [load(stream)](#load_stream_34) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_35) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream(stream)](#load_stream_stream_36) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_37) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_38) | يحمّل صورة جديدة من مسار الملف أو عنوان URL المحدد.<br/>            إذا كان _filePath_ مسار ملف، فإن الطريقة تفتح الملف فقط.<br/>            إذا كان _filePath_ عنوان URL، فإن الطريقة تُنزّل الملف، تخزّنه مؤقتًا، وتفتحه. |
| remove_metadata() | يزيل البيانات الوصفية. |
| [resize(new_width, new_height)](#resize_new_width_new_height_39) | يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_40) | يقوم بتغيير حجم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_41) | يقوم بتغيير حجم الصورة. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_42) | يقوم بتغيير حجم الصورة. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_43) | يقوم بتغيير حجم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_44) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_45) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_46) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_47) | يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_48) | يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_49) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_50) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_51) | يقوم بتغيير عرض الصورة بنسبة متناسبة. |
| [rotate(angle)](#rotate_angle_52) | تدوير الصورة حول المركز. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_53) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يقوم بحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_54) | يقوم بحفظ الصورة إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_55) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_56) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_57) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_58) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_59) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_60) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream(stream)](#save_to_stream_stream_61) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_62) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63) | يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_64) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_65) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_66) | يضبط لوحة ألوان الصورة. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_67) | يحاول تعيين مثيل _metadata_، إذا كان مثيل [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق النوع [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Property: use_palette {#use_palette1}

يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.

**See also:**

**[Example # 1](#example_221)**: Determine if the palette is used by the image.


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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



**See also:**

**[Example # 1](#example_22)**: This example determines whether image can be loaded from a file.


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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



**See also:**

**[Example # 1](#example_23)**: This example determines whether image can be loaded from a file stream.


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


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


### Method: can_save(options) {#can_save_options_8}


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



**See also:**

**[Example # 1](#example_26)**: This example shows how to determine whether image can be saved to the specifi...


### Method: create(files)  [static] {#create_files_9}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


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



**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


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


### Method: create(images)  [static] {#create_images_13}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


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

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

يقص المستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل. |

### Method: get_default_options(args) {#get_default_options_args_22}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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



**See also:**

**[Example # 1](#example_24)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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



**See also:**

**[Example # 1](#example_25)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_25}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_26}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_27}


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


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/> يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/> على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/> طريقة [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/> لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/> إلى طريقة [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) كمعامل ثانٍ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات المستندة إلى إعدادات الملف الأصلي. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_29}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_30}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_31}


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


### Method: load(file_path)  [static] {#load_file_path_32}


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



**See also:**

**[Example # 1](#example_1)**: This example demonstrates the loading of an existing Image file into an insta...


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_33}


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


### Method: load(stream)  [static] {#load_stream_34}


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



**See also:**

**[Example # 1](#example_6)**: This example demonstrates the use of a file stream objects to load an existin...


### Method: load(stream, load_options)  [static] {#load_stream_load_options_35}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_36}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_37}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_38}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_39}


```
 resize(new_width, new_height) 
```

يُعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |


**See also:**

**[Example # 1](#example_182)**: The following example shows how to resize a metafile (WMF and EMF).

**[Example # 2](#example_185)**: The following example shows how to resize SVG image and save it to PNG.


### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_40}


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

**[Example # 1](#example_209)**: Resize image using specific Resize Type.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_41}


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


**See also:**

**[Example # 1](#example_28)**: This example loads an image and resizes it using various resizing settings.

**[Example # 2](#example_209)**: Resize image using specific Resize Type.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_42}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_43}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_44}


```
 resize_height_proportionally(new_height) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_45}


```
 resize_height_proportionally(new_height, resize_type) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |


**See also:**

**[Example # 1](#example_30)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_46}


```
 resize_height_proportionally(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_47}


```
 resize_height_proportionally_settings(new_height, settings) 
```

يقوم بتغيير ارتفاع الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_48}


```
 resize_width_proportionally(new_width) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_49}


```
 resize_width_proportionally(new_width, resize_type) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | نوع التحجيم. |


**See also:**

**[Example # 1](#example_29)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_50}


```
 resize_width_proportionally(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_51}


```
 resize_width_proportionally_settings(new_width, settings) 
```

يقوم بتغيير عرض الصورة بنسبة متناسبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | إعدادات تحجيم الصورة. |

### Method: rotate(angle) {#rotate_angle_52}


```
 rotate(angle) 
```

تدوير الصورة حول المركز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_53}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | نوع تدوير/قلب الصورة. |


**See also:**

**[Example # 1](#example_8)**: This example demonstrates the use of Rotate operation on an image. Example lo...

**[Example # 2](#example_31)**: This example loads an image, rotates it by 90 degrees clockwise and optionall...


### Method: save(file_path) {#save_file_path_54}


```
 save(file_path) 
```

يقوم بحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ الصورة فيه. |

### Method: save(file_path, options) {#save_file_path_options_55}


```
 save(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |


**See also:**

**[Example # 1](#example_9)**: This example shows the simple steps to save an Image. To demonstrate this ope...

**[Example # 2](#example_32)**: The following example loads a BMP image from a file, then saves the image to ...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_56}


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


**See also:**

**[Example # 1](#example_33)**: The following example loads a BMP image from a file, then saves a rectangular...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, over_write) {#save_file_path_over_write_57}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_58}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_59}


```
 save(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |


**See also:**

**[Example # 1](#example_10)**: This example shows the process of saving an Image to MemoryStream. To demonst...

**[Example # 2](#example_34)**: The following example loads an image from a file, then saves the image to a P...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_60}


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


**See also:**

**[Example # 1](#example_35)**: The following example loads an image from a file, then saves a rectangular pa...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save_to_stream(stream) {#save_to_stream_stream_61}


```
 save_to_stream(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_62}


```
 save_to_stream_with_options(stream, options_base) 
```

يقوم بحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة فيه. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_64}


```
 save_with_options(file_path, options) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد وفقاً لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_65}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_66}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | اللوحة التي يجب ضبطها. |
| update_colors | bool | إذا تم ضبطه على <c>true</c> سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. لاحظ أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات مطابقة في اللوحة. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_67}


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


## **Examples**
### This example demonstrates the loading of an existing Image file into an instance of aspose.imaging.Image using file path specified {#example_1}
``` python

from aspose.imaging import Image
# إنشاء مثيل Image وتهيئته بملف صورة موجود من موقع القرص.
with Image.load(r"C:\temp\sample.bmp") as image:
	# قم ببعض معالجة الصورة
	pass


```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#إنشاء مثيل من `BmpOptions` وتعيين خصائصه المتنوعة
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#إنشاء مثيل من `FileCreateSource` وتعيينه كـ `source` لمثيل `BmpOptions`
	#المعامل `Boolean` الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#إنشاء مثيل من Image وتهيئته بمثيل BmpOptions عن طريق استدعاء طريقة Create
	with Image.create(bmp_options, 500, 500) as image:
		#قم ببعض معالجة الصورة
		# احفظ جميع التغييرات
		image.save()


```

### This example demonstrates the use of a file stream objects to load an existing Image file {#example_6}
``` python

from aspose.imaging import Image

# إنشاء مثيل من FileStream
with open(r"C:\temp\sample.bmp", "rb"):
	#إنشاء مثيل من فئة Image وتحميل ملف موجود عبر كائن FileStream عن طريق استدعاء طريقة Load
	with Image.load(stream) as image:
		#قم ببعض معالجة الصور.
		pass

```

### This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the `Rotate` operation on the image according to the value of enumeration `aspose.imaging.RotateFlipType` {#example_8}
``` python

from aspose.imaging import Image, RotateFlipType
#إنشاء نسخة من فئة الصورة وتهيئتها بملف صورة موجود عبر File path
with Image.load(r"C:\temp\sample.bmp") as image:
	# قم بتدوير الصورة بزاوية 180 درجة حول المحور X
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	# احفظ جميع التغييرات.
	image.save()


```

### This example shows the simple steps to save an Image. To demonstrate this operation, we load an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format using file path {#example_9}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from os.path import join as path_join

directory = "c:\\temp"

#إنشاء نسخة من فئة الصورة وتهيئتها بملف موجود عبر File path
with Image.load(path_join(directory, "sample.bmp")) as image:
	#تدوير الصورة بزاوية 180 درجة حول المحور X
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	#احفظ الصورة كملف PSD إلى File Path باستخدام إعدادات PsdOptions الافتراضية
	image.save(path_join(directory, "output.psd"), PsdOptions())


```

### This example shows the process of saving an Image to MemoryStream. To demonstrate this operation, example loads an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format {#example_10}
``` python
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.extensions import StreamExtensions as stream_ext

#إنشاء نسخة من MemoryStream
with stream_ext.create_memory_stream() as stream:
	#إنشاء نسخة من فئة الصورة وتهيئتها بملف موجود عبر File path
	with Image.load(r"C:\temp\sample.bmp") as image:
		#تدوير الصورة بزاوية 180 درجة حول المحور X
		image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
		#احفظ الصورة كملف PSD إلى MemoryStream باستخدام إعدادات PsdOptions الافتراضية
		image.save(stream, PsdOptions())


```

### This example determines whether image can be loaded from a file. {#example_22}
``` python

from aspose.imaging import Image

# استخدم مسارًا مطلقًا للملف
can_load: bool = Image.can_load(r"c:\temp\sample.gif")


```

### This example determines whether image can be loaded from a file stream. {#example_23}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ext
import os.path import join

directory = r"c:\temp"

canLoad = False

# استخدم تدفق ملف
with open(join(directory, "sample.bmp"), "rb"):
	canLoad = Image.can_load(stream)

print(f"Can load the file: {canLoad}")

# البيانات التالية ليست تدفق صورة صالح، لذا تُعيد الدالة CanLoad القيمة false.
imageData = [0, 0, 0, 0, 0, 0, 0, 0]
with strm_ext.create_memory_stream_from_bytes(imageData) as stream:
	canLoad = Image.can_load(stream)

print(f"Can load the byte buffer: {canLoad}")


```

### This example shows how to determine the image format without loading the entire image from a file. {#example_24}
``` python

from aspose.imaging import Image
from os.path import join as path_join

directory = "c:\\temp\\"

# استخدم مسارًا مطلقًا للملف
file_format = Image.get_file_format(path_join(directory, "sample.gif"))
print(f"The file format is {file_format}")


```

### This example shows how to determine the image format without loading the entire image from a file stream. {#example_25}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ex
from os.path import join as path_join

directory = "c:\\temp\\"

# استخدم تدفق ملف
with open(path_join(directory, "sample.bmp"), "rb") as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")

# البيانات التالية ليست تدفق صورة صالح، لذا تُعيد الدالة get_file_format القيمة FileFormat.UNKNOWN
imageData = bytearray([0, 0, 0, 0, 0, 0, 0, 0])
with strm_ex.create_memory_stream_from_bytes(imageData) as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")


```

### This example shows how to determine whether image can be saved to the specified file format represented by the passed save options. {#example_26}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	saveOptions = JpegOptions()
	saveOptions.quality = 50
	# تحديد ما إذا كان يمكن حفظ الصورة كملف jpeg
	canSave: bool = image.can_save(saveOptions)
	print(canSave)


```

### This example loads an image and resizes it using various resizing settings. {#example_28}
``` python
from aspose.imaging import Image, ImageResizeSettings, ResizeType, ImageFilterType,\
	ColorQuantizationMethod
from os.path import join as path_join

directory = "c:\\temp\\"

resizeSettings = ImageResizeSettings()

# الخوارزمية التكيفية المستندة إلى الدالة النسبية الموزونة والممزجة وتداخل lanczos3.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# المرشح المستطيل الصغير.
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# عدد الألوان في لوحة الألوان.
resizeSettings.entries_count = 256
# تكميم اللون غير مستخدم.
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE

# طريقة إقليدية
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

with Image.load(path_join(directory, "sample.gif")) as image:
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
	image.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(path_join(directory, "downsample.adaptive.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically. {#example_29}
``` python
from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
	image.resize_width_proportionally(image.width * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
	image.resize_width_proportionally(image.width // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخط.
	image.resize_width_proportionally(image.width * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخط.
	image.resize_width_proportionally(image.width // 2, ResizeType.BILINEAR_RESAMPLE);
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically. {#example_30}
``` python

from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
	image.resize_height_proportionally(image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
	image.resize_height_proportionally(image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخط.
	image.resize_height_proportionally(image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخط.
	image.resize_height_proportionally(image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_31}
``` python

from aspose.imaging import Image, RotateFlipType
from os.path import join as path_join

directory = "c:\\temp\\"

rotateFlipTypes = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X,
				   RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]

for rotateFlipType in rotateFlipTypes:
	# تدوير، انعكاس وحفظ إلى ملف الإخراج.
	with Image.Load(path_join(directory, "sample.bmp")) as image:
		image.rotate_flip(rotateFlipType)
		image.save(path_join(directory, f"sample.{rotateFlipType}.bmp"))


```

### The following example loads a BMP image from a file, then saves the image to a PNG file. {#example_32}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# احفظ الصورة بالكامل إلى ملف PNG.
	save_options = PngOptions()
	image.save(path_join(dir, "output.png"), save_options)

```

### The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file. {#example_33}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# احفظ النصف العلوي من الصورة إلى ملف PNG.
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	image.save(path_join(dir, "output.png"), save_options, bounds)

```

### The following example loads an image from a file, then saves the image to a PNG file stream. {#example_34}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# احفظ الصورة بالكامل إلى تدفق ملف.
		image.save(output_stream, save_options)

```

### The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream. {#example_35}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# احفظ النصف العلوي من الصورة إلى تدفق ملف.
		image.save(output_stream, save_options, bounds)


```

### The following example shows how to save an entire BMP image or part of it to a file or stream. {#example_90}
``` python

from os.path import join as path_join
from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.extensions import StreamExtensions as strm_ext

directory = "c:\\temp\\"
with Image.load(path_join(directory, "sample.bmp")) as image:
	bmpImage = as_of(image, BmpImage)
		
	# تحويل إلى صورة بالأبيض والأسود
	bmpImage.binarize_otsu()

	# احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
	image.save()

	saveOptions = BmpOptions()

	# تحتوي اللوحة على لونين فقط: الأسود والأبيض في هذه الحالة.
	saveOptions.palette = ColorPaletteHelper.create_monochrome()

	# بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) يكفي تخصيص بت واحد لكل بكسل.
	saveOptions.bits_per_pixel = 1

	# احفظ في موقع آخر باستخدام الخيارات المحددة.
	image.save(path_join(directory, "sample.bw.palettized.bmp"), saveOptions)

	# احفظ الجزء المركزي فقط من الصورة.
	bounds = Rectangle(image.width // 4, image.height // 4, image.width // 2, image.height // 2)
	image.save(path_join(directory, "sample.bw.palettized.part.bmp"), saveOptions, bounds)

	# احفظ الصورة بالكامل إلى MemoryStream
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions);
		print("The size of the whole image in bytes:", stream.tell())

	# احفظ الجزء المركزي من الصورة إلى تدفق الذاكرة
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions, bounds)
		print("The size of the central part of the image in bytes: ", stream.tell())

#قد يبدو الإخراج هكذا:
#حجم الصورة بالكامل بالبايت: 24062
#حجم الجزء المركزي من الصورة بالبايت: 6046

```

### The following example shows how to resize a metafile (WMF and EMF). {#example_182}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.emf import MetaImage
from os.path import join

dir_ = "c:\\temp"
file_names = ["image3.emf", "image4.wmf"]
for file_name in file_names:
	input_file_path = join(dir_, file_name)
	output_file_path = join(dir_, "Downscale_" + file_name)
	with aspycore.as_of(Image.load(input_file_path), MetaImage) as image:
		image.resize(image.width // 4, image.height // 4)
		image.save(output_file_path)


```

### The following example shows how to resize SVG image and save it to PNG. {#example_185}
``` python

from aspose.imaging import PointF, Image
from aspose.imaging.imageoptions import PngOptions
from os import path

dir_ = "c:\\aspose.imaging\\net\\issues\\3549"
file_names = ["Logotype.svg", "sample_car.svg", "rg1024_green_grapes.svg", "MidMarkerFigure.svg", "embeddedFonts.svg"]
scales = [PointF(0.5, 0.5), PointF(1.0, 1.0), PointF(2.0, 2.0), PointF(3.5, 9.2)]
for input_file in file_names:
	for scale in scales:
		output_file = "{0}_{1}_{2}.png".format(input_file, str(scale.x), str(scale.y))
		with Image.load(path.join(dir_, input_file)) as image:
			image.resize(int(image.width * scale.x), int(image.height * scale.y))
			image.save(path.join(dir_, output_file), PngOptions())


```

### Resize image using specific Resize Type. {#example_209}
``` python
from aspose.imaging import Image, ResizeType, ImageResizeSettings, ImageFilterType

with Image.load("Photo.jpg") as image:
	image.resize(640, 480, ResizeType.CATMULL_ROM)
	image.save("ResizedPhoto.jpg")
	image.resize(1024, 768, ResizeType.CUBIC_CONVOLUTION)
	image.save("ResizedPhoto2.jpg")
	resize_settings = ImageResizeSettings()
	resize_settings.mode = ResizeType.CUBIC_BSPLINE
	resize_settings.filter_type = ImageFilterType.SMALL_RECTANGULAR
	image.resize(800, 800, resize_settings)
	image.save("ResizedPhoto3.jpg")


```

### Determine if the palette is used by the image. {#example_221}
``` python

from aspose.imaging import Image

with Image.load("Sample.bmp") as image:
	if image.use_palette:
		print("The palette is used by the image")

```

