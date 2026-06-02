---
title: "فئة BigTiffOptions"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.imageoptions/bigtiffoptions/
---

**Summary:** The API for BigTIFF raster image format creation is specifically designed<br/>            to serve to the unique requirements of applications utilizing large-scale<br/>            imaging data from scanners. This API facilitates the seamless generation<br/>            of BigTIFF format, which combines multiple TIFF images into a single,<br/>            comprehensive image. It ensures efficient processing of extensive image<br/>            data, providing developers with a powerful tool for creating and<br/>            manipulating high-resolution, multi-image formats.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BigTiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, TiffOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BigTiffOptions(expected_format)](#BigTiffOptions_expected_format_1) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian. |
| [BigTiffOptions(expected_format, byte_order)](#BigTiffOptions_expected_format_byte_order_2) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [BigTiffOptions(options)](#BigTiffOptions_options_3) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [BigTiffOptions(tags)](#BigTiffOptions_tags_4) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
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
| compressed_quality | int | r/w | يحصل أو يعيّن جودة الصورة المضغوطة.<br/>            يُستخدم مع ضغط Jpeg. |
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
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
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
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian. |
| [create_with_options(options)](#create_with_options_options_5) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [create_with_tags(tags)](#create_with_tags_tags_6) | ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | يحصل على نسخة العلامة حسب النوع. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | يحصل على عدد العلامات الصالحة. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [remove_tag(tag)](#remove_tag_tag_10) | يزيل العلامة. |
| [remove_tags(tags)](#remove_tags_tags_11) | يزيل العلامات. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |
| validate() | يتحقق مما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات |


### Constructor: BigTiffOptions(expected_format) {#BigTiffOptions_expected_format_1}


```
 BigTiffOptions(expected_format) 
```

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف Tiff المتوقع. |

### Constructor: BigTiffOptions(expected_format, byte_order) {#BigTiffOptions_expected_format_byte_order_2}


```
 BigTiffOptions(expected_format, byte_order) 
```

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف Tiff المتوقع. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | ترتيب البايت لتنسيق ملف tiff المستخدم. |

### Constructor: BigTiffOptions(options) {#BigTiffOptions_options_3}


```
 BigTiffOptions(options) 
```

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | مصدر الخيارات. |

### Constructor: BigTiffOptions(tags) {#BigTiffOptions_tags_4}


```
 BigTiffOptions(tags) 
```

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامات لتهيئة الخيارات. |

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

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . بشكل افتراضي يتم استخدام نظام little endian.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | تنسيق ملف Tiff المتوقع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | كائن BigTiffOptions جديد. |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | مصدر الخيارات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | نسخة من الخيارات. |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

ينشئ مثيلًا جديدًا من الفئة [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامات لتهيئة الخيارات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | كائن BigTiffOptions جديد مع العلامات. |


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
| bool | صحيح إذا كان _metadata_ غير فارغ وكانت نسخة [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            تدعم و/أو تنفذ نسخة [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); وإلا، خطأ. |


