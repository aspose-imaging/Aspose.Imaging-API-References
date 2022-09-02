---
title: WebPImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Веб-изображение.
type: docs
weight: 8080
url: /ru/net/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

Веб-изображение.

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WebPImage](webpimage#constructor)(RasterImage) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс из rasterImage. |
| [WebPImage](webpimage#constructor_4)(Stream) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) class из потока. |
| [WebPImage](webpimage#constructor_6)(string) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс из файла . |
| [WebPImage](webpimage#constructor_1)(RasterImage, LoadOptions) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс из rasterImage. |
| [WebPImage](webpimage#constructor_5)(Stream, LoadOptions) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс из потока. |
| [WebPImage](webpimage#constructor_7)(string, LoadOptions) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс из файла . |
| [WebPImage](webpimage#constructor_2)(int, int, WebPOptions) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс с пустым изображением. |
| [WebPImage](webpimage#constructor_3)(int, int, WebPOptions, LoadOptions) | Инициализирует новый экземпляр[`WebPImage`](../webpimage) класс с пустым изображением. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.imaging/image/container) { get; } | Получает[`Image`](../../aspose.imaging/image) контейнер. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat) { get; } | Получает значение формата файла |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha) { get; } | Получает альфа-канал. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Получает высоту изображения. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options) { get; } | Получает или задает параметры. |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount) { get; } | Получает количество страниц. |
| override [PageExportingAction](../../aspose.imaging.fileformats.webp/webpimage/pageexportingaction) { get; set; } | Получает или задает действие экспорта страницы. Обратите внимание, что установка этого метода автоматически освобождает ресурсы страницы после его выполнения. Он будет выполняться непосредственно перед сохранением каждой страницы. |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages) { get; } | Получает блоки. |
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
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Получает или устанавливает данные XMP из кадра. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock)(IFrame) | Добавляет новый блок Webp. |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage)(RasterImage) | Добавляет страницу к изображению. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness)(int) | Настройка*brightness* для изображения. |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) контрастный |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma#adjustgamma)(float) | Гамма-коррекция изображения. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma#adjustgamma_1)(float, float, float) | Гамма-коррекция изображения. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley#binarizebradley_1)(double, int) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed)(byte) | Бинаризация изображения с заданным порогом |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu)() | Бинаризация изображения с пороговым значением Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Кэширует приватные данные. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанном формате файла, представленном переданными параметрами сохранения. |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks)() | Очищает все блоки Webp. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop#crop)(Rectangle) | Обрезка изображения. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop#crop_1)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Выполняет сглаживание текущего изображения. |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Выполняет сглаживание текущего изображения. |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
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
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale)() | Преобразование изображения в его представление в градациях серого |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock)(int, IFrame) | Добавляет новый блок Webp. |
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
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock)(IFrame) | Удаляет блок Webp. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Изменяет размер изображения. По умолчаниюNearestNeighbourResample используется. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Изменяет размер высоты пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Изменяет размер высоты пропорционально. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Изменяет ширину пропорционально. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Изменяет ширину пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Изменяет ширину пропорционально. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Изменяет ширину пропорционально. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Повернуть изображение вокруг центра. |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate изображение вокруг центра. |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip)(RotateFlipType) | Вращает, переворачивает или вращает и переворачивает только активный кадр. |
| [Save](../../aspose.imaging/image/save)() | Сохраняет данные изображения в базовый поток. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| override [Save](../../aspose.imaging/image/save)(string) | Сохраняет изображение в указанном месте файла. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Сохраняет 32-битные пиксели ARGB. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Сохраняет пиксели. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Устанавливает 32-битный пиксель изображения ARGB для указанной позиции. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Задает палитру изображения. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Устанавливает разрешение для этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Преобразует растровое изображение в растровое. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

### Примеры

В этом примере показано, как загрузить изображение WebP из файла и сохранить его в формате PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение WebP из файла.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Сохранить в PNG
    // Обратите внимание, что в формате PNG будет сохранен только активный кадр, так как PNG не является многостраничным форматом.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
