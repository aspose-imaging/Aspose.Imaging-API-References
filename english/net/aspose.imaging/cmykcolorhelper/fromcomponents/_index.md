---
title: CmykColorHelper.FromComponents
second_title: Aspose.Imaging for .NET API Reference
description: CmykColorHelper method. Creates CMYK from a 32bit cyan magenta yellow and black values
type: docs
weight: 10
url: /net/aspose.imaging/cmykcolorhelper/fromcomponents/
---
## CmykColorHelper.FromComponents method

Creates CMYK from a 32-bit cyan, magenta, yellow and black values.

```csharp
public static int FromComponents(int cyan, int magenta, int yellow, int black)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cyan | Int32 | The cyan component. Valid values are 0 through 255. |
| magenta | Int32 | The magenta component. Valid values are 0 through 255. |
| yellow | Int32 | The yellow component. Valid values are 0 through 255. |
| black | Int32 | The black component. Valid values are 0 through 255. |

### Return Value

The CMYK color presented as a 32-bit integer value.

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

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


