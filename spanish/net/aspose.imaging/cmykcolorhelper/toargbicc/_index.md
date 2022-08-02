---
title: ToArgbIcc
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La conversión de colores CMYK a colores ARGB utilizando la conversión Icc con perfiles predeterminados.
type: docs
weight: 80
url: /es/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

La conversión de colores CMYK a colores ARGB utilizando la conversión Icc con perfiles predeterminados.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| cmykPixels | Int32[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Valor_devuelto

Los colores ARGB.

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

La conversión de colores CMYK a colores ARGB utilizando la conversión Icc con perfiles personalizados.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| cmykPixels | Int32[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmykIccStream | Stream | El flujo que contiene el perfil CMYK Icc. |
| rgbIccStream | Stream | El flujo que contiene el perfil RGB Icc. |

### Valor_devuelto

Los colores ARGB.

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

La conversión de color CMYK a color ARGB utilizando la conversión Icc con perfiles predeterminados.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| cmykPixel | Int32 | El color CMYK presentado como un valor entero de 32 bits. |

### Valor_devuelto

El color ARGB.

### Ejemplos

El siguiente ejemplo muestra cómo convertir colores CMYK a sus equivalentes RGB utilizando perfiles ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // cian
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Amarillo
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Negro
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

// Especifique su ruta a los perfiles ICC RGB y CMYK personalizados.
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

//La salida se ve así:
//Convertir CMYK a RGB utilizando perfiles ICC predeterminados.            
//CMYK(255,0,0,0) => RGB (46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//Convierta CMYK a RGB utilizando perfiles ICC personalizados.
//CMYK(255,0,0,0) => RGB (46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

La conversión de color CMYK a color ARGB utilizando la conversión Icc con perfil personalizado.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| cmykPixel | Int32 | El color CMYK presentado como un valor entero de 32 bits. |
| cmykIccStream | Stream | El flujo que contiene el perfil CMYK Icc. |
| rgbIccStream | Stream | El flujo que contiene el perfil RGB Icc. |

### Valor_devuelto

El color ARGB.

### Ejemplos

El siguiente ejemplo muestra cómo convertir colores CMYK a sus equivalentes RGB utilizando perfiles ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // cian
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Amarillo
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Negro
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

// Especifique su ruta a los perfiles ICC RGB y CMYK personalizados.
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

//La salida se ve así:
//Convertir CMYK a RGB utilizando perfiles ICC predeterminados.            
//CMYK(255,0,0,0) => RGB (46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//Convierta CMYK a RGB utilizando perfiles ICC personalizados.
//CMYK(255,0,0,0) => RGB (46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Ver también

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* espacio de nombres [Aspose.Imaging](../../cmykcolorhelper)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
