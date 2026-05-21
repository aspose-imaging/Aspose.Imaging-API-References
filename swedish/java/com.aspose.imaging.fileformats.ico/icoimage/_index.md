---
title: "IcoImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera ICO‑bildfiler utan ansträngning med vårt API som stödjer olika filformat och bildtyper inklusive PNG och BMP."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Manipulera ICO‑bildfiler utan ansträngning med vårt API, som stödjer olika filformat och bildtyper inklusive PNG och BMP. Anpassa inställningar för bitar per pixel och uppdatera bilddimensioner sömlöst, vilket säkerställer optimal representation och kompatibilitet för dina ikoner på olika plattformar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Starta ICO‑bildskapande utan ansträngning med klassen [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Utformad för enkelhet och effektivitet, klassen [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) ger dig möjlighet att skapa ICO‑bilder med lätthet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta filformatet utan ansträngning med denna egenskap, vilket möjliggör sömlös integration i ditt arbetsflöde. |
| [getPageCount()](#getPageCount--) | Få omedelbar insikt i dokumentets struktur med denna enkla egenskap. |
| [getPages()](#getPages--) | Hämta omfattande information om dokumentets sidor enkelt via denna egenskap. |
| [hasAlpha()](#hasAlpha--) | Bestäm om en alfakanal finns i detta fall med denna egenskap. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Utöka din ICO-bild genom att lägga till ett bildsidoinlägg och utnyttja [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Berika din ICO-bild enkelt genom att infoga ett bildsidoinlägg med standardinställningarna från [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diversifiera din ICO-bild enkelt genom att integrera ett bildinlägg anpassat efter dina behov med de angivna [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [removePage(int index)](#removePage-int-) | Finjustera din ICO-bild genom att ta bort ett specifikt bildinlägg placerat på den angivna `` i filen. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Starta skapandet av ICO-bilder enkelt med klassen [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). Denna konstruktor låter dig initiera nya instanser av ICO-bilder genom att ange bredd, höjd och parametrar för skapandealternativ. Med denna enkla konstruktor kan du anpassa ICO-bilder efter dina exakta specifikationer, vilket säkerställer sömlös kompatibilitet och visuell attraktionskraft på olika plattformar och enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | ICO-skapandealternativen. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


Utformad för enkelhet och effektivitet ger klassen [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) dig möjlighet att skapa ICO-bilder med lätthet. Denna konstruktor initierar en ny instans av klassen och ger en solid grund för dina bildmanipuleringsbehov. Oavsett om du utvecklar applikationer eller förbättrar användargränssnitt, förenklar klassen [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) ICO-bildhantering så att du kan fokusera på att leverera exceptionella upplevelser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | ICO-alternativen. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta filformatet enkelt med denna egenskap, vilket möjliggör sömlös integration i ditt arbetsflöde. Genom att använda denna egenskap får du tillgång till kritisk information om ditt fils format, vilket säkerställer kompatibilitet och effektiv bearbetning.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Få omedelbar insikt i dokumentets struktur med denna enkla egenskap. Genom att anropa denna egenskap hämtar du enkelt det totala antalet sidor som finns i filen.

**Returns:**
int - sidantalet.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Hämta omfattande information om dokumentets sidor enkelt via denna egenskap. Genom att komma åt denna egenskap får du tillgång till en samling eller array som innehåller alla sidor i dokumentet.

**Returns:**
com.aspose.imaging.Image[] - sidorna.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bestäm om en alfakanal finns i detta fall med denna egenskap. Den erbjuder ett snabbt sätt att kontrollera om bilden eller dokumentet innehåller en alfakanal, vilket är avgörande för olika bildbehandlings- och renderingsuppgifter. Idealisk för att säkerställa kompatibilitet och hantera transparenseffekter i bilder eller dokument.

**Returns:**
boolean – ett värde som indikerar om detta objekt har alfa.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Utöka din ICO-bild genom att lägga till ett bildsidoinlägg och utnyttja [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Denna metod integrerar sömlöst rasterbilder i din ICO-fil och konverterar dem till ett högkvalitativt 32-bitars PNG-format. Perfekt för att förbättra dina ICO-filer med rasterbilder samtidigt som optimal kompatibilitet och renderingskvalitet säkerställs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Berika din ICO-bild enkelt genom att infoga ett bildsidoinlägg med standardinställningarna från [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Denna metod konverterar smidigt den infogade bilden till ett 32-bitars PNG-format, vilket säkerställer kompatibilitet och högkvalitativ rendering i ICO-bilden. Perfekt för att sömlöst integrera PNG-bilder i dina ICO-filer med lätthet och effektivitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | Bilden. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Diversifiera din ICO-bild enkelt genom att integrera ett bildinlägg anpassat efter dina behov med de angivna [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Denna metod införlivar bilden sömlöst enligt dina anpassade alternativ, vilket säkerställer flexibilitet och precision i din ICO-fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | Bilden. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | ICO-alternativen. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Finjustera din ICO-bild genom att ta bort ett specifikt bildinlägg placerat på den angivna `` i filen. Denna metod ger exakt kontroll över din bildkomposition, så att du kan förfina din ICO-fil med lätthet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |

