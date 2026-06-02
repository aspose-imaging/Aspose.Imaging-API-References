---
title: "IRasterImageRawDataLoader 类"
type: docs
weight: 5570
url: /zh/python-net/aspose.imaging/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IRasterImageRawDataLoader

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | 获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | 加载原始数据。 |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

加载原始数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于加载原始数据的矩形。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | 原始数据加载器。 |

