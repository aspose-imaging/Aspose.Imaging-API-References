---
title: "WmfRasterizationOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de rasterisation Wmf."
type: docs
weight: 55
url: /fr/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Les options de rasterisation Wmf.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Initialise une nouvelle instance de la classe `WmfRasterizationOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Obtient ou définit le mode de rendu WMF. |
| [setRenderMode(int value)](#setRenderMode-int-) | Obtient ou définit le mode de rendu WMF. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copie ceci vers `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Initialise une nouvelle instance de la classe `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Obtient ou définit le mode de rendu WMF.

Valeur : le mode de rendu WMF.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Obtient ou définit le mode de rendu WMF.

Valeur : le mode de rendu WMF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copie ceci vers `vectorRasterizationOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

