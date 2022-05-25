---
title: ToArgbIcc
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## CmykColorHelper.ToArgbIcc method (1 of 4)

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | The CMYK pixels presented as 32-bit integer values. |

### Return Value

The ARGB colors.

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToArgbIcc method (2 of 4)

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | The CMYK colors presented as 32-bit integer values. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |

### Return Value

The ARGB colors.

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToArgbIcc method (3 of 4)

The conversion from CMYK color to ARGB Color using Icc conversion with default profiles.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | The CMYK color presented as a 32-bit integer value. |

### Return Value

The ARGB color.

### Examples

The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.

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

// Specify your path to custom RGB and CMYK ICC profiles.
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

//The output looks like this:
//Convert CMYK to RGB using default ICC profiles.            
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convert CMYK to RGB using custom ICC profiles.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToArgbIcc method (4 of 4)

The conversion from CMYK color to ARGB color using Icc conversion with custom profile.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | The CMYK color presented as a 32-bit integer value. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |

### Return Value

The ARGB color.

### Examples

The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.

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

// Specify your path to custom RGB and CMYK ICC profiles.
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

//The output looks like this:
//Convert CMYK to RGB using default ICC profiles.            
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convert CMYK to RGB using custom ICC profiles.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
