---
title: "فئة DxfOptions"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.imageoptions/dxfoptions/
---

**Summary:** API for Drawing Interchange Format (DXF) vector image creation offers<br/>            tailored solutions for generating AutoCAD drawing files with precision and<br/>            flexibility. Designed specifically for working with text lines and Bezier<br/>            curves, developers can efficiently manipulate these elements, count Bezier<br/>            points, and convert curves into polylines for seamless exporting, ensuring<br/>            compatibility and fidelity in DXF vector images.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DxfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [DxfOptions()](#DxfOptions__1) | يقوم بإنشاء نسخة جديدة من الفئة DxfOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bezier_point_count | System.Byte | r/w | عدد النقاط التي يجب توليدها عند تحويل منحنيات بيزييه إلى خطوط متعددة، الحد الأدنى 4. يُستخدم عندما تكون كل من [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) و [DxfOptions.convert_text_beziers](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) مُحددة إلى <c>true</c> |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| convert_text_beziers | bool | r/w | يعمل عندما تكون [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) مُحددة إلى <c>true</c>. ما إذا كان سيتم تحويل منحنيات بيزييه في حدود النص إلى خطوط متعددة النقاط. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| text_as_lines | bool | r/w | ما إذا كان يجب تصدير النص كحدود تتكون من خطوط متعددة (الافتراضي) أو ككيانات TEXT قابلة للتحرير في Autocad.<br/>            إذا تم تعيين هذا الخيار |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: DxfOptions() {#DxfOptions__1}


```
 DxfOptions() 
```

يقوم بإنشاء نسخة جديدة من الفئة DxfOptions

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


## **Examples**
### This example demonstrates export to Dxf format {#example_3}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DxfOptions
#إنشاء مثيل Image وتهيئته بملف صورة موجود من موقع القرص.
with Image.load("input.svg") as image:
	options = DxfOptions()
	options.text_as_lines = True
	options.convert_text_beziers = True
	options.bezier_point_count = 20
	image.save("output.dxf", options)


```

