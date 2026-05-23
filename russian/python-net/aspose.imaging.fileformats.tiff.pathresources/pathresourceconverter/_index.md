---
title: "PathResourceConverter Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | Преобразует экземпляр [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в ресурсы пути. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Преобразует ресурсы пути в экземпляр [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

Преобразует экземпляр [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в ресурсы пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Графический путь. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Размер изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Ресурсы пути. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Преобразует ресурсы пути в экземпляр [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Ресурсы пути. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Размер изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Экземпляр [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Создайте GraphicsPath, используя PathResources из TIFF‑изображения
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Нарисовать красную линию и сохранить изображение
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

