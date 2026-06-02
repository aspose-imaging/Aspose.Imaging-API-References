---
title: "PdfCoreOptions Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Initialisiert eine neue Instanz der PdfCoreOptions Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Gibt an, auf welcher Ebene in der Dokumentgliederung Lesezeichenobjekte angezeigt werden.<br/>            0 - nicht angezeigt.<br/>            1 auf erster Ebene und so weiter.<br/>            Standard ist 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Liest oder setzt die Kompression. |
| expanded_outline_levels | int | r/w | Gibt an, wie viele Ebenen in der Dokumentgliederung beim Anzeigen der PDF-Datei erweitert angezeigt werden sollen.<br/>            0 - die Dokumentgliederung ist nicht erweitert.<br/>            1 - Elemente der ersten Ebene sind erweitert und so weiter.<br/>            Standard ist 0. |
| headings_outline_levels | int | r/w | Gibt an, wie viele Ebenen von Gliederungspunkten in die Dokumentgliederung aufgenommen werden sollen.<br/>            0 - keine Gliederung, 1 - eine Gliederungsebene und so weiter.<br/>            Standard ist 0. |
| jpeg_quality | int | r/w | Gibt die Qualität der JPEG-Kompression für Bilder an (wenn JPEG-Kompression verwendet wird).<br/>            Standard ist 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Liest oder setzt die PDF-Konformität. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Initialisiert eine neue Instanz der PdfCoreOptions Klasse

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

