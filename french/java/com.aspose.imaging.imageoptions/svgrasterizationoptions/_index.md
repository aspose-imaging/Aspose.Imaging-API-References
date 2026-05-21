---
title: "SvgRasterizationOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de rasterisation SVG."
type: docs
weight: 46
url: /fr/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

Les options de rasterisation SVG.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Initialise une nouvelle instance de la classe `SvgRasterizationOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getScaleX()](#getScaleX--) | Obtient ou définit l'échelle x. |
| [setScaleX(float value)](#setScaleX-float-) | Obtient ou définit l'échelle x. |
| [getScaleY()](#getScaleY--) | Obtient ou définit l'échelle y. |
| [setScaleY(float value)](#setScaleY-float-) | Obtient ou définit l'échelle y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copie cette instance dans `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Initialise une nouvelle instance de la classe `SvgRasterizationOptions`.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Obtient ou définit l'échelle x.

**Returns:**
float - L'échelle x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Obtient ou définit l'échelle x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'échelle x. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger une image.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Pour rasteriser le SVG, nous devons spécifier les options de rasterisation.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Définissez la couleur par défaut d'un arrière-plan pour une image. La valeur par défaut est blanc.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Définir la taille de la page
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // L'anticrénelage est appliqué aux lignes et courbes ainsi qu'aux bords des zones remplies.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé sans hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Réduisez la taille de l'image 10 fois, c'est-à-dire que la taille de sortie sera de 10 % de la taille originale.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Enregistrer dans un fichier PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Obtient ou définit l'échelle y.

**Returns:**
float - L'échelle y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Obtient ou définit l'échelle y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'échelle y. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger une image.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Pour rasteriser le SVG, nous devons spécifier les options de rasterisation.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Définissez la couleur par défaut d'un arrière-plan pour une image. La valeur par défaut est blanc.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Définir la taille de la page
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // L'anticrénelage est appliqué aux lignes et courbes ainsi qu'aux bords des zones remplies.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé sans hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Réduisez la taille de l'image 10 fois, c'est-à-dire que la taille de sortie sera de 10 % de la taille originale.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Enregistrer dans un fichier PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copie cette instance dans `vectorRasterizationOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Les options de rasterisation vectorielle. |

