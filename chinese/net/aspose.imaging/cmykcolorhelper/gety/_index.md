---
title: GetY
second_title: Aspose.Imaging for .NET API 参考
description: 获取黄色分量值
type: docs
weight: 50
url: /zh/net/aspose.imaging/cmykcolorhelper/gety/
---
## CmykColorHelper.GetY method

获取黄色分量值。

```csharp
public static int GetY(int cmyk)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cmyk | Int32 | CMYK 颜色以 32 位整数值表示。 |

### 返回值

黄色分量值。

### 例子

以下示例显示如何在不应用 ICC 配置文件的情况下将 RGB 颜色转换为对应的 CMYK 颜色。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),       // 青色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),       // 洋红色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),       // 黄色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),       // 黑色
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

    //输出看起来像这样：
    //在不使用ICC配置文件的情况下将CMYK转换为RGB。
    //CMYK(255,0,0,0) => RGB(0,255,255)
    //CMYK(0,255,0,0) => RGB(255,0,255)
    //CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

以下示例显示了如何在不使用 ICC 配置文件的情况下按照简单的公式快速将 CMYK 颜色转换为对应的 RGB 颜色。

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),       // 青色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),       // 洋红色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),       // 黄色
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),       // 黑色
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

    //输出看起来像这样：
    //在不使用ICC配置文件的情况下将CMYK转换为RGB。
    //CMYK(255,0,0,0) => RGB(0,255,255)
    //CMYK(0,255,0,0) => RGB(255,0,255)
    //CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

### 也可以看看

* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.Imaging](../../cmykcolorhelper)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
