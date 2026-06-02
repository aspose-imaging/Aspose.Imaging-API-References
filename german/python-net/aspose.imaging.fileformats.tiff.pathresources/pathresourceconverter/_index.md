---
title: "PathResourceConverter Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Konvertiert die [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) Instanz zu Pfadressourcen. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Konvertiert Pfadressourcen zur [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) Instanz. |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Konvertiert die [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) Instanz zu Pfadressourcen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der Grafikpfad. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Größe des Bildes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Die Pfadressourcen. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Konvertiert Pfadressourcen zur [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Die Pfadressourcen. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Größe des Bildes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Die [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) Instanz. |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Erstelle den GraphicsPath mithilfe von PathResources aus einem TIFF-Bild
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Zeichne eine rote Linie und speichere das Bild
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

