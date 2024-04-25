---
title: DicomImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Это класс реализации работающей с изображением из файла DICOM
type: docs
weight: 2410
url: /ru/aspose.imaging.fileformats.dicom/dicomimage/
---
## DicomImage class

Это класс реализации, работающей с изображением из файла DICOM

```csharp
public sealed class DicomImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DicomImage](dicomimage#constructor_1)(Stream) | Инициализирует новый экземпляр[`DicomImage`](../dicomimage) класс. |
| [DicomImage](dicomimage#constructor_2)(Stream, LoadOptions) | Инициализирует новый экземпляр[`DicomImage`](../dicomimage) класс. |
| [DicomImage](dicomimage#constructor)(DicomOptions, int, int) | Инициализирует новый экземпляр[`DicomImage`](../dicomimage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.dicom/dicomimage/activepage) { get; set; } | Получает или задает активную страницу. |
| [ActivePageIndex](../../aspose.imaging.fileformats.dicom/dicomimage/activepageindex) { get; } | Получает активную страницу индекса. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.imaging/image/container) { get; } | Получает[`Image`](../../aspose.imaging/image) контейнер. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [DicomPages](../../aspose.imaging.fileformats.dicom/dicomimage/dicompages) { get; } | Получает страницы. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [FileFormat](../../aspose.imaging.fileformats.dicom/dicomimage/fileformat) { get; } | Получает значение формата файла |
| [FileInfo](../../aspose.imaging.fileformats.dicom/dicomimage/fileinfo) { get; } | Получает значение, которое содержит информационный заголовок файла DICOM |
| override [HasAlpha](../../aspose.imaging.fileformats.dicom/dicomimage/hasalpha) { get; } | Получает альфа-канал. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Получает высоту изображения. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| override [PageCount](../../aspose.imaging.fileformats.dicom/dicomimage/pagecount) { get; } | Получает количество страниц. |
| override [PageExportingAction](../../aspose.imaging.fileformats.dicom/dicomimage/pageexportingaction) { get; set; } | Получает или задает действие экспорта страницы. Обратите внимание, что установка этого метода автоматически освобождает ресурсы страницы после его выполнения. Он будет выполняться непосредственно перед сохранением каждой страницы. |
| override [Pages](../../aspose.imaging.fileformats.dicom/dicomimage/pages) { get; } | Получает страницы. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения предварительно умножаться. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Получает или задает пользовательский конвертер цветов |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Получает или задает резервный индекс для использования, когда индекс палитры выходит за пределы |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Получает или задает преобразователь индексированных цветов |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Получает исходный размер строки в байтах. |
| [Size](../../aspose.imaging/image/size) { get; } | Получает размер изображения. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Получает прозрачный цвет изображения. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда доступна загрузка необработанных данных. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Получает или задает разрешение по вертикали в пикселях на дюйм этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Получает ширину изображения. |
| override [XmpData](../../aspose.imaging.fileformats.dicom/dicomimage/xmpdata) { get; set; } | Получает или задает данные Xmp. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage#addpage)() | Добавляет новую страницу в конец списка страниц. |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage#addpage_1)(RasterImage) | Добавляет страницу к изображению. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness)(int) | Настройка*brightness* для изображения. |
| override [AdjustContrast](../../aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) контрастный |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma#adjustgamma)(float) | Гамма-коррекция изображения. |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma#adjustgamma_1)(float, float, float) | Гамма-коррекция изображения. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeBradley](../../aspose.imaging.fileformats.dicom/dicomimage/binarizebradley#binarizebradley_1)(double, int) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeFixed](../../aspose.imaging.fileformats.dicom/dicomimage/binarizefixed)(byte) | Бинаризация изображения с заданным порогом |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu)() | Бинаризация изображения с пороговым значением Otsu |
| override [CacheData](../../aspose.imaging.fileformats.dicom/dicomimage/cachedata)() | Кэширует приватные данные. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанном формате файла, представленном переданными параметрами сохранения. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop#crop)(Rectangle) | Обрезка изображения. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop#crop_1)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Выполняет сглаживание текущего изображения. |
| override [Dither](../../aspose.imaging.fileformats.dicom/dicomimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Выполняет сглаживание текущего изображения. |
| override [Filter](../../aspose.imaging.fileformats.dicom/dicomimage/filter)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Получает изображение 32-битного пикселя ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Получает массив 32-битных пикселей ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с помощью частичной загрузки пикселей. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичной загрузки пикселей. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Получает дату и время последнего изменения образа ресурса. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Получает параметры, основанные на настройках исходного файла. Это может быть полезно для сохранения без изменений битовой глубины и других параметров исходного изображения. Например, если мы загружаем черно-белое изображение PNG с 1 битом на пиксель, а затем сохраните его, используя the [`Save`](../../aspose.imaging/datastreamsupporter/save) будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их [`Save`](../../aspose.imaging/image/save) метод в качестве второго параметра. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Получает пиксель изображения. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Получает угол наклона. Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании. |
| override [Grayscale](../../aspose.imaging.fileformats.dicom/dicomimage/grayscale)() | Преобразование изображения в его представление в градациях серого |
| [InsertPage](../../aspose.imaging.fileformats.dicom/dicomimage/insertpage)(int) | Вставляет новую страницу в список страниц по указанному индексу. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Загружает 32-битные пиксели ARGB. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Загружает 64-битные пиксели ARGB. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Загружает 32-битные пиксели ARGB частично по пакетам. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Загружает пиксели частично пачками. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) а также[`Rotate`](../../aspose.imaging/rasterimage/rotate) методы. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует!:GetSkewAngle а также[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) методы. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [RemovePage](../../aspose.imaging.fileformats.dicom/dicomimage/removepage)(int) | Удаляет страницу с указанным индексом из списка страниц. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Изменяет размер изображения. По умолчаниюNearestNeighbourResample используется. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Изменяет размер высоты пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Изменяет размер высоты пропорционально. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Изменяет ширину пропорционально. |
| [ResizeProportional](../../aspose.imaging.fileformats.dicom/dicomimage/resizeproportional)(int, int, ResizeType) | Выполняет пропорциональное изменение размера изображения. Пропорциональное изменение размера изменит размер каждого кадра в соответствии с соотношением*newWidth*/ширина и*newHeight* /высота. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Изменяет ширину пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Изменяет ширину пропорционально. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Изменяет ширину пропорционально. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Повернуть изображение вокруг центра. |
| override [Rotate](../../aspose.imaging.fileformats.dicom/dicomimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate изображение вокруг центра. |
| override [RotateFlip](../../aspose.imaging.fileformats.dicom/dicomimage/rotateflip)(RotateFlipType) | Вращает, переворачивает или вращает и переворачивает только активный кадр. |
| [Save](../../aspose.imaging/image/save)() | Сохраняет данные изображения в базовый поток. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| override [Save](../../aspose.imaging/image/save)(string) | Сохраняет изображение в указанном месте файла. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.imaging.fileformats.dicom/dicomimage/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| [SaveAll](../../aspose.imaging.fileformats.dicom/dicomimage/saveall)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла (индексатор + имя файла) в указанном формате файла в соответствии с параметрами сохранения.. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Сохраняет 32-битные пиксели ARGB. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Сохраняет пиксели. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Устанавливает 32-битный пиксель изображения ARGB для указанной позиции. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Задает палитру изображения. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| override [SetResolution](../../aspose.imaging.fileformats.dicom/dicomimage/setresolution)(double, double) | Устанавливает разрешение для этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Преобразует растровое изображение в растровое. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

### Примеры

Изменить тип цвета при сжатии DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Используйте сжатие RLE в изображении DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

Используйте сжатие JPEG 2000 в изображении DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

Используйте сжатие JPEG в изображении DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

В этом примере показано, как загрузить изображение DICOM из файлового потока.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение DICOM из файлового потока.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Сохраняем каждую страницу как отдельное изображение PNG.                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Генерируем имя файла на основе индекса страницы.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // Страница DICOM — это растровое изображение, поэтому все разрешенные операции с растровым изображением применимы к странице DICOM.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

Создайте многостраничное изображение Dicom.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Рисуем что-нибудь с помощью векторной графики
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Сохраняем пиксели нарисованного изображения. Теперь они находятся на первой странице изображения Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Добавляем несколько страниц после, делая их темнее
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Добавляем несколько страниц перед главной, делая их ярче
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Сохраняем созданное многостраничное изображение в выходной файл
    image.Save("MultiPage.dcm");
}
```

### Смотрите также

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* пространство имен [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
