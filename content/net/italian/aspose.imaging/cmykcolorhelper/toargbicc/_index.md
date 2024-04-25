---
title: ToArgbIcc
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti.
type: docs
weight: 80
url: /it/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili predefiniti.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | Int32[] | I pixel CMYK presentati come valori interi a 32 bit. |

### Valore di ritorno

I colori ARGB.

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

La conversione da colori CMYK a colori ARGB utilizzando la conversione Icc con profili personalizzati.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | Int32[] | I colori CMYK presentati come valori interi a 32 bit. |
| cmykIccStream | Stream | Il flusso contenente il profilo Icc CMYK. |
| rgbIccStream | Stream | Il flusso contenente il profilo Icc RGB. |

### Valore di ritorno

I colori ARGB.

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

La conversione da colore CMYK a colore ARGB utilizzando la conversione Icc con profili predefiniti.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | Int32 | Il colore CMYK presentato come un valore intero a 32 bit. |

### Valore di ritorno

Il colore ARGB.

### Esempi

L'esempio seguente mostra come convertire i colori CMYK nelle loro controparti RGB utilizzando i profili ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Ciano
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Giallo
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Nero
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

// Specifica il percorso per i profili ICC RGB e CMYK personalizzati.
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

//L'output è simile a questo:
//Converti CMYK in RGB utilizzando i profili ICC predefiniti.            
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//Converti CMYK in RGB utilizzando profili ICC personalizzati.
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

La conversione da colore CMYK a colore ARGB utilizzando la conversione Icc con profilo personalizzato.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | Int32 | Il colore CMYK presentato come un valore intero a 32 bit. |
| cmykIccStream | Stream | Il flusso contenente il profilo Icc CMYK. |
| rgbIccStream | Stream | Il flusso contenente il profilo Icc RGB. |

### Valore di ritorno

Il colore ARGB.

### Esempi

L'esempio seguente mostra come convertire i colori CMYK nelle loro controparti RGB utilizzando i profili ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Ciano
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Giallo
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Nero
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

// Specifica il percorso per i profili ICC RGB e CMYK personalizzati.
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

//L'output è simile a questo:
//Converti CMYK in RGB utilizzando i profili ICC predefiniti.            
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//Converti CMYK in RGB utilizzando profili ICC personalizzati.
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
