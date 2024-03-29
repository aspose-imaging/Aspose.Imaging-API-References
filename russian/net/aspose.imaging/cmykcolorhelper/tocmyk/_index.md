---
title: ToCmyk
second_title: Справочник по Aspose.Imaging for .NET API
description: Преобразование цветов ARGB в цвета CMYK.
type: docs
weight: 90
url: /ru/net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

Преобразование цветов ARGB в цвета CMYK.

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | Int32[] | Цвета ARGB представлены в виде 32-битных целых чисел. |

### Возвращаемое значение

Цвета CMYK представлены в виде 32-битных целых значений.

### Смотрите также

* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

Преобразование цвета ARGB в цвет CMYK.

```csharp
public static int ToCmyk(int argbPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixel | Int32 | Цвет ARGB, представленный в виде 32-битного целого числа. |

### Возвращаемое значение

Цвет CMYK, представленный в виде 32-битного целого числа.

### Смотрите также

* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

Преобразование цвета ARGB в цвет CMYK.

```csharp
public static int ToCmyk(Color pixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | Color | Цвет ARGB. |

### Возвращаемое значение

Цвет CMYK, представленный в виде 32-битного целого числа.

### Примеры

В следующем примере центральная область растрового изображения заполняется черными пикселями с использованием метода Aspose.Imaging.RasterImage.SaveCmyk32Pixels.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Получить целочисленное представление черного цвета в цветовом пространстве CMYK.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Черный квадрат.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Рисуем черный квадрат в центре изображения.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

В следующем примере показано, как преобразовать цвета RGB в их аналоги CMYK без применения профилей ICC.

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

//Вывод выглядит так:
//Преобразование RGB в CMYK без использования профилей ICC.
//RGB(255,0,0) => CMYK(0,255,255,0)
//RGB(0,128,0) => CMYK(255,0,255,127)
//RGB(0,0,255) => CMYK(255,255,0,0)
```

### Смотрите также

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

Преобразование цветов ARGB в цвета CMYK.

```csharp
public static int[] ToCmyk(Color[] pixels)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
