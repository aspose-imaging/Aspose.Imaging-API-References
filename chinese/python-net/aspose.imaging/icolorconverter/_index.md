---
title: "IColorConverter 类"
type: docs
weight: 5200
url: /zh/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | 将传入的数据转换为输出格式。 |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

将传入的数据转换为输出格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | 源格式。 |
| 数据 | System.Byte | 源数据。 |
| offset | int | 数据复制应开始的字节偏移量。 |
| bit_start | int | 位起始位置。注意，此值不是字节对齐的值，而是实际的位，复制应从此位开始。 |
| samples_count | int | 样本计数。 |
| lines_count | int | 行计数。 |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | 目标格式。 |
| output_data | System.Byte | 输出数据。 |
| output_offset | int | 数据复制应开始的输出偏移量。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 已转换的字节计数。 |


