---
title: "IPartialRawDataLoader Класс"
type: docs
weight: 5530
url: /ru/python-net/aspose.imaging/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialRawDataLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Обрабатывает загруженные данные. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Обрабатывает загруженные данные. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Обрабатывает загруженные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник данных. |
| данные | System.Byte | The raw data. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Начальная точка данных. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Конечная точка данных. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Обрабатывает загруженные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник данных. |
| данные | System.Byte | The raw data. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Начальная точка данных. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Конечная точка данных. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

