---
title: ToCmykIcc
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.
type: docs
weight: 110
url: /it/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili personalizzati.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | Color[] | I colori ARGB. |
| rgbIccStream | Stream | Il flusso contenente il profilo Icc RGB. |
| cmykIccStream | Stream | Il flusso contenente il profilo Icc CMYK. |

### Valore di ritorno

I colori CMYK presentati come valori interi a 32 bit.

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

La conversione da colori ARGB a colori CMYK utilizzando la conversione Icc con profili predefiniti.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | Color[] | I colori ARGB. |

### Valore di ritorno

I colori CMYK presentati come valori interi a 32 bit.

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili predefiniti.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | Color | Il colore ARGB. |

### Valore di ritorno

Il colore CMYK presentato come un valore intero a 32 bit.

### Esempi

L'esempio seguente mostra come convertire i colori RGB nelle loro controparti CMYK utilizzando i profili ICC.

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

// Specifica il percorso per i profili ICC RGB e CMYK.
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

//L'output è simile a questo:
//Converti RGB in CMYK utilizzando i profili ICC predefiniti.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
//Converti RGB in CMYK utilizzando profili ICC personalizzati.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

La conversione da colore ARGB a colore CMYK utilizzando la conversione Icc con profili personalizzati.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | Color | Il colore ARGB. |
| rgbIccStream | Stream | Il flusso contenente il profilo Icc RGB. |
| cmykIccStream | Stream | Il flusso contenente il profilo Icc CMYK. |

### Valore di ritorno

Il colore CMYK presentato come un valore intero a 32 bit.

### Esempi

L'esempio seguente mostra come convertire i colori RGB nelle loro controparti CMYK utilizzando i profili ICC.

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

// Specifica il percorso per i profili ICC RGB e CMYK.
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

//L'output è simile a questo:
//Converti RGB in CMYK utilizzando i profili ICC predefiniti.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
//Converti RGB in CMYK utilizzando profili ICC personalizzati.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
