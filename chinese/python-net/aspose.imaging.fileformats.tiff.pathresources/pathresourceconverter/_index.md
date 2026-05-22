---
title: "PathResourceConverter 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | 将 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 实例转换为路径资源。 |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | 将路径资源转换为 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 实例。 |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

将 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 实例转换为路径资源。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 图形路径。 |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | 图像大小。 |

**Returns**

| Type | Description |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | 路径资源。 |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

将路径资源转换为 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | 路径资源。 |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | 图像大小。 |

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 实例。 |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# 使用来自 TIFF 图像的 PathResources 创建 GraphicsPath
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# 绘制红色线条并保存图像
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

