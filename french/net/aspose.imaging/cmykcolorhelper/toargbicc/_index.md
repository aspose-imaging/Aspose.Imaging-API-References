---
title: ToArgbIcc
second_title: Référence de l'API Aspose.Imaging pour .NET
description: La conversion des couleurs CMJN en couleurs ARGB à laide de la conversion Icc avec les profils par défaut.
type: docs
weight: 80
url: /fr/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

La conversion des couleurs CMJN en couleurs ARGB à l'aide de la conversion Icc avec les profils par défaut.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cmykPixels | Int32[] | Les pixels CMJN présentés sous forme de valeurs entières 32 bits. |

### Return_Value

Les couleurs ARGB.

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

La conversion des couleurs CMJN en couleurs ARGB à l'aide de la conversion Icc avec des profils personnalisés.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cmykPixels | Int32[] | Les couleurs CMJN présentées sous forme de valeurs entières 32 bits. |
| cmykIccStream | Stream | Le flux contenant le profil CMJN Icc. |
| rgbIccStream | Stream | Le flux contenant le profil RVB Icc. |

### Return_Value

Les couleurs ARGB.

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

La conversion de la couleur CMJN en couleur ARGB à l'aide de la conversion Icc avec les profils par défaut.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cmykPixel | Int32 | La couleur CMJN présentée sous la forme d'une valeur entière 32 bits. |

### Return_Value

La couleur ARGB.

### Exemples

L'exemple suivant montre comment convertir les couleurs CMJN en leurs homologues RVB à l'aide des profils ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Jaune
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Le noir
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

// Spécifiez votre chemin vers les profils ICC RVB et CMJN personnalisés.
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

//La sortie ressemble à ceci :
//Convertir CMJN en RVB en utilisant les profils ICC par défaut.            
//CMJN(255,0,0,0) => RVB (46 188 220)
//CMJN(0,255,0,0) => RVB(231,52,142)
//CMJN(0,0,255,0) => RVB(244,253,63)
//CMJN(0,0,0,255) => RVB(21,21,21)
//Convertissez CMJN en RVB à l'aide de profils ICC personnalisés.
//CMJN(255,0,0,0) => RVB (46 188 220)
//CMJN(0,255,0,0) => RVB(231,52,142)
//(0,0,255,0) => RVB(244,253,63)
//CMJN(0,0,0,255) => RVB(21,21,21)
```

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

La conversion de la couleur CMJN en couleur ARGB à l'aide de la conversion Icc avec un profil personnalisé.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cmykPixel | Int32 | La couleur CMJN présentée sous la forme d'une valeur entière 32 bits. |
| cmykIccStream | Stream | Le flux contenant le profil CMJN Icc. |
| rgbIccStream | Stream | Le flux contenant le profil RVB Icc. |

### Return_Value

La couleur ARGB.

### Exemples

L'exemple suivant montre comment convertir les couleurs CMJN en leurs homologues RVB à l'aide des profils ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Jaune
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Le noir
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

// Spécifiez votre chemin vers les profils ICC RVB et CMJN personnalisés.
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

//La sortie ressemble à ceci :
//Convertir CMJN en RVB en utilisant les profils ICC par défaut.            
//CMJN(255,0,0,0) => RVB (46 188 220)
//CMJN(0,255,0,0) => RVB(231,52,142)
//CMJN(0,0,255,0) => RVB(244,253,63)
//CMJN(0,0,0,255) => RVB(21,21,21)
//Convertissez CMJN en RVB à l'aide de profils ICC personnalisés.
//CMJN(255,0,0,0) => RVB (46 188 220)
//CMJN(0,255,0,0) => RVB(231,52,142)
//(0,0,255,0) => RVB(244,253,63)
//CMJN(0,0,0,255) => RVB(21,21,21)
```

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
