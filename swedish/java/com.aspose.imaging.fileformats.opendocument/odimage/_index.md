---
title: "OdImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Det öppna dokumentet"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

Det öppna dokumentet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Hämtar standardsidan som är kopplad till bilden och ger nödvändig åtkomst till huvudsidan i bildsamlingen. |
| [isCached()](#isCached--) | Erhåller ett booleskt värde som indikerar om objektets data för närvarande är cachad, vilket eliminerar behovet av att läsa data. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bitar per pixel för bilden. |
| [getPageCount()](#getPageCount--) | Hämtar det totala antalet sidor i bilden. |
| [getOdMetadata()](#getOdMetadata--) | Hämtar metadata som är specifik för OpenDocument-filer. |
| [getRecords()](#getRecords--) | Hämtar OpenDocument-posterna som lagras i bilden. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Hämtar standardsidan som är associerad med bilden och ger väsentlig åtkomst till huvudsidan i bildsamlingen. Denna egenskap förenklar navigering och manipulation av bilddata, vilket förbättrar effektiviteten i mjukvaruutvecklingsarbetsflöden.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Erhåller ett booleskt värde som indikerar om objektets data för närvarande är cachad, vilket eliminerar behovet av dataläsning. Denna egenskap fungerar som en optimeringsindikator och förbättrar prestanda genom att minimera redundanta dataåtkomstoperationer.

**Returns:**
boolean - ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bitar per pixel för bilden. Denna egenskap ger insikt i detaljnivån och färgdjupet som representeras i bilden, vilket underlättar olika bildbehandlingsuppgifter och optimeringar.

**Returns:**
int - bildens bitar per pixel-antal.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämtar det totala antalet sidor i bilden. Denna egenskap är avgörande för applikationer som hanterar flersidiga bilder och gör det möjligt att exakt bestämma antalet sidor som är tillgängliga för bearbetning eller visning.

**Returns:**
int - sidantalet.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


Hämtar metadata som är specifik för OpenDocument-filer. Denna egenskap möjliggör åtkomst till väsentlig information som är inbäddad i OD-filer, vilket underlättar olika operationer såsom extraktion, modifiering eller analys av metadata.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Hämtar OpenDocument-posterna som lagras i bilden. Denna egenskap ger åtkomst till specifika strukturerade dataelement som är inbäddade i OpenDocument-filer, vilket underlättar hämtning eller manipulation av relevant information för vidare bearbetning eller analys.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - posterna.
