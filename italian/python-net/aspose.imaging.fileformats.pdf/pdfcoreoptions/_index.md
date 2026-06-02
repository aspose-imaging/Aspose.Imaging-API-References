---
title: "PdfCoreOptions Classe"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Inizializza una nuova istanza della classe PdfCoreOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Specifica a quale livello nella struttura del documento visualizzare gli oggetti segnalibro.<br/>            0 - non visualizzato.<br/>            1 al primo livello e così via.<br/>            Il valore predefinito è 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Ottiene o imposta la compressione. |
| expanded_outline_levels | int | r/w | Specifica quanti livelli nella struttura del documento mostrare espansi quando il file PDF viene visualizzato.<br/>            0 - la struttura del documento non è espansa.<br/>            1 - gli elementi del primo livello nel documento sono espansi e così via.<br/>            Il valore predefinito è 0. |
| headings_outline_levels | int | r/w | Specifica quanti livelli di voci della struttura includere nella struttura del documento.<br/>            0 - nessuna struttura, 1 - un livello di struttura e così via.<br/>            Il valore predefinito è 0. |
| jpeg_quality | int | r/w | Specifica la qualità della compressione JPEG per le immagini (se viene utilizzata la compressione JPEG).<br/>            Il valore predefinito è 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Ottiene o imposta la conformità PDF. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Inizializza una nuova istanza della classe PdfCoreOptions

## **Examples**
### Convert EPS image to PDF using PostScript rendering. {#example_206}
``` python

from aspose.imaging import Image, PdfComplianceVersion
from aspose.imaging.imageoptions import PdfOptions
from aspose.imaging.fileformats.pdf import PdfCoreOptions

with Image.load("Sample.eps") as image:
	options = PdfOptions()
	options.pdf_core_options = PdfCoreOptions()
	options.pdf_core_options.pdf_compliance = PdfComplianceVersion.PDF_A1B # Set required PDF compliance
	image.save("Sample.pdf", options)


```

