---
title: HdrImageOptions Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/
---

**Summary:** The hdr image options

**Module:** [aspose.imaging.fileformats.core.photo.hdr](/imaging/python-net/aspose.imaging.fileformats.core.photo.hdr/)

**Full Name:** aspose.imaging.fileformats.core.photo.hdr.HdrImageOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [HdrImageOptions()](#HdrImageOptions__1) | Initializes a new instance of the HdrImageOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [align_images](#align_images1) | bool | r/w | Gets or sets a value indicating whether [align images]. |
| [sample_count](#sample_count2) | int | r/w | Gets or sets the sample count. |
| [smooth_factor](#smooth_factor3) | int | r/w | Gets or sets the smooth factor. |


### Constructor: HdrImageOptions() {#HdrImageOptions__1}


```
 HdrImageOptions() 
```

Initializes a new instance of the HdrImageOptions class

### Property: align_images {#align_images1}

Gets or sets a value indicating whether [align images].

**See also:**

**[Example # 1](#example_249)**: The example shows how HDR processing is carried out.


### Property: sample_count {#sample_count2}

Gets or sets the sample count.

**See also:**

**[Example # 1](#example_249)**: The example shows how HDR processing is carried out.


### Property: smooth_factor {#smooth_factor3}

Gets or sets the smooth factor.

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

