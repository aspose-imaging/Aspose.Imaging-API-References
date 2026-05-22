---
title: "الفئة FileCreateSource"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | يُنشئ مثلاً جديدًا من الفئة [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | يُنشئ مثلاً جديدًا من الفئة [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| file_path | string | r | يحصل على مسار الملف لإنشائه. |
| is_temporal | bool | r | يحصل على قيمة تُشير إلى ما إذا كان الملف سيكون مؤقتًا. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | يحصل على حاوية الدفق. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

يُنشئ مثلاً جديدًا من الفئة [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لإنشائه. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

يُنشئ مثلاً جديدًا من الفئة [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لإنشائه. |
| is_temporal | bool | إذا تم تعيينه إلى <c>true</c> سيكون الملف المُنشأ مؤقتًا. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

يحصل على حاوية الدفق.

**Returns**

| نوع | الوصف |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#يُنشئ مثلاً من BmpOptions ويضبط خصائصه المتنوعة
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#إنشاء مثيل من `FileCreateSource` وتعيينه كـ `source` لمثيل `BmpOptions`
	#إذا لم يُمرّر المعامل الثاني، فإن الملف يكون بشكل افتراضي `is_temporal` مُعيّنًا إلى True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#يُنشئ مثلاً من Image
	with Image.create(bmp_options, 500, 500) as image:
		#قم ببعض معالجة الصورة
		image.save()

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

