---
title: "CmykColorHelper.ToCmykIcc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色"
type: docs
weight: 130
url: /zh/net/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_5}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Color[] | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int[], Stream, Stream) {#tocmykicc_7}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int[] ToCmykIcc(int[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_4}

使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Color[] | ARGB 颜色。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int[]) {#tocmykicc_6}

使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int[] ToCmykIcc(int[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | ARGB 颜色。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToCmykIcc(Color pixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | 颜色 | ARGB 颜色。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

## 示例

以下示例展示了如何使用 ICC 配置文件将 RGB 颜色转换为对应的 CMYK 颜色。

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

//输出如下：
//使用默认 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//使用自定义 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int) {#tocmykicc_2}

使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToCmykIcc(int argb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | Int32 | ARGB 颜色。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | 颜色 | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

## 示例

以下示例展示了如何使用 ICC 配置文件将 RGB 颜色转换为对应的 CMYK 颜色。

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

//输出如下：
//使用默认 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//使用自定义 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int, Stream, Stream) {#tocmykicc_3}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToCmykIcc(int argb, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | Int32 | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


