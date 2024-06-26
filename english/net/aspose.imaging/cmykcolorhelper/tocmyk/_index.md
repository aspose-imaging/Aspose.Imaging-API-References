---
title: CmykColorHelper.ToCmyk
second_title: Aspose.Imaging for .NET API Reference
description: CmykColorHelper method. The conversion from ARGB colors to CMYK colors
type: docs
weight: 90
url: /net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

The conversion from ARGB colors to CMYK colors.

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | Int32[] | The ARGB colors presented as 32-bit integer values. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

The conversion from ARGB color to CMYK color.

```csharp
public static int ToCmyk(int argbPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| argbPixel | Int32 | The ARGB color presented as a 32-bit integer value. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

The conversion from ARGB color to CMYK color.

```csharp
public static int ToCmyk(Color pixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixel | Color | The ARGB color. |

### Return Value

The CMYK color presented as a 32-bit integer value.

## Examples

The following example fills the central area of a raster image with black pixels using the Aspose.Imaging.RasterImage.SaveCmyk32Pixels method.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Get an integer representation of black in the CMYK color space.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // The black square.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Draw the black square at the center of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.

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

//The output looks like this:
//Convert RGB to CMYK without using ICC profiles.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

The conversion from ARGB colors to CMYK colors.

```csharp
public static int[] ToCmyk(Color[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Color[] | The ARGB colors. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


