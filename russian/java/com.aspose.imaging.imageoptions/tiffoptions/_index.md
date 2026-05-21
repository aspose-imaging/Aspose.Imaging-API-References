---
title: "TiffOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры формата TIFF."
type: docs
weight: 48
url: /ru/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Параметры формата файла TIFF. Обратите внимание, что теги ширины и высоты будут перезаписаны при создании изображения параметрами width и height, поэтому нет необходимости указывать их напрямую. Учтите, что многие параметры возвращают значение по умолчанию, но это не означает, что параметр установлен явно как значение тега. Чтобы проверить наличие тега, используйте свойство Tags или соответствующий метод IsTagPresent.

` ПРЕДУПРЕЖДЕНИЕ! никогда не изменяйте параметры tiff при сохранении, так как это может вызвать побочные эффекты и трудно обнаруживаемые ошибки. Следующая строка была специально оставлена закомментированной, поскольку она приводила к неправильному определению начала данных. Переданные параметры не содержали spp (хотя параметры в таком случае некорректны, но всё равно эта ситуация вызывает ошибки) и следующая строка добавляла теги +spp и +bpp, и когда параметры записывались после полностью записанных данных, они перезаписывали начало данных для несжатого кодека!!! См. TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Инициализирует новый экземпляр класса `TiffOptions`. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Инициализирует новый экземпляр класса `TiffOptions`. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Инициализирует новый экземпляр класса `TiffOptions`. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса `TiffOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Получает количество допустимых тегов. |
| [getTagCount()](#getTagCount--) | Получает количество тегов. |
| [getFileStandard()](#getFileStandard--) | Получает или задает стандарт TIFF‑файла. |
| [setFileStandard(int value)](#setFileStandard-int-) | Получает или задает стандарт TIFF‑файла. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Получает или задает предельный размер выделения памяти по умолчанию. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Получает или задает предельный размер выделения памяти по умолчанию. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| [isValid()](#isValid--) | Получает значение, указывающее, правильно ли настроены `TiffOptions`. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Получает или задает YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает YCbCrCoefficients. |
| [isTiled()](#isTiled--) | Получает значение, указывающее, разбита ли изображение на плитки. |
| [getArtist()](#getArtist--) | Получает или задает исполнителя. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Получает или задает исполнителя. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Определяет, присутствует ли тег в параметрах или нет. |
| [getByteOrder()](#getByteOrder--) | Получает или задает значение, указывающее порядок байтов TIFF. |
| [setByteOrder(int value)](#setByteOrder-int-) | Получает или задает значение, указывающее порядок байтов TIFF. |
| [getIccProfile()](#getIccProfile--) | Получает поток профиля icc. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Задает поток профиля icc. |
| [isDisableIccExport()](#isDisableIccExport--) | Получает значение, указывающее, отключён ли экспорт профиля ICC (профиль ICC применяется к исходным пикселям заранее). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Задает значение, указывающее, отключён ли экспорт профиля ICC (профиль ICC применяется к исходным пикселям заранее). |
| [getBitsPerSample()](#getBitsPerSample--) | Получает количество бит на образец. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Задает количество бит на образец. |
| [getExtraSamples()](#getExtraSamples--) | Получает значения дополнительных образцов. |
| [getCompression()](#getCompression--) | Получает тип сжатия. |
| [setCompression(int value)](#setCompression-int-) | Задает тип сжатия. |
| [getCompressedQuality()](#getCompressedQuality--) | Получает качество сжатого изображения. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Задает качество сжатого изображения. |
| [getCopyright()](#getCopyright--) | Получает информацию об авторском праве. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Задает информацию об авторском праве. |
| [getColorMap()](#getColorMap--) | Получает или задает карту цветов. |
| [setColorMap(int[] value)](#setColorMap-int---) | Получает или задает карту цветов. |
| [getPalette()](#getPalette--) | Получает или задает палитру цветов. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Получает или задает палитру цветов. |
| [getDateTime()](#getDateTime--) | Получает или задает дату и время. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Получает или задает дату и время. |
| [getDocumentName()](#getDocumentName--) | Получает или задает имя документа. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Получает или задает имя документа. |
| [getAlphaStorage()](#getAlphaStorage--) | Получает или задает параметр хранения альфа-канала. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Получает или задает параметр хранения альфа-канала. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Получает значение, указывающее, присутствуют ли дополнительные образцы. |
| [getFillOrder()](#getFillOrder--) | Получает или задает порядок заполнения битов байта. |
| [setFillOrder(int value)](#setFillOrder-int-) | Получает или задает порядок заполнения битов байта. |
| [getHalfToneHints()](#getHalfToneHints--) | Получает или задает подсказки полутонов. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Получает или задает подсказки полутонов. |
| [getImageDescription()](#getImageDescription--) | Получает или задает описание изображения. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Получает или задает описание изображения. |
| [getInkNames()](#getInkNames--) | Получает или задает названия чернил. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Получает или задает названия чернил. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Получает или задает производителя сканера. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Получает или задает производителя сканера. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Получает или задает максимальное значение образца. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Получает или задает максимальное значение образца. |
| [getMinSampleValue()](#getMinSampleValue--) | Получает или задает минимальное значение образца. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Получает или задает минимальное значение образца. |
| [getScannerModel()](#getScannerModel--) | Получает или задает модель сканера. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Получает или задает модель сканера. |
| [getOrientation()](#getOrientation--) | Получает или задает ориентацию. |
| [setOrientation(int value)](#setOrientation-int-) | Получает или задает ориентацию. |
| [getPageName()](#getPageName--) | Получает или задает имя страницы. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Получает или задает имя страницы. |
| [getPageNumber()](#getPageNumber--) | Получает или задает тег номера страницы. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Получает или задает тег номера страницы. |
| [getPhotometric()](#getPhotometric--) | Получает или задает фотометрический параметр. |
| [setPhotometric(int value)](#setPhotometric-int-) | Получает или задает фотометрический параметр. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Получает или задает планарную конфигурацию. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Получает или задает планарную конфигурацию. |
| [getResolutionUnit()](#getResolutionUnit--) | Получает или задает единицу разрешения. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Получает или задает единицу разрешения. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Получает или задает количество строк в полосе. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Получает или задает количество строк в полосе. |
| [getTileWidth()](#getTileWidth--) | Получает или задает ширину плитки. |
| [setTileWidth(long value)](#setTileWidth-long-) | Получает или задает ширину плитки. |
| [getTileLength()](#getTileLength--) | Получает или задает длину плитки. |
| [setTileLength(long value)](#setTileLength-long-) | Получает или задает длину плитки. |
| [getSampleFormat()](#getSampleFormat--) | Получает или задает формат образца. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Получает или задает формат образца. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Получает количество образцов на пиксель. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Получает или задает максимальное значение образца. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Получает или задает максимальное значение образца. |
| [getSminSampleValue()](#getSminSampleValue--) | Получает или задает минимальное значение образца. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Получает или задает минимальное значение образца. |
| [getSoftwareType()](#getSoftwareType--) | Получает или задает тип программного обеспечения. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Получает или задает тип программного обеспечения. |
| [getStripByteCounts()](#getStripByteCounts--) | Получает или задает количество байтов в полосе. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Получает или задает количество байтов в полосе. |
| [getStripOffsets()](#getStripOffsets--) | Получает или задает смещения полосы. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Получает или задает смещения полосы. |
| [getTileByteCounts()](#getTileByteCounts--) | Получает или задает количество байтов плитки. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Получает или задает количество байтов плитки. |
| [getTileOffsets()](#getTileOffsets--) | Получает или задает смещения плитки. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Получает или задает смещения плитки. |
| [getSubFileType()](#getSubFileType--) | Получает или задает общее указание типа данных, содержащихся в этом подфайле. |
| [setSubFileType(long value)](#setSubFileType-long-) | Получает или задает общее указание типа данных, содержащихся в этом подфайле. |
| [getTargetPrinter()](#getTargetPrinter--) | Получает или задает целевой принтер. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Получает или задает целевой принтер. |
| [getThreshholding()](#getThreshholding--) | Получает или задает пороговое значение. |
| [setThreshholding(int value)](#setThreshholding-int-) | Получает или задает пороговое значение. |
| [getTotalPages()](#getTotalPages--) | Получает общее количество страниц. |
| [getXposition()](#getXposition--) | Получает или задает позицию по оси X. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает позицию по оси X. |
| [getResolutionSettings()](#getResolutionSettings--) | Получает или задает настройки разрешения. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Получает или задает настройки разрешения. |
| [getXresolution()](#getXresolution--) | Получает или задает разрешение по оси X. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси X. |
| [getYposition()](#getYposition--) | Получает или задает позицию по оси Y. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает позицию по оси Y. |
| [getYresolution()](#getYresolution--) | Получает или задает разрешение по оси Y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси Y. |
| [getFaxT4Options()](#getFaxT4Options--) | Получает или задает параметры факса T4. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Получает или задает параметры факса T4. |
| [getPredictor()](#getPredictor--) | Получает или задает предсказатель для сжатия LZW. |
| [setPredictor(int value)](#setPredictor-int-) | Получает или задает предсказатель для сжатия LZW. |
| [getImageLength()](#getImageLength--) | Получает или задает длину изображения. |
| [setImageLength(long value)](#setImageLength-long-) | Получает или задает длину изображения. |
| [getImageWidth()](#getImageWidth--) | Получает или задает ширину изображения. |
| [setImageWidth(long value)](#setImageWidth-long-) | Получает или задает ширину изображения. |
| [getExifIfd()](#getExifIfd--) | Получает или задает указатель на EXIF IFD. |
| [getTags()](#getTags--) | Получает или задает теги. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Получает или задает теги. |
| [getValidTagCount()](#getValidTagCount--) | Получает количество действительных тегов. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель. |
| [getXPTitle()](#getXPTitle--) | Получает информацию об изображении, используемую в Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Устанавливает информацию об изображении, используемую в Windows Explorer. |
| [getXPComment()](#getXPComment--) | Получает комментарий к изображению, используемый в Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Устанавливает комментарий к изображению, используемый в Windows Explorer. |
| [getXPAuthor()](#getXPAuthor--) | Получает автора изображения, используемого в Windows Explorer. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Устанавливает автора изображения, используемого в Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Получает тему изображения, используемую в Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Устанавливает изображение объекта, которое используется Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Получает информацию об изображении, используемую в Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Устанавливает информацию об изображении, используемую в Windows Explorer. |
| [getExifData()](#getExifData--) | Получает данные Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Устанавливает данные Exif. |
| [removeTag(int tag)](#removeTag-int-) | Удаляет тег. |
| [removeTags(int[] tags)](#removeTags-int...-) | Удаляет теги. |
| [validate()](#validate--) | Проверяет, имеет ли параметры допустимую комбинацию тегов |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Добавляет теги. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Добавляет новый тег. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Получает экземпляр тега по типу. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
В этом примере демонстрируется использование различных классов из пространства имен SaveOptions для экспорта. Изображение типа Gif загружается в экземпляр класса Image, а затем экспортируется в несколько форматов.
``` java
String dir = "c:\\temp\\";

//Загрузите существующее изображение (типа Gif) в экземпляр класса Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Экспорт в формат BMP с использованием параметров по умолчанию.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Экспорт в формат JPEG с использованием параметров по умолчанию.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Экспорт в формат PNG с использованием параметров по умолчанию.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Экспорт в формат TIFF с использованием параметров по умолчанию.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. Эти страницы будут представлены как кадры в результирующем TIFF.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Инициализирует новый экземпляр класса `TiffOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | int | Ожидаемый формат файла TIFF. |
| byteOrder | int | Порядок байтов формата файла TIFF. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Инициализирует новый экземпляр класса `TiffOptions`. По умолчанию используется порядок little endian.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | int | Ожидаемый формат файла TIFF. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Инициализирует новый экземпляр класса `TiffOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Параметры, из которых копировать. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Инициализирует новый экземпляр класса `TiffOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги, с помощью которых инициализировать параметры. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Получает количество допустимых тегов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги для проверки. |

**Returns:**
int — количество допустимых тегов.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Получает количество тегов.

**Returns:**
int — количество тегов.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Получает или задает стандарт TIFF‑файла.

**Returns:**
int — стандарт файла TIFF.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Получает или задает стандарт TIFF‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Стандарт файла TIFF. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Получает или задает предельный размер выделения памяти по умолчанию.

**Returns:**
int — предел выделения памяти по умолчанию.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Получает или задает предельный размер выделения памяти по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Предел выделения памяти по умолчанию. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены.

**Returns:**
boolean — `true`, если компоненты должны быть премультиплицированы; иначе `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если компоненты должны быть премультиплицированы; иначе `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Получает значение, указывающее, правильно ли настроен `TiffOptions`. Используйте метод Validate, чтобы найти причину ошибки.

**Returns:**
boolean — `true`, если TiffOptions правильно настроен; иначе `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Получает или задает коэффициенты субдискретизации для фотометрии YCbCr.

**Returns:**
int[] — коэффициенты субдискретизации для фотометрии YCbCr.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Получает или задает коэффициенты субдискретизации для фотометрии YCbCr.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Коэффициенты субдискретизации для фотометрии YCbCr. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Установите 8 бит для каждого цветового компонента.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Установите порядок байтов Big Endian (Motorola).
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Установите сжатие LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Позволяет уменьшить размер изображений с непрерывным тоном.
// В настоящее время это поле используется только с кодированием LZW, поскольку LZW, вероятно, единственная схема кодирования TIFF.
// который значительно выигрывает от шага предсказателя.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Установите цветовую модель RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Для YCbCr вы можете использовать один из следующих вариантов:
// Поле YCbCrSubSampling   Факторы выборки JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Все цветовые компоненты будут храниться в единой плоскости.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Создайте TIFF‑кадр размером 100×100 пикселей.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Получает или задает YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Коэффициенты YCbCr.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Получает или задает YCbCrCoefficients.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Коэффициенты YCbCr. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Получает значение, указывающее, разбита ли изображение на плитки.

**Returns:**
boolean - `true`, если изображение разбито на плитки; иначе `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Получает или задает исполнителя.

**Returns:**
java.lang.String - Автор.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Получает или задает исполнителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Исполнитель. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Определяет, присутствует ли тег в параметрах или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тег | int | Идентификатор тега для проверки. |

**Returns:**
boolean - `true`, если тег присутствует; иначе `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Получает или задает значение, указывающее порядок байтов TIFF.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Получает или задает значение, указывающее порядок байтов TIFF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Установите 8 бит для каждого цветового компонента.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Установите порядок байтов Big Endian (Motorola).
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Установите сжатие LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Позволяет уменьшить размер изображений с непрерывным тоном.
// В настоящее время это поле используется только с кодированием LZW, поскольку LZW, вероятно, единственная схема кодирования TIFF.
// который значительно выигрывает от шага предсказателя.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Установите цветовую модель RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Для YCbCr вы можете использовать один из следующих вариантов:
// Поле YCbCrSubSampling   Факторы выборки JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Все цветовые компоненты будут храниться в единой плоскости.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Создайте TIFF‑кадр размером 100×100 пикселей.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Получает поток профиля icc.

**Returns:**
byte[] - ICC‑профиль.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Задает поток профиля icc.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] | ICC‑профиль. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Получает значение, указывающее, отключён ли экспорт профиля ICC (профиль ICC применяется к исходным пикселям заранее).

**Returns:**
boolean - значение, указывающее, отключён ли экспорт ICC‑профиля (ICC‑профиль применяется к исходным пикселям заранее).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Задает значение, указывающее, отключён ли экспорт профиля ICC (профиль ICC применяется к исходным пикселям заранее).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, отключён ли экспорт ICC‑профиля (ICC‑профиль применяется к исходным пикселям заранее). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Получает количество бит на образец.

**Returns:**
int[] - Значение бит на образец.

При установке этого значения имейте в виду, что оно также задаст значение SamplesPerPixel равным длине массива. Эти два свойства тесно связаны, поэтому их можно задавать только вместе.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Задает количество бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int[] | Значение бит на образец. |

При установке этого значения имейте в виду, что оно также задаст значение SamplesPerPixel равным длине массива. Эти два свойства тесно связаны, поэтому их можно задавать только вместе. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Создать постоянный, а не временный источник файла.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Заполнить активный кадр кистью линейного градиента.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Параметры градаций серого
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Создать копию активного кадра в градациях серого.
    // Данные пикселей сохраняются, но конвертируются в требуемый формат.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Добавить вновь созданный кадр в TIFF‑изображение.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


Получает значения дополнительных образцов.

Значение: значение дополнительных образцов.

**Returns:**
int[] - значения дополнительных образцов.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Получает тип сжатия.

**Returns:**
int - Сжатие.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Задает тип сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Сжатие. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Параметры первого кадра
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Установите 8 бит для каждого цветового компонента.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Установите порядок байтов Big Endian (Motorola).
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Установите сжатие LZW.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Установите цветовую модель RGB.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Все цветовые компоненты будут храниться в единой плоскости.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Создайте первый кадр TIFF размером 100×100 пикселей.
// Обратите внимание, что вам не нужно явно освобождать кадры, если они включены в TiffImage.
// При освобождении контейнера все кадры будут освобождены автоматически.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Заполните первый кадр градиентом от синего к желтому.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Параметры первого кадра
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Установите 1 бит на пиксель для чёрно‑белого изображения.
createOptions2.setBitsPerSample(new int[]{1});

// Установите порядок байтов Little Endian (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Установите сжатие CCITT Group 3 Fax.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Установите чёрно‑белую цветовую модель, где 0 — чёрный, 1 — белый.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Создайте второй кадр TIFF размером 200×200 пикселей.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Заполните второй кадр градиентом от синего к желтому.
// Он будет автоматически преобразован в чёрно‑белый формат из‑за соответствующих настроек кадра.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Создайте TIFF‑изображение.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Получает качество сжатого изображения. Используется с сжатием Jpeg.

**Returns:**
int — качество сжатого изображения.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Устанавливает качество сжатого изображения. Используется с сжатием Jpeg.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | качество сжатого изображения. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Установите цветовую модель RGB.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Установите сжатие Jpeg.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Установите 8 бит для каждого цветового компонента.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Получает информацию об авторском праве.

**Returns:**
java.lang.String - Авторские права.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Задает информацию об авторском праве.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Авторские права. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Получает или задает карту цветов.

**Returns:**
int[] - Цветовая карта.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Получает или задает карту цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Цветовая карта. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает или задает палитру цветов.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Получает или задает палитру цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Получает или задает дату и время.

**Returns:**
java.lang.String - Дата и время.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Получает или задает дату и время.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Дата и время. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Получает или задает имя документа.

**Returns:**
java.lang.String - Имя документа.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Получает или задает имя документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя документа. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Получает или задает параметр хранения альфа-канала. Параметры, отличные от `TiffAlphaStorage.Unspecified`, используются, когда определено более 3 `SamplesPerPixel`

**Returns:**
int - Параметр хранения альфа.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Получает или задает параметр хранения альфа-канала. Параметры, отличные от `TiffAlphaStorage.Unspecified`, используются, когда определено более 3 `SamplesPerPixel`

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Параметр хранения альфа. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Получает значение, указывающее, присутствуют ли дополнительные образцы.

**Returns:**
boolean - `true`, если присутствуют дополнительные образцы; иначе `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Получает или задает порядок заполнения битов байта.

**Returns:**
int - Порядок заполнения битов байта.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Получает или задает порядок заполнения битов байта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Порядок заполнения битов байта. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Получает или задает подсказки полутонов.

**Returns:**
int[] - Подсказки полутонов.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Получает или задает подсказки полутонов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Подсказки полутонов. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Получает или задает описание изображения.

**Returns:**
java.lang.String - Описание изображения.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Получает или задает описание изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Описание изображения. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Получает или задает названия чернил.

**Returns:**
java.lang.String - Имена чернил.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Получает или задает названия чернил.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имена чернил. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Получает или задает производителя сканера.

**Returns:**
java.lang.String - Производитель сканера.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Получает или задает производителя сканера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Производитель сканера. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Получает или задает максимальное значение образца.

**Returns:**
int[] - Максимальное значение образца.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Получает или задает максимальное значение образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Максимальное значение образца. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Получает или задает минимальное значение образца.

**Returns:**
int[] - Минимальное значение образца.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Получает или задает минимальное значение образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Минимальное значение образца. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Получает или задает модель сканера.

**Returns:**
java.lang.String - Модель сканера.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Получает или задает модель сканера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Модель сканера. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Получает или задает ориентацию.

**Returns:**
int - Ориентация [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Получает или задает ориентацию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Ориентация [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Получает или задает имя страницы.

**Returns:**
java.lang.String - Имя страницы.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Получает или задает имя страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя страницы. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Получает или задает тег номера страницы.

**Returns:**
int[] - Тег номера страницы.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Получает или задает тег номера страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Тег номера страницы. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Получает или задает фотометрический параметр.

**Returns:**
int - Фотометрия.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Получает или задает фотометрический параметр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Фотометрия. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Создать постоянный, а не временный источник файла.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Заполнить активный кадр кистью линейного градиента.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Параметры градаций серого
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Создать копию активного кадра в градациях серого.
    // Данные пикселей сохраняются, но конвертируются в требуемый формат.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Добавить вновь созданный кадр в TIFF‑изображение.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Получает или задает планарную конфигурацию.

**Returns:**
int - Планарная конфигурация.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Получает или задает планарную конфигурацию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Планарная конфигурация. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Установите 8 бит для каждого цветового компонента.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Установите порядок байтов Big Endian (Motorola).
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Установите сжатие LZW.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Установите цветовую модель RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Все цветовые компоненты будут храниться в единой плоскости.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Создайте TIFF‑кадр размером 100×100 пикселей.
// Обратите внимание, что вам не нужно явно освобождать кадр, если он включён в TiffImage.
// При освобождении контейнера все кадры будут освобождены автоматически.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Заполните весь кадр градиентом от синего к жёлтому.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Создайте TIFF‑изображение.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Получает или задает единицу разрешения.

**Returns:**
int - Единица разрешения.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Получает или задает единицу разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Единица разрешения. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Получает или задает количество строк в полосе.

**Returns:**
long - Строки на полосу.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Получает или задает количество строк в полосе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Строки на полосу. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Получает или задает ширину плитки.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Получает или задает ширину плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Получает или задает длину плитки.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Получает или задает длину плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Получает или задает формат образца.

**Returns:**
int[] - Формат образца.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Получает или задает формат образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Формат образца. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Получает количество образцов на пиксель. Чтобы изменить значение этого свойства, используйте сеттер свойства `BitsPerSample`.

**Returns:**
int - Образцов на пиксель.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Returns:**
long[] - Максимальное значение образца.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] | Максимальное значение образца. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Returns:**
long[] - Минимальное значение образца.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] | Минимальное значение образца. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Получает или задает тип программного обеспечения.

**Returns:**
java.lang.String - Тип программного обеспечения.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Получает или задает тип программного обеспечения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Тип программного обеспечения. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Получает или задает количество байтов в полосе.

**Returns:**
long[] - Количество байтов в полосе.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Получает или задает количество байтов в полосе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] | Количество байтов в полосе. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Получает или задает смещения полосы.

**Returns:**
long[] - Смещения полос.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Получает или задает смещения полосы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] | Смещения полос. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Получает или задает количество байтов плитки.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Получает или задает количество байтов плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Получает или задает смещения плитки.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Получает или задает смещения плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Получает или задает общее указание типа данных, содержащихся в этом подфайле.

**Returns:**
long - Общее указание типа данных, содержащихся в этом подфайле.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Получает или задает общее указание типа данных, содержащихся в этом подфайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Общее указание типа данных, содержащихся в этом подфайле. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Получает или задает целевой принтер.

**Returns:**
java.lang.String - Целевой принтер.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Получает или задает целевой принтер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Целевой принтер. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Получает или задает пороговое значение.

**Returns:**
int - Пороговая обработка.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Получает или задает пороговое значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Пороговая обработка. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Получает общее количество страниц.

**Returns:**
int - Общее количество страниц.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Получает или задает позицию по оси X.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Получает или задает позицию по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Позиция по оси x. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Получает или задает настройки разрешения.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Получает или задает настройки разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Получает или задает разрешение по оси X.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Получает или задает разрешение по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Разрешение по оси x. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Получает или задает позицию по оси Y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Получает или задает позицию по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Позиция по оси y. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Получает или задает разрешение по оси Y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Получает или задает разрешение по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Разрешение по оси y. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Получает или задает параметры факса T4.

**Returns:**
long - Параметры факса t4.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Получает или задает параметры факса T4.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Параметры факса t4. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Получает или задает предсказатель для сжатия LZW.

**Returns:**
int - Тип предиктора.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Получает или задает предсказатель для сжатия LZW.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Тип предиктора. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Установите 8 бит для каждого цветового компонента.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Установите порядок байтов Big Endian (Motorola).
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Установите сжатие LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Позволяет уменьшить размер изображений с непрерывным тоном.
// В настоящее время это поле используется только с кодированием LZW, поскольку LZW, вероятно, единственная схема кодирования TIFF.
// который значительно выигрывает от шага предсказателя.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Установите цветовую модель RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Для YCbCr вы можете использовать один из следующих вариантов:
// Поле YCbCrSubSampling   Факторы выборки JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Все цветовые компоненты будут храниться в единой плоскости.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Создайте TIFF‑кадр размером 100×100 пикселей.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Получает или задает длину изображения.

**Returns:**
long - Длина изображения.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Получает или задает длину изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Длина изображения. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Получает или задает ширину изображения.

**Returns:**
long - Ширина изображения.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Получает или задает ширину изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Ширина изображения. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Получает или задает указатель на EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Получает или задает теги.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - Теги.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Получает или задает теги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Получает количество допустимых тегов. Это не общее количество тегов, а число тегов, которые могут быть сохранены.

**Returns:**
int - Количество допустимых тегов.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель.

**Returns:**
int - Количество бит на пиксель.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Получает информацию об изображении, используемую в Windows Explorer.

Значение: Информация об изображении, используемая в Windows Explorer. `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) игнорируется Windows Explorer, если тег `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) существует.

**Returns:**
java.lang.String - информация об изображении, используемая в Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Устанавливает информацию об изображении, используемую в Windows Explorer.

Значение: Информация об изображении, используемая в Windows Explorer. `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) игнорируется Windows Explorer, если тег `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) существует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | информация об изображении, используемая в Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Получает комментарий к изображению, используемый в Windows Explorer.

Значение: Комментарий к изображению, используемый в Windows Explorer.

**Returns:**
java.lang.String - комментарий к изображению, используемый в Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Устанавливает комментарий к изображению, используемый в Windows Explorer.

Значение: Комментарий к изображению, используемый в Windows Explorer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | комментарий к изображению, используемый в Windows Explorer. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Получает автора изображения, используемого в Windows Explorer.

Значение: Автор изображения, используется Windows Explorer. Тег `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) игнорируется Windows Explorer, если существует тег `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)).

**Returns:**
java.lang.String - автор изображения, используемый в Windows Explorer.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Устанавливает автора изображения, используемого в Windows Explorer.

Значение: Автор изображения, используется Windows Explorer. Тег `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) игнорируется Windows Explorer, если существует тег `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | автор изображения, используемый в Windows Explorer. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Получает тему изображения, используемую в Windows Explorer.

Значение: Тема изображения, используется Windows Explorer.

**Returns:**
java.lang.String - тема изображения, используемая в Windows Explorer.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Устанавливает изображение объекта, которое используется Windows Explorer.

Значение: Тема изображения, используется Windows Explorer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | тема изображения, используемая в Windows Explorer. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Получает информацию об изображении, используемую в Windows Explorer.

Значение: Информация об изображении, используется Windows Explorer.

**Returns:**
java.lang.String - информация об изображении, используемая в Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Устанавливает информацию об изображении, используемую в Windows Explorer.

Значение: Информация об изображении, используется Windows Explorer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | информация об изображении, используемая в Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Получает данные Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Устанавливает данные Exif.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Данные Exif. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Удаляет тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тег | int | Тег для удаления. |

**Returns:**
boolean - true, если успешно удалён
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Удаляет теги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| теги | int[] | Теги для удаления. |

**Returns:**
boolean - `` если размер коллекции тегов изменился.
### validate() {#validate--}
```
public void validate()
```


Проверяет, имеет ли параметры допустимую комбинацию тегов

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Добавляет теги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги для добавления. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Добавляет новый тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Тег для добавления. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Получает экземпляр тега по типу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagKey | int | Ключ тега. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
