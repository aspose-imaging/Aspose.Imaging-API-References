---
title: "aspose.imaging"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging/
---


Модуль является ядром вложенных модулей и самым базовым объектом, используемым для обработки Aspose.Imaging.

## **Classes**
| **Class** | **Description** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Определяет шаблон смешивания. Этот класс не может быть наследован. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Базовый класс кисти. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Содержит информацию о текущей версии сборки. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Содержит настройки кэша. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK‑цвет пикселя. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Вспомогательные методы для работы с CMYK‑цветом, представленным как знаковое 32‑битное целое значение.<br/>            Предоставляет аналогичный API структуре [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/).<br/>            Он более лёгкий, потому что CMYK‑цвет представлен просто как Int32, а не как структура с внутренними полями.<br/>            По возможности предпочтительно использовать статические методы этого класса вместо устаревшей<br/>            структуры [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвет пикселя. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Определяет массивы цветов и позиций, используемые для интерполяции смешивания цветов в многокрасочном градиенте. Этот класс не может быть наследован. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Определяет карту для преобразования цветов. Несколько методов класса [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) корректируют цвета изображения, используя таблицу переопределения цветов, которая представляет собой массив структур [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Не наследуемый. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Определяет матрицу 5 x 5, содержащую координаты пространства RGBA. Несколько методов класса [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) корректируют цвета изображения, используя цветовую матрицу. Этот класс не может быть наследован. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Определяет массив цветов, составляющих цветовую палитру. Цвета представлены в виде 32‑битных ARGB цветов. Не наследуемый. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Вспомогательный класс для манипуляций с цветовыми палитрами. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Преобразует цвета в структуры GDI+ Color и из них. Этот класс не может быть наследован. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Инкапсулирует пользовательскую определяемую line cap. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | Контейнер потока данных. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Представляет объект, подлежащий освобождению. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | Встроенный класс изображения |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | Фигура. Контейнер для форм. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Вспомогательный класс для обработки файловых потоков. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Определяет конкретный формат текста, включая семейство шрифта, размер и атрибуты стиля. Этот класс не может быть наследован. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | Общие настройки шрифтов рендерера векторных форматов изображений. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Представляет графику в соответствии с графическим движком, используемым в текущей сборке. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Представляет серию соединённых линий и кривых. Этот класс не может быть наследован. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | Продвинутый процессор буфера. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | Кадр анимации |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | Процессор буфера. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | Конвертер цветов. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Интерфейс цветовой палитры. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Интерфейс метаданных изображения. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Создатель изображения. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Дескриптор создателя изображения, определяющий свойства создателя. Дескриптор создателя используется для преодоления<br/>            необходимости содержать каждый экземпляр создателя изображения в памяти и проблем многопоточности. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | Дескриптор изображения. Содержит базовые свойства и методы для всех остальных типов дескрипторов изображений. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Экспортер изображений. Может экспортировать данные из внутреннего формата `aspose.imaging` в указанный формат данных. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Представляет дескриптор экспортера изображений. Дескриптор экспортера используется для устранения необходимости содержать каждый экземпляр экспортера<br/>            в памяти и проблем многопоточности. |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Загрузчик изображений. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Дескриптор загрузчика изображений, определяющий свойства загрузчика. Дескриптор загрузчика используется для устранения<br/>            необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | Конвертер цветов для индексированных форматов изображений. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Интерфейс контейнера метаданных изображения. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | Интерфейс многостраничного изображения |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | Расширенный интерфейс многостраничного изображения |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Представляет объект с границами. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Представляет упорядоченную форму. Упорядоченная форма — это непрерывный набор точек, имеющих начальную и конечную точку.<br/>            Непрерывный набор точек, соединённых по определённому правилу. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Соответствует 32-битным ARGB‑пикселям, загруженным частично. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Загрузчик 64‑битных ARGB‑пикселей. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Соответствует пикселям, загруженным частично. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Загрузчик частичных данных. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | Загрузчик 32‑битных ARGB‑пикселей растрового изображения. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | Загрузчик 64‑битных ARGB‑пикселей растрового изображения. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | Загрузчик пикселей растрового изображения. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | Загрузчик необработанных данных растрового изображения. |
| [Image](/imaging/python-net/aspose.imaging/image/) | Изображение является базовым классом для всех типов изображений. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) объект содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга. [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) объект поддерживает несколько настроек коррекции цвета, включая матрицы коррекции цвета, матрицы коррекции в градациях серого, значения гамма‑коррекции, таблицы сопоставления цветов и пороговые значения цвета. Во время рендеринга цвета могут быть скорректированы, затемнены, осветлены и удалены. Чтобы применить такие изменения, инициализируйте [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) объект и передайте путь к этому [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) объекту (а также путь к [Image](/imaging/python-net/aspose.imaging/image/)) в метод DrawImage. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Представляет реестр создателей изображений. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Представляет реестр экспортёров изображений. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Представляет реестр загрузчиков изображений. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Базовые параметры изображения. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Класс настроек изменения размера изображения |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Класс для представления последовательности элементов |
| [License](/imaging/python-net/aspose.imaging/license/) | Предоставляет методы лицензирования компонента. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Представляет параметры загрузки. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Заменяет матрицу GDI+. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Предоставляет измеряемые методы для интеграции |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Представляет необобщённый словарь. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Необобщённый список объектов |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | Объект, имеющий границы. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Кеш для OpenType шрифтов, установленных в системе. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Определяет объект, используемый для рисования линий, кривых и фигур. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Формат данных пикселей. Это неизменяемый объект. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Представляет упорядоченную пару координат x и y с плавающей запятой, определяющих точку в двумерной плоскости. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Представляет растровое изображение, поддерживающее операции растровой графики. Это изображение кеширует данные пикселей при необходимости. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | Растровое многостраничное изображение |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Представляет растровое изображение, поддерживающее операции растровой графики. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Настройки необработанных данных |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Сохраняет набор из четырёх целых чисел, представляющих положение и размер прямоугольника. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Сохраняет набор из четырёх чисел с плавающей запятой, представляющих положение и размер прямоугольника. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей. Этот класс не может быть унаследован. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Настройки удаления фона |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | Настройка разрешения для параметров сохранения изображения. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | Форма. Непрерывный набор точек, соединённых по определённому правилу. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Представляет сегмент формы. Сегмент — это линия или кривая, соединяющая две точки. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Представляет размер. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Хранит упорядоченную пару чисел с плавающей запятой, обычно ширину и высоту прямоугольника. |
| [Source](/imaging/python-net/aspose.imaging/source/) | Источник используется для хранения всей соответствующей информации для объектного конвейера. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Представляет контейнер разделённого потока, который содержит поток и предоставляет процедуры обработки потока. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Представляет контейнер потока, который содержит поток и предоставляет процедуры обработки потока. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Инкапсулирует информацию о размещении текста (например, выравнивание, ориентацию и табуляцию), манипуляции отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть наследован. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | Объект, поддерживающий прозрачность. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | Векторное изображение является базовым классом для всех типов векторных изображений. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | Векторное многостраничное изображение |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Указывает, как графика должна обрабатываться после отображения. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Указывает тип кэша, который следует использовать. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Представляет используемый набор символов. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Указывает, какие объекты используют информацию о коррекции цвета. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Указывает отдельные каналы в цветовом пространстве CMYK (циан, мажента, желтый, чёрный). Это перечисление используется методами SetOutputChannel. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Метод сравнения цветов для приведения к ближайшему соседу |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Указывает типы изображений и цветов, которые будут затронуты настройками коррекции цвета и градаций серого объекта [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Методы квантования цветов |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Указывает уровень качества, используемый при композитинге. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Указывает тип графической формы, используемой на обоих концах каждого тире в пунктирной линии. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Указывает стиль пунктирных линий, рисуемых объектом [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | Режим восстановления данных. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Метод дизеринга. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | Методы дизеринга, используемые для управления преобразованием цветов. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Один из поддерживаемых форматов файлов изображений. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Указывает, как заполняется внутренняя часть замкнутого контура. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Указывает информацию о стиле, применяемую к тексту. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Указывает единицу измерения для заданных данных. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Указывает различные шаблоны, доступные для объектов [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/). |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Указывает тип отображения префиксов горячих клавиш, относящихся к тексту. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Фильтры изображений для использования |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | Перечисление [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) указывает алгоритм, используемый при масштабировании или вращении изображений. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Указывает известные системные цвета. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Указывает доступные стили окончаний, с помощью которых объект [Pen](/imaging/python-net/aspose.imaging/pen/) может завершать линию. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Указывает, как соединять последовательные отрезки линий или кривых в фигуре (подпути), содержащейся в объекте [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Указывает порядок операций преобразования матрицы. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Метод извлечения палитры изображения |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Указывает уровень соответствия PDF для выходного файла. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Указывает выравнивание объекта [Pen](/imaging/python-net/aspose.imaging/pen/) относительно теоретической линии нулевой ширины. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Указывает тип заливки, который объект [Pen](/imaging/python-net/aspose.imaging/pen/) использует для заполнения линий. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | Фактическое значение формата данных пикселей. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | Тип обработки. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Указывает тип изменения размера. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Перечисление единиц разрешения. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Указывает, насколько изображение вращается и ось, используемую для его отражения. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Предоставляет поля, представляющие контрольные точки в [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) для перемещения. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Указывает, применяется ли сглаживание (антиалиасинг) к линиям и кривым и к краям заполненных областей. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Указывает выравнивание текстовой строки относительно её прямоугольника размещения. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | Перечисление указывает, как заменять цифры в строке в соответствии с локалью или языком пользователя. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Указывает информацию об отображении и размещении текстовых строк. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Указывает, как обрезать символы в строке, которая не полностью помещается в форму размещения. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Указывает качество отображения текста. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Указывает тип применяемого искажения трансформации. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Указывает, как текстура или градиент заполняются плиткой, когда они меньше области заполнения. |
