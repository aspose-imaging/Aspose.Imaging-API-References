---
title: LinearGradientBrush
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземплярLinearGradientBrushaspose.imaging.brushes/lineargradientbrush класс с параметрами по умолчанию. Начальный цвет черный конечный цвет белый угол 45 градусов и прямоугольник расположен в 00 с размером 11.
type: docs
weight: 10
url: /ru/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс с параметрами по умолчанию. Начальный цвет черный, конечный цвет белый, угол 45 градусов и прямоугольник расположен в (0,0) с размером (1,1).

```csharp
public LinearGradientBrush()
```

### Смотрите также

* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс с указанными точками и цветами.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | Point | А[`Point`](../../../aspose.imaging/point) структура, представляющая начальную точку линейного градиента. |
| point2 | Point | А[`Point`](../../../aspose.imaging/point) структура, представляющая конечную точку линейного градиента. |
| color1 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая начальный цвет линейного градиента. |
| color2 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая конечный цвет линейного градиента. |

### Примеры

В следующем примере показано, как создать копию существующего кадра в градациях серого и добавить ее в изображение TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Создать постоянный, а не временный источник файла.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Заливаем активный кадр кистью с линейным градиентом.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Параметры оттенков серого
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Создаем копию активного кадра в градациях серого.
    // Данные пикселей сохраняются, но преобразуются в нужный формат.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Добавляем только что созданный кадр к изображению TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Смотрите также

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс с указанными точками и цветами.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | PointF | А[`PointF`](../../../aspose.imaging/pointf) структура, представляющая начальную точку линейного градиента. |
| point2 | PointF | А[`PointF`](../../../aspose.imaging/pointf) структура, представляющая конечную точку линейного градиента. |
| color1 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая начальный цвет линейного градиента. |
| color2 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая конечный цвет линейного градиента. |

### Смотрите также

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | А[`RectangleF`](../../../aspose.imaging/rectanglef) структура, задающая границы линейного градиента. |
| color1 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая начальный цвет для градиента. |
| color2 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая конечный цвет градиента. |
| angle | Single | Угол, измеренный в градусах по часовой стрелке от оси x линии ориентации градиента. |

### Смотрите также

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | А[`RectangleF`](../../../aspose.imaging/rectanglef) структура, задающая границы линейного градиента. |
| color1 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая начальный цвет для градиента. |
| color2 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая конечный цвет градиента. |
| angle | Single | Угол, измеренный в градусах по часовой стрелке от оси x линии ориентации градиента. |

### Смотрите также

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | А[`RectangleF`](../../../aspose.imaging/rectanglef) структура, задающая границы линейного градиента. |
| color1 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая начальный цвет для градиента. |
| color2 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая конечный цвет градиента. |
| angle | Single | Угол, измеренный в градусах по часовой стрелке от оси x линии ориентации градиента. |
| isAngleScalable | Boolean | если установлено`истинный` угол изменяется при преобразованиях с этим[`LinearGradientBrush`](../../lineargradientbrush). |

### Смотрите также

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Инициализирует новый экземпляр[`LinearGradientBrush`](../../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | А[`RectangleF`](../../../aspose.imaging/rectanglef) структура, задающая границы линейного градиента. |
| color1 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая начальный цвет для градиента. |
| color2 | Color | А[`Color`](../../../aspose.imaging/color) структура, представляющая конечный цвет градиента. |
| angle | Single | Угол, измеренный в градусах по часовой стрелке от оси x линии ориентации градиента. |
| isAngleScalable | Boolean | если установлено`истинный` угол изменяется при преобразованиях с этим[`LinearGradientBrush`](../../lineargradientbrush). |

### Смотрите также

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* пространство имен [Aspose.Imaging.Brushes](../../lineargradientbrush)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
