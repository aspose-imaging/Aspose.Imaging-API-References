---
title: "PdfImageCompressionOptions Aufzählung"
type: docs
weight: 400
url: /de/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

PDF-Bildkomprimierungsoptionen

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| AUTO | Wählt automatisch die am besten geeignete Kompression für jedes Bild aus. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Unterstützt keine Transparenz. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Unterstützt keine Transparenz. |
| FLATE | Flate-Kompression. |
| JPEG | Jpeg-Kompression.<br/>            Unterstützt keine Transparenz. |
| LZW_BASELINE_PREDICTOR | Die Prädiktorauswahl ist auf den PNG Paeth-Prädiktor beschränkt, um den Vorgang zu beschleunigen. In der Praxis<br/>            liefert sie überraschend gute Ergebnisse. Besser als [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | Die Prädiktorauswahl ist komplexer und sollte zu kleineren Bildgrößen führen, jedoch<br/>            mehr Zeit benötigen. RFC 2083 besagt, dass dies der beste Ansatz ist. Aber bei den Testdaten schlägt der Basis‑Prädiktor
            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) stark zu, sodass der optimierte Prädiktor um <br/>            25‑40 % geringere Kompressionsraten erzielt. |
| NONE | Speichert Rohbildbytes, was zu größeren PDF-Dateigrößen führt. |
| RLE | Run‑Length-Kompression. |
