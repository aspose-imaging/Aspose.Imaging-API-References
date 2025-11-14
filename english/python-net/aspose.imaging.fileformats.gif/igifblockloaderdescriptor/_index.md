---
title: IGifBlockLoaderDescriptor Class
type: docs
weight: 110
url: /python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | Determines whether loader can load the specified data. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | Loads the gif block. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

Determines whether loader can load the specified data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | The stream container to load data from. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> loader can load the specified data; otherwise, <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

Loads the gif block.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | The stream container. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The container palette. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | A new gif block. |


