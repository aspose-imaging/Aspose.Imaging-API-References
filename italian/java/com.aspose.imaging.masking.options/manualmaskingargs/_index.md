---
title: "ManualMaskingArgs"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta gli argomenti specificati per il metodo di mascheramento manuale"
type: docs
weight: 15
url: /it/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Rappresenta gli argomenti specificati per il metodo di mascheramento manuale
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMask()](#getMask--) | Ottiene l'insieme di forme grafiche che costituiscono la maschera. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Imposta l'insieme di forme grafiche che costituiscono la maschera. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
Questo esempio mostra come scomporre un'immagine raster in più immagini utilizzando il mascheramento dell'immagine e una maschera manuale. Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini utilizzata per separare lo sfondo dagli oggetti dell'immagine in primo piano.
``` java
String dir = "c:\\temp\\";

// Definisci una maschera manuale.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Imposta la maschera manuale.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utilizza l'algoritmo di clustering manuale.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Tutte le forme che compongono una maschera saranno combinate in una sola.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Una dimensione massima prevista dell'immagine PNG TrueColor con Alpha.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Ogni cluster (segmento) verrà salvato in un file PNG separato.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // Il colore di sfondo sarà arancione.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // L'area dell'immagine sorgente a cui verrà applicato il mascheramento.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Ottieni le immagini dal risultato del mascheramento e salvale in PNG.
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


Ottiene l'insieme di forme grafiche che costituiscono la maschera.

Valore: La maschera.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Imposta l'insieme di forme grafiche che costituiscono la maschera.

Valore: La maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | l'insieme di forme grafiche che costituiscono la maschera. |

