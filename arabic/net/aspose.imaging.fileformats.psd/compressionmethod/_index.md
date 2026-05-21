---
title: "عدد التعداد CompressionMethod"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Psd.CompressionMethod عدد التعداد. يحدد طريقة الضغط المستخدمة لبيانات الصورة"
type: docs
weight: 7580
url: /ar/net/aspose.imaging.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

يحدد طريقة الضغط المستخدمة لبيانات الصورة.

```csharp
public enum CompressionMethod : short
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Raw | `0` | بدون ضغط. يتم تخزين بيانات الصورة كبايتات خام بترتيب RGBA مسطّح. هذا يعني أنه أولاً تُكتب جميع بيانات R، ثم جميع بيانات G، ثم جميع بيانات B وأخيراً جميع بيانات A. |
| RLE | `1` | يبدأ بيانات الصورة المضغوطة بتقنية RLE بعدد البايتات لجميع خطوط المسح (الصفوف * القنوات)، حيث يُخزن كل عدد كقيمة من بايتين. يتبع ذلك البيانات المضغوطة بتقنية RLE، حيث يتم ضغط كل خط مسح بشكل منفصل. ضغط RLE هو نفس خوارزمية الضغط المستخدمة في روتين PackBits في ROM ماكintosh ومعيار TIFF. |
| ZipWithoutPrediction | `2` | ZIP بدون توقع. |
| ZipWithPrediction | `3` | ZIP مع توقع. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Psd](../../aspose.imaging.fileformats.psd/)
* assembly [Aspose.Imaging](../../)


