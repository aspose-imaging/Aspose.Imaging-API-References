---
title: "VectorRasterizationOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de rasterisation vectorielle."
type: docs
weight: 52
url: /fr/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Les options de rasterisation vectorielle. Veuillez noter que [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) ne dérivera plus de [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) depuis la version 24.12 d'Aspose.Imaging.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Obtient le mode d'anticrénelage. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Définit le mode d'anticrénelage. |
| [getBorderX()](#getBorderX--) | Obtient ou définit la bordure X. |
| [setBorderX(float value)](#setBorderX-float-) | Obtient ou définit la bordure X. |
| [getBorderY()](#getBorderY--) | Obtient ou définit la bordure Y. |
| [setBorderY(float value)](#setBorderY-float-) | Obtient ou définit la bordure Y. |
| [getCenterDrawing()](#getCenterDrawing--) | Obtient une valeur indiquant si le dessin centré. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Définit une valeur indiquant si le dessin est centré. |
| [getPageHeight()](#getPageHeight--) | Obtient la hauteur de la page. |
| [setPageHeight(float value)](#setPageHeight-float-) | Définit la hauteur de la page. |
| [getPageSize()](#getPageSize--) | Obtient la taille de la page. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Définit la taille de la page. |
| [getPageWidth()](#getPageWidth--) | Obtient la largeur de la page. |
| [setPageWidth(float value)](#setPageWidth-float-) | Définit la largeur de la page. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient une couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit une couleur d'arrière-plan. |
| [getDrawColor()](#getDrawColor--) | Obtient une couleur de premier plan. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Définit une couleur de premier plan. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Obtient l'indice de rendu du texte. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Définit l'indice de rendu du texte. |
| [getPositioning()](#getPositioning--) | Obtient le positionnement. |
| [setPositioning(int value)](#setPositioning-int-) | Définit le positionnement. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Obtient le mappage de remplacement du texte. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Définit le mappage de remplacement du texte. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copie cette instance dans `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | Crée un clone superficiel de l'objet. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Obtient le mode d'anticrénelage.

**Returns:**
int - le mode d'anticrénelage.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Définit le mode d'anticrénelage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le mode d'anticrénelage. |


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

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Obtient ou définit la bordure X.

**Returns:**
float - La bordure X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Obtient ou définit la bordure X.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La bordure X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Obtient ou définit la bordure Y.

**Returns:**
float - La bordure Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Obtient ou définit la bordure Y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La bordure Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Obtient une valeur indiquant si le dessin centré.

**Returns:**
boolean - une valeur indiquant si le dessin est centré.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Définit une valeur indiquant si le dessin est centré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si le dessin centré. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Obtient la hauteur de la page.

**Returns:**
float - la hauteur de la page.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Définit la hauteur de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | la hauteur de la page. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Obtient la taille de la page.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Définit la taille de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | la taille de la page. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Le texte sera converti en formes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La taille de la page.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris les EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Le texte sera converti en formes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La taille de la page.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Définissez la marge horizontale
    rasterizationOptions.setBorderX(50);

    // Définissez la marge verticale
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Obtient la largeur de la page.

**Returns:**
float - la largeur de la page.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Définit la largeur de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | la largeur de la page. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient une couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Définit une couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | une couleur d'arrière-plan. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Le texte sera converti en formes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La taille de la page.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris les EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Le texte sera converti en formes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La taille de la page.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Définissez la marge horizontale
    rasterizationOptions.setBorderX(50);

    // Définissez la marge verticale
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Obtient une couleur de premier plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Définit une couleur de premier plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | une couleur de premier plan. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Obtient l'indice de rendu du texte.

Valeur : le conseil de rendu du texte.

**Returns:**
int - l'indice de rendu du texte.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Définit l'indice de rendu du texte.

Valeur : le conseil de rendu du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'indice de rendu du texte. |


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

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Obtient le positionnement.

Valeur : Le positionnement.

**Returns:**
int - le positionnement.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Définit le positionnement.

Valeur : Le positionnement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le positionnement. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Obtient le mappage de remplacement du texte.

Valeur : Le mappage de remplacement du texte.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - le mappage de remplacement du texte.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Définit le mappage de remplacement du texte.

Valeur : Le mappage de remplacement du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.HashMap<java.lang.String,java.lang.String> | le mappage de remplacement du texte. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copie cette instance dans `vectorRasterizationOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Les options de rasterisation vectorielle. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Crée un clone superficiel de l'objet.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
