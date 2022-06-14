---
title: GifFrameBlock
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | UInt16 | Ширина изображения. |
| height | UInt16 | Высота изображения. |

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

В этом примере показано, как создать изображение GIF с пользовательской палитрой и сохранить его в файл.

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

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |
| width | UInt16 | Ширина изображения. |
| height | UInt16 | Высота изображения. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |
| width | UInt16 | Ширина изображения. |
| height | UInt16 | Высота изображения. |
| colorPalette | IColorPalette | Цветовая палитра. |
| isPaletteSorted | Boolean | если установлено значение` true` цветовая палитра сортируется. |
| isGifFrameInterlaced | Boolean | если установлено значение` true` кадр GIF чересстрочный. |
| bitsPerPixel | Byte | Количество бит на пиксель. |

### Смотрите также

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(RasterImage image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение для инициализации пикселей кадра и данных палитры. |

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение для инициализации пикселей кадра и данных палитры. |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение для инициализации пикселей кадра и данных палитры. |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |
| isPaletteSorted | Boolean | если установлено значение` true` цветовая палитра сортируется. |
| isGifFrameInterlaced | Boolean | если установлено значение` true` кадр GIF чересстрочный. |
| lzwCodeSize | Byte | Количество бит на пиксель. |

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации пикселя кадра и данных палитры. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации пикселя кадра и данных палитры. |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации пикселя кадра и данных палитры. |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |
| isPaletteSorted | Boolean | если установлено значение` true` цветовая палитра сортируется. |
| isGifFrameInterlaced | Boolean | если установлено значение` true` кадр GIF чересстрочный. |
| lzwCodeSize | Byte | Количество бит на пиксель. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации пикселя кадра и данных палитры. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации пикселя кадра и данных палитры. |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Инициализирует новый экземпляр класса[`GifFrameBlock`](../../gifframeblock).

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации пикселя кадра и данных палитры. |
| left | UInt16 | Левая позиция изображения. |
| top | UInt16 | Верхняя позиция изображения. |
| isPaletteSorted | Boolean | если установлено значение` true` цветовая палитра сортируется. |
| isGifFrameInterlaced | Boolean | если установлено значение` true` кадр GIF чересстрочный. |
| lzwCodeSize | Byte | Количество бит на пиксель. |

### Смотрите также

* class [GifFrameBlock](../../gifframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
