---
title: PathResourceConverter Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Converts the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instance to path resources. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Converts path resources to the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instance. |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Converts the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instance to path resources.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The graphics path. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Size of the image. |

**Returns**

| Type | Description |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | The path resources. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Converts path resources to the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | The path resources. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Size of the image. |

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instance. |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_188}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Create the GraphicsPath using PathResources from TIFF image
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Draw red line and save the image
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

