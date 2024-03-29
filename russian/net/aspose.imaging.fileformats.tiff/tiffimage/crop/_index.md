---
title: Crop
second_title: Справочник по Aspose.Imaging for .NET API
description: Обрезка изображения.
type: docs
weight: 240
url: /ru/net/aspose.imaging.fileformats.tiff/tiffimage/crop/
---
## Crop(Rectangle) {#crop}

Обрезка изображения.

```csharp
public override void Crop(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник. |

### Примеры

В следующем примере выполняется обрезка изображения в формате TIFF. Область обрезки задается через Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Обрезать изображение. Область кадрирования представляет собой прямоугольную центральную область изображения.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(tiffImage.Width / 4, tiffImage.Height / 4, tiffImage.Width / 2, tiffImage.Height / 2);
    tiffImage.Crop(area);

    // Сохраняем обрезанное изображение в PNG
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [TiffImage](../../tiffimage)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* сборка [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Обрезать изображение со сдвигами.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | Int32 | Левый сдвиг. |
| rightShift | Int32 | Правильный сдвиг. |
| topShift | Int32 | Верхняя смена. |
| bottomShift | Int32 | Нижний сдвиг. |

### Примеры

В следующем примере выполняется обрезка изображения в формате TIFF. Область обрезки задается с помощью левого, верхнего, правого и нижнего полей.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Обрезать снова. Установите поле в 10% от размера изображения.
    int horizontalMargin = tiffImage.Width / 10;
    int verticalMargin = tiffImage.Height / 10;
    tiffImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Сохраняем обрезанное изображение в формате PNG.
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [TiffImage](../../tiffimage)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
