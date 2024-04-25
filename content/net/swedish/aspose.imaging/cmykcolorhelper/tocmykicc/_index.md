---
title: ToCmykIcc
second_title: Aspose.Imaging för .NET API-referens
description: Omvandlingen från ARGB-färger till CMYK-färger med Icc-konvertering med anpassade profiler.
type: docs
weight: 110
url: /sv/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

Omvandlingen från ARGB-färger till CMYK-färger med Icc-konvertering med anpassade profiler.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | Color[] | ARGB-färgerna. |
| rgbIccStream | Stream | Strömmen som innehåller RGB Icc-profil. |
| cmykIccStream | Stream | Strömmen som innehåller CMYK Icc-profil. |

### Returvärde

CMYK-färgerna presenteras som 32-bitars heltalsvärden.

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering med standardprofiler.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | Color[] | ARGB-färgerna. |

### Returvärde

CMYK-färgerna presenteras som 32-bitars heltalsvärden.

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering med standardprofiler.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | Color | ARGB-färgen. |

### Returvärde

CMYK-färgen presenteras som ett 32-bitars heltalsvärde.

### Exempel

Följande exempel visar hur man konverterar RGB-färger till sina CMYK-motsvarigheter med hjälp av ICC-profiler.

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

// Ange din sökväg till RGB- och CMYK ICC-profilerna.
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

//Utgången ser ut så här:
//Konvertera RGB till CMYK med standard ICC-profiler.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247;21;254;85)
//RGB(0,0,255) => CMYK(254;195;0.134)
//Konvertera RGB till CMYK med hjälp av anpassade ICC-profiler.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238;16;254;80)
//RGB(0,0,255) => CMYK(242;182;0;0)
```

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering med anpassade profiler.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | Color | ARGB-färgen. |
| rgbIccStream | Stream | Strömmen som innehåller RGB Icc-profil. |
| cmykIccStream | Stream | Strömmen som innehåller CMYK Icc-profil. |

### Returvärde

CMYK-färgen presenteras som ett 32-bitars heltalsvärde.

### Exempel

Följande exempel visar hur man konverterar RGB-färger till sina CMYK-motsvarigheter med hjälp av ICC-profiler.

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

// Ange din sökväg till RGB- och CMYK ICC-profilerna.
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

//Utgången ser ut så här:
//Konvertera RGB till CMYK med standard ICC-profiler.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247;21;254;85)
//RGB(0,0,255) => CMYK(254;195;0.134)
//Konvertera RGB till CMYK med hjälp av anpassade ICC-profiler.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238;16;254;80)
//RGB(0,0,255) => CMYK(242;182;0;0)
```

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
