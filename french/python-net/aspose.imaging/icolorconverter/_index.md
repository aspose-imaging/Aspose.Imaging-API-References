---
title: "IColorConverter Classe"
type: docs
weight: 5200
url: /fr/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Convertit les données transmises au format de sortie. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Convertit les données transmises au format de sortie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Le format source. |
| données | System.Byte | Les données source. |
| offset | int | Le décalage en octets où la copie des données doit commencer. |
| bit_start | int | Le début du bit. Notez que cette valeur n'est pas alignée sur un octet, mais correspond au bit réel où la copie doit commencer. |
| samples_count | int | Le nombre d'échantillons. |
| lines_count | int | Le nombre de lignes. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Le format de destination. |
| output_data | System.Byte | Les données de sortie. |
| output_offset | int | Le décalage de sortie où la copie des données doit commencer. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre d'octets convertis. |


