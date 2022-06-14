---
title: JpegImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаJpegImageaspose.imaging.fileformats.jpeg/jpegimage.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Инициализирует новый экземпляр класса[`JpegImage`](../../jpegimage).

```csharp
public JpegImage(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации данных пикселей и палитры. |

### Примеры

В примере показано, как загрузить JpegImage из файла.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение JPEG из файла.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
     // Обработаем изображение.
     // Сохраняем в другой файл JPEG.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Смотрите также

* class [JpegImage](../../jpegimage)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* сборка [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Инициализирует новый экземпляр класса[`JpegImage`](../../jpegimage).

```csharp
public JpegImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации данных пикселей и палитры. |

### Примеры

В примере показано, как загрузить JpegImage из файлового потока.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение JPEG из файлового потока.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
         // Обработаем изображение.
         // Сохраняем в другой файл JPEG.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Смотрите также

* class [JpegImage](../../jpegimage)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* сборка [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Инициализирует новый экземпляр класса[`JpegImage`](../../jpegimage).

```csharp
public JpegImage(RasterImage rasterImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение для инициализации данных пикселей и палитры. |

### Примеры

В примере показано, как загрузить JpegImage из другого RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение JPEG из другого растрового изображения.
 // Во-первых, создайте временное изображение PNG, которое будет основой для построения изображения JPEG.
 // Вы также можете загрузить изображение PNG из файла или использовать изображение любого другого растрового формата.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
     // Заливаем всё изображение PNG красным цветом.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

     // Создаем изображение JPEG на основе изображения PNG.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
         // Сохраняем в файл JPEG
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* сборка [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Инициализирует новый экземпляр класса[`JpegImage`](../../jpegimage).

```csharp
public JpegImage(int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |

### Примеры

В следующем примере показано, как создать изображение JPEG указанного размера.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение BMP из файла.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
     // Обработаем изображение.

     // Используйте дополнительные опции, чтобы указать нужные параметры изображения.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

     // Количество бит на канал 8.
     // Когда используется палитра, индекс цвета сохраняется в данных изображения вместо самого цвета.
    saveOptions.BitsPerChannel = 8;

     // Установить прогрессивный тип сжатия.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

     // Установить качество изображения. Это значение от 1 до 100.
    saveOptions.Quality = 100;

     // Установить разрешение по горизонтали/вертикали на 96 точек на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

     // Если исходное изображение цветное, оно будет преобразовано в оттенки серого.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

     // Используйте палитру для уменьшения выходного размера.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

В следующем примере загружается изображение BMP и сохраняется в формате JPEG с использованием различных параметров сохранения.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение BMP из файла.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
     // Обработаем изображение.

     // Используйте дополнительные опции, чтобы указать нужные параметры изображения.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

     // Количество бит на канал 8.
     // Когда используется палитра, индекс цвета сохраняется в данных изображения вместо самого цвета.
    saveOptions.BitsPerChannel = 8;

     // Установить прогрессивный тип сжатия.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

     // Установить качество изображения. Это значение от 1 до 100.
    saveOptions.Quality = 100;

     // Установить разрешение по горизонтали/вертикали на 96 точек на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

     // Если исходное изображение цветное, оно будет преобразовано в оттенки серого.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

     // Используйте палитру для уменьшения выходного размера.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

### Смотрите также

* class [JpegImage](../../jpegimage)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* сборка [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Инициализирует новый экземпляр класса[`JpegImage`](../../jpegimage).

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| jpegOptions | JpegOptions | Параметры JPEG. |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |

### Примеры

В следующем примере загружается изображение BMP и сохраняется в формате JPEG с использованием различных параметров сохранения.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем изображение в формате JPEG 100x100 px.
 // Используйте дополнительные опции, чтобы указать нужные параметры изображения.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

 // Количество бит на канал 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.BitsPerChannel = 8;

 // Установить прогрессивный тип сжатия.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

 // Установить качество изображения. Это значение от 1 до 100.
createOptions.Quality = 100;

 // Установить разрешение по горизонтали/вертикали на 96 точек на дюйм.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

 // Это стандартная опция для изображений JPEG.
 // Два компонента цветности (Cb и Cr) могут быть подвергнуты уменьшению пропускной способности, субдискретизации, сжатию.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

     // Заливаем изображение оттенками серого градиента
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

     // Сохраняем в файл.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

В следующем примере показано, как создать изображение JPEG указанного размера с указанными параметрами.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем изображение в формате JPEG 100x100 px.
 // Используйте дополнительные опции, чтобы указать нужные параметры изображения.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

 // Количество бит на канал 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.BitsPerChannel = 8;

 // Установить прогрессивный тип сжатия.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

 // Установить качество изображения. Это значение от 1 до 100.
createOptions.Quality = 100;

 // Установить разрешение по горизонтали/вертикали на 96 точек на дюйм.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

 // Это стандартная опция для изображений JPEG.
 // Два компонента цветности (Cb и Cr) могут быть подвергнуты уменьшению пропускной способности, субдискретизации, сжатию.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

     // Заливаем изображение оттенками серого градиента
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

     // Сохраняем в файл.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Смотрите также

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
