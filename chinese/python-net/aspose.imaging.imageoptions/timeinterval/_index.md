---
title: "TimeInterval 类"
type: docs
weight: 340
url: /zh/python-net/aspose.imaging.imageoptions/timeinterval/
---

**Summary:** Represents the time interval in milliseconds

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TimeInterval

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TimeInterval(from_address, to)](#TimeInterval_from_address_to_1) | 初始化一个新的 [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| from_address | int | r/w | 获取或设置 From 毫秒。 |
| to | int | r/w | 获取或设置 To 毫秒。 |


### Constructor: TimeInterval(from_address, to) {#TimeInterval_from_address_to_1}


```
 TimeInterval(from_address, to) 
```

初始化一个新的 [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| from_address | int | From 毫秒。 |
| to | int | To 毫秒。 |

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

