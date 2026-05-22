---
title: "FileCreateSource 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | 初始化 [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) 类的新实例。 |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | 初始化 [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| file_path | string | r | 获取要创建的文件路径。 |
| is_temporal | bool | r | 获取一个值，指示文件是否为临时文件。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | 获取流容器。 |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

初始化 [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 要创建的文件路径。 |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

初始化 [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 要创建的文件路径。 |
| is_temporal | bool | 如果设置为 <c>true</c>，创建的文件将是临时的。 |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

获取流容器。

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 流容器。 |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#创建 BmpOptions 的实例并设置其各种属性。
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#创建 `FileCreateSource` 实例并将其分配为 `BmpOptions` 实例的 `source`
	#如果未传递第二个参数，则默认情况下文件的 `is_temporal` 设置为 True。
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#创建 Image 的实例。
	with Image.create(bmp_options, 500, 500) as image:
		#进行一些图像处理
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#创建 `BmpOptions` 实例并设置其各种属性
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#创建 `FileCreateSource` 实例并将其分配为 `BmpOptions` 实例的 `source`
	#第二个 `Boolean` 参数决定要创建的文件是否为_temporal
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#创建 Image 实例并通过调用 Create 方法使用 BmpOptions 实例进行初始化
	with Image.create(bmp_options, 500, 500) as image:
		#进行一些图像处理
		# 保存所有更改
		image.save()


```

