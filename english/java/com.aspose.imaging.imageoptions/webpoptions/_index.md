---
title: WebPOptions
second_title: Aspose.Imaging for Java API Reference
description: Create modern WebP raster web images using our API featuring robust support for lossless and lossy compression as well as alpha channels and animation loops.
type: docs
weight: 53
url: /java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Create modern WebP raster web images using our API, featuring robust support for lossless and lossy compression, as well as alpha channels and animation loops. Enhance your web content with dynamic visuals while optimizing file sizes for improved loading speeds and user experience.
## Constructors

| Constructor | Description |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLossless()](#getLossless--) | Gets or sets a value indicating whether this `WebPOptions` is lossless. |
| [setLossless(boolean value)](#setLossless-boolean-) | Gets or sets a value indicating whether this `WebPOptions` is lossless. |
| [getQuality()](#getQuality--) | Gets or sets the quality. |
| [setQuality(float value)](#setQuality-float-) | Gets or sets the quality. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Gets or sets the animation loop count. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Gets or sets the animation loop count. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Gets or sets the color of the animation background. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Gets or sets the color of the animation background. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. These pages will be presented as animated frames in the output WEBP.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Gets or sets a value indicating whether this `WebPOptions` is lossless.

**Returns:**
boolean - `true` if lossless; otherwise, `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Gets or sets a value indicating whether this `WebPOptions` is lossless.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if lossless; otherwise, `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Gets or sets the quality.

**Returns:**
float - The quality.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Gets or sets the quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The quality. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Gets or sets the animation loop count.

**Returns:**
int - The animation loop count, 0 - infinity.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Gets or sets the animation loop count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The animation loop count, 0 - infinity. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Gets or sets the color of the animation background.

**Returns:**
long - The color of the animation background.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Gets or sets the color of the animation background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The color of the animation background. |

