---
title: "SampleRoundingMode Sıralaması"
type: docs
weight: 80
url: /tr/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

n-bit değerinin 8-bit değere nasıl dönüştürüleceğini tanımlar.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| EKSTRAPOLE | 8-bit bir değeri n bite sığdırmak için ekstrapole eder, burada 1 &lt; n &lt; 8.<br/>            Tüm olası 8-bit değerlerin sayısı 1 &lt;&lt; 8 = 256'dır, 0'dan 255'e.<br/>            Tüm olası n-bit değerlerin sayısı 1 &lt;&lt; n, 0'dan (1 &lt;&lt; n) - 1'e.<br/>            Bazı 8-bit değer V8'e karşılık gelen en makul n-bit değer Vn, Vn = V8 &gt;&gt; (8 - n) eşittir. |
| KIRP | 8-bit bir değeri n bite sığdırmak için kırpar, burada 1 &lt; n &lt; 8.<br/>            Tüm olası n-bit değerlerin sayısı 1 &lt;&lt; n, 0'dan (1 &lt;&lt; n) - 1'e.<br/>            Bazı 8-bit değer V8'e karşılık gelen en makul n-bit değer Vn, Vn = V8 &amp; ((1 &lt;&lt; n) - 1) eşittir. |
