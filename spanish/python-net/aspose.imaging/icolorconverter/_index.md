---
title: "IColorConverter Clase"
type: docs
weight: 5200
url: /es/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Convierte los datos proporcionados al formato de salida. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Convierte los datos proporcionados al formato de salida.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | El formato de origen. |
| datos | System.Byte | Los datos de origen. |
| offset | int | El desplazamiento en bytes donde debe comenzar la copia de datos. |
| bit_start | int | El inicio de bit. Nota que este valor no está alineado a bytes; en su lugar es el bit real donde debe comenzar la copia. |
| samples_count | int | El recuento de muestras. |
| lines_count | int | El recuento de líneas. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | El formato de destino. |
| output_data | System.Byte | Los datos de salida. |
| output_offset | int | El desplazamiento de salida donde debe comenzar la copia de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El recuento de bytes convertidos. |


