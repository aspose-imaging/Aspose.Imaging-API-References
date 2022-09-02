---
title: TiffOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры формата файла tiff. Обратите внимание что теги ширины и высоты будут перезаписаны при создании изображения параметрами ширины и высоты поэтому нет необходимости указывать их напрямую. Обратите внимание что многие параметры возвращают значение по умолчанию но это не означает что этот параметр задается явно как значение тега. Чтобы проверить наличие тега используйте свойство Tags или соответствующий метод IsTagPresent.
type: docs
weight: 10220
url: /ru/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

Параметры формата файла tiff. Обратите внимание, что теги ширины и высоты будут перезаписаны при создании изображения параметрами ширины и высоты, поэтому нет необходимости указывать их напрямую. Обратите внимание, что многие параметры возвращают значение по умолчанию, но это не означает, что этот параметр задается явно как значение тега. Чтобы проверить наличие тега, используйте свойство Tags или соответствующий метод IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Инициализирует новый экземпляр[`TiffOptions`](../tiffoptions) класс. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Инициализирует новый экземпляр[`TiffOptions`](../tiffoptions)учебный класс. По умолчанию используется соглашение с прямым порядком байтов. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Инициализирует новый экземпляр[`TiffOptions`](../tiffoptions) класс. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Инициализирует новый экземпляр[`TiffOptions`](../tiffoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Получает или задает параметр хранения альфа-канала. Варианты кромеUnspecified используются, когда их более 3[`SamplesPerPixel`](./samplesperpixel) определено. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Получает или устанавливает исполнителя. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Получает количество бит на пиксель. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Получает или устанавливает биты на выборку. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Получает или задает значение, указывающее порядок байтов tiff. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Получает или задает цветовую карту. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Получает или задает качество сжатого изображения. Используется со сжатием JPEG. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Получает или задает сжатие. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Получает или устанавливает авторские права. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Получает или задает дату и время. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Получает или задает значение, указывающее, отключен ли экспорт профиля ICC (профиль ICC заранее применяется к исходным пикселям). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Получает или задает имя документа. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Получает или устанавливает указатель на EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Получает значения дополнительных выборок. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Получает или задает параметры факса t4. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Получает или задает стандарт файла TIFF. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Получает или задает порядок заполнения байтовых битов. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Получает или задает полутоновые подсказки. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Получает или задает поток профиля Icc. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Получает или задает описание изображения. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Получает или задает длину изображения. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Получает или задает ширину изображения. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Получает или задает имена чернил. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Получает значение, указывающее, присутствуют ли дополнительные выборки. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Получает значение, указывающее, является ли изображение мозаичным. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Получает значение, указывающее,[`TiffOptions`](../tiffoptions) были правильно настроены. Используйте метод проверки, чтобы найти причину сбоя. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Получает или задает максимальное значение выборки. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Получает или задает минимальное значение выборки. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Получает или задает ориентацию. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Получает или задает имя страницы. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Получает или задает тег номера страницы. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Получает или задает цветовую палитру. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Получает или задает фотометрический параметр. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Получает или задает плоскую конфигурацию. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Получает или задает предиктор для сжатия LZW. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты предварительно умножаться. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Получает или задает единицу измерения разрешения. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Получает или задает количество строк на полосу. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Получает или задает образец формата. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Получает выборки на пиксель. Чтобы изменить значение этого свойства, используйте[`BitsPerSample`](./bitspersample) установщик свойств. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Получает или задает производителя сканера. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Получает или задает модель сканера. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Получает или задает максимальное значение выборки. Значение имеет тип поля, который лучше всего соответствует образцу данных (тип Byte, Short или Long). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Получает или задает минимальное значение выборки. Значение имеет тип поля, который лучше всего соответствует образцу данных (тип Byte, Short или Long). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Получает или задает тип программного обеспечения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Получает или задает счетчик байтов полосы. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Получает или задает смещения полосы. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Получает или задает общее указание типа данных, содержащихся в этом подфайле. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Получает или устанавливает теги. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Получает или задает целевой принтер. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Получает или задает пороговое значение. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Получает или задает количество байтов тайла. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Получает или устанавливает длину тайла. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Получает или задает смещения плитки. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Получает или устанавливает ширину плитки. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Получает общее количество страниц. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Получает количество действительных тегов. Это не общее количество тегов, а количество тегов, которые могут быть сохранены. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Получает или задает автора изображения, используемого проводником Windows. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Получает или задает комментарий к изображению, который используется проводником Windows. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Получает или задает изображение темы, используемое проводником Windows. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Получает или задает позицию x. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Получает или задает информацию об изображении, используемом проводником Windows. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Получает или задает информацию об изображении, используемом проводником Windows. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Получает или задает разрешение x. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Получает или задает YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Получает или задает коэффициенты субдискретизации для фотометрического YCbCr. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Получает или задает позицию Y. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Получает или задает разрешение по оси y. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Добавляет новый тег. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Добавляет теги. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Получает экземпляр тега по типу. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Определяет, присутствует ли тег в опциях или нет. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Удаляет тег. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Проверяет, имеют ли параметры допустимую комбинацию тегов |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Получает количество допустимых тегов. |

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

В следующем примере показано, как преобразовать многостраничное векторное изображение в формат TIFF в общем виде без ссылки на конкретный тип изображения.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Экспортировать только первые две страницы. Эти страницы будут представлены в виде кадров в выходном файле TIFF.
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

В этих примерах используются GraphicsPath и класс Graphics для создания и управления рисунками на поверхности изображения. Пример создает новое изображение (типа Tiff), очищает поверхность и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отображения путей на поверхности.

```csharp
[C#]

//Создаем экземпляр FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Создаем экземпляр TiffOptions и устанавливаем его различные свойства
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Устанавливаем источник для экземпляра ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Создаем экземпляр изображения 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Создаем и инициализируем экземпляр класса Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Очистить графическую поверхность
        graphics.Clear(Color.Wheat);

        //Создаем экземпляр класса GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Создаем экземпляр класса Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // Добавляем фигуры к объекту Figure
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Добавить объект Figure в GraphicsPath
        graphicspath.AddFigure(figure);

        // Нарисовать путь с помощью объекта Pen черного цвета
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // сохранить все изменения.
        image.Save();
    }
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
