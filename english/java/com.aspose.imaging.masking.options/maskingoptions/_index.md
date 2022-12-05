---
title: MaskingOptions
second_title: Aspose.Imaging for Java API Reference
description: Represents the common image masking options.
type: docs
weight: 16
url: /java/com.aspose.imaging.masking.options/maskingoptions/
---
**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Represents the common image masking options.
## Constructors

| Constructor | Description |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | The background object number |
## Methods

| Method | Description |
| --- | --- |
| [getMethod()](#getMethod--) | Gets the segmentation method. |
| [setMethod(int value)](#setMethod-int-) | Sets the segmentation method. |
| [getArgs()](#getArgs--) | Gets the arguments for segmentation algorithm. |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-) | Sets the arguments for segmentation algorithm. |
| [getExportOptions()](#getExportOptions--) | Gets the image export options. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.imaging.ImageOptionsBase-) | Sets the image export options. |
| [getMaskingArea()](#getMaskingArea--) | Gets the masking area. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.imaging.Rectangle-) | Sets the masking area. |
| [getDecompose()](#getDecompose--) | Gets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Gets the background replacement color. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.imaging.Color-) | Sets the background replacement color. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm. Image masking is an image processing technique that is used to split the background from the foreground image objects.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Set the number of clusters (separated objects). The default value is 2, the foreground object and the background.
    args.setNumberOfObjects(3);

    // Set the maximum number of iterations.
    args.setMaxIterationNumber(50);

    // Set the precision of segmentation method (optional)
    args.setPrecision(1);

    // Each cluster (segment) will be stored to a separate PNG file.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Use K-means clustering.
    // K-means clustering allows to split image into several independent clusters (segments).
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // The backgroung color will be orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
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


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method. Image masking is an image processing technique that is used to split the background from the foreground image objects.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Suggestion #1.
    // Analyze the image visually and set the area of interest. The result of segmentation will include only objects that will be completely located within this area.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Suggestion #2.
    // Analyze the image visually and set the points that belong to separated objects.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Each cluster (segment) will be stored to a separate PNG file.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Use GraphCut clustering.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // The background color will be orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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


## Example: Using a segment mask to speed up the segmentation process

``` java
// Masking export options
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Use GraphCut clustering.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// The background color will be transparent.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Reducing image size to speed up the segmentation process
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Getting the foreground mask
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Increase the size of the mask to the size of the original image
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applying the mask to the original image to obtain a foreground segment
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Masking export options
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Use GraphCut clustering.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// The background color will be orange.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Starting a session for the first time and saving to a file
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Resuming a masking session from a file
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analyze the image visually and set the points that belong to separated objects.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Explicit transfer of export options, since it is not serializable
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


The background object number

### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets the segmentation method.

Value: The segmentation method.

**Returns:**
int - the segmentation method.
### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Sets the segmentation method.

Value: The segmentation method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the segmentation method. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method. Image masking is an image processing technique that is used to split the background from the foreground image objects.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Suggestion #1.
    // Analyze the image visually and set the area of interest. The result of segmentation will include only objects that will be completely located within this area.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Suggestion #2.
    // Analyze the image visually and set the points that belong to separated objects.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Each cluster (segment) will be stored to a separate PNG file.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Use GraphCut clustering.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // The background color will be orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Gets the arguments for segmentation algorithm.

Value: The arguments for segmentation algorithm.

**Returns:**
[IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### setArgs(IMaskingArgs value) {#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Sets the arguments for segmentation algorithm.

Value: The arguments for segmentation algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | the arguments for segmentation algorithm. |

### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Gets the image export options.

Value: The image export options that will be used to create the resulting images.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - the image export options.
### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.imaging.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Sets the image export options.

Value: The image export options that will be used to create the resulting images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | the image export options. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method. Image masking is an image processing technique that is used to split the background from the foreground image objects.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Suggestion #1.
    // Analyze the image visually and set the area of interest. The result of segmentation will include only objects that will be completely located within this area.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Suggestion #2.
    // Analyze the image visually and set the points that belong to separated objects.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Each cluster (segment) will be stored to a separate PNG file.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Use GraphCut clustering.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // The background color will be orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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

### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Gets the masking area.

Value: The masking area which is a partial area of the source image. Rectangle.Empty value means full source image area.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the masking area.
### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.imaging.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Sets the masking area.

Value: The masking area which is a partial area of the source image. Rectangle.Empty value means full source image area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | the masking area. |

### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Gets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.

Value: `true` if decompose; otherwise, `false`.

**Returns:**
boolean - a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.
### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.

Value: `true` if decompose; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |

### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Gets the background replacement color.

Value: The background replacement color. This color will be used as background color in resulting images.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background replacement color.
### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.imaging.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Sets the background replacement color.

Value: The background replacement color. This color will be used as background color in resulting images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the background replacement color. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method. Image masking is an image processing technique that is used to split the background from the foreground image objects.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Suggestion #1.
    // Analyze the image visually and set the area of interest. The result of segmentation will include only objects that will be completely located within this area.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Suggestion #2.
    // Analyze the image visually and set the points that belong to separated objects.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Each cluster (segment) will be stored to a separate PNG file.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Use GraphCut clustering.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // The background color will be orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Create an instance of the ImageMasking class.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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

