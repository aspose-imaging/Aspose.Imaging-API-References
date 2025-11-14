---
title: FileCreateSource Class
type: docs
weight: 10
url: /python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Initializes a new instance of the [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) class. |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Initializes a new instance of the [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| file_path | string | r | Gets the file path to create. |
| is_temporal | bool | r | Gets a value indicating whether file will be temporal. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Gets the stream container. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Initializes a new instance of the [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to create. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Initializes a new instance of the [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to create. |
| is_temporal | bool | If set to <c>true</c> the created file will be temporal. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Gets the stream container.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | the stream container. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Creates an instance of BmpOptions and set its various properties
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Create an instance of `FileCreateSource` and assign it as `source` for the instance of `BmpOptions`
	#If second parameter is not passed, then by default the file has `is_temporal` set to True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Creates an instance of Image
	with Image.create(bmp_options, 500, 500) as image:
		#do some image processing
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Create an instance of `BmpOptions` and set its various properties
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Create an instance of `FileCreateSource` and assign it as `source` for the instance of `BmpOptions`
	#Second `Boolean` parameter determines if the file to be created is_temporal or not
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Create an instance of Image and initialize it with instance of BmpOptions by calling Create method
	with Image.create(bmp_options, 500, 500) as image:
		#do some image processing
		# save all changes
		image.save()


```

