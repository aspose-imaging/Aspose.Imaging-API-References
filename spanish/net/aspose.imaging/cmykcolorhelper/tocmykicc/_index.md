---
title: ToCmykIcc
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La conversión de colores ARGB a colores CMYK utilizando la conversión Icc con perfiles personalizados.
type: docs
weight: 110
url: /es/net/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

La conversión de colores ARGB a colores CMYK utilizando la conversión Icc con perfiles personalizados.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pixels | Color[] | Los colores ARGB. |
| rgbIccStream | Stream | El flujo que contiene el perfil RGB Icc. |
| cmykIccStream | Stream | El flujo que contiene el perfil CMYK Icc. |

### Valor_devuelto

Los colores CMYK presentados como valores enteros de 32 bits.

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

La conversión de colores ARGB a colores CMYK utilizando la conversión Icc con perfiles predeterminados.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pixels | Color[] | Los colores ARGB. |

### Valor_devuelto

Los colores CMYK presentados como valores enteros de 32 bits.

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

La conversión de color ARGB a color CMYK utilizando la conversión Icc con perfiles predeterminados.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pixel | Color | El color ARGB. |

### Valor_devuelto

El color CMYK presentado como un valor entero de 32 bits.

### Ejemplos

El siguiente ejemplo muestra cómo convertir colores RGB a sus equivalentes CMYK utilizando perfiles ICC.

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

// Especifique su ruta a los perfiles ICC RGB y CMYK.
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

//La salida se ve así:
//Convertir RGB a CMYK utilizando perfiles ICC predeterminados.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
//Convierta RGB a CMYK utilizando perfiles ICC personalizados.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

La conversión de color ARGB a color CMYK utilizando la conversión Icc con perfiles personalizados.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pixel | Color | El color ARGB. |
| rgbIccStream | Stream | El flujo que contiene el perfil RGB Icc. |
| cmykIccStream | Stream | El flujo que contiene el perfil CMYK Icc. |

### Valor_devuelto

El color CMYK presentado como un valor entero de 32 bits.

### Ejemplos

El siguiente ejemplo muestra cómo convertir colores RGB a sus equivalentes CMYK utilizando perfiles ICC.

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

// Especifique su ruta a los perfiles ICC RGB y CMYK.
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

//La salida se ve así:
//Convertir RGB a CMYK utilizando perfiles ICC predeterminados.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
//Convierta RGB a CMYK utilizando perfiles ICC personalizados.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
