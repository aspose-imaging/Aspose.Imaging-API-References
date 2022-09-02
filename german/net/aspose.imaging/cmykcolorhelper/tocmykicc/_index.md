---
title: ToCmykIcc
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen.
type: docs
weight: 110
url: /de/net/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | Color[] | Die ARGB-Farben. |
| rgbIccStream | Stream | Der Stream, der das RGB Icc-Profil enthält. |
| cmykIccStream | Stream | Der Stream, der das CMYK-Icc-Profil enthält. |

### Rückgabewert

Die CMYK-Farben werden als 32-Bit-Ganzzahlwerte dargestellt.

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit Standardprofilen.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | Color[] | Die ARGB-Farben. |

### Rückgabewert

Die CMYK-Farben werden als 32-Bit-Ganzzahlwerte dargestellt.

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

Die Konvertierung von ARGB-Farbe in CMYK-Farbe mithilfe der Icc-Konvertierung mit Standardprofilen.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | Color | Die ARGB-Farbe. |

### Rückgabewert

Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert.

### Beispiele

Das folgende Beispiel zeigt, wie RGB-Farben mithilfe von ICC-Profilen in ihre CMYK-Gegenstücke konvertiert werden.

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

// Geben Sie Ihren Pfad zu den RGB- und CMYK-ICC-Profilen an.
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

//Die Ausgabe sieht so aus:
// Konvertieren Sie RGB in CMYK unter Verwendung von Standard-ICC-Profilen.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
// Konvertieren Sie RGB in CMYK mit benutzerdefinierten ICC-Profilen.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

Die Konvertierung von ARGB-Farbe in CMYK-Farbe mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | Color | Die ARGB-Farbe. |
| rgbIccStream | Stream | Der Stream, der das RGB Icc-Profil enthält. |
| cmykIccStream | Stream | Der Stream, der das CMYK-Icc-Profil enthält. |

### Rückgabewert

Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert.

### Beispiele

Das folgende Beispiel zeigt, wie RGB-Farben mithilfe von ICC-Profilen in ihre CMYK-Gegenstücke konvertiert werden.

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

// Geben Sie Ihren Pfad zu den RGB- und CMYK-ICC-Profilen an.
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

//Die Ausgabe sieht so aus:
// Konvertieren Sie RGB in CMYK unter Verwendung von Standard-ICC-Profilen.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
// Konvertieren Sie RGB in CMYK mit benutzerdefinierten ICC-Profilen.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
