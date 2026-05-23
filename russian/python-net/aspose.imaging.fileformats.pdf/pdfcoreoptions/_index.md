---
title: "Класс PdfCoreOptions"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | Инициализирует новый экземпляр класса PdfCoreOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Указывает, на каком уровне в структуре документа отображать объекты закладок.<br/>            0 - не отображается.<br/>            1 - на первом уровне и далее.<br/>            По умолчанию 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Получает или задает сжатие. |
| expanded_outline_levels | int | r/w | Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре PDF‑файла.<br/>            0 - структура документа не развернута.<br/>            1 - элементы первого уровня развернуты и далее.<br/>            По умолчанию 0. |
| headings_outline_levels | int | r/w | Указывает, сколько уровней элементов структуры включать в структуру документа.<br/>            0 - без структуры, 1 - один уровень структуры и далее.<br/>            По умолчанию 0. |
| jpeg_quality | int | r/w | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие).<br/>            По умолчанию 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | Получает или задает соответствие PDF. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

Инициализирует новый экземпляр класса PdfCoreOptions

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

