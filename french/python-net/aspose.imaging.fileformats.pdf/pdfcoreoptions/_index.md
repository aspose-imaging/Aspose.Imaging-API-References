---
title: "Classe PdfCoreOptions"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Initialise une nouvelle instance de la classe PdfCoreOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Spécifie à quel niveau dans le plan du document afficher les objets de signet.<br/>            0 - non affiché.<br/>            1 au premier niveau et ainsi de suite.<br/>            La valeur par défaut est 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Obtient ou définit la compression. |
| expanded_outline_levels | int | r/w | Spécifie combien de niveaux du plan du document doivent être affichés développés lorsque le fichier PDF est visualisé.<br/>            0 - le plan du document n'est pas développé.<br/>            1 - les éléments du premier niveau du document sont développés et ainsi de suite.<br/>            La valeur par défaut est 0. |
| headings_outline_levels | int | r/w | Spécifie combien de niveaux d'éléments de plan inclure dans le plan du document.<br/>            0 - aucun plan, 1 - un niveau de plan et ainsi de suite.<br/>            La valeur par défaut est 0. |
| jpeg_quality | int | r/w | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée).<br/>            La valeur par défaut est 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Obtient ou définit la conformité PDF. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Initialise une nouvelle instance de la classe PdfCoreOptions

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

