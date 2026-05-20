---
title: "Html5CanvasOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie mühelos HTML5 Canvas-Dateien mit unserer API, die es Ihnen ermöglicht, Elemente wie Formulare, Text, Bilder, Animationen und Links nahtlos zu kombinieren."
type: docs
weight: 23
url: /de/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

Erstellen Sie mühelos HTML5 Canvas-Dateien mit unserer API, die es Ihnen ermöglicht, Elemente wie Formulare, Text, Bilder, Animationen und Links nahtlos zu kombinieren. Profitieren Sie von robusten Funktionen, einschließlich Unterstützung für Tag-Bezeichner und Kodierungseinstellungen, die optimale Leistung und Anpassbarkeit für Ihre Webprojekte gewährleisten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Initialisiert eine neue Instanz der [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) Klasse. |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Initialisiert eine neue Instanz der `ImageOptionsBase` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Ruft den Canvas-Tag-Bezeichner ab. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Setzt den Canvas-Tag-Bezeichner. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Liefert einen Wert, der angibt, ob die vollständige HTML‑Seite generiert werden soll. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Legt einen Wert fest, der angibt, ob die vollständige HTML‑Seite generiert werden soll. |
| [getEncoding()](#getEncoding--) | Liefert die Kodierung. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Legt die Kodierung fest. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Jedes Vektorbild (SVG, WMF, CMX usw.) kann als Quelle für Ihre Canvas‑Bilder verwendet werden. Der folgende Code erstellt ein einfaches Canvas‑Bild.
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
Sie können mehr als ein Canvas‑Bild in eine HTML‑Seite einbetten oder eine bereits vorhandene Seite aktualisieren. Dafür müssen Sie nur das Canvas‑Tag exportieren.
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


Initialisiert eine neue Instanz der [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) Klasse.

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Initialisiert eine neue Instanz der `ImageOptionsBase` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Die Bildoptionen. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Ruft den Canvas-Tag-Bezeichner ab.

**Returns:**
java.lang.String – der Canvas‑Tag‑Bezeichner.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Setzt den Canvas-Tag-Bezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | der Canvas‑Tag‑Bezeichner. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Liefert einen Wert, der angibt, ob die vollständige HTML‑Seite generiert werden soll.

**Returns:**
boolean – ein Wert, der angibt, ob die vollständige HTML‑Seite generiert werden soll.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Legt einen Wert fest, der angibt, ob die vollständige HTML‑Seite generiert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob die vollständige HTML‑Seite generiert werden soll. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
Sie können mehr als ein Canvas‑Bild in eine HTML‑Seite einbetten oder eine bereits vorhandene Seite aktualisieren. Dafür müssen Sie nur das Canvas‑Tag exportieren.
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


Liefert die Kodierung.

**Returns:**
java.nio.charset.Charset – die Kodierung.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Legt die Kodierung fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset | die Kodierung. |

