---
title: ToCmykIcc
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 130
url: /aspose.imaging/cmykcolorhelper/tocmykicc/
---
## CmykColorHelper.ToCmykIcc method (1 of 8)

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Color[] | The ARGB colors. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (2 of 8)

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

```csharp
public static int[] ToCmykIcc(int[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | The ARGB colors. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (3 of 8)

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Color[] | The ARGB colors. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (4 of 8)

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

```csharp
public static int[] ToCmykIcc(int[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | The ARGB colors. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (5 of 8)

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixel | Color | The ARGB color. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### Examples

The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.

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

// Specify your path to the RGB and CMYK ICC profiles.
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

//The output looks like this:
//Convert RGB to CMYK using default ICC profiles.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convert RGB to CMYK using custom ICC profiles.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (6 of 8)

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

```csharp
public static int ToCmykIcc(int argb)
```

| Parameter | Type | Description |
| --- | --- | --- |
| argb | Int32 | The ARGB color. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### See Also

* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (7 of 8)

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixel | Color | The ARGB color. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### Examples

The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.

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

// Specify your path to the RGB and CMYK ICC profiles.
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

//The output looks like this:
//Convert RGB to CMYK using default ICC profiles.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convert RGB to CMYK using custom ICC profiles.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### See Also

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

---

## CmykColorHelper.ToCmykIcc method (8 of 8)

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

```csharp
public static int ToCmykIcc(int argb, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| argb | Int32 | The ARGB color. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### See Also

* class [CmykColorHelper](../../cmykcolorhelper)
* namespace [Aspose.Imaging](../../cmykcolorhelper)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
