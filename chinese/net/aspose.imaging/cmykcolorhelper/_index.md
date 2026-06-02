---
title: "类 CmykColorHelper"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.CmykColorHelper 类。帮助方法用于处理以有符号 32 位整数表示的 CMYK 颜色。提供与 CmykColor 结构类似的 API。由于 CMYK 颜色仅作为 Int32 而非具有内部字段的结构呈现，它更轻量。请在可能的情况下优先使用此类的静态方法，而不是已弃用的 CmykColor 结构。"
type: docs
weight: 290
url: /zh/net/aspose.imaging/cmykcolorhelper/
---
## CmykColorHelper class

帮助方法用于处理以有符号 32 位整数表示的 CMYK 颜色。提供与 [`CmykColor`](../cmykcolor/) 结构类似的 API。由于 CMYK 颜色仅作为 Int32 而非具有内部字段的结构呈现，它更轻量。请在可能的情况下优先使用此类的静态方法，而不是已弃用的 [`CmykColor`](../cmykcolor/) 结构。

```csharp
public static class CmykColorHelper
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromComponents](../../aspose.imaging/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 从 32 位青色、品红、黄色和黑色值创建 CMYK。 |
| static [GetC](../../aspose.imaging/cmykcolorhelper/getc/)(int) | 获取青色分量值。 |
| static [GetK](../../aspose.imaging/cmykcolorhelper/getk/)(int) | 获取黑色分量值。 |
| static [GetM](../../aspose.imaging/cmykcolorhelper/getm/)(int) | 获取品红分量值。 |
| static [GetY](../../aspose.imaging/cmykcolorhelper/gety/)(int) | 获取黄色分量值。 |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb/#toargb)(int) | CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgb32](../../aspose.imaging/cmykcolorhelper/toargb32/)(int[]) | CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc)(int) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykaBytes](../../aspose.imaging/cmykcolorhelper/tocmykabytes/)(int[], int, int) | 将 ARGB 转换为 CMYKA（带透明度）。 |
| static [ToCmykaIccBytes](../../aspose.imaging/cmykcolorhelper/tocmykaiccbytes/)(int[], int, int, Stream, Stream) | 使用自定义 ICC 配置文件，将 RGB 转换为 CMYKA（带 alpha）。 |
| static [ToCmykBytes](../../aspose.imaging/cmykcolorhelper/tocmykbytes/)(int[], int, int) | 将 ARGB 转换为 CMYK。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | 使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_4)(Color[]) | 使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_2)(int) | 使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_6)(int[]) | 使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_5)(Color[], Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_3)(int, Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_7)(int[], Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIccBytes](../../aspose.imaging/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc)(int) | 使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反。 |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc_2)(int[]) | 使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反。 |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc_1)(int, Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc_3)(int[], Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


