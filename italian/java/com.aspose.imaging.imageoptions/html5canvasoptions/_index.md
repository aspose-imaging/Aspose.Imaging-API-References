---
title: "Html5CanvasOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea file HTML5 Canvas senza sforzo con la nostra API consentendoti di combinare senza soluzione di continuità elementi come moduli, testo, immagini, animazioni e collegamenti."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

Crea file HTML5 Canvas senza sforzo con la nostra API, consentendoti di combinare senza soluzione di continuità elementi come moduli, testo, immagini, animazioni e collegamenti. Approfitta di funzionalità robuste, tra cui il supporto per l'identificatore del tag e le impostazioni di codifica, garantendo prestazioni ottimali e personalizzazione per i tuoi progetti web.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Inizializza una nuova istanza della classe [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions). |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Inizializza una nuova istanza della classe `ImageOptionsBase`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Ottiene l'identificatore del tag canvas. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Imposta l'identificatore del tag canvas. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Restituisce un valore che indica se la pagina HTML completa deve essere generata. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Imposta un valore che indica se la pagina HTML completa deve essere generata. |
| [getEncoding()](#getEncoding--) | Restituisce la codifica. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Qualsiasi immagine vettoriale (SVG, WMF, CMX, ecc.) può essere usata come sorgente per le tue immagini Canvas. Il codice seguente crea un'immagine Canvas semplice.
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
Puoi incorporare più di un'immagine Canvas all'interno di una pagina HTML o aggiornare una pagina già esistente. Per farlo è necessario esportare solo il tag Canvas.
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


Inizializza una nuova istanza della classe [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions).

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Inizializza una nuova istanza della classe `ImageOptionsBase`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Le opzioni dell'immagine. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Ottiene l'identificatore del tag canvas.

**Returns:**
java.lang.String - l'identificatore del tag canvas.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Imposta l'identificatore del tag canvas.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | l'identificatore del tag canvas. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Restituisce un valore che indica se la pagina HTML completa deve essere generata.

**Returns:**
boolean - un valore che indica se la pagina HTML completa deve essere generata.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Imposta un valore che indica se la pagina HTML completa deve essere generata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se la pagina HTML completa deve essere generata. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
Puoi incorporare più di un'immagine Canvas all'interno di una pagina HTML o aggiornare una pagina già esistente. Per farlo è necessario esportare solo il tag Canvas.
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


Restituisce la codifica.

**Returns:**
java.nio.charset.Charset - la codifica.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Imposta la codifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset | la codifica. |

