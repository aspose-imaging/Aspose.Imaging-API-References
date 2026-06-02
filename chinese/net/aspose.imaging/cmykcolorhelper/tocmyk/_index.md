---
title: "CmykColorHelper.ToCmyk"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。将 ARGB 颜色转换为 CMYK 颜色"
type: docs
weight: 90
url: /zh/net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixels | Int32[] | ARGB 颜色以 32 位整数值表示。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int ToCmyk(int argbPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixel | Int32 | ARGB 颜色以 32 位整数值表示。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int ToCmyk(Color pixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | 颜色 | ARGB 颜色。 |

### 返回值

CMYK 颜色以 32 位整数值的形式呈现。

## 示例

以下示例使用 Aspose.Imaging.RasterImage.SaveCmyk32Pixels 方法在光栅图像的中心区域填充黑色像素。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 获取黑色在 CMYK 颜色空间中的整数表示。
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // 黑色方块。
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // 在图像中心绘制黑色方块。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

以下示例展示了如何在不使用 ICC 配置文件的情况下将 RGB 颜色转换为对应的 CMYK 颜色。

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK without using ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

//输出如下：
//在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### 另请参见

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

ARGB 颜色到 CMYK 颜色的转换。

```csharp
public static int[] ToCmyk(Color[] pixels)
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


