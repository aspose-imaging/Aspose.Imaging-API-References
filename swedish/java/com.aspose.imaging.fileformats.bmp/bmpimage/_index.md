---
title: "BmpImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Du kan enkelt hantera Bitmap BMP- och Device Independent Bitmap DIB-filer, vilket underlättar effektiv manipulation och bearbetning av rasterbilder."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Du kan enkelt hantera Bitmap (BMP)- och Device Independent Bitmap (DIB)-filer, vilket underlättar effektiv manipulation och bearbetning av rasterbilder. Genom att utföra olika operationer på bilder förenklar detta API arbetsflödet och erbjuder utvecklare ett pålitligt verktygssats för att arbeta med BMP- och DIB-format i sina programvaruapplikationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Börja använda BmpImage‑klassen enkelt med denna konstruktor som initierar en ny instans. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Skapa enkelt en ny instans av klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) med denna konstruktor, med angivna parametrar som sökväg, bitsPerPixel och komprimering. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Börja använda klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) enkelt genom att initiera en ny instans med denna konstruktor, med en ström som indata. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Börja arbeta med klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sömlöst genom att skapa en ny instans med en ström, samt angivna parametrar som bitsPerPixel och komprimering. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Skapa enkelt en ny instans av klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) genom att initiera den med ett RasterImage‑objekt. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Börja arbeta med klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sömlöst genom att skapa en ny instans med ett rasterImage samt angivna parametrar som bitsPerPixel och komprimering. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Börja använda klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) enkelt genom att skapa en ny instans med angivna bredd‑ och höjdp​arametrar. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Börja använda klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sömlöst genom att initiera en ny instans med parametrar som bredd, höjd, bitdjup och palett. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Skapa enkelt en ny instans av klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) med den här konstruktorn, och ange parametrar som bredd, höjd, bitsPerPixel och palett. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Få snabbt åtkomst till viktiga detaljer om din bitmap-bild med denna enkla funktion. |
| [getFileFormat()](#getFileFormat--) | Hämta enkelt filformatvärdet med den här användarvänliga egenskapen. |
| [getRawDataFormat()](#getRawDataFormat--) | Hämta enkelt formatet på dina rådata med denna användarvänliga funktion. |
| [getRawLineSize()](#getRawLineSize--) | Få snabbt åtkomst till storleken på varje rårad i byte med denna enkla egenskap. |
| [getCompression()](#getCompression--) | Hämta kompressionstypen som används för bilden enkelt med denna egenskap. |
| [getWidth()](#getWidth--) | Få enkelt åtkomst till bildens bredd med denna egenskap. |
| [getHeight()](#getHeight--) | Hämta bildens höjd enkelt med denna egenskap. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Få åtkomst till antalet bitar per pixel för bilden enkelt med denna egenskap. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Denna egenskap låter dig enkelt hämta eller ange den horisontella upplösningen, mätt i pixlar per tum, för objektet [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Denna egenskap låter dig enkelt hämta eller ange den horisontella upplösningen, mätt i pixlar per tum, för objektet [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getVerticalResolution()](#getVerticalResolution--) | Hämta eller ange den vertikala upplösningen enkelt, mätt i pixlar per tum, för detta [RasterImage](../../com.aspose.imaging/rasterimage)-objekt med denna egenskap. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Hämta eller ange den vertikala upplösningen enkelt, mätt i pixlar per tum, för detta [RasterImage](../../com.aspose.imaging/rasterimage)-objekt med denna egenskap. |
| [hasAlpha()](#hasAlpha--) | Hämtar ett värde som indikerar om detta objekt har alfa. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Justera upplösningen för din [RasterImage](../../com.aspose.imaging/rasterimage) enkelt med denna användarvänliga metod. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämta standardalternativen enkelt med denna enkla metod. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Skapa en BMP-bild 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fyll bilden med ett enkelt linjärt röd-svart gradient.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Läs in en PNG-bild från en fil.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP-bild sparas med transparensstöd som standard.
    // Om du vill ange sådant läge explicit, bör BmpOptions's Compression property sättas till BitmapCompression.Bitfields.
    // BitmapCompression.Bitfields-komprimeringsmetoden är standardkomprimeringsmetoden i BmpOptions.
    // Samma resultat av att exportera en Bmp-bild med transparens kan uppnås på någon av följande sätt.
    // Med implicita standardalternativ:
    pngImage.save(outputPathPng);
    // Med explicita standardalternativ:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specificera BitmapCompression.Bitfields-komprimeringsmetoden:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Läs in en PNG-bild från en fil.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP-bild sparas med transparensstöd som standard, vilket uppnås genom att använda BitmapCompression.Bitfields-komprimeringsmetoden.
    // För att spara en BMP-bild med Rgb-komprimeringsmetoden bör BmpOptions med Compression property satt till BitmapCompression.Rgb anges.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Börja använda BmpImage-klassen enkelt med den här konstruktorn som initierar en ny instans. Perfekt för utvecklare som vill komma igång med [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)-objekt snabbt och effektivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att läsa in bilden från och initiera pixel- och palettdata med. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Skapa enkelt en ny instans av klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) med den här konstruktorn, med angivna parametrar som sökväg, bitsPerPixel och kompression. Idealiskt för utvecklare som vill initiera BmpImage-objekt snabbt och effektivt, med exakt kontroll över bildens egenskaper.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att läsa in bilden från och initiera pixel- och palettdata med. |
| bitsPerPixel | int | Bitar per pixel. |
| kompression | long | Kompressionen att använda. |
| horizontalResolution | double | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |
| verticalResolution | double | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Börja använda klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) enkelt genom att initiera en ny instans med den här konstruktorn, med en ström som indata. Perfekt för utvecklare som söker ett bekvämt sätt att arbeta med BmpImage-objekt från olika datakällor, vilket säkerställer flexibilitet och enkel integration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa in bilden från och initiera pixel- och palettdata med. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Börja arbeta med klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sömlöst genom att skapa en ny instans med en ström, samt angivna parametrar som bitsPerPixel och kompression. Perfekt för utvecklare som söker ett enkelt sätt att hantera BmpImage-objekt, vilket säkerställer flexibilitet och effektivitet i deras projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa in bilden från och initiera pixel- och palettdata med. |
| bitsPerPixel | int | Bitar per pixel. |
| kompression | long | Kompressionen att använda. |
| horizontalResolution | double | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |
| verticalResolution | double | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Skapa enkelt en ny instans av klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) genom att initiera den med ett RasterImage-objekt. Perfekt för utvecklare som vill konvertera befintliga rasterbilder till BmpImage-formatet sömlöst, vilket säkerställer kompatibilitet och enkel integration i deras projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska initieras med pixel- och palettdata. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Börja arbeta med klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sömlöst genom att skapa en ny instans med ett rasterImage samt angivna parametrar som bitsPerPixel och kompression. Perfekt för utvecklare som söker ett enkelt sätt att hantera BmpImage-objekt, vilket säkerställer flexibilitet och effektivitet i deras projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska initieras med pixel- och palettdata. |
| bitsPerPixel | int | Bitar per pixel. |
| kompression | long | Kompressionen att använda. |
| horizontalResolution | double | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |
| verticalResolution | double | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Börja använda klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) enkelt genom att skapa en ny instans med angivna bredd- och höjdpärametrar. Idealiskt för utvecklare som söker ett bekvämt sätt att generera BmpImage-objekt med anpassade dimensioner, vilket säkerställer flexibilitet och enkel integration i deras projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Börja använda klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sömlöst genom att initiera en ny instans med parametrar såsom bredd, höjd, bitdjup och palett. Perfekt för utvecklare som söker ett enkelt sätt att skapa BmpImage‑objekt med anpassade dimensioner och färgkonfigurationer, vilket säkerställer flexibilitet och effektivitet i deras projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |
| bitsPerPixel | int | Bitar per pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Skapa enkelt en ny instans av klassen [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) med denna konstruktor, och ange parametrar som bredd, höjd, bitsPerPixel och palett. Perfekt för utvecklare som söker ett bekvämt sätt att generera BmpImage‑objekt med anpassade dimensioner och färgkonfigurationer, vilket säkerställer flexibilitet och enkel integration i deras projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |
| bitsPerPixel | int | Bitar per pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |
| kompression | long | Kompressionen att använda. |
| horizontalResolution | double | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |
| verticalResolution | double | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen avvika något från den angivna. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Få snabbt åtkomst till viktiga detaljer om din bitmap‑bild med denna enkla funktion. Perfekt för utvecklare som behöver hämta headerinformation för sina bilder.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Antalet palettfärger som krävs för att visa bitmapen: 0
//Antalet palettfärger som används i bitmapen: 0
//Bitmapkomprimeringen: 0
//Bitmapens höjd: 100
//Bitmapens bredd: 100
//Bitmapens rådatastorlek i byte: 40000
//Antalet plan: 1
//Den horisontella upplösningen för bitmapen, i pixlar per meter: 0
//Den vertikala upplösningen för bitmapen, i pixlar per meter: 0
//Antalet bitar per pixel: 32
//Extra bitmasker: null
//Headerstorleken i byte: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta enkelt filformatvärdet med denna användarvänliga egenskap. Idealisk för utvecklare som söker snabb åtkomst till information om filformatet.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// Hjälparklassen som används i huvudexemplet nedan.
class Utils {
    // Hjälpmetoden för att få en strängrepresentation av filformatet.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

// Skapa en 32-bpp BMP-bild på 100 × 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Skapa en 24-bpp BMP-bild på 100 × 100 px.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// I de flesta fall stöder inte BMP alfakanal, så resultatet kommer sannolikt att se ut så här:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, använda kanaler: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, använda kanaler: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Hämta enkelt formatet på dina rådata med denna användarvänliga funktion. Perfekt för utvecklare som vill snabbt få tillgång till viktig information om deras dataformat.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
//Rålinjestorleken i byte: 1500
//Bitmapkomprimeringen: 0
//Bitmapbredden: 500
//Bitmaphöjden: 500
//Antalet bitar per pixel: 24
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
//Ställ in upplösningsvärden till 96 dpi
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Få snabbt åtkomst till storleken på varje rå rad i byte med denna enkla egenskap. Perfekt för utvecklare som behöver hantera rå bilddata effektivt.

**Returns:**
int - Den råa radstorleken i byte.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
//Rålinjestorleken i byte: 1500
//Bitmapkomprimeringen: 0
//Bitmapbredden: 500
//Bitmaphöjden: 500
//Antalet bitar per pixel: 24
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
//Ställ in upplösningsvärden till 96 dpi
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Hämta kompressionstypen som används för bilden enkelt med denna egenskap. Perfekt för utvecklare som snabbt behöver åtkomst till information om bildkompression.

**Returns:**
long - Bildkompressionen [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// Hjälparklassen som används i huvudexemplet nedan.
class Utils {
    // Hjälpmetoden för att få en strängrepresentation av filformatet.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Skapa en monokrom palette som endast innehåller röda och gröna färger.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Skapa en 8-bpp BMP-bild på 100 x 100 px.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Fyll hela bilden med rött.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Spara bilden till en ström för att få den resulterande bildstorleken.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// Utdata kan se ut så här:
// Kompressionen=RGB
// Antalet bitar per pixel=8
// Bildens dimensioner=100 x 100
// Rå radstorlek=100
// Utdata storlek i byte=11078
// ---------------------------------------------
// Kompression=RLE8
// Antalet bitar per pixel=8
// Bildens dimensioner=100 x 100
// Rå radstorlek=100
// Utdata storlek i byte=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Få enkelt åtkomst till bildens bredd med denna egenskap. Perfekt för utvecklare som söker snabb information om bildens dimensioner.

**Returns:**
int - Bildbredden i pixlar.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
//Rålinjestorleken i byte: 1500
//Bitmapkomprimeringen: 0
//Bitmapbredden: 500
//Bitmaphöjden: 500
//Antalet bitar per pixel: 24
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
//Ställ in upplösningsvärden till 96 dpi
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämta bildens höjd enkelt med denna egenskap. Perfekt för utvecklare som snabbt behöver åtkomst till information om bildens dimensioner.

**Returns:**
int - Bildhöjden i pixlar.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
//Rålinjestorleken i byte: 1500
//Bitmapkomprimeringen: 0
//Bitmapbredden: 500
//Bitmaphöjden: 500
//Antalet bitar per pixel: 24
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
//Ställ in upplösningsvärden till 96 dpi
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Få enkelt åtkomst till antalet bitar per pixel för bilden med denna egenskap. Perfekt för utvecklare som söker snabb information om bildkvalitet och djup.

**Returns:**
int - Bildens bitar per pixel-antal.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
//Rålinjestorleken i byte: 1500
//Bitmapkomprimeringen: 0
//Bitmapbredden: 500
//Bitmaphöjden: 500
//Antalet bitar per pixel: 24
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
//Ställ in upplösningsvärden till 96 dpi
//Den horisontella upplösningen, i pixlar per tum: 96.012
//Den vertikala upplösningen, i pixlar per tum: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Denna egenskap gör det enkelt att hämta eller ange den horisontella upplösningen, mätt i pixlar per tum, för [RasterImage](../../com.aspose.imaging/rasterimage)-objektet. Perfekt för utvecklare som behöver exakt kontroll över bildens upplösning i sina applikationer.

**Returns:**
double - Den horisontella upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden \\#setResolution(double, double).setResolution(double, double) för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Hämta horisontell och vertikal upplösning för BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 0.0
// Den vertikala upplösningen, i pixlar per tum: 0.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 96.012
// Den vertikala upplösningen, i pixlar per tum: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Denna egenskap gör det enkelt att hämta eller ange den horisontella upplösningen, mätt i pixlar per tum, för [RasterImage](../../com.aspose.imaging/rasterimage)-objektet. Perfekt för utvecklare som behöver exakt kontroll över bildens upplösning i sina applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den horisontella upplösningen. |

--------------------

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden \\#setResolution(double, double).setResolution(double, double) för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämta eller ange enkelt den vertikala upplösningen, mätt i pixlar per tum, för detta [RasterImage](../../com.aspose.imaging/rasterimage)-objekt med denna egenskap. Perfekt för utvecklare som kräver exakt kontroll över bildens upplösning i sina applikationer.

**Returns:**
double - Den vertikala upplösningen.

--------------------

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden \\#setResolution(double, double).setResolution(double, double) för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Hämta horisontell och vertikal upplösning för BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 0.0
// Den vertikala upplösningen, i pixlar per tum: 0.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 96.012
// Den vertikala upplösningen, i pixlar per tum: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Hämta eller ange enkelt den vertikala upplösningen, mätt i pixlar per tum, för detta [RasterImage](../../com.aspose.imaging/rasterimage)-objekt med denna egenskap. Perfekt för utvecklare som kräver exakt kontroll över bildens upplösning i sina applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den vertikala upplösningen. |

--------------------

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda metoden \\#setResolution(double, double).setResolution(double, double) för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar ett värde som indikerar om detta objekt har alfa.

**Returns:**
boolean – ett värde som indikerar om detta objekt har alfa.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Justera upplösningen för din [RasterImage](../../com.aspose.imaging/rasterimage) enkelt med denna användarvänliga metod. Perfekt för utvecklare som söker exakt kontroll över bildens upplösning i sina applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Hämta horisontell och vertikal upplösning för BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 0.0
// Den vertikala upplösningen, i pixlar per tum: 0.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 96.012
// Den vertikala upplösningen, i pixlar per tum: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämta standardalternativen enkelt med denna raka metod. Perfekt för utvecklare som vill ha snabb åtkomst till standardinställningar eller konfigurationer för bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
