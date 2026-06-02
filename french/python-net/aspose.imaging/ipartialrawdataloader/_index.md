---
title: "Classe IPartialRawDataLoader"
type: docs
weight: 5530
url: /fr/python-net/aspose.imaging/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialRawDataLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Traite les données chargées. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Traite les données chargées. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Traite les données chargées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de données. |
| données | System.Byte | Les données brutes. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Le point de données de départ. S'il n'est pas égal à (left,top), cela signifie que nous n'avons pas de rectangle complet. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Le point de données final. S'il n'est pas égal à (right,bottom), cela signifie que nous n'avons pas de rectangle complet. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Traite les données chargées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de données. |
| données | System.Byte | Les données brutes. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Le point de données de départ. S'il n'est pas égal à (left,top), cela signifie que nous n'avons pas de rectangle complet. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Le point de données final. S'il n'est pas égal à (right,bottom), cela signifie que nous n'avons pas de rectangle complet. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

