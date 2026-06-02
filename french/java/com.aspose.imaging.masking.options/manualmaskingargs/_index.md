---
title: "ManualMaskingArgs"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente les arguments qui sont spécifiés pour la méthode de masquage manuelle"
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Représente les arguments qui sont spécifiés pour la méthode de masquage manuelle
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMask()](#getMask--) | Obtient l'ensemble des formes graphiques qui constituent le masque. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Définit l'ensemble des formes graphiques qui constituent le masque. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
Cet exemple montre comment décomposer une image raster en plusieurs images en utilisant le masquage d'image et un masque manuel. Le masquage d'image est une technique de traitement d'image utilisée pour séparer l'arrière-plan des objets d'image au premier plan.
``` java
String dir = "c:\\temp\\";

// Définissez un masque manuel.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Définissez le masque manuel.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utilisez l'algorithme de regroupement manuel.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Toutes les formes composant un masque seront combinées en une seule.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Une taille maximale attendue de l'image PNG TrueColor avec Alpha.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Chaque cluster (segment) sera enregistré dans un fichier PNG séparé.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // La couleur d'arrière-plan sera orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // La zone de l'image source sur laquelle le masquage sera appliqué.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Diviser l'image source en plusieurs clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtenez les images à partir du résultat du masquage et enregistrez-les au format PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Blue hills.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

### ManualMaskingArgs() {#ManualMaskingArgs--}
```
public ManualMaskingArgs()
```


### getMask() {#getMask--}
```
public final GraphicsPath getMask()
```


Obtient l'ensemble des formes graphiques qui constituent le masque.

Valeur : le masque.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Définit l'ensemble des formes graphiques qui constituent le masque.

Valeur : le masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | l'ensemble des formes graphiques qui composent le masque. |

