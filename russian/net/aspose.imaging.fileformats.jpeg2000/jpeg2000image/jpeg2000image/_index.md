---
title: Jpeg2000Image
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации данных пикселей и палитры. |

### Примеры

В этом примере показано, как загрузить изображение JPEG2000 из файла и сохранить его в формате PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение JPEG2000.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
     // Сохранить в PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации данных пикселей и палитры с помощью |
| bitsPerPixel | Int32 | Количество бит на пиксель. |

### Смотрите также

* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации данных пикселей и палитры. |

### Примеры

В этом примере показано, как загрузить изображение JPEG2000 из файлового потока и сохранить его в формате PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение JPEG2000 из потока.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
     // Сохранить в PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации данных пикселей и палитры. |
| bitsPerPixel | Int32 | Количество бит на пиксель. |

### Смотрите также

* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения |
| height | Int32 | Высота изображения |

### Примеры

В этом примере показано, как создать изображение JPEG2000 и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение JPEG2000 размером 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

     // Заливаем все изображение красным.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

     // Сохраняем в файл
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Смотрите также

* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения |
| height | Int32 | Высота изображения |
| options | Jpeg2000Options | Опции. |

### Примеры

В этом примере показано, как создать изображение PNG и сохранить его в формате JPEG2000 с нужными параметрами.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

 // Использовать необратимое дискретное вейвлет-преобразование 9-7
createOptions.Irreversible = true;

 // JP2 — это «контейнерный» формат для кодовых потоков JPEG 2000.
 // J2K — это необработанные сжатые данные без оболочки.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

 // Создаем изображение JPEG2000 размером 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

     // Заливаем все изображение красным.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

     // Сохраняем в файл
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

В этом примере показано, как создать изображение JPEG2000 с нужными параметрами и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

 // Использовать необратимое дискретное вейвлет-преобразование 9-7
createOptions.Irreversible = true;

 // JP2 — это «контейнерный» формат для кодовых потоков JPEG 2000.
 // J2K — это необработанные сжатые данные без оболочки.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

 // Создаем изображение JPEG2000 размером 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

     // Заливаем все изображение красным.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

     // Сохраняем в файл
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Смотрите также

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения |
| height | Int32 | Высота изображения |
| bitsCount | Int32 | Количество битов. |

### Смотрите также

* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(RasterImage image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение. |

### Примеры

В этом примере показано, как создать изображение JPEG2000 из другого растрового изображения.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG размером 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

     // Заливаем все изображение красным.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

     // Создаем изображение JPEG2000 на основе изображения PNG.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
         // Сохраняем в файл
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Инициализирует новый экземпляр класса[`Jpeg2000Image`](../../jpeg2000image).

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение для инициализации данных пикселей и палитры. |
| bitsPerPixel | Int32 | Количество бит на пиксель. |

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
