---
title: "CmykColorHelper.FromComponents"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。从 32 位青色、品红、黄色和黑色值创建 CMYK。"
type: docs
weight: 10
url: /zh/net/aspose.imaging/cmykcolorhelper/fromcomponents/
---
## CmykColorHelper.FromComponents method

从 32 位青色、品红、黄色和黑色值创建 CMYK。

```csharp
public static int FromComponents(int cyan, int magenta, int yellow, int black)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 青色 | Int32 | 青色分量。有效值范围为 0 到 255。 |
| 品红 | Int32 | 品红分量。有效值范围为 0 到 255。 |
| 黄色 | Int32 | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | Int32 | 黑色分量。有效值范围为 0 到 255。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

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

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


