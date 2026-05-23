---
title: "TimeInterval Sınıfı"
type: docs
weight: 340
url: /tr/python-net/aspose.imaging.imageoptions/timeinterval/
---

**Summary:** Represents the time interval in milliseconds

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TimeInterval

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TimeInterval(from_address, to)](#TimeInterval_from_address_to_1) | Yeni bir [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| from_address | int | r/w | From milisaniyelerini alır veya ayarlar. |
| to | int | r/w | To milisaniyelerini alır veya ayarlar. |


### Constructor: TimeInterval(from_address, to) {#TimeInterval_from_address_to_1}


```
 TimeInterval(from_address, to) 
```

Yeni bir [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| from_address | int | From milisaniyeleri. |
| to | int | To milisaniyeleri. |

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

