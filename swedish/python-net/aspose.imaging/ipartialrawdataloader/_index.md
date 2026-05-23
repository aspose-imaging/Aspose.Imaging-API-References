---
title: "IPartialRawDataLoader-klass"
type: docs
weight: 5530
url: /sv/python-net/aspose.imaging/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialRawDataLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Bearbetar den inlästa datan. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Bearbetar den inlästa datan. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Bearbetar den inlästa datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Daterektangeln. |
| data | System.Byte | Rådata. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Bearbetar den inlästa datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Daterektangeln. |
| data | System.Byte | Rådata. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

