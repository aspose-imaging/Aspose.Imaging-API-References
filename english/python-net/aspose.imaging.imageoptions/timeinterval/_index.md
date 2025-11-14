---
title: TimeInterval Class
type: docs
weight: 340
url: /python-net/aspose.imaging.imageoptions/timeinterval/
---

**Summary:** Represents the time interval in milliseconds

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TimeInterval

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TimeInterval(from_address, to)](#TimeInterval_from_address_to_1) | Initializes a new instance of the [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| from_address | int | r/w | Gets or sets From milliseconds. |
| to | int | r/w | Gets or sets To milliseconds. |


### Constructor: TimeInterval(from_address, to) {#TimeInterval_from_address_to_1}


```
 TimeInterval(from_address, to) 
```

Initializes a new instance of the [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| from_address | int | From milliseconds. |
| to | int | To milliseconds. |

## **Examples**
### Export of part of animation from GIF image based on time interval. {#example_199}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import GifOptions, MultiPageOptions, MultiPageMode, TimeInterval

with Image.load("Animation.gif") as image:
	obj_init = MultiPageOptions()
	obj_init.mode = MultiPageMode.TIME_INTERVAL
	obj_init.time_interval = TimeInterval(0, 400)
	options = GifOptions()
	options.full_frame = True
	options.multi_page_options = obj_init
	image.save("PartOfAnimation.gif", options)


```

