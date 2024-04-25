---
title: GifOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры создания формата файла gif.
type: docs
weight: 10000
url: /ru/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Параметры создания формата файла gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Инициализирует новый экземпляр[`GifOptions`](../gifoptions) класс. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Инициализирует новый экземпляр[`GifOptions`](../gifoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Получает или задает индекс цвета фона GIF. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Получает или задает цветовое разрешение GIF. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Получает или задает значение, указывающее, есть ли у GIF трейлер. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение GIF прозрачный цвет. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Истинно, если изображение должно быть чересстрочным. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Получает или задает значение, указывающее, отсортированы ли элементы палитры. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Получает или устанавливает количество циклов (по умолчанию 1 цикл) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Получает или задает максимально допустимую разницу в пикселях. Если больше нуля, будет использоваться сжатие с потерями. Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 — очень легкое сжатие, 200 — тяжелое. очень высокие уровни потерь не дадут такого большого выигрыша. Диапазон допустимых значений: [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Получает или задает соотношение сторон GIF в пикселях. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

В этом примере демонстрируется использование различных классов из пространства имен SaveOptions для целей экспорта. Изображение типа Gif загружается в экземпляр Image, а затем экспортируется в несколько форматов.

```csharp
[C#]

string dir = "c:\\temp\\";

//Загружаем существующее изображение (типа Gif) в экземпляр класса Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Экспорт в формат файла BMP, используя параметры по умолчанию
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    // Экспорт в формат файла JPEG с использованием параметров по умолчанию
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    // Экспорт в формат файла PNG с параметрами по умолчанию
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    // Экспорт в формат файла TIFF с параметрами по умолчанию
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

В следующем примере показано, как преобразовать многостраничное векторное изображение в формат GIF в общем виде без ссылки на конкретный тип изображения.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Экспортировать только первые две страницы. Эти страницы будут представлены в виде анимированных кадров в выходном формате GIF.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

В этом примере показано, как загрузить информацию о пикселях в массив цвета типа, манипулировать массивом и установить его обратно в изображение. Для выполнения этих операций в этом примере создается новый файл изображения (в формате GIF) с использованием объекта MemoryStream.

```csharp
[C#]

//Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Создаем экземпляр GifOptions и устанавливаем его различные свойства, включая свойство Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Создаем экземпляр изображения
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Получить пиксели изображения, указав область в качестве границы изображения
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Цикл по массиву и установка цвета альтернативного индексированного пикселя
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Устанавливаем желтый цвет индексированного пикселя
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Устанавливаем синий цвет индексированного пикселя
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        // Применяем изменения пикселей к изображению
        image.SavePixels(image.Bounds, pixels);

        // сохранить все изменения.
        image.Save();
    }

    // Запись MemoryStream в файл
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
