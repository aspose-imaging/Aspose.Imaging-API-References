---
title: "تعداد PdfImageCompressionOptions"
type: docs
weight: 400
url: /ar/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

خيارات ضغط صور Pdf

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| AUTO | يختار تلقائيًا أنسب ضغط لكل صورة. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            لا يدعم الشفافية. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            لا يدعم الشفافية. |
| FLATE | ضغط Flate. |
| JPEG | ضغط Jpeg.<br/>            لا يدعم الشفافية. |
| LZW_BASELINE_PREDICTOR | اختيار Predictor مقيد بـ PNG Paeth predictor لتسريع العملية. في الممارسة العملية<br/>            يؤدي أداءً مفاجئًا جيدًا. أفضل من [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | اختيار Predictor أكثر تعقيدًا ويجب أن ينتج أحجام صور أصغر ولكن<br/>            يستغرق وقتًا أطول. تقول RFC 2083 إنه الطريقة المثلى. لكن على بيانات الاختبار، baseline predictor<br/>            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) يتفوق، مما يترك optimized predictor خلفه <br/>            بزيادة معدل ضغط يتراوح بين 25-40٪. |
| NONE | يحفظ بايتات الصورة الخام مما يؤدي إلى أحجام ملفات PDF أكبر. |
| RLE | ضغط Run Length. |
