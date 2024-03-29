---
title: Save
second_title: Справочник по Aspose.Imaging for .NET API
description: Сохраняет данные изображения в базовый поток.
type: docs
weight: 240
url: /ru/net/aspose.imaging/image/save/
---
## Save() {#save}

Сохраняет данные изображения в базовый поток.

```csharp
public void Save()
```

### Примеры

В следующем примере показано, как сохранить все изображение BMP или его часть в файл или поток.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Преобразование в черно-белое изображение
    bmpImage.BinarizeOtsu();

    // Сохранить в то же место с параметрами по умолчанию.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Палитра содержит только два цвета: в данном случае черный и белый.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Для всех монохромных изображений (в том числе черно-белых) достаточно выделить 1 бит на пиксель.
    saveOptions.BitsPerPixel = 1;

    // Сохраняем в другое место с указанными параметрами.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Сохраняем только центральную часть изображения.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Сохраняем все изображение в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Сохраняем центральную часть изображения в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Вывод может выглядеть так:
//Размер всего изображения в байтах: 24062
//Размер центральной части изображения в байтах: 6046
```

### Смотрите также

* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Сохраняет изображение в указанном месте файла.

```csharp
public override void Save(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для сохранения изображения. |

### Смотрите также

* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| options | ImageOptionsBase | Опции. |

### Примеры

В следующем примере изображение BMP загружается из файла, а затем сохраняется в файл PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Сохраняем все изображение в файл PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

В этом примере показаны простые шаги для сохранения изображения. Чтобы продемонстрировать эту операцию, мы загружаем существующий файл из некоторого места на диске, выполняем операцию поворота изображения и сохраняем изображение в формате PSD, используя путь к файлу.

```csharp
[C#]

string dir = "c:\\temp\\";

//Создаем экземпляр класса изображения и инициализируем его существующим файлом через путь к файлу
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Поворачиваем изображение на 180 градусов вокруг оси X
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    // Сохраняем изображение как PSD в путь к файлу с настройками PsdOptions по умолчанию
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

В следующем примере показано, как сохранить все изображение BMP или его часть в файл или поток.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Преобразование в черно-белое изображение
    bmpImage.BinarizeOtsu();

    // Сохранить в то же место с параметрами по умолчанию.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Палитра содержит только два цвета: в данном случае черный и белый.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Для всех монохромных изображений (в том числе черно-белых) достаточно выделить 1 бит на пиксель.
    saveOptions.BitsPerPixel = 1;

    // Сохраняем в другое место с указанными параметрами.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Сохраняем только центральную часть изображения.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Сохраняем все изображение в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Сохраняем центральную часть изображения в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Вывод может выглядеть так:
//Размер всего изображения в байтах: 24062
//Размер центральной части изображения в байтах: 6046
```

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| options | ImageOptionsBase | Варианты. |
| boundsRectangle | Rectangle | Конечный образ ограничивает прямоугольник. Установите пустой прямоугольник для использования исходных границ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | опции |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Не удалось сохранить изображение. |

### Примеры

Следующий пример загружает изображение BMP из файла, а затем сохраняет прямоугольную часть изображения в файл PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Сохраняем верхнюю половину изображения в файл PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

В следующем примере показано, как сохранить все изображение BMP или его часть в файл или поток.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Преобразование в черно-белое изображение
    bmpImage.BinarizeOtsu();

    // Сохранить в то же место с параметрами по умолчанию.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Палитра содержит только два цвета: в данном случае черный и белый.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Для всех монохромных изображений (в том числе черно-белых) достаточно выделить 1 бит на пиксель.
    saveOptions.BitsPerPixel = 1;

    // Сохраняем в другое место с указанными параметрами.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Сохраняем только центральную часть изображения.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Сохраняем все изображение в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Сохраняем центральную часть изображения в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Вывод может выглядеть так:
//Размер всего изображения в байтах: 24062
//Размер центральной части изображения в байтах: 6046
```

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который сохраняются данные изображения. |
| optionsBase | ImageOptionsBase | Варианты сохранения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | вариантыБаза |
| ArgumentException | Невозможно сохранить в указанном формате, так как в данный момент он не поддерживается.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Не удалось экспортировать изображение. |

### Примеры

В следующем примере изображение загружается из файла, а затем сохраняется в файловый поток PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Сохраняем все изображение в файловый поток.
        image.Save(outputStream, saveOptions);
    }
}
```

В этом примере показан процесс сохранения изображения в MemoryStream. Чтобы продемонстрировать эту операцию, пример загружает существующий файл из некоторого места на диске, выполняет операцию поворота изображения и сохраняет изображение в формате PSD.

```csharp
[C#]

//Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Создаем экземпляр класса изображения и инициализируем его существующим файлом через путь к файлу
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        // Поворачиваем изображение на 180 градусов вокруг оси X
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        // Сохраняем изображение как PSD в MemoryStream с настройками PsdOptions по умолчанию
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

В следующем примере показано, как сохранить все изображение BMP или его часть в файл или поток.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Преобразование в черно-белое изображение
    bmpImage.BinarizeOtsu();

    // Сохранить в то же место с параметрами по умолчанию.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Палитра содержит только два цвета: в данном случае черный и белый.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Для всех монохромных изображений (в том числе черно-белых) достаточно выделить 1 бит на пиксель.
    saveOptions.BitsPerPixel = 1;

    // Сохраняем в другое место с указанными параметрами.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Сохраняем только центральную часть изображения.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Сохраняем все изображение в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Сохраняем центральную часть изображения в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Вывод может выглядеть так:
//Размер всего изображения в байтах: 24062
//Размер центральной части изображения в байтах: 6046
```

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который сохраняются данные изображения. |
| optionsBase | ImageOptionsBase | Варианты сохранения. |
| boundsRectangle | Rectangle | Конечный образ ограничивает прямоугольник. Установите пустой прямоугольник для использования исходных границ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | вариантыБаза |
| ArgumentException | Невозможно сохранить в указанном формате, так как в данный момент он не поддерживается.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Не удалось экспортировать изображение. |

### Примеры

В следующем примере изображение загружается из файла, а затем сохраняется прямоугольная часть изображения в файловый поток PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Сохраняем верхнюю половину изображения в файловый поток.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

В следующем примере показано, как сохранить все изображение BMP или его часть в файл или поток.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Преобразование в черно-белое изображение
    bmpImage.BinarizeOtsu();

    // Сохранить в то же место с параметрами по умолчанию.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Палитра содержит только два цвета: в данном случае черный и белый.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Для всех монохромных изображений (в том числе черно-белых) достаточно выделить 1 бит на пиксель.
    saveOptions.BitsPerPixel = 1;

    // Сохраняем в другое место с указанными параметрами.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Сохраняем только центральную часть изображения.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Сохраняем все изображение в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Сохраняем центральную часть изображения в поток памяти
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Вывод может выглядеть так:
//Размер всего изображения в байтах: 24062
//Размер центральной части изображения в байтах: 6046
```

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
