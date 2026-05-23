---
title: "IPartialRawDataLoader Klasse"
type: docs
weight: 5530
url: /de/python-net/aspose.imaging/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialRawDataLoader

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Verarbeitet die geladenen Daten. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Verarbeitet die geladenen Daten. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Verarbeitet die geladenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Datenrechteck. |
| Daten | System.Byte | Die Rohdaten. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Der Startdatenpunkt. Wenn er nicht gleich (left,top) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Der Enddatenpunkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Verarbeitet die geladenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Datenrechteck. |
| Daten | System.Byte | Die Rohdaten. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Der Startdatenpunkt. Wenn er nicht gleich (left,top) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Der Enddatenpunkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

