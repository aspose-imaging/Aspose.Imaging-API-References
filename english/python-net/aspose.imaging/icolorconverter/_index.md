---
title: IColorConverter Class
type: docs
weight: 5160
url: /python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Converts the passed data to the output format. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Converts the passed data to the output format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | The source format. |
| data | System.Byte | The source data. |
| offset | int | The offset in bytes where data copying should begin. |
| bit_start | int | The bit start. Note this value is not byte aligned value instead this is actual bit where copying should begin. |
| samples_count | int | The samples count. |
| lines_count | int | The lines count. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | The destination format. |
| output_data | System.Byte | The output data. |
| output_offset | int | The output offset where data copying should start. |

**Returns**

| Type | Description |
| :- | :- |
| int | The converted bytes count. |


