---
title: "ManualMaskingArgs"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Argumente dar, die für die manuelle Maskierungsmethode angegeben werden."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Stellt die Argumente dar, die für die manuelle Maskierungsmethode angegeben werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMask()](#getMask--) | Ruft die Menge der grafischen Formen ab, die die Maske bilden. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Setzt die Menge der grafischen Formen, die die Maske bilden. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
Dieses Beispiel zeigt, wie ein Rasterbild mithilfe von Bildmaskierung und einer manuellen Maske in mehrere Bilder zerlegt wird. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrund‑Bildobjekten zu trennen.
``` java
String dir = "c:\\temp\\";

// Definiere eine manuelle Maske.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Setze die manuelle Maske.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Verwende den manuellen Clustering‑Algorithmus.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Alle Formen, aus denen eine Maske besteht, werden zu einer einzigen kombiniert.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Eine maximal erwartete Größe des TrueColor‑mit‑Alpha‑PNG‑Bildes.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Jeder Cluster (Segment) wird in einer separaten PNG‑Datei gespeichert.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // Die Hintergrundfarbe wird orange sein.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Der Bereich des Quellbildes, auf den die Maskierung angewendet wird.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Erhalten Sie Bilder aus dem Maskierungsergebnis und speichern Sie sie als PNG.
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


Ruft die Menge der grafischen Formen ab, die die Maske bilden.

Wert: Die Maske.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Setzt die Menge der grafischen Formen, die die Maske bilden.

Wert: Die Maske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | die Menge der grafischen Formen, die die Maske bilden. |

