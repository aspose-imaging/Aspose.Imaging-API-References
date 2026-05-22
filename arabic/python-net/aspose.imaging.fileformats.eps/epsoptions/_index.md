---
title: "فئة EpsOptions"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.eps/epsoptions/
---

**Summary:** EPS options (currently not used)

**Module:** [aspose.imaging.fileformats.eps](/imaging/python-net/aspose.imaging.fileformats.eps/)

**Full Name:** aspose.imaging.fileformats.eps.EpsOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EpsOptions()](#EpsOptions__1) | يُنشئ مثلاً جديدًا من فئة EpsOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| sub_type | [EpsType](/imaging/python-net/aspose.imaging.fileformats.eps.consts/epstype/) | r/w | يحصل أو يضبط النوع الفرعي لتنسيق EPS. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: EpsOptions() {#EpsOptions__1}


```
 EpsOptions() 
```

يُنشئ مثلاً جديدًا من فئة EpsOptions

### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ نسخة متماثلة لهذا الكائن.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | نسخة متماثلة لهذا الكائن. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


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


