---
title: TgaImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Изображение TGA.
type: docs
weight: 7580
url: /ru/net/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

Изображение TGA.

```csharp
public class TgaImage : RasterCachedImage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TgaImage](tgaimage#constructor)(RasterImage) | Инициализирует новый экземпляр[`TgaImage`](../tgaimage) класс. |
| [TgaImage](tgaimage#constructor_1)(Stream) | Инициализирует новый экземпляр[`TgaImage`](../tgaimage) класс. |
| [TgaImage](tgaimage#constructor_2)(string) | Инициализирует новый экземпляр[`TgaImage`](../tgaimage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments) { get; set; } | Получает или задает комментарии автора. Это поле ASCII, состоящее из 324 байтов, организованных в виде четырех строк по 80 символов, за каждой из которых следует завершающий нуль. |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname) { get; set; } | Получает или задает имя автора. Это поле содержит в общей сложности 40 символов ASCII для имени. Если используется поле , оно должно содержать имя человека, создавшего изображение (автора). |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel) { get; } | Получает количество бит на пиксель. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel) { get; } | Получает количество байтов на пиксель. |
| [Container](../../aspose.imaging/image/container) { get; } | Получает[`Image`](../../aspose.imaging/image) контейнер. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp) { get; set; } | Получает или задает метку даты/времени. Это поле определяет значение даты и времени сохранения изображения. Несмотря на то, что операционные системы обычно используют файлы с отметками времени и даты, эта функция предоставляется, поскольку операционная система может изменить отметку времени и даты, если файл скопирован. Используя эту область, вы гарантируете неизмененный регион для даты и времени записи. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat) { get; } | Получает формат файла. |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator) { get; } | Получает часть знаменателя значения гаммы. Неисправленное изображение (изображение без гаммы) должно иметь в результате значение 1,0. |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator) { get; } | Получает часть числителя значения гаммы. Нескорректированное изображение (изображение без гаммы) должно иметь в результате значение 1,0. |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha) { get; } | Получает значение, указывающее, является ли это[`TgaImage`](../tgaimage) имеет альфа-канал. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap) { get; } | Получает значение, указывающее, имеет ли это изображение цветовую карту. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height) { get; } | Получает высоту этого изображения. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid) { get; set; } | Получает или задает идентификатор изображения. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale) { get; } | Получает значение, указывающее, является ли это[`TgaImage`](../tgaimage) в оттенках серого. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid) { get; set; } | Получает или задает имя/идентификатор задания. |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime) { get; set; } | Получает или задает время задания. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator) { get; } | Получает часть знаменателя соотношения сторон пикселя. |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator) { get; } | Получает часть числителя пропорций пикселя. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения предварительно умножаться. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Получает или задает пользовательский конвертер цветов |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Получает или задает резервный индекс для использования, когда индекс палитры выходит за пределы |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Получает или задает преобразователь индексированных цветов |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Получает исходный размер строки в байтах. |
| [Size](../../aspose.imaging/image/size) { get; } | Получает размер изображения. |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid) { get; set; } | Получает или устанавливает идентификатор программного обеспечения. Всего 40 символов ASCII для идентификатора программного обеспечения. |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion) { get; set; } | Получает или задает версию программного обеспечения. Допустимая длина строки версии 3-4 символа. |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter) { get; set; } | Получает или задает буквенную часть версии программного обеспечения. |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber) { get; set; } | Получает или задает часть номера версии программного обеспечения. |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor) { get; set; } | Получает или задает ключевой цвет. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда доступна загрузка необработанных данных. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Получает или задает разрешение по вертикали в пикселях на дюйм этого[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width) { get; } | Получает ширину этого изображения. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Получает или задает метаданные XMP. |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin) { get; set; } | Получает или задает абсолютную горизонтальную координату для нижнего левого угла изображения , поскольку оно расположено на устройстве отображения, имеющем начало координат в левом нижнем углу экрана (например, серия TARGA). |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin) { get; set; } | Получает или задает абсолютную вертикальную координату нижнего левого угла изображения , поскольку оно расположено на устройстве отображения, имеющем начало координат в левом нижнем углу экрана (например, серии TARGA). |

## Методы

| Имя | Описание |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Настройка яркости изображения. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Изображение контрастное |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Гамма-коррекция изображения. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Гамма-коррекция изображения. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Бинаризация изображения с заданным порогом |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Бинаризация изображения с пороговым значением Otsu |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанном формате файла, представленном переданными параметрами сохранения. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone)() | Создает новый объект, являющийся копией текущего экземпляра. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone_1)(TgaImage) | Клонировать другое[`TgaImage`](../tgaimage) свойства объекта. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop)(Rectangle) | Обрезка изображения. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop_1)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Выполняет сглаживание текущего изображения. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Выполняет сглаживание текущего изображения. |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals_1)(object) | Сравнение равенства. |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals)(TgaImage) | Сравнение равенства. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Получает изображение 32-битного пикселя ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Получает массив 32-битных пикселей ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с помощью частичной загрузки пикселей. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичной загрузки пикселей. |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode)() | Получить хэш-код этого экземпляра. Не подходит для использования в качестве ключа, т.к.[`TgaImage`](../tgaimage) не является неизменным. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Получает дату и время последнего изменения образа ресурса. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Получает параметры, основанные на настройках исходного файла. Это может быть полезно для сохранения без изменений битовой глубины и других параметров исходного изображения. Например, если мы загружаем черно-белое изображение PNG с 1 битом на пиксель, а затем сохраните его, используя the [`Save`](../../aspose.imaging/datastreamsupporter/save) будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их [`Save`](../../aspose.imaging/image/save) метод в качестве второго параметра. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Получает пиксель изображения. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Получает угол наклона. Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Преобразование изображения в его представление в градациях серого |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Загружает 32-битные пиксели ARGB. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Загружает 64-битные пиксели ARGB. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Загружает 32-битные пиксели ARGB частично по пакетам. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Загружает пиксели частично пачками. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) а также[`Rotate`](../../aspose.imaging/rasterimage/rotate) методы. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) а также[`Rotate`](../../aspose.imaging/rasterimage/rotate) методы. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Изменяет размер изображения. По умолчаниюNearestNeighbourResample используется. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Изменяет размер высоты пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Изменяет размер высоты пропорционально. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Изменяет размер высоты пропорционально. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Изменяет ширину пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Изменяет ширину пропорционально. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Изменяет ширину пропорционально. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Повернуть изображение вокруг центра. |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate изображение вокруг центра. |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip)(RotateFlipType) | Переворот с поворотом. |
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
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality) | Сравнение равенства. |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality) | Сравнение не на равенство. |

### Примеры

Сохранение изображения JPG как изображения TGA.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Загрузка изображения PNG, преобразование его в TgaImage и сохранение в виде изображения TGA.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

Обновление общедоступных свойств загруженного изображения TGA.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Получение значений публичных свойств загруженного изображения TGA.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### Смотрите также

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* пространство имен [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
