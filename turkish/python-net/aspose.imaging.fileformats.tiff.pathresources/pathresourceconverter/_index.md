---
title: "PathResourceConverter Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---

**Summary:** Converts [PathResource](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) to [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) and vice versa.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResourceConverter

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [from_graphics_path(graphics_path, image_size)](#from_graphics_path_graphics_path_image_size_1) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) örneğini yol kaynaklarına dönüştürür. |
| [to_graphics_path(path_resources, image_size)](#to_graphics_path_path_resources_image_size_2) | Yol kaynaklarını [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) örneğine dönüştürür. |


### Method: from_graphics_path(graphics_path, image_size)  [static] {#from_graphics_path_graphics_path_image_size_1}


```
 from_graphics_path(graphics_path, image_size) 
```

[GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) örneğini yol kaynaklarına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Grafik yolu. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Resmin boyutu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Yol kaynakları. |


### Method: to_graphics_path(path_resources, image_size)  [static] {#to_graphics_path_path_resources_image_size_2}


```
 to_graphics_path(path_resources, image_size) 
```

Yol kaynaklarını [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) örneğine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_resources | [PathResource[]](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/) | Yol kaynakları. |
| image_size | [Size](/imaging/python-net/aspose.imaging/size/) | Resmin boyutu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) örneği. |


## **Examples**
### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# TIFF görüntüsünden PathResources kullanarak GraphicsPath oluştur.
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Kırmızı çizgi çiz ve resmi kaydet
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

