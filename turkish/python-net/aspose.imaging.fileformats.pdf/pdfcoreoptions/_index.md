---
title: "PdfCoreOptions Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | PdfCoreOptions sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | Belge taslağında yer imleri nesnelerinin hangi seviyede görüntüleneceğini belirtir.<br/>            0 - görüntülenmez.<br/>            1 - ilk seviyede ve devamında.<br/>            Varsayılan değer 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | Sıkıştırmayı alır veya ayarlar. |
| expanded_outline_levels | int | r/w | PDF dosyası görüntülendiğinde belge taslağında kaç seviyenin genişletilmiş gösterileceğini belirtir.<br/>            0 - belge taslağı genişletilmez.<br/>            1 - belge içindeki ilk seviye öğeleri genişletilir ve devam eder.<br/>            Varsayılan değer 0. |
| headings_outline_levels | int | r/w | Belge taslağına kaç seviye başlık öğesi ekleneceğini belirtir.<br/>            0 - taslak yok, 1 - bir taslak seviyesi ve devamı.<br/>            Varsayılan değer 0. |
| jpeg_quality | int | r/w | Görüntüler için JPEG sıkıştırma kalitesini belirtir (JPEG sıkıştırma kullanılıyorsa).<br/>            Varsayılan değer 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | PDF uyumluluğunu alır veya ayarlar. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

PdfCoreOptions sınıfının yeni bir örneğini başlatır.

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

