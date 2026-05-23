---
title: "IRasterImageRawDataLoader klass"
type: docs
weight: 5570
url: /sv/python-net/aspose.imaging/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IRasterImageRawDataLoader

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Hämtar de aktuella inställningarna för rådata. Observera att när dessa inställningar används laddas data utan konvertering. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | Läser in rådata. |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Läser in rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda rådata från. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Inställningarna för rådata att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Rådatainläsaren. |

