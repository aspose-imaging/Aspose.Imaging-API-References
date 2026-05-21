---
title: "EmfRasterizationOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de rasterisation Emf."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Les options de rasterisation Emf.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Obtient ou définit le mode de rendu. |
| [setRenderMode(int value)](#setRenderMode-int-) | Obtient ou définit le mode de rendu. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copie ceci vers `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Obtient ou définit le mode de rendu.

**Returns:**
int - Le mode de rendu.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Obtient ou définit le mode de rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de rendu. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copie ceci vers `vectorRasterizationOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

