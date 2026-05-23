---
title: "IColorConverter klass"
type: docs
weight: 5200
url: /sv/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Konverterar den överförda datan till utdataformatet. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Konverterar den överförda datan till utdataformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Källformatet. |
| data | System.Byte | Källdata. |
| offset | int | Förskjutningen i byte där datakopiering ska börja. |
| bit_start | int | Bitstarten. Observera att detta värde inte är bytejusterat utan är den faktiska biten där kopieringen ska börja. |
| samples_count | int | Antalet prover. |
| lines_count | int | Antalet rader. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Målformatet. |
| output_data | System.Byte | Utdatadata. |
| output_offset | int | Utdataskiftet där datakopiering ska starta. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet konverterade byte. |


