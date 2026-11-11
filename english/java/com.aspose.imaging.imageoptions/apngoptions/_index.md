---
title: ApngOptions
second_title: Aspose.Imaging for Java API Reference
description: The API for Animated PNG Animated Portable Network Graphics image file format creation is a dynamic tool for developers seeking to generate captivating animated images.
type: docs
weight: 10
url: /java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)

**All Implemented Interfaces:**
com.aspose.internal.imageoptions.interfaces.IHasAnimationLoopCount
```
public class ApngOptions extends PngOptions implements IHasAnimationLoopCount
```

The API for Animated PNG (Animated Portable Network Graphics) image file format creation is a dynamic tool for developers seeking to generate captivating animated images. With customizable options such as frame duration and the number of times to loop, this API allows for fine-tuning animated content according to specific needs. Whether creating engaging web graphics or interactive visuals, you can leverage this API to seamlessly incorporate APNG images with precise control over animation parameters.
## Constructors

| Constructor | Description |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Initializes a new instance of the [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) class. |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Initializes a new instance of the `ApngOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getLoopCount()](#getLoopCount--) | Gets the number of times to loop animation. |
| [setLoopCount(int value)](#setLoopCount-int-) | Sets the number of times to loop animation. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Gets the default frame duration. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Sets the default frame duration. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Export to APNG animation with unlimited animation cycles as default
    image.save("Animation1.webp.png", new ApngOptions());
    // Setting up animation cycles
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Setting up the default frame duration
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Initializes a new instance of the [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) class.

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Initializes a new instance of the `ApngOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | The PNG options. |

### getLoopCount() {#getLoopCount--}
```
public final int getLoopCount()
```


Gets the number of times to loop animation. Default is -1 meaning the value may be inherited from saved image or will be set to 0 (infinite looping).

**Returns:**
int - the number of times to loop animation.
### setLoopCount(int value) {#setLoopCount-int-}
```
public final void setLoopCount(int value)
```


Sets the number of times to loop animation. Default is -1 meaning the value may be inherited from saved image or will be set to 0 (infinite looping).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the number of times to loop animation. |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Gets the default frame duration.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Sets the default frame duration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

