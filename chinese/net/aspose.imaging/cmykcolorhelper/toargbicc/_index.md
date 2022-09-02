---
title: ToArgbIcc
second_title: Aspose.Imaging for .NET API 参考
description: 使用默认配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换
type: docs
weight: 80
url: /zh/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

使用默认配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK 像素表示为 32 位整数值。 |

### 返回值

ARGB 颜色。

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

使用带有自定义配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK 颜色显示为 32 位整数值。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |

### 返回值

ARGB 颜色。

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

使用默认配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK 颜色显示为 32 位整数值。 |

### 返回值

ARGB 颜色。

### 例子

以下示例显示了如何使用 ICC 配置文件将 CMYK 颜色转换为对应的 RGB 颜色。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // 青色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // 洋红色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // 黄色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // 黑色的
};

System.Console.WriteLine("Convert CMYK to RGB using default ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
        
    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// 指定自定义 RGB 和 CMYK ICC 配置文件的路径。
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert CMYK to RGB using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (int cmykColor in cmykColors)
    {
        Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
            
        System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
    }
}

//输出看起来像这样：
//使用默认的 ICC 配置文件将 CMYK 转换为 RGB。            
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//使用自定义 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

使用带有自定义配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK 颜色显示为 32 位整数值。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |

### 返回值

ARGB 颜色。

### 例子

以下示例显示了如何使用 ICC 配置文件将 CMYK 颜色转换为对应的 RGB 颜色。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // 青色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // 洋红色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // 黄色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // 黑色的
};

System.Console.WriteLine("Convert CMYK to RGB using default ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
        
    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// 指定自定义 RGB 和 CMYK ICC 配置文件的路径。
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert CMYK to RGB using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (int cmykColor in cmykColors)
    {
        Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
            
        System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
    }
}

//输出看起来像这样：
//使用默认的 ICC 配置文件将 CMYK 转换为 RGB。            
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//使用自定义 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### 也可以看看

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
