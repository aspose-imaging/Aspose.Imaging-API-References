---
title: PdfImageCompressionOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Pdf görüntü sıkıştırma seçenekleri
type: docs
weight: 10100
url: /tr/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

Pdf görüntü sıkıştırma seçenekleri

```csharp
public enum PdfImageCompressionOptions
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Auto | `0` | Her görüntü için en uygun sıkıştırmayı otomatik olarak seçer. |
| None | `1` | Daha büyük pdf dosyası boyutlarıyla sonuçlanan ham görüntü baytlarını kaydeder. |
| Rle | `2` | Çalışma Uzunluğu sıkıştırması. |
| Flate | `3` | Düz sıkıştırma. |
| LzwBaselinePredictor | `4` | Tahmini seçimi, süreci hızlandırmak için PNG Paeth tahmincisi ile sınırlıdır. Uygulamada şaşırtıcı derecede iyi performans gösteriyor. Daha iyiLzwOptimizedPredictor . |
| LzwOptimizedPredictor | `5` | Öngörü seçimi daha karmaşıktır ve daha küçük görüntü boyutlarına neden olur, ancak daha fazla zaman alır. RFC 2083, bunun en iyi yol olduğunu söylüyor. Ancak test veri tabanı tahmincisi üzerindeLzwBaselinePredictor %25-40 sıkıştırma oranı kazancıyla optimize edilmiş tahminci bırakarak kıçı tekmeliyor. |
| Jpeg | `6` | Jpeg sıkıştırma. Şeffaflığı desteklemez. |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Şeffaflığı desteklemez. |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Şeffaflığı desteklemez. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->