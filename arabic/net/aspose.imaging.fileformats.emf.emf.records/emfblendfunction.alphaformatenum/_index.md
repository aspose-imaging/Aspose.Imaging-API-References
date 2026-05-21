---
title: "التعداد EmfBlendFunction.AlphaFormatEnum"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBlendFunctionAlphaFormatEnum enum. بنية تحدد كيفية تفسير بكسلات المصدر والوجهة بالنسبة للشفافية ألفا."
type: docs
weight: 3370
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
## EmfBlendFunction.AlphaFormatEnum enumeration

هيكل يحدد كيفية تفسير بكسلات المصدر والوجهة بالنسبة للشفافية ألفا.

```csharp
public enum AlphaFormatEnum : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| NotTransparency | `0` | البكسلات في صورة المصدر لا تحدد شفافية ألفا. في هذه الحالة، قيمة SrcConstantAlpha تحدد دمج صور المصدر والوجهة. ملاحظة أن المعادلات التالية تقسم SrcConstantAlpha على 255، مما ينتج قيمة في النطاق من 0 إلى 1. |
| AC_SRC_ALPHA | `1` | يشير إلى أن صورة المصدر هي 32 بت لكل بكسل ويحدد قيمة شفافية ألفا لكل بكسل. |

### انظر أيضًا

* struct [EmfBlendFunction](../emfblendfunction/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


