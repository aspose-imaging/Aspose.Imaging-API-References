---
title: ManualMaskingArgs
second_title: Aspose.Imaging for Java API Reference
description: Represents the arguments that are specified for manual masking method
type: docs
weight: 15
url: /java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Represents the arguments that are specified for manual masking method
## Constructors

| Constructor | Description |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMask()](#getMask--) | Gets the set of graphic shapes that form mask. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Sets the set of graphic shapes that form mask. |

## Example
This example shows how to decompose a raster image into multiple images using image masking and a manual mask. Image masking is an image processing technique that is used to split the background from the foreground image objects.
``` java
String dir = "c:\\temp\\";

// Define a manual mask.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Set the manual mask.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Use manual clustering algorithm.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // All shapes making up a mask will be combined into one.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // A maximum expected size of the TrueColor with Alpha PNG image.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Each cluster (segment) will be stored to a separate PNG file.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // The backgroung color will be orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // The area of the source image that masking will be applied to.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtain images from masking result and save them to PNG.
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


Gets the set of graphic shapes that form mask.

Value: The mask.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Sets the set of graphic shapes that form mask.

Value: The mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | the set of graphic shapes that form mask. |

