---
title: "IColorConverter Klasse"
type: docs
weight: 5200
url: /de/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Konvertiert die übergebenen Daten in das Ausgabeformat. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Konvertiert die übergebenen Daten in das Ausgabeformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Das Quellformat. |
| Daten | System.Byte | Die Quelldaten. |
| offset | int | Der Offset in Bytes, an dem das Kopieren von Daten beginnen soll. |
| bit_start | int | Der Bit-Start. Hinweis: Dieser Wert ist nicht byte‑ausgerichtet, sondern das tatsächliche Bit, an dem das Kopieren beginnen soll. |
| samples_count | int | Die Anzahl der Samples. |
| lines_count | int | Die Zeilenanzahl. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Das Zielformat. |
| output_data | System.Byte | Die Ausgabedaten. |
| output_offset | int | Der Ausgabe-Offset, an dem das Kopieren von Daten beginnen soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl der konvertierten Bytes. |


