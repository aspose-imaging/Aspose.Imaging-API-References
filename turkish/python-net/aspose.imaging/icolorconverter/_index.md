---
title: "IColorConverter Sınıfı"
type: docs
weight: 5200
url: /tr/python-net/aspose.imaging/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorConverter

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Geçilen verileri çıktı formatına dönüştürür. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Geçilen verileri çıktı formatına dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Kaynak biçim. |
| veri | System.Byte | Kaynak veri. |
| offset | int | Veri kopyalamanın başlaması gereken bayt cinsinden ofset. |
| bit_start | int | Bit başlangıcı. Bu değerin bayt hizalı bir değer olmadığını, bunun yerine kopyalamanın başlaması gereken gerçek bit olduğunu unutmayın. |
| samples_count | int | Örnek sayısı. |
| lines_count | int | Satır sayısı. |
| dest_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Hedef biçim. |
| output_data | System.Byte | Çıktı verisi. |
| output_offset | int | Veri kopyalamanın başlaması gereken çıktı ofseti. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Dönüştürülen bayt sayısı. |


