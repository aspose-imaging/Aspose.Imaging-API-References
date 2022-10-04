---
title: EmfBlendFunction.AlphaFormatEnum
second_title: Aspose.Imaging for .NET API Referansı
description: Kaynak ve hedef piksellerin alfa şeffaflığına göre nasıl yorumlanacağını belirten bir yapı.
type: docs
weight: 3280
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
## EmfBlendFunction.AlphaFormatEnum enumeration

Kaynak ve hedef piksellerin alfa şeffaflığına göre nasıl yorumlanacağını belirten bir yapı.

```csharp
public enum AlphaFormatEnum : byte
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| NotTransparency | `0` | Kaynak bitmap'teki pikseller alfa saydamlığını belirtmiyor. Bu durumunda, SrcConstantAlpha değeri, kaynak ve hedef bitmap'lerin karışımını belirler. Aşağıdaki denklemlerde SrcConstantAlpha'nın 255'e bölündüğünü ve bunun 0 ila 1. aralığında bir değer ürettiğini unutmayın. |
| AC_SRC_ALPHA | `1` | Kaynak bitmap'in piksel başına 32 bit olduğunu belirtir ve her piksel için bir alfa saydamlık değeri belirtir. |

### Ayrıca bakınız

* struct [EmfBlendFunction](../emfblendfunction)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->