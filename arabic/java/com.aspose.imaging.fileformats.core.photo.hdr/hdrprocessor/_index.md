---
title: "HdrProcessor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معالج HDR."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/
---
**Inheritance:**
java.lang.Object
```
public final class HdrProcessor
```

معالج HDR.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [process(RasterImage[] images, HdrImageOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.hdr.HdrImageOptions-) | يعالج الصور المحددة. |

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


يعالج الصور المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | الصور. |
| options | [HdrImageOptions](../../com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions) | الخيارات. |

**Returns:**
int[] - مصفوفة من بكسلات ARGB
