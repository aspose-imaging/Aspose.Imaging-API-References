---
title: "PdfCoreOptions فئة"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | يُنشئ مثلاً جديدًا من الفئة PdfCoreOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | يحدد المستوى الذي يتم فيه عرض كائنات الإشارات المرجعية في مخطط المستند.<br/>            0 - غير معروض.<br/>            1 في المستوى الأول وهكذا.<br/>            القيمة الافتراضية هي 0. |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | يحصل أو يضبط الضغط. |
| expanded_outline_levels | int | r/w | يحدد عدد المستويات في مخطط المستند التي يتم توسيعها عند عرض ملف PDF.<br/>            0 - مخطط المستند غير موسع.<br/>            1 - عناصر المستوى الأول في المستند مُوسعة وهكذا.<br/>            القيمة الافتراضية هي 0. |
| headings_outline_levels | int | r/w | يحدد عدد مستويات عناصر المخطط التي تُدرج في مخطط المستند.<br/>            0 - لا مخطط، 1 - مستوى مخطط واحد وهكذا.<br/>            القيمة الافتراضية هي 0. |
| jpeg_quality | int | r/w | يحدد جودة ضغط JPEG للصور (إذا تم استخدام ضغط JPEG).<br/>            القيمة الافتراضية هي 95. |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | يحصل أو يعيّن توافق PDF. |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

يُنشئ مثلاً جديدًا من الفئة PdfCoreOptions

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

