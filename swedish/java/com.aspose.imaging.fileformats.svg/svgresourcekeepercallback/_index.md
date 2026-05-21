---
title: "SvgResourceKeeperCallback"
second_title: "Aspose.Imaging för Java API-referens"
description: "Resurs‑hållare‑callback"
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

Resurs‑hållare‑callback
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Kallas när bildresursen är klar för export. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Kallas när teckensnittresursen är klar för export. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Kallas när SVG-dokumentet är klart för export. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Kallas när bildresursen är klar för export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageData | byte[] | Resursdata. |
| imageType | int | Typ av bilden. |
| suggestedFileName | java.lang.String | Namn på den föreslagna filen. |
| useEmbeddedImage | boolean[] | Om den är satt till `true` måste den inbäddade bilden användas. |

**Returns:**
java.lang.String - Returnerar sökvägen till den sparade resursen. Sökvägen bör vara relativ till mål‑SVG‑dokumentet.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Kallas när teckensnittresursen är klar för export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | Alternativen för teckensnittslagring. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Kallas när SVG-dokumentet är klart för export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlData | byte[] | SVG‑data. |
| suggestedFileName | java.lang.String | Namn på den föreslagna filen. |

**Returns:**
java.lang.String - Returnerar sökvägen till det sparade SVG‑dokumentet.
