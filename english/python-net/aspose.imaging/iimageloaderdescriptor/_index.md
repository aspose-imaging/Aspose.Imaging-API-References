---
title: IImageLoaderDescriptor Class
type: docs
weight: 5210
url: /python-net/aspose.imaging/iimageloaderdescriptor/
---

The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.Imaging Version:** 23.6

The IImageLoaderDescriptor type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| supported_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Gets the supported format. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_0) | Determines whether image loader can read a new image from the specified stream and optionally using the <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__1) | Creates a new loader instance. |

### can_load(stream_container, load_options) {#can_load_stream_container_load_options_0}


```
 can_load(stream_container, load_options) 
```

Determines whether image loader can read a new image from the specified stream and optionally using the <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | The stream container. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The file format details specified by <paramref name="loadOptions" />. The <paramref name="loadOptions" /> may be null. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image loader created by this descriptor can read image from stream; otherwise, <c>false</c>. |


### create_instance() {#create_instance__1}


```
 create_instance() 
```

Creates a new loader instance.

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader) | A new loader instance. |


