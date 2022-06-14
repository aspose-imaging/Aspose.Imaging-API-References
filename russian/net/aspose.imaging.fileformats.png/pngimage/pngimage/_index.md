---
title: PngImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаPngImageaspose.imaging.fileformats.png/pngimage.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина. |
| height | Int32 | Высота. |

### Примеры

В этом примере показано, как создать PNG-изображение заданного размера, заполнить его сплошным цветом и сохранить в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG размером 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
     // Произвести некоторую обработку изображения, например, заполнить все изображение красным цветом.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

     // Сохраняем в файл.
    pngImage.Save(dir + "output.png");
}
```

### Смотрите также

* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения. |

### Примеры

В этом примере показано, как загрузить изображение PNG из файла.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загружаем изображение PNG из файла.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
     // Преобразование изображения в оттенки серого, представление
    pngImage.Grayscale();

     // Сохраняем в файл.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Смотрите также

* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(RasterImage rasterImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Растровое изображение. |

### Примеры

В этом примере показано, как загрузить изображение PNG из изображения BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загружаем изображение TrueColor PNG из изображения BMP.
 // Во-первых, создайте временное изображение BMP, которое будет основой для построения изображения PNG.
 // Вы также можете загрузить изображение BMP из файла или использовать изображение любого другого растрового формата.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
     // Заливаем все изображение BMP красным цветом.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(string path, PngColorType colorType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения. |
| colorType | PngColorType | Тип цвета. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException |  |

### Примеры

В этом примере показано, как загрузить изображение PNG из файла с указанным типом цвета.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загружаем изображение PNG из файла.
 // Обратите внимание, что цветное изображение будет автоматически преобразовано в оттенки серого.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
     // Сохраняем в файл.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Смотрите также

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Растровое изображение. |
| colorType | PngColorType | Тип цвета. |

### Примеры

В этом примере показано, как загрузить изображение PNG из изображения BMP с указанным типом цвета.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузите изображение PNG в оттенках серого из цветного изображения BMP.
 // Во-первых, создайте временное изображение BMP, которое будет основой для построения изображения PNG.
 // Вы также можете загрузить изображение BMP из файла или использовать изображение любого другого растрового формата.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
     // Заливаем все изображение BMP красным цветом.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

     // Цвета пикселей изображения будут преобразованы в их оттенки серого.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения. |

### Примеры

В этом примере показано, как загрузить изображение PNG из файла или файлового потока.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загрузить изображение PNG из файлового потока.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
         // Преобразование изображения в оттенки серого, представление
        pngImage.Grayscale();

         // Сохраняем в файл.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Смотрите также

* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина. |
| height | Int32 | Высота. |
| colorType | PngColorType | Тип цвета. |

### Примеры

В этом примере показано, как создать изображение PNG заданного размера с указанным типом цвета, заполнить его сплошным цветом и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG в градациях серого размером 100x100 px.
// Все цвета будут автоматически преобразованы в формат оттенков серого.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
     // Произвести некоторую обработку изображения, например, заполнить все изображение красным цветом.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

     // Сохраняем в файл.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Смотрите также

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Инициализирует новый экземпляр класса[`PngImage`](../../pngimage).

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pngOptions | PngOptions | Параметры png. |
| width | Int32 | Ширина. |
| height | Int32 | Высота. |

### Примеры

В этом примере показано, как создать изображение PNG с указанными параметрами, заполнить его цветами линейного градиента и сохранить в файл .

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

 // Количество бит на цвет channel
createOptions.BitDepth = 8;

 // Каждый пиксель представляет собой тройку (красный, зеленый, синий), за которой следует альфа-компонент.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

 // Максимальный уровень сжатия.
createOptions.CompressionLevel = 9;

 // Использование фильтров позволяет более эффективно сжимать непрерывные тональные изображения.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

 // Использовать прогрессивную загрузку
createOptions.Progressive = true;

 // Создаем изображение PNG с пользовательскими параметрами.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

     // Заливаем изображение полупрозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

     // Сохраняем в файл.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### Смотрите также

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
