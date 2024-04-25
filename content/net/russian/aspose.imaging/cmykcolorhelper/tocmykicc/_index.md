---
title: ToCmykIcc
second_title: Справочник по Aspose.Imaging for .NET API
description: Преобразование цветов ARGB в цвета CMYK с помощью преобразования Icc с пользовательскими профилями.
type: docs
weight: 110
url: /ru/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

Преобразование цветов ARGB в цвета CMYK с помощью преобразования Icc с пользовательскими профилями.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | Color[] | Цвета ARGB. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB Icc. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK Icc. |

### Возвращаемое значение

Цвета CMYK представлены в виде 32-битных целых значений.

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

Преобразование цветов ARGB в цвета CMYK с использованием преобразования Icc с профилями по умолчанию.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | Color[] | Цвета ARGB. |

### Возвращаемое значение

Цвета CMYK представлены в виде 32-битных целых значений.

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

Преобразование цвета ARGB в цвет CMYK с использованием преобразования Icc с профилями по умолчанию.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | Color | Цвет ARGB. |

### Возвращаемое значение

Цвет CMYK, представленный в виде 32-битного целого числа.

### Примеры

В следующем примере показано, как преобразовать цвета RGB в их аналоги CMYK с помощью профилей ICC.

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

// Укажите свой путь к профилям RGB и CMYK ICC.
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

//Вывод выглядит так:
// Преобразование RGB в CMYK с использованием профилей ICC по умолчанию.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
// Преобразование RGB в CMYK с использованием пользовательских профилей ICC.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

Преобразование цвета ARGB в цвет CMYK с помощью преобразования Icc с пользовательскими профилями.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | Color | Цвет ARGB. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB Icc. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK Icc. |

### Возвращаемое значение

Цвет CMYK, представленный в виде 32-битного целого числа.

### Примеры

В следующем примере показано, как преобразовать цвета RGB в их аналоги CMYK с помощью профилей ICC.

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

// Укажите свой путь к профилям RGB и CMYK ICC.
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

//Вывод выглядит так:
// Преобразование RGB в CMYK с использованием профилей ICC по умолчанию.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
// Преобразование RGB в CMYK с использованием пользовательских профилей ICC.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242,182,0,0)
```

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
