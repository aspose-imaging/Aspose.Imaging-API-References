---
title: PdfCoreOptions Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Initializes a new instance of the PdfCoreOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Specifies at which level in the document outline to display bookmark objects.<br/>            0 - not displayed.<br/>            1 at first level and so on.<br/>            Default is 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Gets or sets the compression. |
| expanded_outline_levels | int | r/w | Specifies how many levels in the document outline to show expanded when the PDF file is viewed.<br/>            0 - the document outline is not expanded.<br/>            1 - first level items in the document are expanded and so on.<br/>            Default is 0. |
| headings_outline_levels | int | r/w | Specifies how many levels of outline items to include in the document outline.<br/>            0 - no outline, 1 - one outline level and so on.<br/>            Default is 0. |
| jpeg_quality | int | r/w | Specifies the quality of JPEG compression for images (if JPEG compression is used).<br/>            Default is 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Gets or sets the PDF compliance. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Initializes a new instance of the PdfCoreOptions class

## **Examples**
### Convert EPS image to PDF using PostScript rendering. {#example_203}
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

