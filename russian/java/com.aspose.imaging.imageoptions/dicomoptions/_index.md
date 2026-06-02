---
title: "DicomOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для создания растрового формата изображений Digital Imaging and Communications in Medicine (DICOM) является специализированным инструментом, адаптированным для медицинских устройств."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.imageoptions/dicomoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DicomOptions extends ImageOptionsBase
```

The API для создания растрового формата изображений Digital Imaging and Communications in Medicine (DICOM) — это специализированный инструмент, адаптированный для приложений медицинских устройств. Он обеспечивает беспрепятственное создание DICOM‑изображений, что критически важно для хранения медицинских данных и содержащей важную идентификационную информацию. С возможностями установки сжатия, определения типов цветов и встраивания метаданных XMP разработчики могут гарантировать соответствие требованиям и гибкость при работе с DICOM‑изображениями для медицинской визуализации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DicomOptions()](#DicomOptions--) | Инициализирует новый экземпляр класса [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions). |
| [DicomOptions(DicomOptions options)](#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompression()](#getCompression--) | Получает тип сжатия. |
| [setCompression(Compression value)](#setCompression-com.aspose.imaging.fileformats.dicom.Compression-) | Задает тип сжатия. |
| [getColorType()](#getColorType--) | Получает тип цвета. |
| [setColorType(int value)](#setColorType-int-) | Устанавливает тип цвета. |

## Example: The following example shows export to DICOM file format (single and multipage).

``` java
String fileName = "sample.jpg";
String inputFileNameSingle = fileName;
String inputFileNameMultipage = "multipage.tif";
String outputFileNameSingleDcm = "output.dcm";
String outputFileNameMultipageDcm = "outputMultipage.dcm";

// Следующий пример кода преобразует изображение JPEG в формат файла DICOM.
try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileNameSingle))
{
    image.save(outputFileNameSingleDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}

// Формат DICOM поддерживает многостраничные изображения. Вы можете конвертировать изображения GIF или TIFF в DICOM так же, как изображения JPEG.
try(com.aspose.imaging.Image imageMultiple = com.aspose.imaging.Image.load(inputFileNameMultipage))
{
    imageMultiple.save(outputFileNameMultipageDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Нарисуйте что‑нибудь с помощью векторной графики.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Сохраните пиксели нарисованного изображения. Они теперь находятся на первой странице изображения Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Добавьте несколько страниц после, сделав их темнее.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Добавьте несколько страниц перед основной страницей, сделав их ярче.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Сохраните созданное многостраничное изображение в выходной файл.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomOptions() {#DicomOptions--}
```
public DicomOptions()
```


Инициализирует новый экземпляр класса [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions).

### DicomOptions(DicomOptions options) {#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-}
```
public DicomOptions(DicomOptions options)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) |  |

### getCompression() {#getCompression--}
```
public final Compression getCompression()
```


Получает тип сжатия.

Значение: Сжатие.

**Returns:**
[Compression](../../com.aspose.imaging.fileformats.dicom/compression) - the compression.
### setCompression(Compression value) {#setCompression-com.aspose.imaging.fileformats.dicom.Compression-}
```
public final void setCompression(Compression value)
```


Задает тип сжатия.

Значение: Сжатие.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Compression](../../com.aspose.imaging.fileformats.dicom/compression) | сжатие. |

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Получает тип цвета.

Значение: тип цвета.

**Returns:**
int — тип цвета.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Устанавливает тип цвета.

Значение: тип цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | тип цвета. |


**Example: Use JPEG compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


**Example: Use JPEG 2000 compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


**Example: Use RLE compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


**Example: Change Color Type in DICOM compression.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

