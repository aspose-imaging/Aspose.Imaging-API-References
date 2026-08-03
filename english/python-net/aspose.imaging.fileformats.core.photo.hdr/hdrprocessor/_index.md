---
title: HdrProcessor Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/
---

**Summary:** The HDR processor

**Module:** [aspose.imaging.fileformats.core.photo.hdr](/imaging/python-net/aspose.imaging.fileformats.core.photo.hdr/)

**Full Name:** aspose.imaging.fileformats.core.photo.hdr.HdrProcessor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(images, options)](#process_images_options_1) | Processes the specified images. |


### Method: process(images, options)  [static] {#process_images_options_1}


```
 process(images, options) 
```

Processes the specified images.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [RasterImage[]](/imaging/python-net/aspose.imaging/rasterimage/) | The images. |
| options | [HdrImageOptions](/imaging/python-net/aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/) | The options. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Array of ARGB pixels |



**See also:**

**[Example # 1](#example_249)**: The example shows how HDR processing is carried out.


## **Examples**
### The example shows how HDR processing is carried out. {#example_249}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, RasterImage
from aspose.imaging.fileformats.core.photo.hdr import HdrImageOptions, HdrProcessor
from aspose.imaging.fileformats.png import PngImage

image1 = "DSC_6912.JPG"
image2 = "DSC_6913.JPG"
image3 = "DSC_6914.JPG"
align = True
result_file_path = f"{image1}_result.jpg"
images = [None] * (3)
images[0] = aspycore.as_of(Image.load(image1), RasterImage)
images[1] = aspycore.as_of(Image.load(image2), RasterImage)
images[2] = aspycore.as_of(Image.load(image3), RasterImage)
try:
	obj_init = HdrImageOptions()
	obj_init.sample_count = 100
	obj_init.smooth_factor = 200
	obj_init.align_images = align
	pixels = HdrProcessor.process(images, obj_init)
	with PngImage(images[0].width, images[0].height) as image:
		image.save_argb_32_pixels(image.bounds, pixels)
		image.save(result_file_path)
finally:
	# perform disposing the images
	for image in images:
		with image as _:
			pass


```

