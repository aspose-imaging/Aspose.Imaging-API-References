---
title: "SvgRasterizationOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di rasterizzazione SVG."
type: docs
weight: 46
url: /it/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

Le opzioni di rasterizzazione SVG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Inizializza una nuova istanza della classe `SvgRasterizationOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getScaleX()](#getScaleX--) | Ottiene o imposta la scala x. |
| [setScaleX(float value)](#setScaleX-float-) | Ottiene o imposta la scala x. |
| [getScaleY()](#getScaleY--) | Ottiene o imposta la scala y. |
| [setScaleY(float value)](#setScaleY-float-) | Ottiene o imposta la scala y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia questa istanza in `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Inizializza una nuova istanza della classe `SvgRasterizationOptions`.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Ottiene o imposta la scala x.

**Returns:**
float - La scala x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Ottiene o imposta la scala x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La scala x. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Usare Aspose.Imaging.Image.Load è un modo unificato per caricare un'immagine.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Per rasterizzare SVG è necessario specificare le opzioni di rasterizzazione.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Imposta il colore predefinito di sfondo per un'immagine. Il valore predefinito è bianco.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Imposta la dimensione della pagina
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // L'anti-aliasing è applicato a linee, curve e ai bordi delle aree riempite.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Riduci la dimensione dell'immagine di 10 volte, cioè la dimensione di output sarà il 10% della dimensione originale.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Salva in un file PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Ottiene o imposta la scala y.

**Returns:**
float - La scala y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Ottiene o imposta la scala y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La scala y. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Usare Aspose.Imaging.Image.Load è un modo unificato per caricare un'immagine.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Per rasterizzare SVG è necessario specificare le opzioni di rasterizzazione.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Imposta il colore predefinito di sfondo per un'immagine. Il valore predefinito è bianco.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Imposta la dimensione della pagina
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // L'anti-aliasing è applicato a linee, curve e ai bordi delle aree riempite.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Riduci la dimensione dell'immagine di 10 volte, cioè la dimensione di output sarà il 10% della dimensione originale.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Salva in un file PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia questa istanza in `vectorRasterizationOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Le opzioni di rasterizzazione vettoriale. |

