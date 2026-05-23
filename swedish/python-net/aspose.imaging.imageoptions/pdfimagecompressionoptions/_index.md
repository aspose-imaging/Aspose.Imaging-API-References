---
title: "PdfImageCompressionOptions uppräkning"
type: docs
weight: 400
url: /sv/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

PDF-bildkomprimeringsalternativ

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Member name** | **Description** |
| :- | :- |
| AUTO | Väljer automatiskt den mest lämpliga komprimeringen för varje bild. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Stöder inte transparens. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Stöder inte transparens. |
| FLATE | Flate-komprimering. |
| JPEG | Jpeg-komprimering.<br/>            Stöder inte transparens. |
| LZW_BASELINE_PREDICTOR | Prediktorvalet är begränsat till PNG Paeth-prediktor för att påskynda processen. I praktiken<br/>            presterar det förvånansvärt bra. Bättre än [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | Prediktorvalet är mer komplicerat och bör resultera i mindre bildstorlekar men<br/>            tar mer tid. RFC 2083 säger att det är det bästa sättet. Men på testdata ger baslinjeprediktorn
            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) en kraftig förbättring jämfört med den optimerade prediktorn <br/>            med 25‑40 % högre komprimeringsgrad. |
| NONE | Sparar råa bildbytes vilket resulterar i större pdf-filstorlekar. |
| RLE | Run Length-komprimering. |
