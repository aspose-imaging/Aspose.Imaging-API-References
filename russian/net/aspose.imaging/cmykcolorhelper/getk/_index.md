---
title: GetK
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает значение черного компонента.
type: docs
weight: 30
url: /ru/net/aspose.imaging/cmykcolorhelper/getk/
---
## CmykColorHelper.GetK method

Получает значение черного компонента.

```csharp
public static int GetK(int cmyk)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | Int32 | Цвет CMYK, представленный как 32-битное целочисленное значение. |

### Возвращаемое значение

Значение черного компонента.

### Примеры

В следующем примере показано, как преобразовать цвета RGB в их аналоги CMYK без применения профилей ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),    // голубой
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),    // Пурпурный
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),    // Желтый
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),    // Черный
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

 // Вывод выглядит так: 
 //Преобразование CMYK в RGB без использования профилей ICC.
 //CMYK(255,0,0,0) => RGB(0,255,255)
 //CMYK(0,255,0,0) => RGB(255,0,255)
 //CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

В следующем примере показано, как быстро преобразовать цвета CMYK в их аналоги RGB с помощью простых формул без использования профилей ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),    // голубой
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),    // Пурпурный
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),    // Желтый
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),    // Черный
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

 // Вывод выглядит так: 
 //Преобразование CMYK в RGB без использования профилей ICC.
 //CMYK(255,0,0,0) => RGB(0,255,255)
 //CMYK(0,255,0,0) => RGB(255,0,255)
 //CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

### Смотрите также

* class [CmykColorHelper](../../cmykcolorhelper)
* пространство имен [Aspose.Imaging](../../cmykcolorhelper)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->