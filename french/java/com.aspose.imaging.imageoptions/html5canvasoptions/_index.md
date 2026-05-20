---
title: "Html5CanvasOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez des fichiers HTML5 Canvas facilement avec notre API vous permettant de combiner sans effort des éléments tels que des formulaires texte images animations et liens."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

Créez des fichiers HTML5 Canvas facilement avec notre API, vous permettant de combiner sans effort des éléments tels que des formulaires, du texte, des images, des animations et des liens. Bénéficiez de fonctionnalités robustes, notamment la prise en charge de l'identifiant de balise et des paramètres d'encodage, garantissant des performances optimales et une personnalisation pour vos projets web.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Initialise une nouvelle instance de la classe [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions). |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Initialise une nouvelle instance de la classe `ImageOptionsBase`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Obtient l'identifiant de balise du canvas. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Définit l'identifiant de balise du canvas. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Obtient une valeur indiquant si la page HTML complète doit être générée. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Définit une valeur indiquant si la page HTML complète doit être générée. |
| [getEncoding()](#getEncoding--) | Obtient le codage. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Définit le codage. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Toute image vectorielle (SVG, WMF, CMX, etc.) peut être utilisée comme source pour vos images Canvas. Le code suivant crée une image Canvas simple.
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
Vous pouvez intégrer plusieurs images Canvas dans une page HTML ou mettre à jour une page déjà existante. Pour ce faire, vous devez exporter uniquement la balise Canvas.
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


Initialise une nouvelle instance de la classe [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions).

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Initialise une nouvelle instance de la classe `ImageOptionsBase`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Les options d'image. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Obtient l'identifiant de balise du canvas.

**Returns:**
java.lang.String - l'identifiant de la balise canvas.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Définit l'identifiant de balise du canvas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | l'identifiant de la balise canvas. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Obtient une valeur indiquant si la page HTML complète doit être générée.

**Returns:**
boolean - une valeur indiquant si la page HTML complète doit être générée.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Définit une valeur indiquant si la page HTML complète doit être générée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si la page HTML complète doit être générée. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
Vous pouvez intégrer plusieurs images Canvas dans une page HTML ou mettre à jour une page déjà existante. Pour ce faire, vous devez exporter uniquement la balise Canvas.
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


Obtient le codage.

**Returns:**
java.nio.charset.Charset - le codage.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Définit le codage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset | le codage. |

