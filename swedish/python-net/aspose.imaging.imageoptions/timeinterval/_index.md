---
title: "TimeInterval klass"
type: docs
weight: 340
url: /sv/python-net/aspose.imaging.imageoptions/timeinterval/
---

**Summary:** Represents the time interval in milliseconds

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TimeInterval

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TimeInterval(from_address, to)](#TimeInterval_from_address_to_1) | Initierar en ny instans av klassen [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| from_address | int | r/w | Hämtar eller anger From-millisekunder. |
| to | int | r/w | Hämtar eller anger To-millisekunder. |


### Constructor: TimeInterval(from_address, to) {#TimeInterval_from_address_to_1}


```
 TimeInterval(from_address, to) 
```

Initierar en ny instans av klassen [TimeInterval](/imaging/python-net/aspose.imaging.imageoptions/timeinterval/)

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| from_address | int | From-millisekunder. |
| to | int | To-millisekunder. |

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

