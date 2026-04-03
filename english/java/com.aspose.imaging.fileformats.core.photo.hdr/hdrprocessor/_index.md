---
title: HdrProcessor
second_title: Aspose.Imaging for Java API Reference
description: The HDR processor
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/
---
**Inheritance:**
java.lang.Object
```
public final class HdrProcessor
```

The HDR processor
## Methods

| Method | Description |
| --- | --- |
| [process(RasterImage[] images, HdrImageOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.hdr.HdrImageOptions-) | Processes the specified images. |

## Example: The example shows how HDR processing is carried out.

``` java
String image1 = "DSC_6912.JPG";
String image2 = "DSC_6913.JPG";
String image3 = "DSC_6914.JPG";
boolean align = true;
            
String resultFilePath = image1 + "_result.jpg";
RasterImage[] images = new RasterImage[3];
images[0] = (RasterImage)Image.load(image1);
images[1] = (RasterImage)Image.load(image2);
images[2] = (RasterImage)Image.load(image3);
            
try
{
    HdrImageOptions hdrOptions = new HdrImageOptions();
    hdrOptions.setSampleCount(100);
    hdrOptions.setSmoothFactor(200);
    hdrOptions.setAlignImages(align);
    int[] pixels = HdrProcessor.process(images, hdrOptions);
            
    try (PngImage image = new PngImage(images[0].getWidth(), images[0].getHeight()))
    {
        image.saveArgb32Pixels(image.getBounds(), pixels);
        image.save(resultFilePath);
    }
}
finally
{
    for (RasterImage image : images)
    {
        image.close();
    }
}
```

### process(RasterImage[] images, HdrImageOptions options) {#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.hdr.HdrImageOptions-}
```
public static int[] process(RasterImage[] images, HdrImageOptions options)
```


Processes the specified images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | The images. |
| options | [HdrImageOptions](../../com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions) | The options. |

**Returns:**
int[] - Array of ARGB pixels
