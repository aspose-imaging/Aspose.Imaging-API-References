---
title: "OdgImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera OpenDocument Graphic ODG vektorbildfilformat med vårt API, som är allmänt använt av OpenOffice och LibreOffice Draw-applikationer för att lagra teckningselement i ett vektorformat."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Manipulera OpenDocument Graphic (ODG) vektorbildfilformat med vårt API, som är allmänt använt av OpenOffice och LibreOffice Draw-applikationer för att lagra teckningselement i ett vektorformat. Parsar dokument sömlöst, får åtkomst till sidor, ändrar storlek och roterar bilder, vilket säkerställer effektiv bearbetning och anpassning av ODG-filer för att möta dina specifika krav.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Starta en ny skapelse av [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage)-klassobjektet genom att initiera en ny instans. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Utformad för sömlös integration i mjukvarulösningar initierar [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage)-konstruktorn en ny instans genom att utnyttja en strömbehållare. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta enkelt filformatvärdet med den här användarvänliga egenskapen. |
| [getPages()](#getPages--) | Genom att hämta samlingen av sidor möjliggör denna egenskap åtkomst till hela mängden sidor som är kopplade till en bild. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att läsa in en bild.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // Kasta till OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Hämta alla sidor
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Utför någon bildbehandling.
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Starta en ny skapelse av [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage)-klassobjektet genom att initiera en ny instans. Utnyttja potentialen i en strömbehållare kombinerad med parametrar för inläsningsalternativ, och behåll en mångsidig konstruktor för att sömlöst ladda bilder. Denna konstruktor möjliggör effektiv bildhantering och erbjuder anpassningsbara inläsningskonfigurationer för förbättrad anpassningsförmåga och prestanda i olika scenarier.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömmen. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Inläsningsalternativen |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Utformad för sömlös integration i mjukvarulösningar initierar [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage)-konstruktorn en ny instans genom att utnyttja en strömbehållare. Denna metod säkerställer effektiv hantering av ODG-bilddata i mjukvarumiljöer, optimerar resursanvändning och underlättar strömlinjeformade arbetsflöden för bildbehandling.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta enkelt filformatvärdet med denna användarvänliga egenskap. Idealisk för utvecklare som söker snabb åtkomst till information om filformatet.

**Returns:**
long - ett värde för filformat
### getPages() {#getPages--}
```
public Image[] getPages()
```


Genom att hämta samlingen av sidor möjliggör denna egenskap åtkomst till hela mängden sidor som är kopplade till en bild. Genom att använda denna egenskap kan utvecklare iterera genom enskilda sidor, hämta specifika sidor baserat på deras index eller utföra batchoperationer på hela samlingen.

**Returns:**
com.aspose.imaging.Image[] - sidorna.
