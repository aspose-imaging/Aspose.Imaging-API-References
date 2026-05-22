---
title: "IImageLoaderDescriptor 类"
type: docs
weight: 5350
url: /zh/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | 确定图像加载器是否可以从指定的流读取新图像，并可选地使用 _loadOptions_。 |
| [create_instance()](#create_instance__2) | 创建一个新的加载器实例。 |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

确定图像加载器是否可以从指定的流读取新图像，并可选地使用 _loadOptions_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 流容器。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 由 _loadOptions_ 指定的文件格式详细信息。_loadOptions_ 可能为 null。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果由此描述符创建的图像加载器可以从流读取图像；否则，<c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

创建一个新的加载器实例。

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | 一个新的加载器实例。 |


