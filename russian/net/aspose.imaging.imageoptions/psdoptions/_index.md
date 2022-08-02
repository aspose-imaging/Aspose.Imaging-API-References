---
title: PsdOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры создания файла формата psd.
type: docs
weight: 10140
url: /ru/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Параметры создания файла формата psd.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Инициализирует новый экземпляр[`PsdOptions`](../psdoptions) класс. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Инициализирует новый экземпляр[`PsdOptions`](../psdoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Получает или задает количество битов на цветовой канал. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Получает или задает количество цветовых каналов. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | Получает или задает цветовой режим PSD. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | Получает или задает метод сжатия psd. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Получает или задает версию формата файла. Это может быть PSD или PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Получает или задает значение, указывающее, используется ли параметр [обновить данные предварительного просмотра изображения] для обеспечения максимальной совместимости с другими средствами просмотра изображений PSD. |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Получает или задает значение, указывающее: - Удалить глобальный ресурс текстового движка - Используется для некоторых текстовых файлов psd, только в том случае, когда их нельзя открыть в Adobe Photoshop после обработки (в основном для отсутствующих шрифтов, связанных с текстовыми слоями). После использования этой опции пользователю необходимо сделать следующее в открытом в Photoshop файле: Меню "Текст" -&gt; "Обработать отсутствующие шрифты". После этой операции весь текст снова появится. Обратите внимание, что эта операция может вызвать некоторые окончательные изменения макета. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | Получает или задает параметры векторизации PSD. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | Получает или задает версию файла psd. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | Получить или установить контейнер данных XMP |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

В этом примере демонстрируется использование Aspsoe.Imaging for .Net API для преобразования изображений в формат PSD. Для достижения этой цели в этом примере загружается существующее изображение, а затем сохраняется обратно в формате PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

//Создает экземпляр класса изображения и инициализирует его существующим файлом через путь к файлу
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Создаем экземпляр класса PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Установите CompressionMethod как RLE
    //Примечание: другим поддерживаемым методом сжатия является CompressionMethod.RAW [без сжатия]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //Установите ColorMode в GrayScale
    //Примечание. Другими поддерживаемыми режимами ColorModes являются ColorModes.Bitmap и ColorModes.RGB.
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    // Сохраняем изображение на диск с предоставленными настройками PsdOptions
    image.Save(dir + "output.psd", psdOptions);
}
```

В следующем примере показано, как преобразовать многостраничное векторное изображение в формат PSD в общем виде без ссылки на конкретный тип изображения.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Экспортировать только первые две страницы. Эти страницы будут представлены в виде слоев в выходном PSD.
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

### Смотрите также

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
