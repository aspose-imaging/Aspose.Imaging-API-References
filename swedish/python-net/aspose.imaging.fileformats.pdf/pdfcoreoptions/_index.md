---
title: "PdfCoreOptions klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Initierar en ny instans av PdfCoreOptions-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Anger på vilken nivå i dokumentets innehållsförteckning bokmärkesobjekten ska visas.<br/>            0 - visas inte.<br/>            1 på första nivån och så vidare.<br/>            Standard är 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Hämtar eller anger komprimeringen. |
| expanded_outline_levels | int | r/w | Anger hur många nivåer i dokumentets innehållsförteckning som ska visas expanderade när PDF-filen visas.<br/>            0 - dokumentets innehållsförteckning är inte expanderad.<br/>            1 - objekt på första nivån är expanderade och så vidare.<br/>            Standard är 0. |
| headings_outline_levels | int | r/w | Anger hur många nivåer av innehållsförteckningsobjekt som ska inkluderas i dokumentets innehållsförteckning.<br/>            0 - ingen innehållsförteckning, 1 - en nivå och så vidare.<br/>            Standard är 0. |
| jpeg_quality | int | r/w | Anger kvaliteten på JPEG-komprimering för bilder (om JPEG-komprimering används).<br/>            Standard är 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Hämtar eller anger PDF-efterlevnad. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Initierar en ny instans av PdfCoreOptions-klassen

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

