---
title: "الفئة IColorConverter"
type: docs
weight: 5200
url: /ar/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | يحول البيانات الممررة إلى صيغة الإخراج. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

يحول البيانات الممررة إلى صيغة الإخراج.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | تنسيق المصدر. |
| البيانات | System.Byte | بيانات المصدر. |
| offset | int | الإزاحة بالبايت حيث يجب أن يبدأ نسخ البيانات. |
| bit_start | int | بداية البت. لاحظ أن هذه القيمة ليست قيمة محاذاة بالبايت بل هي البت الفعلي حيث يجب أن يبدأ النسخ. |
| samples_count | int | عدد العينات. |
| lines_count | int | عدد الأسطر. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | تنسيق الوجهة. |
| output_data | System.Byte | بيانات الإخراج. |
| output_offset | int | إزاحة الإخراج حيث يجب أن يبدأ نسخ البيانات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | عدد البايتات المحوّلة. |


