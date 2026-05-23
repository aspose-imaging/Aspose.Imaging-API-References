---
title: "PathResourceConverter klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Konverterar [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instansen till sökvägsresurser. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Konverterar sökvägsresurser till [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instansen. |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Konverterar [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instansen till sökvägsresurser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Grafikvägen. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Bildens storlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Sökvägsresurserna. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Konverterar sökvägsresurser till [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instansen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Sökvägsresurserna. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Bildens storlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Den [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) instansen. |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Skapa GraphicsPath med PathResources från TIFF-bild
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Rita en röd linje och spara bilden
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

