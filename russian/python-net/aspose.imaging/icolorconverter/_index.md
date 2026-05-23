---
title: "Класс IColorConverter"
type: docs
weight: 5200
url: /ru/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Преобразует переданные данные в выходной формат. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Преобразует переданные данные в выходной формат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Исходный формат. |
| данные | System.Byte | Исходные данные. |
| offset | int | Смещение в байтах, с которого должно начаться копирование данных. |
| bit_start | int | Начало бита. Обратите внимание, что это значение не выровнено по байту, а представляет собой фактический бит, с которого должно начаться копирование. |
| samples_count | int | Количество образцов. |
| lines_count | int | Количество строк. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Целевой формат. |
| output_data | System.Byte | Выходные данные. |
| output_offset | int | Смещение вывода, с которого должно начаться копирование данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество преобразованных байтов. |


