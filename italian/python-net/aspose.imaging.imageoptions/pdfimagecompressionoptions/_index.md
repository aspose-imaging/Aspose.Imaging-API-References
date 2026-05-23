---
title: "Enumerazione PdfImageCompressionOptions"
type: docs
weight: 400
url: /it/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

Opzioni di compressione immagine Pdf

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| AUTO | Seleziona automaticamente la compressione più appropriata per ogni immagine. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Non supporta la trasparenza. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Non supporta la trasparenza. |
| FLATE | Compressione Flate. |
| JPEG | Compressione JPEG.<br/>            Non supporta la trasparenza. |
| LZW_BASELINE_PREDICTOR | La selezione del predittore è limitata al predittore PNG Paeth per velocizzare il processo. In pratica<br/>            funziona sorprendentemente bene. È migliore di [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | La selezione del predittore è più complicata e dovrebbe produrre dimensioni di immagine più piccole ma<br/>            richiede più tempo. RFC 2083 afferma che è la soluzione migliore. Tuttavia, sui dati di test il predittore di base [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) è davvero potente, lasciando il predittore ottimizzato indietro <br/>            con un guadagno del 25‑40% nel tasso di compressione. |
| NONE | Salva i byte dell'immagine grezza, risultando in file PDF più grandi. |
| RLE | Compressione Run Length. |
