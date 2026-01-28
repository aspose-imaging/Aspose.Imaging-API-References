---
title: IImageLoaderDescriptor Class
type: docs
weight: 5350
url: /python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Determines whether image loader can read a new image from the specified stream and optionally using the _loadOptions_. |
| [create_instance()](#create_instance__2) | Creates a new loader instance. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Determines whether image loader can read a new image from the specified stream and optionally using the _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | The stream container. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The file format details specified by _loadOptions_. The _loadOptions_ may be null. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image loader created by this descriptor can read image from stream; otherwise, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Creates a new loader instance.

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | A new loader instance. |


