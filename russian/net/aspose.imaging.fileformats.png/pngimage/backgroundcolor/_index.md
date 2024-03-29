---
title: BackgroundColor
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает цвет фона.
type: docs
weight: 20
url: /ru/net/aspose.imaging.fileformats.png/pngimage/backgroundcolor/
---
## PngImage.BackgroundColor property

Получает цвет фона.

```csharp
public override Color BackgroundColor { get; set; }
```

### Примеры

В следующем примере показано, как установить полностью прозрачные цвета для части изображения TrueColor PNG, не поддерживающего альфа-канал.

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// Создаем изображение TrueColor PNG размером 100x100 пикселей.
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // Все красные пиксели будут считаться полностью прозрачными.
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // Все прозрачные пиксели будут иметь фоновый цвет.
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // Заливаем все изображение белым цветом.
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // Заливаем верхнюю левую четверть изображения прозрачным цветом.
    // Это делает верхнюю левую четверть окрашенной в цвет фона.
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### Смотрите также

* struct [Color](../../../aspose.imaging/color)
* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
