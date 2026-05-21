---
title: "HdrProcessor"
second_title: "Aspose.Imaging för Java API-referens"
description: "HDR-processorn"
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/
---
**Inheritance:**
java.lang.Object
```
public final class HdrProcessor
```

HDR-processorn
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process(RasterImage[] images, HdrImageOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.hdr.HdrImageOptions-) | Bearbetar de angivna bilderna. |

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


Bearbetar de angivna bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | Bilderna. |
| options | [HdrImageOptions](../../com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions) | Alternativen. |

**Returns:**
int[] - Array av ARGB-pixlar
