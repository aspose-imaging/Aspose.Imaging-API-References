---
title: "PdfCoreOptions 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/
---

**Summary:** The common options for convertion to PDF

**Module:** [aspose.imaging.fileformats.pdf](/imaging/python-net/aspose.imaging.fileformats.pdf/)

**Full Name:** aspose.imaging.fileformats.pdf.PdfCoreOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PdfCoreOptions()](#PdfCoreOptions__1) | 初始化 PdfCoreOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bookmarks_outline_level | int | r/w | 指定在文档大纲的哪个层级显示书签对象。<br/>            0 - 不显示。<br/>            1 - 第一级，以此类推。<br/>            默认值为 0。 |
| compression | [PdfImageCompressionOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) | r/w | 获取或设置压缩。 |
| expanded_outline_levels | int | r/w | 指定在查看 PDF 文件时文档大纲展开的层级数。<br/>            0 - 文档大纲不展开。<br/>            1 - 文档的第一级项目展开，依此类推。<br/>            默认值为 0。 |
| headings_outline_levels | int | r/w | 指定在文档大纲中包含多少层级的条目。<br/>            0 - 无大纲，1 - 一个大纲层级，依此类推。<br/>            默认值为 0。 |
| jpeg_quality | int | r/w | 指定图像的 JPEG 压缩质量（如果使用 JPEG 压缩）。<br/>            默认值为 95。 |
| pdf_compliance | [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | r/w | 获取或设置 PDF 合规性。 |


### Constructor: PdfCoreOptions() {#PdfCoreOptions__1}


```
 PdfCoreOptions() 
```

初始化 PdfCoreOptions 类的新实例

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

