---
title: "Перечисление PdfImageCompressionOptions"
type: docs
weight: 400
url: /ru/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

Параметры сжатия изображений Pdf

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| AUTO | Автоматически выбирает наиболее подходящее сжатие для каждого изображения. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Не поддерживает прозрачность. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Не поддерживает прозрачность. |
| FLATE | Сжатие Flate. |
| JPEG | Сжатие JPEG.<br/>            Не поддерживает прозрачность. |
| LZW_BASELINE_PREDICTOR | Выбор предиктора ограничен предиктором PNG Paeth для ускорения процесса. На практике<br/>            работает удивительно хорошо. Лучше, чем [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | Выбор предиктора более сложный и должен приводить к меньшему размеру изображений, но<br/>            требует больше времени. RFC 2083 утверждает, что это лучший способ. Однако на тестовых данных базовый предиктор
            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) показывает отличные результаты, оставляя оптимизированный предиктор позади <br/>            с повышением коэффициента сжатия на 25‑40%. |
| NONE | Сохраняет необработанные байты изображения, что приводит к увеличению размеров PDF‑файла. |
| RLE | Сжатие Run Length. |
