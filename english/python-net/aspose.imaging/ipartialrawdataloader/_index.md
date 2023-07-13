---
title: IPartialRawDataLoader Class
type: docs
weight: 5370
url: /python-net/aspose.imaging/ipartialrawdataloader/
---

The partial data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialRawDataLoader

**Aspose.Imaging Version:** 23.6

The IPartialRawDataLoader type exposes the following members:
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_0) | Processes the loaded data. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_1) | Processes the loaded data. |

### process(rectangle, data, start, end) {#process_rectangle_data_start_end_0}


```
 process(rectangle, data, start, end) 
```

Processes the loaded data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The data rectangle. |
| data | byte | The raw data. |
| start | [Point](/imaging/python-net/aspose.imaging/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](/imaging/python-net/aspose.imaging/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

### process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_1}


```
 process(rectangle, data, start, end, load_options) 
```

Processes the loaded data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The data rectangle. |
| data | byte | The raw data. |
| start | [Point](/imaging/python-net/aspose.imaging/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](/imaging/python-net/aspose.imaging/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

