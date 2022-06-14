---
title: GifOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры создания файла формата gif.
type: docs
weight: 10000
url: /ru/net/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Параметры создания файла формата gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Инициализирует новый экземпляр класса[`GifOptions`](../gifoptions). |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Инициализирует новый экземпляр класса[`GifOptions`](../gifoptions). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Получает или задает индекс цвета фона GIF. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Получает или задает цветовое разрешение GIF. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Получает или задает значение, указывающее, есть ли у GIF трейлер. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение GIF прозрачный цвет. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | True, если изображение должно быть чересстрочным. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Получает или задает значение, указывающее, сортируются ли элементы палитры. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Получает или устанавливает количество циклов (по умолчанию 1 цикл) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Получает или задает максимально допустимую разницу в пикселях. Если больше нуля, будет использоваться сжатие с потерями. Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 — очень легкое сжатие, 200 — тяжелое. Это работает лучше всего, когда вводятся лишь небольшие потери, а из-за ограничений алгоритма сжатия очень высокие уровни потерь не дадут такого большого выигрыша. Диапазон допустимых значений:[0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Получает или задает соотношение сторон пикселя GIF. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

Этот пример демонстрирует использование различных классов из пространства имен SaveOptions для целей экспорта. Изображение типа Gif загружается в экземпляр Image, а затем экспортируется в несколько форматов.

```csharp
[C#]

 //Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
     //Создаем экземпляр GifOptions и устанавливаем его различные свойства, включая Source property
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

     //Создаем экземпляр Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
         //Получить пиксели изображения, указав область как изображение border
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

         // Перебираем массив и устанавливаем цвет альтернативного индексированного pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                 //Установите цвет индексированного пикселя на yellow
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Установите цвет индексированного пикселя на blue
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

         // Применяем изменения пикселей к image
        image.SavePixels(image.Bounds, pixels);

         // сохранить все изменения.
        image.Save();
    }

     // Запись MemoryStream в File
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

В следующем примере показано, как преобразовать многостраничное векторное изображение в формат GIF в общем виде без ссылки на конкретный тип изображения.

```csharp
[C#]

 //Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
     //Создаем экземпляр GifOptions и устанавливаем его различные свойства, включая Source property
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

     //Создаем экземпляр Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
         //Получить пиксели изображения, указав область как изображение border
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

         // Перебираем массив и устанавливаем цвет альтернативного индексированного pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                 //Установите цвет индексированного пикселя на yellow
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Установите цвет индексированного пикселя на blue
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

         // Применяем изменения пикселей к image
        image.SavePixels(image.Bounds, pixels);

         // сохранить все изменения.
        image.Save();
    }

     // Запись MemoryStream в File
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

В этом примере показано, как загрузить информацию о пикселях в массив цветов типа, манипулировать массивом и установить его обратно в изображение. Для выполнения этих операций в этом примере создается новый файл изображения (в формате GIF) с использованием объекта MemoryStream.

```csharp
[C#]

 //Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
     //Создаем экземпляр GifOptions и устанавливаем его различные свойства, включая Source property
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

     //Создаем экземпляр Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
         //Получить пиксели изображения, указав область как изображение border
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

         // Перебираем массив и устанавливаем цвет альтернативного индексированного pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                 //Установите цвет индексированного пикселя на yellow
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Установите цвет индексированного пикселя на blue
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

         // Применяем изменения пикселей к image
        image.SavePixels(image.Bounds, pixels);

         // сохранить все изменения.
        image.Save();
    }

     // Запись MemoryStream в File
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
