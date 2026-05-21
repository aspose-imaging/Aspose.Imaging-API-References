---
title: "تعداد EmfRegionMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfRegionMode. يحدد تعداد RegionMode القيم المستخدمة مع EMR_SELECTCLIPPATH و EMR_EXTSELECTCLIPRGN لتحديد المسار الحالي أو منطقة جديدة يتم دمجها مع منطقة القص الحالية"
type: docs
weight: 2920
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
## EmfRegionMode enumeration

تعداد RegionMode يحدد القيم التي تُستخدم مع EMR_SELECTCLIPPATH و EMR_EXTSELECTCLIPRGN، مُحددةً المسار الحالي أو منطقة جديدة يتم دمجها مع منطقة القص الحالية.

```csharp
public enum EmfRegionMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| RGN_AND | `1` | منطقة القص الجديدة تشمل التقاطع (المناطق المتداخلة) بين منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة). |
| RGN_OR | `2` | منطقة القص الجديدة تشمل الاتحاد (المناطق المدمجة) بين منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة). |
| RGN_XOR | `3` | منطقة القص الجديدة تشمل اتحاد منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة) دون المناطق المتداخلة |
| RGN_DIFF | `4` | منطقة القطع الجديدة تشمل مناطق منطقة القطع الحالية مع استبعاد تلك الخاصة بالمسار الحالي (أو المنطقة الجديدة). |
| RGN_COPY | `5` | منطقة القطع الجديدة هي المسار الحالي (أو المنطقة الجديدة). |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


