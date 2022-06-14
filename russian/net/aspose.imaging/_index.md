---
title: Aspose.Imaging
second_title: Справочник по Aspose.Imaging for .NET API
description: Пространство имен является ядром для вложенных пространств имен и самых основных объектов используемых для обработки Aspose.Imaging.
type: docs
weight: 10
url: /ru/net/aspose.imaging/
---
Пространство имен является ядром для вложенных пространств имен и самых основных объектов, используемых для обработки Aspose.Imaging.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AggregateException](./aggregateexception) | Объединяет несколько исключений. |
| [Blend](./blend) | Определяет шаблон перехода. Этот класс не может быть унаследован. |
| [Brush](./brush) | Базовый класс кисти. |
| [BuildVersionInfo](./buildversioninfo) | Содержит информацию о текущей версии сборки. |
| [Cache](./cache) | Содержит настройки кэша. |
| [CmykColorHelper](./cmykcolorhelper) | Вспомогательные методы для работы с цветом CMYK, представленным в виде 32-битного целого числа со знаком. Предоставляет тот же API, что и структура[`CmykColor`](../aspose.imaging/cmykcolor). Он легче, потому что цвет CMYK представлен как Int32, а не как структура с внутренними полями. Пожалуйста, по возможности предпочтительнее использовать статические методы этого класса вместо устаревшей [`CmykColor`](../aspose.imaging/cmykcolor)struct. |
| [ColorBlend](./colorblend) | Определяет массивы цветов и позиций, используемых для интерполяции смешивания цветов в многоцветном градиенте. Этот класс не может быть унаследован. |
| [ColorMap](./colormap) | Определяет карту для преобразования цветов. Несколько методов класса[`ImageAttributes`](../aspose.imaging/imageattributes)настраивают цвета изображения с помощью таблицы переназначения цветов, которая представляет собой массив[`ColorMap`](../aspose.imaging/colormap)структуры. Не передается по наследству. |
| [ColorMatrix](./colormatrix) | Определяет матрицу 5 x 5, содержащую координаты пространства RGBA. Несколько методов класса[`ImageAttributes`](../aspose.imaging/imageattributes)настраивают цвета изображения с помощью цветовой матрицы. Этот класс не может быть унаследован. |
| [ColorPalette](./colorpalette) | Определяет массив цветов, составляющих цветовую палитру. Цвета являются 32-битными цветами ARGB. Не передается по наследству. |
| [ColorPaletteHelper](./colorpalettehelper) | Вспомогательный класс для работы с цветовыми палитрами. |
| [ColorTranslator](./colortranslator) | Преобразует цвета в и из структур GDI+ Color. Этот класс не может быть унаследован. |
| [CompositeException](./compositeexception) | Составное исключение |
| [CustomFontSource](./customfontsource) | Функция поставщика пользовательского источника шрифта |
| [CustomLineCap](./customlinecap) | Инкапсулирует определяемый пользователем конец строки. |
| [DataStreamSupporter](./datastreamsupporter) | Контейнер потока данных. |
| [DisposableObject](./disposableobject) | Представляет одноразовый объект. |
| [EmbeddedImage](./embeddedimage) | Класс встроенного образа |
| [Figure](./figure) | Фигура. Контейнер для форм. |
| [FileStreamContainer](./filestreamcontainer) | Помощник для обработки файлового потока. |
| [Font](./font) | Определяет определенный формат для текста, включая начертание шрифта, размер и атрибуты стиля. Этот класс не может быть унаследован. |
| [FontSettings](./fontsettings) | Общие настройки шрифта рендерера векторных форматов изображения. |
| [Graphics](./graphics) | Представляет графику в соответствии с графическим движком, используемым в текущей сборке. |
| [GraphicsPath](./graphicspath) | Представляет серию соединенных линий и кривых. Этот класс не может быть унаследован. |
| [Image](./image) | Образ является базовым классом для всех типов изображений. |
| [ImageAttributes](./imageattributes) | Объект[`ImageAttributes`](../aspose.imaging/imageattributes)содержит информацию о том, как цвета растрового изображения и метафайла манипулируются во время рендеринга. Объект[`ImageAttributes`](../aspose.imaging/imageattributes)поддерживает несколько настроек настройки цвета, включая матрицы настройки цвета, матрицы настройки оттенков серого, значения гамма-коррекции, таблицы карты цветов и пороговые значения цвета. . Во время рендеринга цвета можно корректировать, затемнять, осветлять и удалять. Чтобы применить такие манипуляции, инициализируйте объект[`ImageAttributes`](../aspose.imaging/imageattributes)и передайте путь этому объекту[`ImageAttributes`](../aspose.imaging/imageattributes)(вместе с путем объекта[`Image`](../aspose.imaging/image)) в метод DrawImage. |
| [ImageCreatorsRegistry](./imagecreatorsregistry) | Представляет реестр создателей образов. |
| [ImageExportersRegistry](./imageexportersregistry) | Представляет реестр экспортеров образов. |
| [ImageLoadersRegistry](./imageloadersregistry) | Представляет реестр загрузчиков образов. |
| [ImageOptionsBase](./imageoptionsbase) | Параметры базы изображений. |
| [ImageResizeSettings](./imageresizesettings) | Класс настроек изменения размера изображения |
| [IntRange](./intrange) | Класс для представления последовательности элементов |
| [License](./license) | Предоставляет методы для лицензирования компонента. |
| [LoadOptions](./loadoptions) | Представляет параметры загрузки. |
| [Matrix](./matrix) | Заменяет матрицу GDI+. |
| [Metered](./metered) | Предоставляет методы для установки измеренного ключа. |
| [NonGenericDictionary](./nongenericdictionary) | Представляет не универсальный словарь. |
| [NonGenericList](./nongenericlist) | Необщий список объектов |
| [ObjectWithBounds](./objectwithbounds) | Объект с границами. |
| [OpenTypeFontsCache](./opentypefontscache) | Кэш для шрифтов OpenType, установленных в системе. |
| [PageExportingAction](./pageexportingaction) | Делегат для запуска перед экспортом страницы |
| [Pen](./pen) | Определяет объект, используемый для рисования линий, кривых и фигур. |
| [PixelDataFormat](./pixeldataformat) | Формат данных пикселей. Это неизменяемый объект. |
| [ProgressEventHandler](./progresseventhandler) | Справочник по функциям обработчика событий Progress |
| [RasterCachedImage](./rastercachedimage) | Представляет растровое изображение, поддерживающее операции с растровой графикой. Это изображение кэширует пиксельные данные, когда это необходимо. |
| [RasterCachedMultipageImage](./rastercachedmultipageimage) | Растровое многостраничное изображение |
| [RasterImage](./rasterimage) | Представляет растровое изображение, поддерживающее операции с растровой графикой. |
| [RawDataSettings](./rawdatasettings) | Настройки необработанных данных |
| [Region](./region) | Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть унаследован. |
| [ResolutionSetting](./resolutionsetting) | Настройка разрешения для параметров сохранения изображения. |
| [Shape](./shape) | Форма. Непрерывный набор точек, соединенных по определенному правилу. |
| [ShapeSegment](./shapesegment) | Представляет сегмент формы. Сегмент — это линия или кривая, соединяющая две точки. |
| [Source](./source) | Источник используется для хранения всей соответствующей информации для канала объекта. |
| [SplitStreamContainer](./splitstreamcontainer) | Представляет контейнер разделенного потока, который содержит поток и предоставляет подпрограммы обработки потока. |
| [StreamContainer](./streamcontainer) | Представляет контейнер потока, который содержит поток и предоставляет подпрограммы обработки потока. |
| [StringFormat](./stringformat) | Инкапсулирует информацию о макете текста (например, выравнивание, ориентация и позиции табуляции), манипуляции с отображением (например, вставка многоточия и замена национальных цифр) и функции OpenType. Этот класс не может быть унаследован. |
| [TransparencySupporter](./transparencysupporter) | Объект, поддерживающий прозрачность. |
| [VectorImage](./vectorimage) | Векторное изображение является базовым классом для всех типов векторных изображений. |
| [VectorMultipageImage](./vectormultipageimage) | Векторное многостраничное изображение |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor) | Расширенный буферный процессор. |
| [IAnimationFrame](./ianimationframe) | Кадр анимации |
| [IBufferProcessor](./ibufferprocessor) | Процессор буфера. |
| [IColorConverter](./icolorconverter) | Преобразователь цвета. |
| [IColorPalette](./icolorpalette) | Интерфейс цветовой палитры. |
| [IImageCreator](./iimagecreator) | Создатель изображения. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor) | Дескриптор создателя изображения, определяющий свойства создателя. Дескриптор создателя используется для преодоления необходимости содержать каждый экземпляр создателя изображения в памяти и проблем многопоточности. |
| [IImageDescriptor](./iimagedescriptor) | Дескриптор изображения. Содержит базовые свойства и методы для всех остальных типов дескрипторов изображений. |
| [IImageExporter](./iimageexporter) | Экспортер изображений. Может экспортировать данные из внутреннего формата Aspose.Imaging в указанный формат данных. |
| [IImageExporterDescriptor](./iimageexporterdescriptor) | Представляет дескриптор экспортера изображений. Дескриптор экспортера используется для преодоления необходимости содержать каждый экземпляр экспортера в памяти и проблем с многопоточностью. |
| [IImageLoader](./iimageloader) | Загрузчик изображений. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor) | Дескриптор загрузчика изображения, определяющий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности. |
| [IIndexedColorConverter](./iindexedcolorconverter) | Преобразователь цвета для индексированных форматов изображений. |
| [IKeyedObject](./ikeyedobject) | Представляет интерфейс для объектов с ключами. |
| [IMultipageImage](./imultipageimage) | Интерфейс многостраничных изображений |
| [IMultipageImageExt](./imultipageimageext) | Расширенный интерфейс многостраничных изображений |
| [IObjectWithBounds](./iobjectwithbounds) | Представляет объект с границами. |
| [IOrderedShape](./iorderedshape) | Представляет упорядоченную форму. Упорядоченная форма представляет собой непрерывный набор точек, имеющих начальную точку и конечную точку. Непрерывный набор точек, соединенных по определенному правилу. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader) | Соответствует частично загруженным 32-битным пикселям ARGB. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader) | 64-битный загрузчик пикселей ARGB. |
| [IPartialPixelLoader](./ipartialpixelloader) | Соответствует частично загруженным пикселям. |
| [IPartialRawDataLoader](./ipartialrawdataloader) | Частичный загрузчик данных. |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader) | 32-битный загрузчик пикселей растрового изображения ARGB. |
| [IRasterImagePixelLoader](./irasterimagepixelloader) | Пиксельный загрузчик растрового изображения. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader) | Загрузчик необработанных данных растрового изображения. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [AnimationDisposalMethods](./animationdisposalmethods) | Указывает способ обработки изображения после его отображения. |
| [CacheType](./cachetype) | Задает используемый тип кэша. |
| [CharacterSet](./characterset) | Представляет используемый набор символов. |
| [ColorAdjustType](./coloradjusttype) | Указывает, какие объекты используют информацию о настройке цвета. |
| [ColorChannelFlag](./colorchannelflag) | Задает отдельные каналы в цветовом пространстве CMYK (голубой, пурпурный, желтый, черный). Это перечисление используется методами SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod) | Метод сравнения цветов для настройки на ближайшего соседа |
| [ColorMatrixFlag](./colormatrixflag) | Указывает типы изображений и цветов, на которые будут влиять настройки цвета и оттенков серого[`ImageAttributes`](../aspose.imaging/imageattributes). |
| [ColorQuantizationMethod](./colorquantizationmethod) | Методы квантования цветов |
| [CompositingQuality](./compositingquality) | Указывает уровень качества для использования во время компоновки. |
| [DashCap](./dashcap) | Указывает тип графической фигуры, используемой на обоих концах каждого тире в пунктирной линии. |
| [DashStyle](./dashstyle) | Задает стиль пунктирных линий, нарисованных с помощью объекта[`Pen`](../aspose.imaging/pen). |
| [DataRecoveryMode](./datarecoverymode) | Режим восстановления данных. |
| [DitheringMethod](./ditheringmethod) | Метод дизеринга. |
| [DitheringMethods](./ditheringmethods) | Методы дизеринга, используемые для управления преобразованием цвета. |
| [FileFormat](./fileformat) | Один из поддерживаемых форматов файлов изображений. |
| [FillMode](./fillmode) | Указывает, как заполняется внутренняя часть замкнутого контура. |
| [FontStyle](./fontstyle) | Указывает информацию о стиле, применяемую к тексту. |
| [GraphicsUnit](./graphicsunit) | Указывает единицу измерения данных. |
| [HatchStyle](./hatchstyle) | Определяет различные шаблоны, доступные для[`HatchBrush`](../aspose.imaging.brushes/hatchbrush)объектов. |
| [HotkeyPrefix](./hotkeyprefix) | Указывает тип отображения префиксов горячих клавиш, относящихся к тексту. |
| [ImageFilterType](./imagefiltertype) | Используемые фильтры изображений |
| [InterpolationMode](./interpolationmode) | Перечисление[`InterpolationMode`](../aspose.imaging/interpolationmode)указывает алгоритм, который используется при масштабировании или повороте изображений. |
| [KnownColor](./knowncolor) | Задает известные системные цвета. |
| [LineCap](./linecap) | Указывает доступные стили заглавных букв, которыми объект[`Pen`](../aspose.imaging/pen)может заканчивать строку. |
| [LineJoin](./linejoin) | Указывает, как соединить последовательные сегменты линии или кривой в фигуре (подпути), содержащейся в объекте[`GraphicsPath`](../aspose.imaging/graphicspath). |
| [MatrixOrder](./matrixorder) | Указывает порядок операций преобразования матрицы. |
| [PaletteMiningMethod](./paletteminingmethod) | Метод анализа палитры изображений |
| [PdfComplianceVersion](./pdfcomplianceversion) | Указывает уровень соответствия PDF для выходного файла. |
| [PenAlignment](./penalignment) | Задает выравнивание объекта[`Pen`](../aspose.imaging/pen)относительно теоретической линии нулевой ширины. |
| [PenType](./pentype) | Определяет тип заливки, которую объект[`Pen`](../aspose.imaging/pen)использует для заполнения линий. |
| [PixelFormat](./pixelformat) | Фактическое значение формата данных пикселей. |
| [ResizeType](./resizetype) | Указывает тип изменения размера. |
| [ResolutionUnit](./resolutionunit) | Единица разрешения enum. |
| [RotateFlipType](./rotatefliptype) | Определяет степень поворота изображения и ось, используемую для отражения изображения. |
| [SeekOrigin](./seekorigin) | Предоставляет поля, представляющие контрольные точки в[`StreamContainer`](../aspose.imaging/streamcontainer)для поиска. |
| [SmoothingMode](./smoothingmode) | Указывает, применяется ли сглаживание (сглаживание) к линиям, кривым и краям заполненных областей. |
| [StringAlignment](./stringalignment) | Задает выравнивание текстовой строки относительно ее прямоугольника макета. |
| [StringDigitSubstitute](./stringdigitsubstitute) | Перечисление указывает, как заменять цифры в строке в соответствии с локалью или языком пользователя. |
| [StringFormatFlags](./stringformatflags) | Задает информацию об отображении и макете для текстовых строк. |
| [StringTrimming](./stringtrimming) | Указывает, как обрезать символы из строки, которая не полностью соответствует форме макета. |
| [TextRenderingHint](./textrenderinghint) | Указывает качество рендеринга текста. |
| [WarpMode](./warpmode) | Указывает тип применяемого преобразования деформации. |
| [WrapMode](./wrapmode) | Указывает, как текстура или градиент укладываются мозаикой, когда они меньше, чем заполняемая область. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
