---
title: CmykColorHelper.ToArgb
second_title: Aspose.Imaging for .NET API Reference
description: CmykColorHelper method. The conversion from CMYK colors to ARGB colors
type: docs
weight: 60
url: /net/aspose.imaging/cmykcolorhelper/toargb/
---
## ToArgb(int[]) {#toargb_1}

The conversion from CMYK colors to ARGB colors.

```csharp
public static Color[] ToArgb(int[] cmykPixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | The CMYK colors presented as 32-bit integer values. |

### Return Value

The ARGB colors.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgb(int) {#toargb}

The conversion from CMYK color to ARGB color.

```csharp
public static Color ToArgb(int cmykPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | The CMYK color presented as a 32-bit integer value. |

### Return Value

The ARGB color.

## Examples

The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.

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

//The output looks like this:
//Convert CMYK to RGB without using ICC profiles.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


