---
title: "Classe PathResourceConverter"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Converte l'istanza [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in risorse di percorso. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Converte le risorse di percorso nell'istanza [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Converte l'istanza [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in risorse di percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il percorso grafico. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Dimensione dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Le risorse di percorso. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Converte le risorse di percorso nell'istanza [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Le risorse di percorso. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Dimensione dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | L'istanza [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Crea il GraphicsPath usando PathResources da immagine TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Disegna una linea rossa e salva l'immagine
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

