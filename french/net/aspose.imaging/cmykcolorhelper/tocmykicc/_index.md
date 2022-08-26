---
title: ToCmykIcc
second_title: Référence de l'API Aspose.Imaging pour .NET
description: La conversion des couleurs ARGB en couleurs CMJN à laide de la conversion Icc avec des profils personnalisés.
type: docs
weight: 110
url: /fr/net/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

La conversion des couleurs ARGB en couleurs CMJN à l'aide de la conversion Icc avec des profils personnalisés.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pixels | Color[] | Les couleurs ARGB. |
| rgbIccStream | Stream | Le flux contenant le profil RVB Icc. |
| cmykIccStream | Stream | Le flux contenant le profil CMJN Icc. |

### Return_Value

Les couleurs CMJN présentées sous forme de valeurs entières 32 bits.

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

La conversion des couleurs ARGB en couleurs CMJN à l'aide de la conversion Icc avec les profils par défaut.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pixels | Color[] | Les couleurs ARGB. |

### Return_Value

Les couleurs CMJN présentées sous forme de valeurs entières 32 bits.

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

La conversion de la couleur ARGB en couleur CMJN à l'aide de la conversion Icc avec les profils par défaut.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pixel | Color | La couleur ARGB. |

### Return_Value

La couleur CMJN présentée sous la forme d'une valeur entière 32 bits.

### Exemples

L'exemple suivant montre comment convertir les couleurs RVB en leurs homologues CMJN à l'aide des profils ICC.

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

// Spécifiez votre chemin vers les profils ICC RVB et CMJN.
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

//La sortie ressemble à ceci :
//Convertir RVB en CMJN en utilisant les profils ICC par défaut.
//RVB(255,0,0) => CMJN(0,254,249,15)
//RVB(0,128,0) => CMJN(247,21,254,85)
//RVB(0,0,255) => CMJN(254,195,0,134)
//Convertissez RVB en CMJN à l'aide de profils ICC personnalisés.
//RVB(255,0,0) => CMJN(0,207,219,0)
//RVB(0,128,0) => CMJN(238,16,254,80)
//RVB(0,0,255) => CMJN(242,182,0,0)
```

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

La conversion de la couleur ARGB en couleur CMJN à l'aide de la conversion Icc avec des profils personnalisés.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pixel | Color | La couleur ARGB. |
| rgbIccStream | Stream | Le flux contenant le profil RVB Icc. |
| cmykIccStream | Stream | Le flux contenant le profil CMJN Icc. |

### Return_Value

La couleur CMJN présentée sous la forme d'une valeur entière 32 bits.

### Exemples

L'exemple suivant montre comment convertir les couleurs RVB en leurs homologues CMJN à l'aide des profils ICC.

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

// Spécifiez votre chemin vers les profils ICC RVB et CMJN.
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

//La sortie ressemble à ceci :
//Convertir RVB en CMJN en utilisant les profils ICC par défaut.
//RVB(255,0,0) => CMJN(0,254,249,15)
//RVB(0,128,0) => CMJN(247,21,254,85)
//RVB(0,0,255) => CMJN(254,195,0,134)
//Convertissez RVB en CMJN à l'aide de profils ICC personnalisés.
//RVB(255,0,0) => CMJN(0,207,219,0)
//RVB(0,128,0) => CMJN(238,16,254,80)
//RVB(0,0,255) => CMJN(242,182,0,0)
```

### Voir également

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
