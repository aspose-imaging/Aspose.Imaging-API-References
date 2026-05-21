---
title: "TgaImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera TGA‑rasterbildfiler med vårt API anpassat för TARGA Truevision Advanced Raster Adapter‑formatet som möjliggör sömlös inläsning och anpassning."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Manipulera TGA‑rasterbildfiler med vårt API, anpassat för TARGA (Truevision Advanced Raster Adapter)-formatet, vilket möjliggör sömlös inläsning och anpassning. Uppdatera enkelt offentliga egenskaper såsom författare, tidsstämpel, bild‑ID och programvaruversion, samtidigt som du använder olika bitar‑per‑pixel‑inställningar, alfakanal och färgtransparenthet. Dessutom kan du exportera TGA‑bilder till andra populära rasterformat, vilket säkerställer kompatibilitet för dina projekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Initierar ett nytt [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) objekt med den angivna filsökvägen för att läsa in bildens innehåll. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Skapa en ny instans av klassen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) genom att tillhandahålla ett rasterbildsobjekt. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Initiera en ny instans av klassen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) med en ström för att läsa in bilden. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta värdet för bitar per pixel, vilket ger viktig information om bildens färgdjup. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Få värdet för byte per pixel, vilket anger hur mycket minne varje pixel i bilden upptar. |
| [hasAlpha()](#hasAlpha--) | Hämta ett booleskt värde som indikerar om [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) innehåller en alfakanal, vilket möjliggör transparenseffekter. |
| [isGrayScale()](#isGrayScale--) | Få ett booleskt värde som indikerar om [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) representerar en gråskala bild. |
| [getWidth()](#getWidth--) | Hämta bildens bredd som representeras av denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instans. |
| [getHeight()](#getHeight--) | Få bildens höjd som kapslas in i denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instans. |
| [getFileFormat()](#getFileFormat--) | Hämta viktig information om bildens filformat som representeras av denna instans av [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | Hämta om denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instans innehåller en färgkarta. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Hämtar täljardelen av gamma‑värdet, vilket är avgörande för korrekt färgrepresentation i bilder. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Hämtar nämnardelen av gamma‑värdet, en viktig faktor för att bestämma färgrepresentation i bilder. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Hämtar täljarkomponenten av pixelaspektförhållandet, vilket påverkar pixelns visuella utseende i bilden. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Hämtar nämnardelen av pixelaspektförhållandet, en avgörande faktor för att bestämma pixelns visuella utseende i bilden. |
| [getXOrigin()](#getXOrigin--) | Hämtar den absoluta horisontella koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien). |
| [setXOrigin(int value)](#setXOrigin-int-) | Ställer in den absoluta horisontella koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien). |
| [getYOrigin()](#getYOrigin--) | Hämtar den absoluta vertikala koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien). |
| [setYOrigin(int value)](#setYOrigin-int-) | Ställer in den absoluta vertikala koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien). |
| [getImageId()](#getImageId--) | Hämtar den unika identifieraren som är associerad med bilden. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Ställer in den unika identifieraren som är associerad med bilden. |
| [getAuthorComments()](#getAuthorComments--) | Hämtar eller anger kommentarer som tillhandahållits av bildens författare. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Hämtar eller anger kommentarer som tillhandahållits av bildens författare. |
| [getAuthorName()](#getAuthorName--) | Hämtar eller anger namnet på författaren som är associerad med bilden. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Hämtar eller anger namnet på författaren som är associerad med bilden. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Hämtar datum/tidsstämpel. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Anger datum/tidsstämpel. |
| [getJobNameOrId()](#getJobNameOrId--) | Hämtar eller anger jobbnamnet eller ID:t som är associerat med bilden. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Hämtar eller anger jobbnamnet eller ID:t som är associerat med bilden. |
| [getJobTime()](#getJobTime--) | Hämtar eller anger tidsstämpeln som visar jobbtiden som är associerad med bilden. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Hämtar eller anger tidsstämpeln som visar jobbtiden som är associerad med bilden. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar eller anger nyckelfärgen som är associerad med bilden. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Hämtar eller anger nyckelfärgen som är associerad med bilden. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar eller anger ett booleskt värde som indikerar om bilden innehåller en transparent färg. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Hämtar eller anger ett booleskt värde som indikerar om bilden innehåller en transparent färg. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller anger bakgrundsfärgen på bilden. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Hämtar eller anger bakgrundsfärgen på bilden. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar eller anger ett värde som indikerar om bilden innehåller en bakgrundsfärg. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Hämtar eller anger ett värde som indikerar om bilden innehåller en bakgrundsfärg. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Hämtar eller anger programvaruversionen som är associerad med bilden. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Hämtar eller anger programvaruversionen som är associerad med bilden. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Hämtar eller anger bokstavskomponenten i programvaruversionen som är associerad med bilden. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Hämtar eller anger bokstavskomponenten i programvaruversionen som är associerad med bilden. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Hämtar eller anger den numeriska komponenten i programvaruversionen som är associerad med bilden. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Hämtar eller anger den numeriska komponenten i programvaruversionen som är associerad med bilden. |
| [getSoftwareId()](#getSoftwareId--) | Hanterar programvaruidentifieringen (ID) som är associerad med bilden, med stöd för upp till 40 ASCII-tecken. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Hanterar programvaruidentifieringen (ID) som är associerad med bilden, med stöd för upp till 40 ASCII-tecken. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Utför en likhetsjämförelse mellan två TGA-bilder, med beaktande av både den första och den andra bilden som är inblandad i jämförelseprocessen. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Genomför en icke-likhetsjämförelse mellan två TGA-bilder, där både den första och den andra bilden som är inblandad i jämförelsen utvärderas. |
| [deepClone()](#deepClone--) | Skapar en dubblett av den aktuella instansen och genererar ett nytt objekt som klonar alla attribut och egenskaper från originalet. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Replikera egenskaperna hos ett annat [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-objekt och skapa en ny instans med identiska attribut. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | I en likhetsjämförelse utvärderar metoden om den aktuella [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instansen är lika med den andra bilden som anges som parameter. |
| [equals(Object other)](#equals-java.lang.Object-) | Metoden utför en likhetsjämförelse mellan den aktuella [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instansen och ett annat objekt som anges som parameter. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Metoden "rotateFlip" möjliggör roterings- och vändningsoperationer på bilden. |
| [hashCode()](#hashCode--) | Hämta hashkoden för den aktuella instansen. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden till en angiven region. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beskär bilden genom att ange förskjutningar för vänster, höger, topp och botten. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändra storlek på bilden samtidigt som specifika inställningar tillämpas för att behålla önskade dimensioner och bildförhållande. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Justera bildens storlek med en angiven storleksändringstyp, som bestämmer hur storleksändringsoperationen utförs. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Roterar bilden kring dess centrum med en angiven vinkel samtidigt som bildstorlekens proportioner bibehålls och bakgrundsfärgen bevaras. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Initierar ett nytt [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-objekt med den angivna filsökvägen för att läsa in bildinnehållet. Denna konstruktor initierar bildinstansen effektivt, vilket möjliggör sömlös åtkomst till TGA-bildfiler och förenklar integrationen i ditt applikationsflöde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen för att läsa in en bild. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Skapa en ny instans av klassen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) genom att tillhandahålla ett rasterbildobjekt. Denna konstruktor underlättar den direkta integrationen av befintliga rasterbilder i TGA-bildformatet, vilket effektiviserar konverteringsprocessen för förbättrad kompatibilitet i dina mjukvarusystem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Initiera en ny instans av klassen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) med en ström för att läsa in bilden. Denna konstruktor möjliggör sömlös integration av bilddata från strömmar, vilket underlättar effektiv hantering och bearbetning av TGA-bilder i dina mjukvaruapplikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen för att läsa in en bild. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta värdet för bitar per pixel, vilket ger viktig information om bildens färgdjup. Denna egenskap fungerar som ett avgörande mått för att förstå detaljnivån och färgrikedomen i bilden, och hjälper utvecklare att optimera bearbetningsalgoritmer och resursallokering för effektiv bildmanipulation och renderingsuppgifter.

**Returns:**
int - bitar per pixel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Hämta värdet för byte per pixel, vilket anger hur mycket minne varje pixel i bilden upptar. Denna egenskap fungerar som ett viktigt mått för minneshantering och optimering, och hjälper utvecklare att effektivt allokera resurser och bearbeta bilddata.

**Returns:**
int - byte per pixel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämta ett booleskt värde som indikerar om [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) innehåller en alfakanal, vilket möjliggör transparenseffekter. Denna egenskap ger viktig information för hantering av bildkomposition och rendering, och hjälper utvecklare att implementera olika visuella effekter och sammansättningsoperationer.

**Returns:**
boolesk - ett värde som indikerar om denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) har en alfakanal.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Hämta ett booleskt värde som indikerar om [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) representerar en gråskala bild. Denna egenskap är avgörande för att skilja mellan färg- och gråskalebilder, och hjälper utvecklare att tillämpa lämpliga bearbetnings- och renderingsmetoder baserat på bildens färgkaraktäristik.

**Returns:**
boolesk - ett värde som indikerar om denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) är gråskala.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämta bredden på bilden som representeras av denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instans. Denna egenskap ger utvecklare viktig information om bildens dimensioner, vilket underlättar olika bildmanipulerings- och bearbetningsuppgifter i deras mjukvaruapplikationer.

**Returns:**
int - bildens bredd i pixlar.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämta höjden på bilden som kapslas in i denna [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instans. Denna egenskap förser utvecklare med kritiska detaljer om bildens vertikala dimensioner, vilket möjliggör sömlös integration och manipulation av bilder i deras mjukvarulösningar.

**Returns:**
int - bildens höjd i pixlar.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta viktig information om bildformatet för bilden som representeras av detta exempel av [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Att förstå bildformatet är avgörande för kompatibilitetskontroller och för att säkerställa sömlös integration i mjukvarusystem, vilket möjliggör effektiv bearbetning och manipulation av bilder.

**Returns:**
long - viktig information om bildformatet för bilden som representeras av detta exempel av [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Hämta om detta [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-exempel innehåller en färgkarta. Att förstå närvaron av en färgkarta är avgörande för korrekt tolkning och manipulation av bildens färgdata.

**Returns:**
boolean - ett värde som indikerar om denna bild har färgkarta.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Hämtar täljardelen av gamma‑värdet, vilket är viktigt för korrekt färgåtergivning i bilder. I bilder utan gamma‑korrektion bör detta värde vara 1,0. Att förstå och använda detta värde är avgörande för att bibehålla färgprecision och säkerställa korrekt bildrendering.

**Returns:**
int - täljardelen av gamma‑värdet, vilket är viktigt för korrekt färgåtergivning i bilder.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Hämtar nämnardelen av gamma‑värdet, en väsentlig faktor för att bestämma färgåtergivning i bilder. För bilder utan gamma‑korrektion bör detta värde vara 1,0, vilket säkerställer korrekt färgrendering. Att uppskatta och utnyttja denna parameter är grundläggande för att upprätthålla färgprecision och uppnå exakt bildvisualisering.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Hämtar täljarkomponenten av pixelaspektförhållandet, vilket påverkar den visuella aspekten av pixlar i bilden. Att förstå och manipulera detta värde är nödvändigt för att uppnå korrekt pixelrepresentation och aspektförhållanden i bildrendering och -bearbetning.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Hämtar nämnardelen av pixelaspektförhållandet, en avgörande faktor för att bestämma den visuella aspekten av pixlar i bilden. Detta värde är nödvändigt för att bevara korrekt pixelrepresentation och aspektförhållanden genom olika bildrenderings- och bearbetningsoperationer, vilket säkerställer högkvalitativ visuell output.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Hämtar den absoluta horisontella koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien).

**Returns:**
int - absolut horisontell koordinat för bildens nedre vänstra hörn när den placeras på en displayenhet med ursprung i bildskärmens nedre vänstra hörn.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Ställer in den absoluta horisontella koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | absolut horisontell koordinat för bildens nedre vänstra hörn när den placeras på en displayenhet med ursprung i bildskärmens nedre vänstra hörn. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Hämtar den absoluta vertikala koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien).

**Returns:**
int - absolut vertikal koordinat för bildens nedre vänstra hörn när den placeras på en displayenhet med ursprung i bildskärmens nedre vänstra hörn.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Ställer in den absoluta vertikala koordinaten för bildens nedre vänstra hörn när den är placerad på en displayenhet med ursprung i skärmens nedre vänstra hörn (t.ex. TARGA-serien).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | absolut vertikal koordinat för bildens nedre vänstra hörn när den placeras på en displayenhet med ursprung i bildskärmens nedre vänstra hörn. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Hämtar den unika identifieraren som är associerad med bilden. Detta ID fungerar som en referenspunkt för att identifiera och särskilja bilden från andra i ett system eller en applikation. Genom att sätta eller hämta Bild‑ID kan du hantera och spåra bilder effektivt, vilket underlättar organiserad bildhantering och återhämtningsprocesser.

Detta valfria fält innehåller identifierande information om bilden. Maxlängden för detta fält är 255 byte.

**Returns:**
java.lang.String - den unika identifieraren som är associerad med bilden.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Sätter den unika identifieraren som är associerad med bilden. Detta ID fungerar som en referenspunkt för att identifiera och särskilja bilden från andra i ett system eller en applikation. Genom att sätta eller hämta Bild‑ID kan du hantera och spåra bilder effektivt, vilket underlättar organiserad bildhantering och återhämtningsprocesser.

Detta valfria fält innehåller identifierande information om bilden. Maxlängden för detta fält är 255 byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | den unika identifieraren som är associerad med bilden. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Hämtar eller sätter kommentarer som tillhandahålls av bildens författare. Dessa kommentarer innehåller ofta värdefull information, såsom beskrivningar, anteckningar eller ytterligare sammanhang om bilden. Genom att komma åt eller ändra egenskapen Author Comments kan utvecklare förbättra metadata som är kopplade till bilden, vilket ger användare värdefulla insikter och kontext kring dess innehåll eller skapelse. Detta är ett ASCII‑fält bestående av 324 byte som är organiserade som fyra rader med 80 tecken, var och en följd av en null‑terminator.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Hämtar eller sätter kommentarer som tillhandahålls av bildens författare. Dessa kommentarer innehåller ofta värdefull information, såsom beskrivningar, anteckningar eller ytterligare sammanhang om bilden. Genom att komma åt eller ändra egenskapen Author Comments kan utvecklare förbättra metadata som är kopplade till bilden, vilket ger användare värdefulla insikter och kontext kring dess innehåll eller skapelse. Detta är ett ASCII‑fält bestående av 324 byte som är organiserade som fyra rader med 80 tecken, var och en följd av en null‑terminator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Hämtar eller sätter namnet på författaren som är associerad med bilden. Denna egenskap låter utvecklare komma åt eller ändra författarens namn‑metadata, vilket ger värdefull information om bildens skapare. Genom att använda egenskapen Author Name kan användare enkelt identifiera den person som ansvarar för att skapa eller bidra till bilden, vilket förbättrar dess övergripande metadata och ger värdefull kontext för betraktare. Detta fält är totalt 40 ASCII‑tecken för namnet. Om fältet används bör det innehålla namnet på personen som skapade bilden (författare).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Hämtar eller sätter namnet på författaren som är associerad med bilden. Denna egenskap låter utvecklare komma åt eller ändra författarens namn‑metadata, vilket ger värdefull information om bildens skapare. Genom att använda egenskapen Author Name kan användare enkelt identifiera den person som ansvarar för att skapa eller bidra till bilden, vilket förbättrar dess övergripande metadata och ger värdefull kontext för betraktare. Detta fält är totalt 40 ASCII‑tecken för namnet. Om fältet används bör det innehålla namnet på personen som skapade bilden (författare).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Författarnamn. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Hämtar datum/tidsstämpel. Detta fält definierar värdet för datum och tid då bilden sparades. Även om operativsystem vanligtvis tids- och datumstämplar filer, tillhandahålls denna funktion eftersom operativsystemet kan ändra tids- och datumstämpeln om filen kopieras. Genom att använda detta område garanteras ett oförändrat område för datum- och tidsregistrering.

**Returns:**
java.util.Date - datum/tidsstämpel.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Ställer in datum/tidsstämpel. Detta fält definierar värdet för datum och tid då bilden sparades. Även om operativsystem vanligtvis tids- och datumstämplar filer, tillhandahålls denna funktion eftersom operativsystemet kan ändra tids- och datumstämpeln om filen kopieras. Genom att använda detta område garanteras du ett oförändrat område för datum- och tidsregistrering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date | Datum/tidsstämpel. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Hämtar eller anger jobbnamnet eller ID:t som är associerat med bilden. Denna egenskap gör det möjligt att komma åt eller ändra metadata relaterade till det specifika jobbet eller projektet som är kopplat till bilden. Genom att använda egenskapen Job Name/ID kan användare enkelt identifiera det projekt eller den uppgift som bilden tillhör, vilket underlättar organisering och hantering av bildresurser inom större arbetsflöden eller projekt.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Hämtar eller anger jobbnamnet eller ID:t som är associerat med bilden. Denna egenskap gör det möjligt att komma åt eller ändra metadata relaterade till det specifika jobbet eller projektet som är kopplat till bilden. Genom att använda egenskapen Job Name/ID kan användare enkelt identifiera det projekt eller den uppgift som bilden tillhör, vilket underlättar organisering och hantering av bildresurser inom större arbetsflöden eller projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Hämtar eller anger tidsstämpeln som indikerar jobbtiden som är associerad med bilden. Denna egenskap låter utvecklare komma åt eller ändra tidsmetadata relaterad till det specifika jobbet eller projektet som är kopplat till bilden.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Hämtar eller anger tidsstämpeln som indikerar jobbtiden som är associerad med bilden. Denna egenskap låter utvecklare komma åt eller ändra tidsmetadata relaterad till det specifika jobbet eller projektet som är kopplat till bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar eller anger nyckelfärgen som är associerad med bilden. Denna egenskap gör det möjligt att komma åt eller ändra färgen som har utsetts som nyckelfärg för specifika bildbehandlingsuppgifter eller effekter. Genom att använda egenskapen Key Color kan användare tillämpa färgbaserade operationer såsom chroma keying eller färgbyte, vilket förbättrar bildmanipuleringsmöjligheter och kreativa möjligheter.

Key Color kan betraktas som \\u2018bakgrundsfärg\\u2019 eller \\u2018transparent färg\\u2019. Detta är färgen på \\u2018icke bild\\u2019-området på skärmen, och samma färg som skärmen skulle rensas till om den raderas i applikationen.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Hämtar eller anger nyckelfärgen som är associerad med bilden. Denna egenskap gör det möjligt att komma åt eller ändra färgen som har utsetts som nyckelfärg för specifika bildbehandlingsuppgifter eller effekter. Genom att använda egenskapen Key Color kan användare tillämpa färgbaserade operationer såsom chroma keying eller färgbyte, vilket förbättrar bildmanipuleringsmöjligheter och kreativa möjligheter.

Key Color kan betraktas som \\u2018bakgrundsfärg\\u2019 eller \\u2018transparent färg\\u2019. Detta är färgen på \\u2018icke bild\\u2019-området på skärmen, och samma färg som skärmen skulle rensas till om den raderas i applikationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar eller anger ett booleskt värde som indikerar om bilden innehåller en transparent färg. Denna egenskap är avgörande för att identifiera om bilden stödjer transparens, vilket hjälper dig att implementera lämplig hantering av transparensrelaterade operationer såsom blandning, sammansättning eller maskning.

**Returns:**
boolean - ett värde som indikerar om bilden har transparent färg.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Hämtar eller anger ett booleskt värde som indikerar om bilden innehåller en transparent färg. Denna egenskap är avgörande för att identifiera om bilden stödjer transparens, vilket hjälper dig att implementera lämplig hantering av transparensrelaterade operationer såsom blandning, sammansättning eller maskning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om bilden har transparent färg. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar eller anger bakgrundsfärgen för bilden. Denna egenskap gör det möjligt att specificera färgen som används för bildens bakgrund, vilket säkerställer konsistens och förbättrar den visuella presentationen. Den är särskilt användbar i scenarier där bilden visas på en bakgrund med en annan färg eller när bilden renderas på en annan canvas.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Hämtar eller anger bakgrundsfärgen för bilden. Denna egenskap gör det möjligt att specificera färgen som används för bildens bakgrund, vilket säkerställer konsistens och förbättrar den visuella presentationen. Den är särskilt användbar i scenarier där bilden visas på en bakgrund med en annan färg eller när bilden renderas på en annan canvas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bakgrundsfärgen. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Hämtar eller anger ett värde som indikerar om bilden innehåller en bakgrundsfärg. Denna egenskap är användbar för att avgöra om bilden har en tydlig bakgrundsfärg som är separerad från förgrundsinnehållet. Den möjliggör anpassning av bildbehandling eller rendering baserat på närvaro eller frånvaro av en bakgrundsfärg.

**Returns:**
boolean - ett värde som indikerar om bilden har bakgrundsfärg.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om bilden innehåller en bakgrundsfärg. Denna egenskap är användbar för att avgöra om bilden har en tydlig bakgrundsfärg som är separerad från förgrundsinnehållet. Den möjliggör anpassning av bildbehandling eller rendering baserat på närvaro eller frånvaro av en bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om bilden har bakgrundsfärg. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Hämtar eller anger programvaruversionen som är associerad med bilden. Den accepterade längden för versionssträngen är vanligtvis 3 till 4 tecken. Denna egenskap är användbar för att spåra den programvara som använts för att skapa eller manipulera bilden och kan ge värdefull kontext för bildbehandling och kompatibilitetskontroller.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Hämtar eller anger programvaruversionen som är associerad med bilden. Den accepterade längden för versionssträngen är vanligtvis 3 till 4 tecken. Denna egenskap är användbar för att spåra den programvara som använts för att skapa eller manipulera bilden och kan ge värdefull kontext för bildbehandling och kompatibilitetskontroller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Hämtar eller anger bokstavskomponenten i programvaruversionen som är associerad med bilden. Denna egenskap representerar en ytterligare detalj inom versionssträngen och kan vara användbar för finare versionsdifferentiering.

**Returns:**
char - Bokstavsdelen av programvaruversionen.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Hämtar eller anger bokstavskomponenten i programvaruversionen som är associerad med bilden. Denna egenskap representerar en ytterligare detalj inom versionssträngen och kan vara användbar för finare versionsdifferentiering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char | Bokstavsdelen av programvaruversionen. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Hämtar eller anger den numeriska komponenten av programvaruversionen som är associerad med bilden. Denna egenskap representerar den numeriska delen av programvaruversionens sträng och ger viktig information om versionen av programvaran som användes för att skapa eller modifiera bilden.

**Returns:**
int - Sifferdelen av programvaruversionen.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Hämtar eller anger den numeriska komponenten av programvaruversionen som är associerad med bilden. Denna egenskap representerar den numeriska delen av programvaruversionens sträng och ger viktig information om versionen av programvaran som användes för att skapa eller modifiera bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Sifferdelen av programvaruversionen. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Hantera programvaruidentifieringen (ID) som är associerad med bilden, med möjlighet att använda upp till 40 ASCII-tecken. Denna egenskap fungerar som ett sätt att unikt identifiera den programvara som användes för att skapa eller bearbeta bilden, och ger värdefull metadata för organisatoriska och informativa ändamål.

**Returns:**
java.lang.String - Programvaru-ID.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Hantera programvaruidentifieringen (ID) som är associerad med bilden, med möjlighet att använda upp till 40 ASCII-tecken. Denna egenskap fungerar som ett sätt att unikt identifiera den programvara som användes för att skapa eller bearbeta bilden, och ger värdefull metadata för organisatoriska och informativa ändamål.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Programvaru-ID. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Utför en likhetsjämförelse mellan två TGA-bilder, med beaktande av både den första och den andra bilden som är involverade i jämförelseprocessen. Denna metod underlättar en enkel bedömning av bildlikhet, vilket säkerställer korrekt analys och beslutsfattande inom bildbehandlingsarbetsflöden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Den första [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) som deltar i jämförelsen. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Den andra [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) som deltar i jämförelsen. |

**Returns:**
boolean - Jämförelsresultat.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Genomför en icke-likhetsjämförelse mellan två TGA-bilder, där både den första och den andra bilden som är involverade i jämförelsen utvärderas. Denna metod hjälper till att identifiera avvikelser eller skillnader mellan bilder, vilket möjliggör exakt analys och beslutsfattande i bildbehandlingsuppgifter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Den första [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) som deltar i jämförelsen. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Den andra [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) som deltar i jämförelsen. |

**Returns:**
boolean - Jämförelsresultat.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Skapar en duplikat av den aktuella instansen, genererar ett nytt objekt som klonar alla attribut och egenskaper från originalet. Denna metod underlättar skapandet av identiska kopior, säkerställer dataintegritet och bevarar tillståndet för den aktuella instansen utan att påverka originalobjektet.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Replikera egenskaperna från ett annat [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-objekt, skapa en ny instans med identiska attribut. Denna operation säkerställer bevarande av dataintegritet och underlättar duplicering av bildegenskaper utan att ändra källobjektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Annan [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


I en likhetsjämförelse utvärderar metoden om den aktuella [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instansen är lika med den andra bilden som tillhandahålls som parameter. Denna operation underlättar att avgöra om två TGA-bilder är identiska, vilket hjälper i bildbehandling och jämförelseuppgifter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Den andra [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) som deltar i jämförelsen. |

**Returns:**
boolean - Jämförelsresultat.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Metoden utför en likhetsjämförelse mellan den aktuella [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-instansen och ett annat objekt som tillhandahålls som parameter. Specifikt utvärderar den om egenskaperna hos den aktuella bilden matchar dem hos det andra objektet, vilket hjälper till att avgöra deras ekvivalens för jämförelsesyften inom bildbehandlingsarbetsflöden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | java.lang.Object | Den andra [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) som deltar i jämförelsen. |

**Returns:**
boolean - Jämförelsresultat.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Metoden "rotateFlip" möjliggör roterings- och vändningsoperationer på bilden. Den erbjuder mångsidig funktionalitet för att manipulera bildens orientering, vilket låter användare utföra rotationer och vändningar enligt deras krav, och underlättar effektiva bildbehandlingsuppgifter inom mjukvaruapplikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations-/vändningstypen. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för den aktuella instansen. Observera dock att denna hashkod kanske inte är lämplig att använda som nyckel, särskilt eftersom instanser av TgaImage-klassen inte är oföränderliga.

**Returns:**
int - Hashkod för denna instans.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden till ett specificerat område. Denna metod låter dig definiera ett rektangulärt område inom bilden som ska behållas, och bortse från resten. Denna operation är användbar för att fokusera på specifikt innehåll i bilden eller ta bort oönskade delar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beskär bilden genom att ange förskjutningar för vänster-, höger-, övre och nedre gränserna. Denna metod låter dig trimma bilden genom att flytta dess gränser oberoende längs de horisontella och vertikala axlarna. Genom att justera dessa förskjutningar kan du exakt kontrollera vilka delar av bilden som ska behållas, vilket effektivt beskär den till önskade dimensioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändra storlek på bilden samtidigt som du tillämpar specifika inställningar för att behålla önskade dimensioner och bildförhållande. Genom att anpassa bildinställningarna kan du effektivt ändra bildens storlek samtidigt som du säkerställer optimal visuell kvalitet och kompatibilitet med olika visningsenheter eller applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Justera bildens storlek med hjälp av en specificerad typ av storleksändring, som bestämmer hur omformningsoperationen utförs. Denna metod ger flexibilitet vid storleksändring av bilder enligt olika algoritmer eller tekniker. Genom att välja rätt typ av storleksändring kan du uppnå önskad balans mellan bildkvalitet och beräkningseffektivitet baserat på specifika krav eller preferenser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Roterar bilden kring dess centrum med en specificerad vinkel samtidigt som proportionell storleksändring upprätthålls och bakgrundsfärgen bevaras. Denna metod möjliggör exakt bildmanipulation och säkerställer att rotationen behåller visuell balans och konsistens med den angivna bakgrundsfärgen. Den är idealisk för uppgifter där exakt rotation kring centrum är nödvändig, såsom orienteringskorrigering eller konstnärliga justeringar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | Om den är inställd på `true` kommer bildens storlek att ändras enligt de roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna orörda och endast `` bildinnehållet roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

