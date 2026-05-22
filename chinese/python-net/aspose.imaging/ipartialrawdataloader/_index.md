---
title: "IPartialRawDataLoader 类"
type: docs
weight: 5530
url: /zh/python-net/aspose.imaging/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialRawDataLoader

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | 处理已加载的数据。 |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | 处理已加载的数据。 |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

处理已加载的数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 数据矩形。 |
| 数据 | System.Byte | 原始数据。 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | 起始数据点。如果不等于 (left,top)，则表示我们没有完整的矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | 结束数据点。如果不等于 (right,bottom)，则表示我们没有完整的矩形。 |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

处理已加载的数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 数据矩形。 |
| 数据 | System.Byte | 原始数据。 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | 起始数据点。如果不等于 (left,top)，则表示我们没有完整的矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | 结束数据点。如果不等于 (right,bottom)，则表示我们没有完整的矩形。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

