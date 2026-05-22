---
title: "فئة TiffOptions"
type: docs
weight: 330
url: /ar/python-net/aspose.imaging.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . |
| [TiffOptions(options)](#TiffOptions_options_3) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . |
| [TiffOptions(tags)](#TiffOptions_tags_4) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | يحصل أو يعيّن خيار تخزين ألفا. تُستخدم الخيارات غير [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            عندما يكون هناك أكثر من 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) معرفين. |
| artist | string | r/w | يحصل أو يضبط الفنان. |
| bits_per_pixel | int | r | يحصل على عدد البتات لكل بكسل. |
| bits_per_sample | int[] | r/w | يحصل أو يضبط عدد البتات لكل عينة. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | يحصل أو يعيّن قيمة تشير إلى ترتيب بايتات TIFF. |
| color_map | int[] | r/w | يحصل أو يعيّن خريطة الألوان. |
| [compressed_quality](#compressed_quality1) | int | r/w | يحصل أو يعيّن جودة الصورة المضغوطة.<br/>            يُستخدم مع ضغط Jpeg. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | يحصل أو يضبط الضغط. |
| حقوق النشر | string | r/w | يحصل أو يضبط حقوق النشر. |
| date_time | string | r/w | يحصل أو يعيّن التاريخ والوقت. |
| default_memory_allocation_limit | int | r/w | يحصل أو يعيّن حد تخصيص الذاكرة الافتراضي. |
| disable_icc_export | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصدير ملف تعريف ICC معطلاً (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا). |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| document_name | string | r/w | يحصل أو يعيّن اسم المستند. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | يحصل أو يعيّن المؤشر إلى EXIF IFD. |
| extra_samples | int[] | r | يحصل على قيم العينات الإضافية. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | يحصل أو يعيّن خيارات الفاكس t4. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | يحصل أو يعيّن معيار ملف TIFF. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | يحصل أو يعيّن ترتيب تعبئة بتات البايت. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| half_tone_hints | int[] | r/w | يحصل أو يعيّن تلميحات النصف لون. |
| image_description | string | r/w | يحصل أو يضبط وصف الصورة. |
| image_length | int | r/w | يحصل أو يضبط طول الصورة. |
| image_width | int | r/w | يحصل أو يضبط عرض الصورة. |
| ink_names | string | r/w | يحصل أو يضبط أسماء الحبر. |
| is_extra_samples_present | bool | r | يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة. |
| is_tiled | bool | r | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى مربعات. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) قد تم تكوينه بشكل صحيح. استخدم طريقة Validate للعثور على سبب الفشل. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| max_sample_value | int[] | r/w | يحصل أو يضبط قيمة العينة القصوى. |
| min_sample_value | int[] | r/w | يحصل أو يضبط قيمة العينة الدنيا. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | الحصول أو تعيين الاتجاه. |
| page_name | string | r/w | يحصل أو يضبط اسم الصفحة. |
| page_number | int[] | r/w | يحصل أو يضبط علامة رقم الصفحة. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | يحصل أو يضبط الفوتومتري. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | يحصل أو يضبط تكوين المستوى. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | يحصل أو يضبط المتنبئ لضغط LZW. |
| premultiply_components | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | يحصل أو يضبط وحدة الدقة. |
| rows_per_strip | int | r/w | يحصل أو يضبط عدد الصفوف لكل شريط. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | يحصل أو يضبط تنسيق العينة. |
| samples_per_pixel | int | r | يحصل على عدد العينات لكل بكسل. لتغيير قيمة هذه الخاصية استخدم مُعيّن الخاصية [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | يحصل أو يضبط مصنع الماسح الضوئي. |
| scanner_model | string | r/w | يحصل أو يضبط طراز الماسح الضوئي. |
| smax_sample_value | int[] | r/w | يحصل أو يضبط قيمة العينة القصوى. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long). |
| smin_sample_value | int[] | r/w | يحصل أو يضبط قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long). |
| software_type | string | r/w | يحصل أو يضبط نوع البرنامج. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| strip_byte_counts | int[] | r/w | يحصل أو يضبط عدد بايتات الشريط. |
| strip_offsets | int[] | r/w | يحصل أو يضبط إزاحات الشريط. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| tag_count | int | r | يحصل على عدد العلامات. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | يحصل أو يضبط العلامات. |
| target_printer | string | r/w | يحصل أو يضبط الطابعة المستهدفة. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | يحصل أو يضبط العتبة. |
| tile_byte_counts | int[] | r/w | يحصل أو يضبط عدد بايتات البلاط. |
| tile_length | int | r/w | يحصل أو يضبط طول البلاط. |
| tile_offsets | int[] | r/w | يحصل أو يضبط إزاحات البلاط. |
| tile_width | int | r/w | يحصل أو يضبط عرض البلاط. |
| total_pages | int | r | يحصل على إجمالي الصفحات. |
| valid_tag_count | int | r | يحصل على عدد العلامات الصالحة. هذا ليس عدد جميع العلامات بل هو عدد العلامات التي يمكن حفظها. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| xp_author | string | r/w | يحصل أو يضبط مؤلف الصورة، والذي يستخدمه Windows Explorer. |
| xp_comment | string | r/w | يحصل أو يضبط التعليق على الصورة، والذي يستخدمه Windows Explorer. |
| xp_keywords | string | r/w | يحصل أو يضبط موضوع الصورة، والذي يستخدمه Windows Explorer. |
| xp_subject | string | r/w | يحصل أو يضبط معلومات حول الصورة، والذي يستخدمه Windows Explorer. |
| xp_title | string | r/w | يحصل أو يضبط معلومات حول الصورة، والذي يستخدمه Windows Explorer. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط موضع x. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط دقة x. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط معاملات YCbCr. |
| y_cb_cr_subsampling | int[] | r/w | يحصل أو يضبط عوامل أخذ العينات الفرعية للخصائص الضوئية YCbCr. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط موضع y. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | يحصل أو يضبط دقة y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | يضيف علامة جديدة. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | يضيف العلامات. |
| [clone()](#clone__3) | ينسخ هذه المثيلة. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian. |
| [create_with_options(options)](#create_with_options_options_5) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . |
| [create_with_tags(tags)](#create_with_tags_tags_6) | ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | يحصل على نسخة العلامة حسب النوع. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | يحصل على عدد العلامات الصالحة. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [remove_tag(tag)](#remove_tag_tag_10) | يزيل العلامة. |
| [remove_tags(tags)](#remove_tags_tags_11) | يزيل العلامات. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |
| validate() | يتحقق مما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف tiff المتوقع. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف tiff المتوقع. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | ترتيب البايت لتنسيق ملف tiff المستخدم. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | الخيارات للنسخ منها. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | الوسوم لتهيئة الخيارات بها. |

### Property: compressed_quality {#compressed_quality1}

يحصل أو يعيّن جودة الصورة المضغوطة.<br/>            يُستخدم مع ضغط Jpeg.

**See also:**

**[Example # 1](#example_117)**: This example shows how to create a TIFF image with the Jpeg compression and t...


### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

يضيف علامة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامة للإضافة. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

يضيف العلامات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامات للإضافة. |

### Method: clone() {#clone__3}


```
 clone() 
```

ينسخ هذه المثيلة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | يعيد نسخة عميقة. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف tiff المتوقع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | الخيارات للنسخ منها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | الوسوم لتهيئة الخيارات بها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

يحصل على نسخة العلامة حسب النوع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | مفتاح العلامة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | مثيل للعلامة إذا كانت موجودة أو null خلاف ذلك. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

يحصل على عدد العلامات الصالحة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامات للتحقق من صحتها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | عدد العلامات الصالحة. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | معرف العلامة للتحقق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كانت العلامة موجودة؛ وإلا <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

يزيل العلامة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | العلامة للإزالة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | true إذا تم الإزالة بنجاح |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

يزيل العلامات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | العلامات للإزالة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | **True** إذا تغير حجم مجموعة العلامات. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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
| bool | صحيح، إذا كان كائن [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) يدعم و/أو ينفّذ كائن [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); وإلا، خطأ. |


## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# إنشاء كائن من تدفق ملف
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# تعيين المصدر للنسخة من ImageOptions
	tiffOptions.source = StreamSource(stream)
	# إنشاء نسخة من Image
	with Image.create(tiffOptions, 500, 500) as image:
		# إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		# مسح سطح Graphics.
		graphics.clear(Color.wheat);
		# إنشاء نسخة من الفئة GraphicsPath
		graphics_path = GraphicsPath()
		# إنشاء نسخة من الفئة Figure
		figure = Figure()
		# إضافة أشكال إلى كائن Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# إضافة كائن Figure إلى GraphicsPath
		graphics_path.add_figure(figure)
		# رسم المسار باستخدام كائن Pen باللون الأسود
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# احفظ جميع التغييرات.
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#تحميل صورة gif موجودة كمثيل لفئة Image
with Image.load(path_join(directory, "sample.gif")) as image:
	# تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.png"), PngOptions())
	# تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

### This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality. {#example_117}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat, TiffPhotometrics, TiffCompressions

with aspycore.as_of(Image.load("zeebra.tif"), TiffImage) as image:
	tiff_options = TiffOptions(TiffExpectedFormat.DEFAULT)
	# عيّن نموذج اللون RGB.
	tiff_options.photometric = TiffPhotometrics.RGB
	# عيّن ضغط Jpeg.
	tiff_options.compression = TiffCompressions.JPEG
	tiff_options.compressed_quality = 50
	# عيّن 8 بتات لكل مكوّن لوني.
	tiff_options.bits_per_sample = [8, 8, 8]
	image.save("zeebra.tif-50.tiff", tiff_options)


```

