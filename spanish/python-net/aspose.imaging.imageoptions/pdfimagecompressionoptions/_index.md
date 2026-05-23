---
title: "Enumeración PdfImageCompressionOptions"
type: docs
weight: 400
url: /es/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

Opciones de compresión de imágenes Pdf

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| AUTO | Selecciona automáticamente la compresión más adecuada para cada imagen. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            No admite transparencia. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            No admite transparencia. |
| FLATE | Compresión Flate. |
| JPEG | Compresión JPEG.<br/>            No admite transparencia. |
| LZW_BASELINE_PREDICTOR | La selección del predictor está restringida al predictor PNG Paeth para acelerar el proceso. En la práctica<br/>            funciona sorprendentemente bien. Mejor que [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | La selección del predictor es más complicada y debería resultar en tamaños de imagen más pequeños pero<br/>            lleva más tiempo. RFC 2083 dice que es la mejor opción. Pero en los datos de prueba el predictor de referencia
            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) es impresionante dejando al predictor optimizado atrás <br/>            con una ganancia de tasa de compresión del 25-40%. |
| NONE | Guarda los bytes de imagen sin procesar, lo que resulta en archivos PDF más grandes. |
| RLE | Compresión Run Length. |
