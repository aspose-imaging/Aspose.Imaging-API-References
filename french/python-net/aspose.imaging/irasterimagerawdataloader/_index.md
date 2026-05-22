---
title: "Classe IRasterImageRawDataLoader"
type: docs
weight: 5570
url: /fr/python-net/aspose.imaging/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IRasterImageRawDataLoader

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | Obtient une valeur indiquant si le chargement de données brutes est pris en charge. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtient les paramètres actuels des données brutes. Notez qu'en utilisant ces paramètres, les données se chargent sans conversion. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | Charge des données brutes. |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Charge des données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas dans le format spécifié, une conversion des données sera effectuée. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Le chargeur de données brutes. |

