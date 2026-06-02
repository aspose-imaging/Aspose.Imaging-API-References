---
title: "IGifBlockLoaderDescriptor 类"
type: docs
weight: 110
url: /zh/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | 确定加载器是否可以加载指定的数据。 |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | 加载 gif 块。 |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

确定加载器是否可以加载指定的数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 用于加载数据的流容器。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 加载器可以加载指定的数据；否则为 <c>false</c>。 |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

加载 gif 块。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 流容器。 |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 容器调色板。 |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | 一个新的 gif 块。 |


