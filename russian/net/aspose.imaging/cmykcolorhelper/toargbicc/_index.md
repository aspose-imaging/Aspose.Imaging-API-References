---
title: ToArgbIcc
second_title: Справочник по Aspose.Imaging for .NET API
description: Преобразование цветов CMYK в цвета ARGB с использованием преобразования Icc с профилями по умолчанию.
type: docs
weight: 80
url: /ru/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

Преобразование цветов CMYK в цвета ARGB с использованием преобразования Icc с профилями по умолчанию.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | Int32[] | Пиксели CMYK представлены в виде 32-битных целых чисел. |

### Возвращаемое значение

Цвета ARGB.

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

Преобразование цветов CMYK в цвета ARGB с использованием преобразования Icc с пользовательскими профилями.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | Int32[] | Цвета CMYK представлены в виде 32-битных целых значений. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK Icc. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB Icc. |

### Возвращаемое значение

Цвета ARGB.

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

Преобразование цвета CMYK в цвет ARGB с использованием преобразования Icc с профилями по умолчанию.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | Int32 | Цвет CMYK, представленный как 32-битное целочисленное значение. |

### Возвращаемое значение

Цвет ARGB.

### Примеры

В следующем примере показано, как преобразовать цвета CMYK в их аналоги RGB с помощью профилей ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),    // голубой
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),    // Пурпурный
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),    // Желтый
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),    // Черный
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

// Укажите путь к пользовательским профилям RGB и CMYK ICC.
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

 // Вывод выглядит так: 
 // Преобразование CMYK в RGB с использованием профилей ICC по умолчанию. 
 //CMYK(255,0,0,0) => RGB(46 188 220)
 //CMYK(0,255,0,0) => RGB(231,52,142)
 //CMYK(0,0,255,0) => RGB(244,253,63)
 //CMYK(0,0,0,255) => RGB(21,21,21)
 //Преобразование CMYK в RGB с использованием пользовательских профилей ICC.
 //CMYK(255,0,0,0) => RGB(46 188 220)
 //CMYK(0,255,0,0) => RGB(231,52,142)
 //(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

Преобразование из цвета CMYK в цвет ARGB с использованием преобразования Icc с пользовательским профилем.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | Int32 | Цвет CMYK, представленный как 32-битное целочисленное значение. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK Icc. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB Icc. |

### Возвращаемое значение

Цвет ARGB.

### Примеры

В следующем примере показано, как преобразовать цвета CMYK в их аналоги RGB с помощью профилей ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),    // голубой
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),    // Пурпурный
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),    // Желтый
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),    // Черный
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

// Укажите путь к пользовательским профилям RGB и CMYK ICC.
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

 // Вывод выглядит так: 
 // Преобразование CMYK в RGB с использованием профилей ICC по умолчанию. 
 //CMYK(255,0,0,0) => RGB(46 188 220)
 //CMYK(0,255,0,0) => RGB(231,52,142)
 //CMYK(0,0,255,0) => RGB(244,253,63)
 //CMYK(0,0,0,255) => RGB(21,21,21)
 //Преобразование CMYK в RGB с использованием пользовательских профилей ICC.
 //CMYK(255,0,0,0) => RGB(46 188 220)
 //CMYK(0,255,0,0) => RGB(231,52,142)
 //(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
