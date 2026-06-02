---
title: "Classe PathResourceConverter"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Convertit l'instance [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en ressources de chemin. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Convertit les ressources de chemin en instance [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Convertit l'instance [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) en ressources de chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le chemin graphique. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Taille de l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Les ressources de chemin. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Convertit les ressources de chemin en instance [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Les ressources de chemin. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Taille de l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | L'instance [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Crée le GraphicsPath en utilisant les PathResources de l'image TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Dessinez une ligne rouge et enregistrez l'image
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

