---
title: "فئة PathResourceConverter"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | يقوم بتحويل نسخة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) إلى موارد المسار. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | يقوم بتحويل موارد المسار إلى نسخة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

يقوم بتحويل نسخة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) إلى موارد المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | مسار الرسومات. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | حجم الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | موارد المسار. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

يقوم بتحويل موارد المسار إلى نسخة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | موارد المسار. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | حجم الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | نسخة [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# إنشاء GraphicsPath باستخدام PathResources من صورة TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# ارسم خطًا أحمر واحفظ الصورة
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

