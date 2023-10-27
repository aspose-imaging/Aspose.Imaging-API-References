---
title: IRasterImageArgb64PixelLoader Class
type: docs
weight: 5350
url: /python-net/aspose.imaging/irasterimageargb64pixelloader/
---

**Summary:** The raster image 64-bit ARGB pixel loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IRasterImageArgb64PixelLoader

**Inheritance:** IRasterImageRawDataLoader

**Aspose.Imaging Version:** 23.10.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_1) | Loads 64-bit ARGB pixels partially (by blocks). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Loads raw data. |


### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader) | The partial pixel loader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load raw data from. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader) | The raw data loader. |

