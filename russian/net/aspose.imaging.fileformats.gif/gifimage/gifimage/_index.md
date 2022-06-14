---
title: GifImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаGifImageaspose.imaging.fileformats.gif/gifimage.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Инициализирует новый экземпляр класса[`GifImage`](../../gifimage).

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Первый кадр для инициализации gif-изображения. |
| globalPalette | IColorPalette | Используемая глобальная палитра. Обратите внимание, что если оба параметра*firstFrame*и*globalPalette*имеют значение null, то используется глобальная палитра по умолчанию. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Кадр не может быть нулевым;firstFrame |
| ArgumentException | Первый кадр уже принадлежит какому-то другому изображению. Проверьте свойство Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Указанная палитра должна содержать число элементов, равное степени 2. Минимальная палитра размер 2, максимальный 256. |

### Примеры

В этом примере показано, как создать изображение GIF с пользовательской палитрой и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем блок кадра GIF размером 100x100 px.
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

Инициализирует новый экземпляр класса[`GifImage`](../../gifimage).

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Первый кадр для инициализации gif-изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Кадр не может быть нулевым;firstFrame |
| ArgumentException | Первый кадр уже принадлежит какому-то другому изображению. Проверьте свойство Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Указанная палитра должна содержать число элементов, равное степени 2. Минимальная палитра размер 2, максимальный 256. |

### Примеры

В этом примере показано, как создать изображение в формате GIF и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем GIF-изображение 100 x 100 px.
 // Первый блок по умолчанию полностью черный.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
     // Первый круг — red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

     // Второй круг — black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

     // Постепенно увеличиваем угол красной дуги shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

     // Постепенно увеличиваем угол черной дуги и стираем красную дугу.
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

В следующем примере показано, как составить анимированное изображение GIF из отдельных блоков GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем GIF-изображение 100 x 100 px.
 // Первый блок по умолчанию полностью черный.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
     // Первый круг — red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

     // Второй круг — black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

     // Постепенно увеличиваем угол красной дуги shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

     // Постепенно увеличиваем угол черной дуги и стираем красную дугу.
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

Инициализирует новый экземпляр класса[`GifImage`](../../gifimage).

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Первый кадр для инициализации gif-изображения. |
| globalPalette | IColorPalette | Используемая глобальная палитра. Обратите внимание, что если оба параметра*firstFrame*и*globalPalette*имеют значение null, то используется глобальная палитра по умолчанию. |
| isPaletteSorted | Boolean | если установлено значение` true` палитра сортируется. Обратите внимание, что параметр используется, когда*globalPalette*не равен нулю. |
| paletteColorResolution | Byte | Цветовое разрешение палитры. Обратите внимание, что параметр используется, когда*globalPalette*не равен нулю. |
| paletteBackgroundColorIndex | Byte | Индекс цвета фона палитры. |
| aspectRatio | Byte | Соотношение сторон. |
| hasTrailer | Boolean | если установлено на` true` изображение gif имеет трейлер, в противном случае трейлер не пишется в конце потока. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Кадр не может быть нулевым;firstFrame |
| ArgumentException | Первый кадр уже принадлежит какому-то другому изображению. Проверьте свойство Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Указанная палитра должна содержать число элементов, равное степени 2. Минимальная палитра размер 2, максимальный 256. |

### Смотрите также

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
