---
title: "DicomOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Digital Imaging and Communications in Medicine DICOM rasterbildformatsskapande är ett specialiserat verktyg anpassat för medicintekniska tillämpningar."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.imageoptions/dicomoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DicomOptions extends ImageOptionsBase
```

API:n för Digital Imaging and Communications in Medicine (DICOM) rasterbildformatsskapande är ett specialiserat verktyg anpassat för medicintekniska tillämpningar. Det möjliggör sömlös generering av DICOM-bilder, avgörande för lagring av medicinska data och innehåller viktig identifieringsinformation. Med funktioner för att ställa in kompression, definiera färgtyper och bädda in XMP-metadata kan utvecklare säkerställa efterlevnad och flexibilitet i hanteringen av DICOM-bilder för medicinsk bildbehandling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DicomOptions()](#DicomOptions--) | Initierar en ny instans av klassen [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions). |
| [DicomOptions(DicomOptions options)](#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompression()](#getCompression--) | Hämtar komprimeringen. |
| [setCompression(Compression value)](#setCompression-com.aspose.imaging.fileformats.dicom.Compression-) | Anger komprimeringen. |
| [getColorType()](#getColorType--) | Hämtar färgens typ. |
| [setColorType(int value)](#setColorType-int-) | Ställer in färgens typ. |

## Example: The following example shows export to DICOM file format (single and multipage).

``` java
String fileName = "sample.jpg";
String inputFileNameSingle = fileName;
String inputFileNameMultipage = "multipage.tif";
String outputFileNameSingleDcm = "output.dcm";
String outputFileNameMultipageDcm = "outputMultipage.dcm";

// Nästa kodexempel konverterar JPEG-bild till DICOM-filformat.
try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileNameSingle))
{
    image.save(outputFileNameSingleDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}

// DICOM-formatet stöder flersidiga bilder. Du kan konvertera GIF- eller TIFF-bilder till DICOM på samma sätt som JPEG-bilder.
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
        // Rita något med vektorgrafik.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Spara pixlarna i den ritade bilden. De finns nu på den första sidan av DICOM-bilden.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Lägg till några sidor efter, vilket gör dem mörkare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Lägg till några sidor framför huvudsidan, vilket gör dem ljusare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Spara den skapade flersidiga bilden till utdatafilen.
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


Initierar en ny instans av klassen [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions).

### DicomOptions(DicomOptions options) {#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-}
```
public DicomOptions(DicomOptions options)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) |  |

### getCompression() {#getCompression--}
```
public final Compression getCompression()
```


Hämtar komprimeringen.

Värde: Kompressionen.

**Returns:**
[Compression](../../com.aspose.imaging.fileformats.dicom/compression) - the compression.
### setCompression(Compression value) {#setCompression-com.aspose.imaging.fileformats.dicom.Compression-}
```
public final void setCompression(Compression value)
```


Anger komprimeringen.

Värde: Kompressionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Compression](../../com.aspose.imaging.fileformats.dicom/compression) | kompressionen. |

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Hämtar färgens typ.

Värde: Färgens typ.

**Returns:**
int – färgens typ.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Ställer in färgens typ.

Värde: Färgens typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | färgens typ. |


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

