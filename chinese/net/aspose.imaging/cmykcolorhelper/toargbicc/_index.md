---
title: "CmykColorHelper.ToArgbIcc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。使用默认配置文件通过 ICC 转换将 CMYK 颜色转换为 ARGB 颜色"
type: docs
weight: 80
url: /zh/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK 像素以 32 位整数值呈现。 |

### 返回值

ARGB 颜色。

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK 颜色以 32 位整数值的形式呈现。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |

### 返回值

ARGB 颜色。

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK 颜色以 32 位整数值的形式呈现。 |

### 返回值

ARGB 颜色。

## 示例

以下示例展示了如何使用 ICC 配置文件将 CMYK 颜色转换为对应的 RGB。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Yellow
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Black
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

//输出如下：
//使用默认 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//使用自定义 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK 颜色以 32 位整数值的形式呈现。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |

### 返回值

ARGB 颜色。

## 示例

以下示例展示了如何使用 ICC 配置文件将 CMYK 颜色转换为对应的 RGB。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Yellow
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Black
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

//输出如下：
//使用默认 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//使用自定义 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


