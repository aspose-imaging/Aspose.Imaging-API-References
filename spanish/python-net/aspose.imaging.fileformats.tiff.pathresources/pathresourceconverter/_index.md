---
title: "Clase PathResourceConverter"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Convierte la instancia de [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) a recursos de ruta. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Convierte los recursos de ruta a la instancia de [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Convierte la instancia de [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) a recursos de ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La ruta gráfica. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Tamaño de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Los recursos de ruta. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Convierte los recursos de ruta a la instancia de [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Los recursos de ruta. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Tamaño de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La instancia de [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Crea el GraphicsPath usando PathResources de una imagen TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Dibujar una línea roja y guardar la imagen
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

