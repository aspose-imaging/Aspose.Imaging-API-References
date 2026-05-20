---
title: "SvgResourceKeeperCallback"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il callback del gestore delle risorse"
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

Il callback del gestore delle risorse
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Chiamato quando la risorsa immagine è pronta per l'esportazione. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Chiamato quando la risorsa font è pronta per l'esportazione. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Chiamato quando il documento SVG è pronto per l'esportazione. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Chiamato quando la risorsa immagine è pronta per l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageData | byte[] | I dati della risorsa. |
| imageType | int | Tipo dell'immagine. |
| suggestedFileName | java.lang.String | Nome del file suggerito. |
| useEmbeddedImage | boolean[] | se impostato a `true` l'immagine incorporata deve essere usata. |

**Returns:**
java.lang.String - Restituisce il percorso della risorsa salvata. Il percorso dovrebbe essere relativo al documento SVG di destinazione.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Chiamato quando la risorsa font è pronta per l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | Le opzioni di memorizzazione del font. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Chiamato quando il documento SVG è pronto per l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlData | byte[] | I dati SVG. |
| suggestedFileName | java.lang.String | Nome del file suggerito. |

**Returns:**
java.lang.String - Restituisce il percorso del documento SVG salvato.
