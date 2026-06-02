---
title: "ManualMaskingArgs"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar argumenten som specificeras för manuell maskeringsmetod"
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Representerar argumenten som specificeras för manuell maskeringsmetod
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMask()](#getMask--) | Hämtar mängden grafiska former som bildar masken. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Ställer in mängden grafiska former som bildar masken. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
Detta exempel visar hur man dekomponerar en rasterbild till flera bilder med hjälp av bildmaskering och en manuell mask. Bildmaskering är en bildbehandlingsteknik som används för att separera bakgrunden från förgrundens bildobjekt.
``` java
String dir = "c:\\temp\\";

// Definiera en manuell mask.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Ställ in den manuella masken.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Använd manuell klustringsalgoritm.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Alla former som utgör en mask kommer att kombineras till en.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // En maximal förväntad storlek på TrueColor med Alpha PNG-bild.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Varje kluster (segment) kommer att sparas i en separat PNG-fil.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // Bakgrundsfärgen blir orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Området i källbilden som maskning kommer att tillämpas på.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Hämta bilder från maskeringsresultatet och spara dem som PNG.
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


Hämtar mängden grafiska former som bildar masken.

Värde: Masken.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Ställer in mängden grafiska former som bildar masken.

Värde: Masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | den uppsättning grafiska former som bildar masken. |

