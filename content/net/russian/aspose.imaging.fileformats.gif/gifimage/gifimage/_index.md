---
title: GifImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземплярGifImageaspose.imaging.fileformats.gif/gifimage класс.
type: docs
weight: 10
url: /ru/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Инициализирует новый экземпляр[`GifImage`](../../gifimage) класс.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Первый кадр для инициализации gif-изображения. |
| globalPalette | IColorPalette | Глобальная палитра для использования. Обратите внимание, если оба*firstFrame* а также*globalPalette* являются нулевыми, то используется глобальная палитра по умолчанию. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Фрейм не может быть пустым;firstFrame |
| ArgumentException | Первый кадр уже принадлежит какому-то другому изображению. Проверьте свойство Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Указанная палитра должна содержать число элементов, равное степени 2. Минимальный размер палитры — 2, максимальный — 256. |

### Примеры

В этом примере показано, как создать изображение GIF с пользовательской палитрой и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем блок GIF Frame размером 100x100 пикселей.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Заливаем весь блок красным.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Используйте 4-битную палитру для уменьшения размера изображения. Качество может ухудшиться.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### Смотрите также

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Инициализирует новый экземпляр[`GifImage`](../../gifimage) класс.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Первый кадр для инициализации gif-изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Фрейм не может быть пустым;firstFrame |
| ArgumentException | Первый кадр уже принадлежит какому-то другому изображению. Проверьте свойство Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Указанная палитра должна содержать число элементов, равное степени 2. Минимальный размер палитры — 2, максимальный — 256. |

### Примеры

В этом примере показано, как создать изображение в формате GIF и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем блок GIF Frame размером 100x100 пикселей.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Заливаем весь блок красным.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

В следующем примере показано, как составить анимированное изображение GIF из отдельных блоков GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем GIF-изображение 100 x 100 пикселей.
// Первый блок по умолчанию полностью черный.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Первый круг красный
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Второй круг черный
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Постепенно увеличивайте угол красной дуги.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Постепенно увеличивайте угол черной дуги и стирайте красную дугу.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Смотрите также

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Инициализирует новый экземпляр[`GifImage`](../../gifimage) класс.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Первый кадр для инициализации gif-изображения. |
| globalPalette | IColorPalette | Глобальная палитра для использования. Обратите внимание, если оба*firstFrame* а также*globalPalette* являются нулевыми, то используется глобальная палитра по умолчанию. |
| isPaletteSorted | Boolean | если установлено`истинный` палитра отсортирована. Обратите внимание, что параметр используется, когда*globalPalette* не является нулевым. |
| paletteColorResolution | Byte | Цветовое разрешение палитры. Обратите внимание, что параметр используется, когда*globalPalette* не является нулевым. |
| paletteBackgroundColorIndex | Byte | Индекс цвета фона палитры. |
| aspectRatio | Byte | Соотношение сторон. |
| hasTrailer | Boolean | если установлено`истинный` GIF-изображение имеет трейлер, иначе в конце потока не будет записано трейлера. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Фрейм не может быть пустым;firstFrame |
| ArgumentException | Первый кадр уже принадлежит какому-то другому изображению. Проверьте свойство Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Указанная палитра должна содержать число элементов, равное степени 2. Минимальный размер палитры — 2, максимальный — 256. |

### Смотрите также

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
