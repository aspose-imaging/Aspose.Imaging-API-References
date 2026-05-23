---
title: "PdfImageCompressionOptions Sınıflandırması"
type: docs
weight: 400
url: /tr/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

PDF görüntü sıkıştırma seçenekleri

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| AUTO | Her görüntü için en uygun sıkıştırmayı otomatik olarak seçer. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Şeffaflığı desteklemez. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Şeffaflığı desteklemez. |
| FLATE | Flate sıkıştırması. |
| JPEG | Jpeg sıkıştırması.<br/>            Şeffaflığı desteklemez. |
| LZW_BASELINE_PREDICTOR | Tahminci seçimi, işlemi hızlandırmak için PNG Paeth tahmincisine sınırlıdır. Pratikte<br/>            şaşırtıcı derecede iyi çalışır. Daha iyisi [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | Tahminci seçimi daha karmaşıktır ve daha küçük görüntü boyutları sağlamalıdır ancak daha fazla zaman alır.<br/>            RFC 2083 buna en iyi yol olduğunu söylüyor. Ancak test verilerinde temel tahminci [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) çok iyi çalışıyor ve optimize edilmiş tahmincinin %25-40 arasında sıkıştırma oranı kazancı bırakıyor. |
| NONE | Ham görüntü baytlarını kaydeder, bu da daha büyük pdf dosya boyutlarına yol açar. |
| RLE | Run Length sıkıştırması. |
