---
title: FrameAligner
second_title: Aspose.Imaging for Java API Reference
description: The Align frames
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.core.photo/framealigner/
---
**Inheritance:**
java.lang.Object
```
public final class FrameAligner
```

The Align frames
## Methods

| Method | Description |
| --- | --- |
| [process(RasterImage[] images, FrameAlignerOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.FrameAlignerOptions-) | Processes the specified images. |

## Example: The example shows how to align a series of images relative to the first one.

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### process(RasterImage[] images, FrameAlignerOptions options) {#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.FrameAlignerOptions-}
```
public static List<Point> process(RasterImage[] images, FrameAlignerOptions options)
```


Processes the specified images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | The images. |
| options | [FrameAlignerOptions](../../com.aspose.imaging.fileformats.core.photo/framealigneroptions) | The options. |

**Returns:**
java.util.List<com.aspose.imaging.Point> - The list of offsets by images
