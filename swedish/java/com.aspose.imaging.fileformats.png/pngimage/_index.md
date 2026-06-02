---
title: "PngImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera Portable Network Graphics PNG rasterbilder med vårt mångsidiga API som erbjuder stöd för komprimeringsnivåer och olika färgdjup inklusive gråskala, indexerad färg, TrueColor och alfakanaler."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Manipulera Portable Network Graphics (PNG) rasterbilder med vårt mångsidiga API, med stöd för komprimeringsnivåer och olika färgdjup inklusive gråskala, indexerad färg, TrueColor och alfakanaler. Bearbeta sömlöst XMP-metadata, vilket möjliggör omfattande hantering av bildmetadata, samtidigt som du enkelt laddar PNG-bilder, utför olika manipulationer, applicerar filter och konverterar bilder till andra filformat för optimal mångsidighet och anpassning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Initiera ett nytt objekt av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att ange parametrarna för bredd och höjd. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) med hjälp av sökvägsparametern för att ange platsen för bildfilen som ska laddas. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att tillhandahålla en rasterbild som parameter. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Initierar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att ange sökvägen till bildfilen och färgtypen. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att ange en rasterbild och en färgtyp. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att initiera den med en ström. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Instansiera en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), och ange parametrarna för önskad bredd, höjd och färgtyp. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Initiera en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), med PNG-alternativ tillsammans med parametrarna för bredd och höjd. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta värdet för bitar per pixel för bilden. |
| [getHeight()](#getHeight--) | Få bildens höjd i pixlar. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämta eller ändra bildens horisontella upplösning. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Hämta eller ändra bildens horisontella upplösning. |
| [getFileFormat()](#getFileFormat--) | Hämtar formatet för filen som är associerad med bildinstansen. |
| [getRawDataFormat()](#getRawDataFormat--) | Kommer åt bildens rådataformat. |
| [getVerticalResolution()](#getVerticalResolution--) | Tillhandahåller åtkomst till bildens vertikala upplösning. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Tillhandahåller åtkomst till bildens vertikala upplösning. |
| [getWidth()](#getWidth--) | Möjliggör hämtning av bildens bredd i pixlar, vilket ger viktig information om dess dimensioner. |
| [hasTransparentColor()](#hasTransparentColor--) | Tillhandahåller ett booleskt värde som indikerar om bilden innehåller en transparent färg. |
| [hasAlpha()](#hasAlpha--) | Returnerar ett booleskt värde som indikerar om bilden har en alfakanal, vilket bestämmer dess transparens. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar bildens transparenta färg, om den finns. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Tillhandahåller ett booleskt värde som indikerar om bilden innehåller en transparent färg. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Modifierar bildens transparenta färg, om den finns. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar ett booleskt värde som indikerar om bilden har en bakgrundsfärg. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar bildens bakgrundsfärg, om en sådan har angetts. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Hämtar ett booleskt värde som indikerar om bilden har en bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Hämtar bildens bakgrundsfärg, om en sådan har angetts. |
| [getInterlaced()](#getInterlaced--) | Hämtar ett booleskt värde som indikerar om [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är interlaced, vilket avgör om bilddata lagras på ett progressivt sätt för snabbare inläsning eller överföring. |
| [isInterlaced()](#isInterlaced--) | Hämtar ett värde som indikerar om denna bildinstans är interlaced. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Läs in en PNG-bild från en fil.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Transformera bilden till en gråskalerepresentation
    pngImage.grayscale();

    // Spara till en fil.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Initiera ett nytt objekt av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att ange bredd- och höjdparametrar. Denna konstruktor förenklar skapandet av PNG-bilder genom att låta utvecklare specificera dimensionerna direkt, vilket underlättar effektiv hantering av PNG-bilddata i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) med hjälp av sökvägsparametern för att ange platsen för bildfilen som ska läsas in. Denna konstruktor gör det möjligt för utvecklare att enkelt skapa PNG-bilder genom att ladda dem från en fil, vilket förenklar processen att arbeta med PNG-bilder i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen för att läsa in en bild. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att tillhandahålla en rasterbild som parameter. Denna konstruktor låter utvecklare att direkt initiera ett PNG-bildobjekt med en befintlig rasterbild, vilket effektiviserar processen att arbeta med PNG-bilder i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Initierar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att ange sökvägen till bildfilen och färgtypen. Denna konstruktor möjliggör bekväm skapning av PNG-bilder från filer med olika färgtyper, vilket ger flexibilitet vid hantering av olika bildformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen för att läsa in en bild. |
| colorType | int | Färgtypen. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att ange en rasterbild och en färgtyp. Denna konstruktor gör det möjligt för utvecklare att direkt konvertera rasterbilder till PNG-format samtidigt som den önskade färgtypen specificeras, vilket ger flexibilitet i färgrepresentation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| colorType | int | Färgtypen. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Skapar en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) genom att initiera den med en ström. Denna konstruktor låter utvecklare att ladda PNG-bilder direkt från en ström, vilket ger flexibilitet vid bildhämtning från olika källor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen för att läsa in en bild. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Instansiera en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), med angivna parametrar för önskad bredd, höjd och färgtyp. Denna konstruktor möjliggör snabb skapning av PNG-bilder med skräddarsydda dimensioner och färgkonfigurationer, vilket underlättar effektiv bildgenerering för olika applikationer och arbetsflöden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| colorType | int | Färgtypen. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Initiera en ny instans av klassen [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), med PNG-alternativ tillsammans med bredd- och höjdparametrar. Denna konstruktor ger utvecklare möjlighet att skapa PNG-bilder med anpassningsbara inställningar och dimensioner, vilket erbjuder flexibilitet i bildgenerering för olika användningsfall.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | PNG-alternativen. |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta antalet bitar per pixel för bilden. Denna egenskap ger viktig information om bildens färgdjup, vilket gör det möjligt för utvecklare att förstå detaljnivån och färgprecisionen i bilddata.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämta bildens höjd i pixlar. Denna egenskap returnerar bildens vertikala dimension, vilket låter utvecklare bestämma dess storlek i pixlar längs den vertikala axeln.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Hämta eller ändra bildens horisontella upplösning. Denna egenskap representerar antalet pixlar per tum längs bildens horisontella axel. Justering av denna upplösning kan påverka bildens fysiska storlek vid utskrift eller visning.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Hämta horisontell och vertikal upplösning för PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Den horisontella upplösningen, i pixlar per tum: 96.0
//Den vertikala upplösningen, i pixlar per tum: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Hämta eller ändra bildens horisontella upplösning. Denna egenskap representerar antalet pixlar per tum längs bildens horisontella axel. Justering av denna upplösning kan påverka bildens fysiska storlek vid utskrift eller visning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar formatet för filen som är associerad med bildinstansen. Denna egenskap ger väsentlig information om filtypen, vilket möjliggör effektiv hantering och bearbetning baserat på specifika formatkrav.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Kommer åt bildens rådataformat. Denna egenskap ger insikt i hur bilddata är strukturerad internt, vilket kan vara användbart för avancerade bildbehandlingsuppgifter eller formatkonvertering.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// PNG-bilderna att ladda.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Ger åtkomst till bildens vertikala upplösning. Utvecklare kan använda denna egenskap för att hämta eller ändra upplösningsinställningen, vilket anger antalet pixlar per tum (PPI) längs bildens vertikala axel.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Hämta horisontell och vertikal upplösning för PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Utdata kan se ut så här:
//Den horisontella upplösningen, i pixlar per tum: 96.0
//Den vertikala upplösningen, i pixlar per tum: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Ger åtkomst till bildens vertikala upplösning. Utvecklare kan använda denna egenskap för att hämta eller ändra upplösningsinställningen, vilket anger antalet pixlar per tum (PPI) längs bildens vertikala axel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Möjliggör hämtning av bildens bredd i pixlar, vilket ger viktig information om dess dimensioner. Denna egenskap används ofta av utvecklare för att bestämma bildens bredd, vilket gör det möjligt att utföra olika operationer baserat på dess storlek

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Tillhandahåller ett booleskt värde som indikerar om bilden innehåller en transparent färg. Denna egenskap är avgörande för applikationer som behöver hantera transparens, vilket låter utvecklare avgöra om ytterligare bearbetning krävs för att hantera transparenta områden i bilden.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Returnerar ett booleskt värde som indikerar om bilden har en alfakanal, vilket bestämmer dess transparens. Denna egenskap är användbar för applikationer som behöver hantera transparens, vilket gör det möjligt för utvecklare att avgöra om ytterligare bearbetning krävs för att hantera transparenta områden i bilden.

**Returns:**
boolean - `true` om denna instans har alfa; annars `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Hjälparklass
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

// Hämta alla stödda PNG-färgtyper.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// Utdata ser ut så här:
// En Grayscale PNG-bild stöder inte alfakanal
// En Truecolor PNG-bild stöder inte alfakanal
// En IndexedColor PNG-bild stöder inte alfakanal
// En GrayscaleWithAlpha PNG-bild stöder alfakanal
// En TruecolorWithAlpha PNG-bild stöder alfakanal
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar bildens transparenta färg, om den finns. Denna egenskap är värdefull för applikationer som kräver exakt hantering av transparenta områden i bilder, vilket gör det möjligt för utvecklare att komma åt och manipulera den specifika transparenta färgen som används.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Tillhandahåller ett booleskt värde som indikerar om bilden innehåller en transparent färg. Denna egenskap är avgörande för applikationer som behöver hantera transparens, vilket låter utvecklare avgöra om ytterligare bearbetning krävs för att hantera transparenta områden i bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Skapa en TrueColor PNG-bild på 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alla röda pixlar kommer att betraktas som helt transparenta.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alla transparenta pixlar kommer att ha en bakgrundsfärg.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fyll hela bilden med vit färg.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fyll det övre vänstra kvartalet av bilden med den transparenta färgen.
    // Detta gör att det övre vänstra kvartalet färgas med bakgrundsfärgen.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Modifierar bildens transparenta färg, om den finns. Denna egenskap är värdefull för applikationer som kräver exakt hantering av transparenta områden i bilder, vilket gör det möjligt för utvecklare att komma åt och manipulera den specifika transparenta färgen som används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Skapa en TrueColor PNG-bild på 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alla röda pixlar kommer att betraktas som helt transparenta.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alla transparenta pixlar kommer att ha en bakgrundsfärg.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fyll hela bilden med vit färg.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fyll det övre vänstra kvartalet av bilden med den transparenta färgen.
    // Detta gör att det övre vänstra kvartalet färgas med bakgrundsfärgen.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Hämtar ett booleskt värde som indikerar om bilden har en bakgrundsfärg. Denna egenskap är användbar för applikationer som behöver avgöra om en bild innehåller en bakgrundsfärg, vilket kan vara viktigt för olika bearbetningsuppgifter såsom sammansättning, rendering eller export.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar bildens bakgrundsfärg, om en sådan har angetts. Denna egenskap är hjälpsam för applikationer som behöver identifiera och eventuellt manipulera en bilds bakgrundsfärg.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Hämtar ett booleskt värde som indikerar om bilden har en bakgrundsfärg. Denna egenskap är användbar för applikationer som behöver avgöra om en bild innehåller en bakgrundsfärg, vilket kan vara viktigt för olika bearbetningsuppgifter såsom sammansättning, rendering eller export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Skapa en TrueColor PNG-bild på 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alla röda pixlar kommer att betraktas som helt transparenta.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alla transparenta pixlar kommer att ha en bakgrundsfärg.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fyll hela bilden med vit färg.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fyll det övre vänstra kvartalet av bilden med den transparenta färgen.
    // Detta gör att det övre vänstra kvartalet färgas med bakgrundsfärgen.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Hämtar bildens bakgrundsfärg, om en sådan har angetts. Denna egenskap är hjälpsam för applikationer som behöver identifiera och eventuellt manipulera en bilds bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Skapa en TrueColor PNG-bild på 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alla röda pixlar kommer att betraktas som helt transparenta.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alla transparenta pixlar kommer att ha en bakgrundsfärg.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fyll hela bilden med vit färg.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fyll det övre vänstra kvartalet av bilden med den transparenta färgen.
    // Detta gör att det övre vänstra kvartalet färgas med bakgrundsfärgen.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Hämtar ett booleskt värde som indikerar om [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är interlaced, vilket avgör om bilddata lagras på ett progressivt sätt för snabbare inläsning eller överföring.

**Returns:**
boolean - `true` om interfolierad; annars `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Hämtar ett värde som indikerar om denna bildinstans är interlaced.

Värde: `true` om den här bildinstansen är interfolierad; annars `false`.

**Returns:**
boolean - ett värde som indikerar om den här bildinstansen är interfolierad.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämtar standardalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade. Till exempel, om vi läser in en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med metoden `DataStreamSupporter.Save(string)`, kommer en PNG-bild med 8 bitar per pixel att genereras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden `Image.Save(string, ImageOptionsBase)` som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
