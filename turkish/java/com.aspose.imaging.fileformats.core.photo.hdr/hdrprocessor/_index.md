---
title: "HdrProcessor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "HDR işlemcisi"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/
---
**Inheritance:**
java.lang.Object
```
public final class HdrProcessor
```

HDR işlemcisi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process(RasterImage[] images, HdrImageOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.hdr.HdrImageOptions-) | Belirtilen görüntüleri işler. |

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


Belirtilen görüntüleri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | Görüntüler. |
| options | [HdrImageOptions](../../com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions) | Seçenekler. |

**Returns:**
int[] - ARGB piksellerinin dizisi
