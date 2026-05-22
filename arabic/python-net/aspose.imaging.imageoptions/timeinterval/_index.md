---
title: "فئة TimeInterval"
type: docs
weight: 340
url: /ar/python-net/aspose.imaging.imageoptions/timeinterval/
---

**Summary:** Represents the time interval in milliseconds

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TimeInterval

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TimeInterval(from_address, to)](#TimeInterval_from_address_to_1) | ينشئ مثلاً جديداً من الفئة [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| from_address | int | r/w | يحصل أو يعيّن From بالمللي ثانية. |
| to | int | r/w | يحصل أو يعيّن To بالمللي ثانية. |


### Constructor: TimeInterval(from_address, to) {#TimeInterval_from_address_to_1}


```
 TimeInterval(from_address, to) 
```

ينشئ مثلاً جديداً من الفئة [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| from_address | int | From بالمللي ثانية. |
| to | int | To بالمللي ثانية. |

## **Examples**
### Export of part of animation from GIF image based on time interval. {#example_223}
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

