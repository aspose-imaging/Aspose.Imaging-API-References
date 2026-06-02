---
title: "JpegImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera JPEG‑rasterbilder effektivt med vårt API som erbjuder stöd för olika färgprofiler såsom RGB och CMYK, anpassningsbara bitar per pixel‑upplösning samt bearbetning av EXIF-, JFIF- och XMP‑metadata‑behållare."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Manipulera JPEG‑rasterbilder effektivt med vårt API, som erbjuder stöd för olika färgprofiler såsom RGB och CMYK, anpassningsbara bitar per pixel‑upplösning och bearbetning av EXIF-, JFIF- och XMP‑metadata‑behållare. Njut av automatisk rotation baserad på orienteringsdata och välj bland olika komprimeringsnivåer, inklusive förlustfri JPEG, för att uppnå optimal bildkvalitet och en balanserad filstorlek för dina projekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | Klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) initieras enkelt genom att anropa dess konstruktor med den angivna sökvägsparametern. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Initiera ett JPEG‑bildobjekt med klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) med en ström‑parameter. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Initiera en ny instans av klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) med en raster‑bildparameter. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Skapa en ny instans av klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) med de angivna bredd‑ och höjdparametrarna. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Initiera ett nytt [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-objekt med de angivna JPEG‑alternativen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta bildens format enkelt med den här egenskapen. |
| [getJpegOptions()](#getJpegOptions--) | Få åtkomst till JPEG-alternativen som används under skapandet eller inläsningen av detta [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-objekt med lätthet. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta bildens pixeldjup enkelt med den här egenskapen, vilket ger insikt i färgens eller gråskalaens rikedom. |
| [getComment()](#getComment--) | Hantera JPEG-filkommentarer med den här egenskapen, så att du kan lägga till eller hämta beskrivande annoteringar som är kopplade till bilden. |
| [setComment(String value)](#setComment-java.lang.String-) | Hantera JPEG-filkommentarer med den här egenskapen, så att du kan lägga till eller hämta beskrivande annoteringar som är kopplade till bilden. |
| [getJpegExifData()](#getJpegExifData--) | Hämtar Exif-instans. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Hantera EXIF-data med den här egenskapen, så att du kan lägga till eller hämta metadata som är kopplade till bilden. |
| [getExifData()](#getExifData--) | Hämtar Exif-data; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Ställer in Exif-data; |
| [getHeight()](#getHeight--) | Hämta bildens höjd enkelt med denna egenskap. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Denna egenskap ger dig åtkomst till den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Denna egenskap ger dig åtkomst till den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum. |
| [getJfif()](#getJfif--) | Denna egenskap låter dig komma åt eller ändra JFIF‑data (JPEG File Interchange Format) som är kopplade till JPEG‑bilden. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Denna egenskap låter dig komma åt eller ändra JFIF‑data (JPEG File Interchange Format) som är kopplade till JPEG‑bilden. |
| [getRawDataFormat()](#getRawDataFormat--) | Denna egenskap hämtar bildens rådataformat, vilket visar hur bilddata är strukturerad och kodad. |
| [getVerticalResolution()](#getVerticalResolution--) | Denna egenskap hanterar den vertikala upplösningen, uttryckt i pixlar per tum, för den associerade [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Denna egenskap hanterar den vertikala upplösningen, uttryckt i pixlar per tum, för den associerade [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getWidth()](#getWidth--) | Denna egenskap hämtar bildens bredd, uttryckt i pixlar. |
| [getRgbColorProfile()](#getRgbColorProfile--) | RGB-färgprofilen för CMYK‑ och YCCK‑JPEG‑bilder säkerställer korrekt färgkonvertering och återgivning. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | RGB-färgprofilen för CMYK‑ och YCCK‑JPEG‑bilder säkerställer korrekt färgkonvertering och återgivning. |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK-färgprofilen som är associerad med CMYK‑ och YCCK‑JPEG‑bilder säkerställer exakt färgkonvertering och trohet. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK-färgprofilen som är associerad med CMYK‑ och YCCK‑JPEG‑bilder säkerställer exakt färgkonvertering och trohet. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | RGBColorProfile är avgörande för korrekt färgkonvertering av CMYK‑ och YCCK‑JPEG‑bilder under sparningsprocessen. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | RGBColorProfile är avgörande för korrekt färgkonvertering av CMYK‑ och YCCK‑JPEG‑bilder under sparningsprocessen. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | CMYK-färgprofilen är viktig för korrekt färgkonvertering av CMYK‑ och YCCK‑JPEG‑bilder under sparningsprocessen. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK-färgprofilen är viktig för korrekt färgkonvertering av CMYK‑ och YCCK‑JPEG‑bilder under sparningsprocessen. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Hämtar eller ändrar flaggan som anger om den inbäddade färgprofilen ignoreras. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Hämtar eller ändrar flaggan som anger om den inbäddade färgprofilen ignoreras. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar de ursprungliga bildalternativen för detta [Image](../../com.aspose.imaging/image)-objekt. |
| [removeMetadata()](#removeMetadata--) | Tar bort metadata för detta bildobjekt genom att sätta `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) och `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) till `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Fastställer upplösningen för den angivna [RasterImage](../../com.aspose.imaging/rasterimage), vilket säkerställer exakt skalning och utskriftsmöjligheter. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Läs in en JPEG-bild från en fil.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Utför någon bildbehandling.
    // Spara till en annan JPEG-fil.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


Klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) initierar enkelt genom att anropa dess konstruktor med den angivna sökvägsparametern. Denna konstruktor möjliggör sömlös skapning av JPEG‑bilder, vilket säkerställer snabb integration i dina projekt med lätthet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att läsa in bilden från och initiera pixel- och palettdata med. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Initiera ett JPEG‑bildobjekt med klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) genom att använda en strömparameter. Denna konstruktor förenklar processen att arbeta med JPEG‑bilder och erbjuder ett enkelt sätt att integrera dem i dina projekt utan ansträngning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa in bilden från och initiera pixel- och palettdata med. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Initiera en ny instans av klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) med en rasterbildparameter. Denna konstruktor ger ett bekvämt sätt att skapa JPEG‑bilder direkt från rasterbilder, vilket effektiviserar arbetsflödet för att arbeta med JPEG‑bilder i dina applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska initieras med pixel- och palettdata. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Skapa en ny instans av klassen [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) med de angivna bredd‑ och höjdpunktsparametrarna. Denna konstruktor låter dig skapa JPEG‑bilder med anpassade dimensioner, vilket ger dig flexibilitet att hantera bildstorlekar i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Initiera ett nytt [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-objekt med de angivna JPEG‑alternativen. Denna konstruktor ger dig möjlighet att anpassa olika inställningar för JPEG‑bilden, såsom komprimeringsnivå, kvalitet och ytterligare parametrar, vilket ger exakt kontroll över det resulterande bildformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | JPEG‑alternativen. |
| bredd | int | Bildbredd. |
| höjd | int | Bildhöjd. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta bildens format enkelt med denna egenskap. Den ger värdefull insikt i filformatet och underlättar sömlös integration samt kompatibilitetskontroller över olika plattformar och applikationer.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Få enkel åtkomst till JPEG‑alternativen som användes vid skapandet eller inläsningen av denna [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-instans. Denna egenskap ger värdefulla detaljer om de specifika inställningarna som användes, vilket ger användarna möjlighet att förstå och reproducera bildbehandlingsarbetsflöden effektivt. Oavsett om det gäller komprimeringsnivåer, kvalitetsinställningar eller andra parametrar, ger denna egenskap väsentliga insikter för sömlös bildmanipulation.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//Utdata ser ut så här:
//Antalet bitar per kanal: 8
//Maximalt tillåten storlek för alla interna buffertar: 0
//Färgtyp: YCbCr
//Komprimeringstyp: Baseline
//Bildkvalitet: 75
//Sampling för komponent 0: 1x1
//Sampling för komponent 1: 1x1
//Sampling för komponent 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta bildens pixeldjup enkelt med denna egenskap, vilket ger insikt i färg- eller gråskalegenskapernas rikedom. Oavsett om det är ett levande fotografi eller en monokrom illustration, ger denna egenskap viktig information om bildens visuella komplexitet.

**Returns:**
int - Bildens bitar per pixel-antal.
### getComment() {#getComment--}
```
public String getComment()
```


Hantera JPEG‑filkommentarer med denna egenskap, så att du kan lägga till eller hämta beskrivande annoteringar som är kopplade till bilden. Oavsett om du märker bilder med metadata eller lägger till ytterligare kontext, ger denna egenskap flexibilitet att organisera och kategorisera dina JPEG‑filer.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Hantera JPEG‑filkommentarer med denna egenskap, så att du kan lägga till eller hämta beskrivande annoteringar som är kopplade till bilden. Oavsett om du märker bilder med metadata eller lägger till ytterligare kontext, ger denna egenskap flexibilitet att organisera och kategorisera dina JPEG‑filer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Hämtar Exif-instans.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Hantera EXIF‑data med denna egenskap, så att du kan lägga till eller hämta metadata som är kopplade till bilden. Oavsett om du extraherar information om kamerainställningarna eller modifierar befintlig metadata, ger denna egenskap flexibilitet att hantera EXIF‑databehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Hämtar Exif-data;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//Utdata ser ut så här:
//Den allmänna EXIF‑datan
//------------------------------------------
//EXIF‑versionen: [B@163e4e87
//Kamerans serienummer: 7100536
//Färgrymd: SRgb
//Ljusstyrka:
//Kontrast: Normal
//Gamma:
//Skärpan: 0
//Bländaren: 4.64(4643856 / 1000000)
//Exponeringsläge: Manuell
//Exponeringsförskjutning: 0.67(4 / 6)
//Exponeringstid: 0.01(1 / 160)
//Brännvidd: 145.00(1450 / 10)
//Enhet för brännplanets upplösning: Cm
//Objektivmodell: 70.0 - 200.0 mm f/ 4.0
//Slutartid: 7.32(7321928 / 1000000)
//JPEG EXIF-data
//------------------------------------------
//Kameratillverkare: NIKON CORPORATION
//Kameramodell: NIKON D5
//Fotometrisk tolkning: 0
//Artist:
//Upphovsrätt:
//Bildbeskrivning:
//Orientering: TopLeft
//Programvara: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Ställer in Exif-data;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif-data; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämta bildens höjd enkelt med denna egenskap. Den ger snabb åtkomst till bildens vertikala dimension, vilket gör att du effektivt kan bestämma dess storlek och bildförhållande utan behov av komplexa beräkningar eller ytterligare metoder.

**Returns:**
int - Bildhöjden i pixlar.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Denna egenskap ger dig åtkomst till den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum. Genom att sätta eller hämta detta värde kan du exakt kontrollera bildens upplösning och säkerställa att den uppfyller dina specifika krav på kvalitet och klarhet.

**Returns:**
double - Den horisontella upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Hämta horisontell och vertikal upplösning för BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 300.0
// Den vertikala upplösningen, i pixlar per tum: 300.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 96.0
// Den vertikala upplösningen, i pixlar per tum: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Denna egenskap ger dig åtkomst till den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum. Genom att sätta eller hämta detta värde kan du exakt kontrollera bildens upplösning och säkerställa att den uppfyller dina specifika krav på kvalitet och klarhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den horisontella upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden `setResolution` för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Denna egenskap låter dig komma åt eller ändra JFIF (JPEG File Interchange Format)-data som är associerade med JPEG-bilden. JFIF är ett standardformat för utbyte av JPEG-komprimerade bilder mellan datorer och andra enheter. Genom att hämta eller sätta denna egenskap kan du interagera med JFIF-data, som kan innehålla information såsom bildens upplösning, bildförhållande och miniatyrbild.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Denna egenskap låter dig komma åt eller ändra JFIF (JPEG File Interchange Format)-data som är associerade med JPEG-bilden. JFIF är ett standardformat för utbyte av JPEG-komprimerade bilder mellan datorer och andra enheter. Genom att hämta eller sätta denna egenskap kan du interagera med JFIF-data, som kan innehålla information såsom bildens upplösning, bildförhållande och miniatyrbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Denna egenskap hämtar bildens rådataformat, vilket visar hur bilddata är strukturerad och kodad. Att förstå det råa dataformatet är avgörande för att bearbeta eller manipulera bilddata effektivt. Det ger insikt i bildens underliggande representation, såsom om den är komprimerad, kodad i ett specifikt färgrymd eller lagrad i ett visst filformat. Genom att komma åt denna egenskap får du värdefull information om bildens datastruktur, vilket möjliggör att utföra olika operationer eller optimeringar anpassade till dess specifika format.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Denna egenskap hanterar den vertikala upplösningen, uttryckt i pixlar per tum, för den associerade [RasterImage](../../com.aspose.imaging/rasterimage). Att justera denna upplösning påverkar bildens storlek och kvalitet när den skrivs ut eller visas i en fast fysisk storlek. Genom att sätta denna egenskap styr du hur tätt bildens pixlar är packade vertikalt, vilket påverkar dess övergripande skärpa och klarhet.

**Returns:**
double - Den vertikala upplösningen.

Observera att detta värde som standard alltid är 72 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden SetResolution för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Hämta horisontell och vertikal upplösning för BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 300.0
// Den vertikala upplösningen, i pixlar per tum: 300.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 96.0
// Den vertikala upplösningen, i pixlar per tum: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Denna egenskap hanterar den vertikala upplösningen, uttryckt i pixlar per tum, för den associerade [RasterImage](../../com.aspose.imaging/rasterimage). Att justera denna upplösning påverkar bildens storlek och kvalitet när den skrivs ut eller visas i en fast fysisk storlek. Genom att sätta denna egenskap styr du hur tätt bildens pixlar är packade vertikalt, vilket påverkar dess övergripande skärpa och klarhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den vertikala upplösningen. |

Observera att detta värde som standard alltid är 72 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden SetResolution för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Denna egenskap hämtar bildens bredd, uttryckt i pixlar. Den ger viktig information om bildens dimensioner, vilket möjliggör exakt rendering, manipulation eller visning av bilddata.

**Returns:**
int - Bildbredden i pixlar.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


RGB-färgprofilen för CMYK- och YCCK-JPEG-bilder säkerställer exakt färgkonvertering och representation. Den måste paras ihop med CMYKColorProfile för att upprätthålla konsistens och trohet i färgrenderingen. Detta par är nödvändigt för applikationer som kräver exakt färghantering och återgivning av bilder, och säkerställer att RGB-data tolkas och visas korrekt.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


RGB-färgprofilen för CMYK- och YCCK-JPEG-bilder säkerställer exakt färgkonvertering och representation. Den måste paras ihop med CMYKColorProfile för att upprätthålla konsistens och trohet i färgrenderingen. Detta par är nödvändigt för applikationer som kräver exakt färghantering och återgivning av bilder, och säkerställer att RGB-data tolkas och visas korrekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Följande exempel läser in PNG och sparar det som CMYK-JPEG med en anpassad ICC-profil. Därefter läses CMYK-JPEG in och sparas tillbaka som PNG. Färgkonverteringen från RGB till CMYK och från CMYK till RGB utförs med hjälp av anpassade ICC-profiler.
``` java
String dir = "c:\\temp\\";

// Läs in PNG och spara det som CMYK-JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Använd anpassade ICC-profiler
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Läs in CMYK-JPEG och spara det som PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Använd anpassade ICC-profiler
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


CMYK-färgprofilen som är associerad med CMYK- och YCCK-JPEG-bilder säkerställer exakt färgkonvertering och trohet. Den fungerar tillsammans med RGBColorProfile för att garantera korrekt färgrepresentation över olika enheter och applikationer. Detta par är avgörande för att upprätthålla konsistens i färgrenderingen och uppnå optimal bildkvalitet.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK-färgprofilen som är associerad med CMYK- och YCCK-JPEG-bilder säkerställer exakt färgkonvertering och trohet. Den fungerar tillsammans med RGBColorProfile för att garantera korrekt färgrepresentation över olika enheter och applikationer. Detta par är avgörande för att upprätthålla konsistens i färgrenderingen och uppnå optimal bildkvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Följande exempel läser in PNG och sparar det som CMYK-JPEG med en anpassad ICC-profil. Därefter läses CMYK-JPEG in och sparas tillbaka som PNG. Färgkonverteringen från RGB till CMYK och från CMYK till RGB utförs med hjälp av anpassade ICC-profiler.
``` java
String dir = "c:\\temp\\";

// Läs in PNG och spara det som CMYK-JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Använd anpassade ICC-profiler
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Läs in CMYK-JPEG och spara det som PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Använd anpassade ICC-profiler
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


RGBColorProfile är avgörande för exakt färgkonvertering av CMYK- och YCCK-JPEG-bilder under sparprocessen. När den paras ihop med CMYKColorProfile säkerställer den att färgerna återges korrekt och upprätthåller konsistens över olika enheter och applikationer. Denna kombination är viktig för att bevara den avsedda färgrepresentationen och uppnå högkvalitativ bildutdata.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


RGBColorProfile är avgörande för exakt färgkonvertering av CMYK- och YCCK-JPEG-bilder under sparprocessen. När den paras ihop med CMYKColorProfile säkerställer den att färgerna återges korrekt och upprätthåller konsistens över olika enheter och applikationer. Denna kombination är viktig för att bevara den avsedda färgrepresentationen och uppnå högkvalitativ bildutdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


CMYK-färgprofilen är viktig för exakt färgkonvertering av CMYK- och YCCK-JPEG-bilder under sparprocessen. Den arbetar i tandem med RGBColorProfile för att säkerställa korrekt färgrepresentation, upprätthålla konsistens och kvalitet över olika enheter och programvara. Denna synkronisering är avgörande för att uppnå exakt och pålitlig färgrendering i de slutligt sparade bilderna.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


CMYK-färgprofilen är viktig för exakt färgkonvertering av CMYK- och YCCK-JPEG-bilder under sparprocessen. Den arbetar i tandem med RGBColorProfile för att säkerställa korrekt färgrepresentation, upprätthålla konsistens och kvalitet över olika enheter och programvara. Denna synkronisering är avgörande för att uppnå exakt och pålitlig färgrendering i de slutligt sparade bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Hämtar eller ändrar flaggan som anger om den inbäddade färgprofilen ignoreras. Genom att sätta denna flagga kan användare ange om standardfärgprofilen ska användas i stället för den inbäddade. Detta alternativ ger större kontroll över färghantering och underlättar justeringar för konsistens och kompatibilitet över olika plattformar och applikationer.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Hämtar eller ändrar flaggan som anger om den inbäddade färgprofilen ignoreras. Genom att sätta denna flagga kan användare ange om standardfärgprofilen ska användas i stället för den inbäddade. Detta alternativ ger större kontroll över färghantering och underlättar justeringar för konsistens och kompatibilitet över olika plattformar och applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar de ursprungliga bildalternativen för detta [Image](../../com.aspose.imaging/image)-objekt.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Tar bort metadata för detta bildobjekt genom att sätta `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) och `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) till `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Fastställer upplösningen för den angivna [RasterImage](../../com.aspose.imaging/rasterimage), vilket säkerställer exakt skalning och utskriftsmöjligheter. Denna metod ger användare möjlighet att anpassa bildens upplösning efter deras specifika krav, oavsett om det gäller digital visning eller fysisk reproduktion. Genom att sätta upplösningen kan användare optimera bildkvaliteten och säkerställa kompatibilitet med olika utskriftsenheter och medier, vilket förbättrar den övergripande visuella upplevelsen och användbarheten av bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för `RasterImage`. |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Hämta horisontell och vertikal upplösning för BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 300.0
// Den vertikala upplösningen, i pixlar per tum: 300.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 96.0
// Den vertikala upplösningen, i pixlar per tum: 96.0
```

