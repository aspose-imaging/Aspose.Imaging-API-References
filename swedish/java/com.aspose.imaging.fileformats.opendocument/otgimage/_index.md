---
title: "OtgImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bearbeta OpenDocument‑mall‑OTG‑ritningsbildfiler med vårt API som utnyttjar OpenDocument‑XML‑formatet med grafik‑innehåll för sömlös manipulation."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Bearbeta OpenDocument‑mall (OTG)‑ritningsbildfiler med vårt API, utnyttjande av OpenDocument‑XML‑formatet med grafik‑innehåll för sömlös manipulation. Analysera enkelt dokument, anpassa bakgrundsfärger och justera sidmått, vilket säkerställer optimal kontroll och flexibilitet för dina OTG‑vektorgrafikprojekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initiera ett nytt [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage)-objekt genom att tillhandahålla en strömbehållare och inläsningsalternativ. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Skapa ett nytt objekt av klassen [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) genom att tillhandahålla en strömbehållare. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Denna egenskap ger åtkomst till OTG-filformatet och erbjuder viktig insikt i vilken typ av data som är innesluten i bildfilen. |
| [getPages()](#getPages--) | Hämtar samlingen av sidor som är kopplade till bilden, vilket möjliggör för mjukvaruutvecklare att effektivt komma åt och manipulera varje enskild sida. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Initiera ett nytt [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage)-objekt genom att tillhandahålla en strömbehållare och inläsningsalternativ. Denna konstruktor ger utvecklare möjlighet att effektivt läsa in OTG-bilder från strömmar samtidigt som anpassade inläsningskonfigurationer specificeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömmen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Skapa ett nytt objekt av klassen [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) genom att tillhandahålla en strömbehållare. Denna konstruktor gör det möjligt för utvecklare att skapa OTG-bilder direkt från strömbehållare, vilket förenklar processen att arbeta med OTG-bilddata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Denna egenskap ger åtkomst till OTG-filformatet och erbjuder viktig insikt i vilken typ av data som är innesluten i bildfilen. Den fungerar som en central referenspunkt för mjukvaruutvecklare, vilket gör det möjligt för dem att effektivt hantera OTG-filer i sina applikationer. Genom att använda denna egenskap kan du fastställa det specifika formatet på bildfilen, vilket underlättar sömlös integration och manipulation av OTG-filer i deras mjukvarusystem.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Hämtar samlingen av sidor som är kopplade till bilden, vilket möjliggör för mjukvaruutvecklare att effektivt komma åt och manipulera varje enskild sida. Denna egenskap underlättar sömlös iteration genom sidorna för olika operationer, vilket förbättrar funktionaliteten och mångsidigheten i bildbehandlingsapplikationer.

**Returns:**
com.aspose.imaging.Image[] - sidorna.
