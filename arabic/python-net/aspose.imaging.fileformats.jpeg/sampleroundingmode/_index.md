---
title: "تعداد SampleRoundingMode"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

يحدد طريقة تحويل قيمة n-بت إلى قيمة 8-بت.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| استنتاج | استنتج قيمة ذات 8 بت لتناسبها في n بت، حيث 1 &lt; n &lt; 8.<br/>            عدد جميع القيم الممكنة ذات 8 بت هو 1 &lt;&lt; 8 = 256، من 0 إلى 255.<br/>            عدد جميع القيم الممكنة ذات n بت هو 1 &lt;&lt; n، من 0 إلى (1 &lt;&lt; n) - 1.<br/>            أكثر قيمة n‑بت منطقية Vn المقابلة لقيمة 8‑بت V8 تساوي Vn = V8 &gt;&gt; (8 - n). |
| اقتطاع | اقتطع قيمة ذات 8 بت لتناسبها في n بت، حيث 1 &lt; n &lt; 8.<br/>            عدد جميع القيم الممكنة ذات n بت هو 1 &lt;&lt; n، من 0 إلى (1 &lt;&lt; n) - 1.<br/>            أكثر قيمة n‑بت منطقية Vn المقابلة لقيمة 8‑بت V8 تساوي Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
