---
title: "تعداد SampleRoundingMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Jpeg.SampleRoundingMode. يحدد طريقة تحويل قيمة nbit إلى قيمة 8bit"
type: docs
weight: 6910
url: /ar/net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

يحدد طريقة تحويل قيمة n-بت إلى قيمة 8-بت.

```csharp
public enum SampleRoundingMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Extrapolate | `0` | استخرج قيمة 8‑بت لتلائمها في n بت، حيث 1 < n < 8. عدد جميع القيم الممكنة ذات 8 بت هو 1 << 8 = 256، من 0 إلى 255. عدد جميع القيم الممكنة ذات n بت هو 1 << n، من 0 إلى (1 << n) - 1. أكثر قيمة n‑بت منطقية Vn المقابلة لبعض قيمة 8‑بت V8 تساوي Vn = V8 >> (8 - n). |
| Truncate | `1` | اقص قيمة 8‑بت لتلائمها في n بت، حيث 1 < n < 8. عدد جميع القيم الممكنة ذات n بت هو 1 << n، من 0 إلى (1 << n) - 1. أكثر قيمة n‑بت منطقية Vn المقابلة لبعض قيمة 8‑بت V8 تساوي Vn = V8 & ((1 << n) - 1). |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg/)
* assembly [Aspose.Imaging](../../)


