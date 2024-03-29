---
title: AssumedObjectData
second_title: Aspose.Imaging for Java API Reference
description: The assumed objects data.
type: docs
weight: 10
url: /java/com.aspose.imaging.masking.options/assumedobjectdata/
---
**Inheritance:**
java.lang.Object
```
public class AssumedObjectData
```

The assumed object's data. Includes object's type and area.
## Constructors

| Constructor | Description |
| --- | --- |
| [AssumedObjectData()](#AssumedObjectData--) | Initializes a new instance of the [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) class. |
| [AssumedObjectData(int type, Rectangle bounds)](#AssumedObjectData-int-com.aspose.imaging.Rectangle-) | Initializes a new instance of the [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) class. |
| [AssumedObjectData(String type, Rectangle bounds)](#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-) | Initializes a new instance of the [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets the object's type. |
| [setType(int value)](#setType-int-) | Sets the object's type. |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Sets the object's bounds. |

## Example: Saving image masking result with feathering based on image size.
Saving image masking result with feathering based on image size. Image masking is performed using auto calculated default strokes. Additionally the data of the two assumed objects is also specified in the AssumedObjects property of the AutoMaskingGraphCutOptions.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// release resources
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration. Image masking is performed using auto calculated default strokes. Additionally the data of the two assumed objects is also specified in the AssumedObjects property of the AutoMaskingGraphCutOptions. After getting initial masking result, applied background/foreground strokes are modified and another masking iteration is performed.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// At this point applied foreground/background strokes can be analyzed and based on it additional
// foreground/background strokes can be manually provided.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// release resources
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Re-using AutoMaskingGraphCutOptions there is no need to perform default strokes calculations second time.
    options.setCalculateDefaultStrokes(false);
    // When both default strokes and ObjectsPoints in the Args property of AutoMaskingArgs are provided, Point arrays are end up combined.
    // The first ObjectsPoints array is considered to be a background points array and
    // the second ObjectsPoints array is considered to be a foreground points array.
    // When both DefaultObjectsRectangles and ObjectsRectangles in the Args property of AutoMaskingArgs are provided,
    // only the array from the Args is being used.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// release resources
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration. Image masking is performed using auto calculated default strokes. Additionally the data of the two assumed objects is also specified in the AssumedObjects property of the AutoMaskingGraphCutOptions. After getting initial masking result, applied background/foreground strokes are modified and another masking iteration is performed using new GraphCutMaskingOptions instance.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// At this point applied foreground/background strokes can be analyzed and based on it additional
// foreground/background strokes can be manually provided.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// release resources
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// release resources
for (MaskingResult res : results)
{
    res.close();
}
```

### AssumedObjectData() {#AssumedObjectData--}
```
public AssumedObjectData()
```


Initializes a new instance of the [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) class.

### AssumedObjectData(int type, Rectangle bounds) {#AssumedObjectData-int-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(int type, Rectangle bounds)
```


Initializes a new instance of the [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The object's type. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | The object's bounds. |

### AssumedObjectData(String type, Rectangle bounds) {#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(String type, Rectangle bounds)
```


Initializes a new instance of the [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.String | The object's type. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | The object's bounds. |

### getType() {#getType--}
```
public final int getType()
```


Gets the object's type.

**Returns:**
int - the object's type.
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Sets the object's type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the object's type. |

### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Gets the object's bounds.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the object's bounds.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Sets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | the object's bounds. |

