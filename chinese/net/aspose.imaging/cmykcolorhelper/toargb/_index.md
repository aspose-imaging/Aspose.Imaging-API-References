---
title: "CmykColorHelper.ToArgb"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。将 CMYK 颜色转换为 ARGB 颜色"
type: docs
weight: 60
url: /zh/net/aspose.imaging/cmykcolorhelper/toargb/
---
## ToArgb(int[]) {#toargb_1}

CMYK 颜色到 ARGB 颜色的转换。

```csharp
public static Color[] ToArgb(int[] cmykPixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK 颜色以 32 位整数值的形式呈现。 |

### 返回值

ARGB 颜色。

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgb(int) {#toargb}

CMYK 颜色到 ARGB 颜色的转换。

```csharp
public static Color ToArgb(int cmykPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK 颜色以 32 位整数值的形式呈现。 |

### 返回值

ARGB 颜色。

## 示例

以下示例展示了如何在不使用 ICC 配置文件的情况下，通过直接公式快速将 CMYK 颜色转换为对应的 RGB 颜色。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Yellow
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Black
};

System.Console.WriteLine("Convert CMYK to RGB without using ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgb(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);

    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

//输出如下：
//在不使用 ICC 配置文件的情况下将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


