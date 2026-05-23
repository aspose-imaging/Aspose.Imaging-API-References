---
title: "IColorConverter Classe"
type: docs
weight: 5200
url: /it/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Converte i dati forniti nel formato di output. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Converte i dati forniti nel formato di output.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Il formato di origine. |
| dati | System.Byte | I dati di origine. |
| offset | int | L'offset in byte dove dovrebbe iniziare la copia dei dati. |
| bit_start | int | L'inizio del bit. Nota che questo valore non è allineato a byte, ma è il bit reale dove dovrebbe iniziare la copia. |
| samples_count | int | Il conteggio dei campioni. |
| lines_count | int | Il conteggio delle linee. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Il formato di destinazione. |
| output_data | System.Byte | I dati di output. |
| output_offset | int | L'offset di output dove dovrebbe iniziare la copia dei dati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il conteggio dei byte convertiti. |


