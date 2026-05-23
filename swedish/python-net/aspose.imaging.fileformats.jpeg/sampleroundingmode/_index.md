---
title: "SampleRoundingMode enumeration"
type: docs
weight: 80
url: /sv/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

Definierar ett sätt att konvertera ett n-bitars värde till ett 8-bitars värde.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EXTRAPOLERA | Extrapolera ett 8‑bitars värde för att passa in i n bitar, där 1 &lt; n &lt; 8.<br/>            Antalet möjliga 8‑bitarsvärden är 1 &lt;&lt; 8 = 256, från 0 till 255.<br/>            Antalet möjliga n‑bitarsvärden är 1 &lt;&lt; n, från 0 till (1 &lt;&lt; n) - 1.<br/>            Det mest rimliga n‑bitarsvärdet Vn som motsvarar ett 8‑bitarsvärde V8 är lika med Vn = V8 &gt;&gt; (8 - n). |
| TRUNKERA | Trunkera ett 8‑bitars värde för att passa in i n bitar, där 1 &lt; n &lt; 8.<br/>            Antalet möjliga n‑bitarsvärden är 1 &lt;&lt; n, från 0 till (1 &lt;&lt; n) - 1.<br/>            Det mest rimliga n‑bitarsvärdet Vn som motsvarar ett 8‑bitarsvärde V8 är lika med Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
