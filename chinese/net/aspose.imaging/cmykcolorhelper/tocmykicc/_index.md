---
title: ToCmykIcc
second_title: Aspose.Imaging for .NET API 参考
description: 使用带有自定义配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换
type: docs
weight: 110
url: /zh/net/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

使用带有自定义配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pixels | Color[] | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色呈现为 32 位整数值。

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

使用带有默认配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pixels | Color[] | ARGB 颜色。 |

### 返回值

CMYK 颜色呈现为 32 位整数值。

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

使用带有默认配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int ToCmykIcc(Color pixel)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pixel | Color | ARGB 颜色。 |

### 返回值

CMYK 颜色以 32 位整数值表示。

### 例子

以下示例显示如何使用 ICC 配置文件将 RGB 颜色转换为对应的 CMYK 颜色。

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK using default ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

    // 指定 RGB 和 CMYK ICC 配置文件的路径。
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert RGB to CMYK using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (Aspose.Imaging.Color rgbColor in rgbColors)
    {
        int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

        System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
    }
}

    //输出看起来像这样：
    //使用默认的ICC配置文件将RGB转换为CMYK。
    //RGB(255,0,0) => CMYK(0,254,249,15)
    //RGB(0,128,0) => CMYK(247,21,254,85)
    //RGB(0,0,255) => CMYK(254,195,0,134)
    //使用自定义 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0) => CMYK(0,207,219,0)
    //RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

使用带有自定义配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pixel | Color | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 32 位整数值表示。

### 例子

以下示例显示如何使用 ICC 配置文件将 RGB 颜色转换为对应的 CMYK 颜色。

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK using default ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

    // 指定 RGB 和 CMYK ICC 配置文件的路径。
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert RGB to CMYK using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (Aspose.Imaging.Color rgbColor in rgbColors)
    {
        int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

        System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
    }
}

    //输出看起来像这样：
    //使用默认的ICC配置文件将RGB转换为CMYK。
    //RGB(255,0,0) => CMYK(0,254,249,15)
    //RGB(0,128,0) => CMYK(247,21,254,85)
    //RGB(0,0,255) => CMYK(254,195,0,134)
    //使用自定义 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0) => CMYK(0,207,219,0)
    //RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
