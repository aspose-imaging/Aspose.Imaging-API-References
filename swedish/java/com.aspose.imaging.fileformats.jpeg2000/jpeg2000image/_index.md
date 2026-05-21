---
title: "Jpeg2000Image"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera JPEG2000 JP2-bildfiler effektivt med vårt API som stödjer ett brett spektrum av bitdjup per pixel och sömlös bearbetning av XMP-metadata som innehåller viktig bildinformation."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Manipulera JPEG2000 (JP2)-bildfiler effektivt med vårt API, som stödjer ett brett spektrum av bitdjup per pixel och sömlös bearbetning av XMP-metadata som innehåller viktig bildinformation. Med funktioner för förlustfri komprimering säkerställer du optimal bildkvalitet samtidigt som filintegriteten bevaras, vilket ger dig möjlighet att anpassa JP2-bilder exakt efter dina specifikationer med lätthet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Börja arbeta med klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) genom att initiera en ny instans med sökvägen till den bild du vill läsa in. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Kom igång enkelt med klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) genom att skapa en ny instans med både filsökvägen och den önskade bitdjup‑per‑pixel‑parametern. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Initiera enkelt en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) genom att tillhandahålla ett strömobjekt. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Initiera en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) med en ström för att läsa in bilden, samt parametrar för bitdjup per pixel. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Skapa en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), och ange parametrarna för bredd och höjd. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Instansiera ett nytt [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-objekt genom att ange parametrarna för bredd, höjd och bildalternativ. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Skapa en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) med parametrar för bredd, höjd och antal bitar. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Instansiera en ny [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-klass med en rasterbild. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Initiera en ny [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-instans med en rasterbild och parametrar för bitdjup per pixel. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta formatet för bildfilen. |
| [getRawDataFormat()](#getRawDataFormat--) | Denna egenskap hämtar bildens rådataformat. |
| [getRawLineSize()](#getRawLineSize--) | Denna egenskap hämtar storleken på en enskild rad av råbilddata i byte. |
| [getWidth()](#getWidth--) | Denna egenskap returnerar bildens bredd i pixlar. |
| [getHeight()](#getHeight--) | Denna egenskap hämtar bildens höjd i pixlar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Denna egenskap returnerar bildens djup, mätt i bitar per pixel (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | Denna egenskap låter dig hämta eller ändra den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Denna egenskap låter dig hämta eller ändra den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | Denna egenskap ger åtkomst till den vertikala upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Denna egenskap ger åtkomst till den vertikala upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). |
| [getComments()](#getComments--) | Denna egenskap möjliggör att hämta eller uppdatera kommentarer som är associerade med bilden. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Denna egenskap möjliggör att hämta eller uppdatera kommentarer som är associerade med bilden. |
| [getCodec()](#getCodec--) | Denna egenskap hämtar JPEG2000-codec som är associerad med bilden. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämta bildalternativen baserat på de ursprungliga filinställningarna. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Läs in en JPEG2000-bild.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Spara som PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Börja arbeta med klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) genom att initiera en ny instans med sökvägen till den bild du vill läsa in. Denna konstruktor möjliggör enkel åtkomst till JPEG2000-bilder och förenklar processen för att läsa in och hantera bildfiler. Genom att ange filsökvägen kan du snabbt börja bearbeta och manipulera JPEG2000-bilder i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att läsa in bilden från och initiera pixel- och palettdata med. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Kom snabbt igång med klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) genom att skapa en ny instans med både filsökvägen och önskat bitar per pixel-parameter. Denna konstruktor möjliggör finjustering av bildläsningsprocessen och säkerställer kompatibilitet med olika bildformat och kvalitetsinställningar. Med denna flexibilitet kan du effektivt hantera och manipulera JPEG2000-bilder enligt dina specifika krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att läsa in bilden från och initiera pixel- och palettdata med |
| bitsPerPixel | int | Bitar per pixel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Initiera enkelt en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) genom att tillhandahålla ett strömobjekt. Denna konstruktor förenklar processen att läsa in JPEG2000-bilder direkt från strömmar och erbjuder flexibilitet och bekvämlighet för att hantera bilddata från olika källor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa in bilden från och initiera pixel- och palettdata med. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Initiera en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) med en ström för att läsa in bilden, tillsammans med parametrar för bitar per pixel. Denna konstruktor erbjuder flexibilitet genom att låta dig ange både bilddatakällan och önskat antal bitar per pixel, vilket ger finare kontroll över bildläsningsprocessen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa in bilden från och initiera pixel- och palettdata med. |
| bitsPerPixel | int | Bitar per pixel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Skapa en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), med angivna bredd- och höjdpametrar. Denna konstruktor låter dig initiera en JPEG2000-bild med specifika dimensioner, vilket är användbart i scenarier där du programmässigt behöver skapa en bild av en viss storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd |
| höjd | int | Bildens höjd |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Instansiera ett nytt [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-objekt genom att ange parametrarna för bredd, höjd och bildalternativ. Denna konstruktor möjliggör skapandet av JPEG2000-bilder med specifika dimensioner och ytterligare alternativ, vilket ger flexibilitet vid bildgenerering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd |
| höjd | int | Bildens höjd |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Alternativen. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Skapa en ny instans av klassen [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) med parametrar för bredd, höjd och bitantal. Denna konstruktor möjliggör skapandet av JPEG2000-bilder med specifika dimensioner och bitdjup, vilket ger flexibilitet för olika bildbehov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd |
| höjd | int | Bildens höjd |
| bitsCount | int | Bitantalet. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Instansiera en ny [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-klass med en rasterbild. Denna konstruktor underlättar skapandet av en JPEG2000-bild från en befintlig rasterbild och erbjuder sömlös integration och konvertering mellan olika bildformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Initiera en ny [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-instans med en rasterbild och parametrar för bitar per pixel. Denna konstruktor möjliggör exakt kontroll över kvaliteten och storleken på den resulterande JPEG2000-bilden, vilket gör den idealisk för scenarier där anpassning är avgörande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska initieras med pixel- och palettdata. |
| bitsPerPixel | int | Bitar per pixel. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta formatet för bildfilen. Denna egenskap ger information om bildens filformat. Använd denna egenskap för att programatiskt bestämma formatet för bildfilen, vilket underlättar lämplig hantering och bearbetning baserat på filens format.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Denna egenskap hämtar det råa dataformatet för bilden. Den ger information om hur pixeldata lagras i minnet. Använd denna egenskap för att förstå det underliggande dataformatet för bilden, vilket kan vara avgörande för olika bildbehandlingsoperationer som färgkonvertering, komprimering eller dekomprimering.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Denna egenskap hämtar storleken på en enskild rad av rå bilddata i byte. Den visar hur mycket minne som upptas av en enskild pixelrad i bildens råa dataformat. Att förstå den råa radstorleken är viktigt för uppgifter som minnesallokering, datamanipulation och bildbehandlingsalgoritmer som arbetar på enskilda bildrader.

**Returns:**
int - Den råa radstorleken i byte.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Denna egenskap returnerar bildens bredd i pixlar. Den ger en grundläggande information om bildens dimensioner, vilket är avgörande för olika bildbehandlingsuppgifter, inklusive storleksändring, beskärning och rendering.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Denna egenskap hämtar bildens höjd i pixlar. Den fungerar som viktig information för att förstå bildens vertikala dimensioner och underlättar olika bildmanipuleringsuppgifter som storleksändring, beskärning och rendering. Genom att komma åt denna egenskap kan användare fastställa bildens vertikala storlek, vilket möjliggör exakt layout och visning i applikationer.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Denna egenskap returnerar bildens djup, mätt i bitar per pixel (bpp). Den visar mängden färginformation som lagras i varje pixel i bilden. Att förstå bilddjupet är avgörande för att bestämma färgåtergivningens noggrannhet och bildens kvalitet. Med denna information kan användare bedöma detaljnivån och färgrikedom i bilden.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Denna egenskap låter dig hämta eller ändra den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). Justering av denna upplösning kan påverka bildens storlek och kvalitet vid utskrift eller visning. Genom att ställa in den horisontella upplösningen kan användare optimera bilden för specifika utskriftsenheter eller applikationer, vilket säkerställer bästa möjliga visuella resultat.

**Returns:**
double - Den horisontella upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Hämta horisontell och vertikal upplösning för Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 72.0
// Den vertikala upplösningen, i pixlar per tum: 72.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 72.0
// Den vertikala upplösningen, i pixlar per tum: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Denna egenskap låter dig hämta eller ändra den horisontella upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). Justering av denna upplösning kan påverka bildens storlek och kvalitet vid utskrift eller visning. Genom att ställa in den horisontella upplösningen kan användare optimera bilden för specifika utskriftsenheter eller applikationer, vilket säkerställer bästa möjliga visuella resultat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den horisontella upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Denna egenskap ger åtkomst till den vertikala upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). Ändring av denna upplösning kan påverka bildens kvalitet och storlek vid utskrift eller visning. Genom att justera den vertikala upplösningen kan användare optimera bilden för olika utskriftsenheter eller applikationer, vilket säkerställer optimal visuell rendering.

**Returns:**
double - Den vertikala upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Hämta horisontell och vertikal upplösning för Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 72.0
// Den vertikala upplösningen, i pixlar per tum: 72.0
// Ställ in upplösningsvärden till 96 dpi
// Den horisontella upplösningen, i pixlar per tum: 72.0
// Den vertikala upplösningen, i pixlar per tum: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Denna egenskap ger åtkomst till den vertikala upplösningen för [RasterImage](../../com.aspose.imaging/rasterimage), mätt i pixlar per tum (PPI). Ändring av denna upplösning kan påverka bildens kvalitet och storlek vid utskrift eller visning. Genom att justera den vertikala upplösningen kan användare optimera bilden för olika utskriftsenheter eller applikationer, vilket säkerställer optimal visuell rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den vertikala upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Denna egenskap möjliggör att hämta eller uppdatera kommentarer som är kopplade till bilden. Kommentarer ger ytterligare information om bildens innehåll, såsom anteckningar, beskrivningar eller metadata. Att ändra dessa kommentarer kan vara användbart för att organisera och kategorisera bilder, samt förmedla viktiga detaljer till betraktare eller användare.

**Returns:**
java.lang.String[] - Kommentarerna.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Denna egenskap möjliggör att hämta eller uppdatera kommentarer som är kopplade till bilden. Kommentarer ger ytterligare information om bildens innehåll, såsom anteckningar, beskrivningar eller metadata. Att ändra dessa kommentarer kan vara användbart för att organisera och kategorisera bilder, samt förmedla viktiga detaljer till betraktare eller användare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] | Kommentarerna. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Denna egenskap hämtar JPEG2000-codec som är associerad med bilden. JPEG2000-codec är ansvarig för kodning och avkodning av bilddata i JPEG2000-formatet, vilket ger effektiv komprimering samtidigt som hög bildkvalitet bibehålls. Åtkomst till denna codec kan vara användbart för att utföra avancerade bildbehandlingsoperationer eller optimera bildkomprimeringsinställningar anpassade efter specifika krav.

**Returns:**
int - Codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämta bildalternativen baserat på de ursprungliga filinställningarna. Denna metod är fördelaktig för att bevara bitdjupet och andra parametrar för den ursprungliga bilden, vilket säkerställer konsistens och bevarar bilddataens integritet. Åtkomst till dessa alternativ underlättar sömlös hantering och bearbetning av bilden samtidigt som dess ursprungliga egenskaper behålls. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) metoden, kommer en PNG-bild med 8 bitar per pixel att genereras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) metoden som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
