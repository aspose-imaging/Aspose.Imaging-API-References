---
title: "PdfCoreOptions Clase"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Inicializa una nueva instancia de la clase PdfCoreOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Especifica en qué nivel del esquema del documento se deben mostrar los objetos de marcador.<br/>            0 - no se muestra.<br/>            1 en el primer nivel y así sucesivamente.<br/>            El valor predeterminado es 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Obtiene o establece la compresión. |
| expanded_outline_levels | int | r/w | Especifica cuántos niveles del esquema del documento se deben mostrar expandidos cuando se visualiza el archivo PDF.<br/>            0 - el esquema del documento no está expandido.<br/>            1 - los elementos del primer nivel del documento están expandidos y así sucesivamente.<br/>            El valor predeterminado es 0. |
| headings_outline_levels | int | r/w | Especifica cuántos niveles de elementos del esquema se deben incluir en el esquema del documento.<br/>            0 - sin esquema, 1 - un nivel de esquema y así sucesivamente.<br/>            El valor predeterminado es 0. |
| jpeg_quality | int | r/w | Especifica la calidad de la compresión JPEG para imágenes (si se utiliza compresión JPEG).<br/>            El valor predeterminado es 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Obtiene o establece la conformidad PDF. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Inicializa una nueva instancia de la clase PdfCoreOptions

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

