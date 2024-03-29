---
title: EmfPointEnum
second_title: Aspose.Imaging for .NET API Referansı
description: Nokta numaralandırması bir çizim çağrısında bir noktanın nasıl kullanılacağını belirtmek için kullanılır.
type: docs
weight: 2790
url: /tr/net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
## EmfPointEnum enumeration

Nokta numaralandırması, bir çizim çağrısında bir noktanın nasıl kullanılacağını belirtmek için kullanılır.

```csharp
[Flags]
public enum EmfPointEnum : byte
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| PT_CLOSEFIGURE | `1` | Bir PT_LINETO veya PT_BEZIERTO türü, bit düzeyinde operatörü kullanılarak VEYA ilgili noktanın bir şekildeki son nokta olduğunu ve şeklin kapalı olduğunu belirtmek için bu değerle birleştirilebilir |
| PT_LINETO | `2` | Geçerli konumdan bu noktaya kadar bir çizginin çizileceğini belirtir, daha sonra yeni geçerli konum olur |
| PT_BEZIERTO | `4` | Bu noktanın bir Bezier eğrisi için bir kontrol noktası veya bitiş noktası olduğunu belirtir. |
| PT_MOVETO | `6` | Bu noktanın ayrık bir şekil başlattığını belirtir. Bu nokta yeni geçerli konum olur. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
