---
title: "SvgResourceKeeperCallback"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le rappel du gestionnaire de ressources"
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

Le rappel du gestionnaire de ressources
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Appelé lorsque la ressource image est prête à être exportée. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Appelé lorsque la ressource police est prête à être exportée. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Appelé lorsque le document SVG est prêt à être exporté. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Appelé lorsque la ressource image est prête à être exportée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageData | byte[] | Les données de la ressource. |
| imageType | int | Type de l'image. |
| suggestedFileName | java.lang.String | Nom du fichier suggéré. |
| useEmbeddedImage | boolean[] | si défini sur `true`, l'image intégrée doit être utilisée. |

**Returns:**
java.lang.String - Retourne le chemin vers la ressource enregistrée. Le chemin doit être relatif au document SVG cible.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Appelé lorsque la ressource police est prête à être exportée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | Les options de stockage de police. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Appelé lorsque le document SVG est prêt à être exporté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlData | byte[] | Les données SVG. |
| suggestedFileName | java.lang.String | Nom du fichier suggéré. |

**Returns:**
java.lang.String - Retourne le chemin vers le document SVG enregistré.
