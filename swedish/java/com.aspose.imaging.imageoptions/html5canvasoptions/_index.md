---
title: "Html5CanvasOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa HTML5 Canvas-filer enkelt med vårt API som låter dig sömlöst kombinera element som formulär text bilder animationer och länkar."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

Skapa HTML5 Canvas-filer enkelt med vårt API, som låter dig sömlöst kombinera element som formulär, text, bilder, animationer och länkar. Dra nytta av robusta funktioner inklusive stöd för taggidentifierare och kodningsinställningar, vilket säkerställer optimal prestanda och anpassning för dina webbprojekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Initierar en ny instans av klassen [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions). |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Initierar en ny instans av klassen `ImageOptionsBase`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Hämtar canvas-tagidentifikatorn. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Ställer in canvas-tagidentifikatorn. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Hämtar ett värde som indikerar om hela HTML‑sidan ska genereras. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Ställer in ett värde som indikerar om hela HTML‑sidan ska genereras. |
| [getEncoding()](#getEncoding--) | Hämtar kodningen. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ställer in kodningen. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Vilken som helst vektorbild (SVG, WMF, CMX osv.) kan användas som källa för dina Canvas‑bilder. Följande kod skapar en enkel Canvas‑bild.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
Du kan bädda in mer än en Canvas‑bild i en HTML‑sida eller uppdatera en redan befintlig sida. För att göra det måste du exportera endast Canvas‑taggen.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


Initierar en ny instans av klassen [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions).

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Initierar en ny instans av klassen `ImageOptionsBase`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Bildalternativen. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Hämtar canvas-tagidentifikatorn.

**Returns:**
java.lang.String - canvas‑taggens identifierare.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Ställer in canvas-tagidentifikatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | canvas‑taggens identifierare. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Hämtar ett värde som indikerar om hela HTML‑sidan ska genereras.

**Returns:**
boolean - ett värde som indikerar om hela HTML‑sidan ska genereras.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Ställer in ett värde som indikerar om hela HTML‑sidan ska genereras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om hela HTML‑sidan ska genereras. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
Du kan bädda in mer än en Canvas‑bild i en HTML‑sida eller uppdatera en redan befintlig sida. För att göra det måste du exportera endast Canvas‑taggen.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Hämtar kodningen.

**Returns:**
java.nio.charset.Charset - kodningen.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Ställer in kodningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset | kodningen. |

