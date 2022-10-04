---
title: GetM
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den Magenta-Komponentenwert ab.
type: docs
weight: 40
url: /de/net/aspose.imaging/cmykcolorhelper/getm/
---
## CmykColorHelper.GetM method

Ruft den Magenta-Komponentenwert ab.

```csharp
public static int GetM(int cmyk)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | Int32 | Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert. |

### Rückgabewert

Der Magenta-Komponentenwert.

### Beispiele

Das folgende Beispiel zeigt, wie Sie RGB-Farben in ihre CMYK-Gegenstücke konvertieren, ohne ICC-Profile anzuwenden.

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

//Die Ausgabe sieht so aus:
//RGB in CMYK umwandeln, ohne ICC-Profile zu verwenden.
//RGB(255,0,0) => CMYK(0,255,255,0)
//RGB(0,128,0) => CMYK(255,0,255,127)
//RGB(0,0,255) => CMYK(255,255,0,0)
```

Das folgende Beispiel zeigt, wie Sie CMYK-Farben schnell in ihre RGB-Gegenstücke konvertieren können, indem Sie einfache Formeln befolgen, ohne ICC-Profile zu verwenden.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Gelb
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Schwarz
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

//Die Ausgabe sieht so aus:
// CMYK in RGB konvertieren, ohne ICC-Profile zu verwenden.
//CMYK(255,0,0,0) => RGB(0,255,255)
//CMYK(0,255,0,0) => RGB(255,0,255)
//CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

### Siehe auch

* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->