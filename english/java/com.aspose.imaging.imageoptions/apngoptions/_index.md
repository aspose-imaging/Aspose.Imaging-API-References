---
title: ApngOptions
second_title: Aspose.Imaging for Java API Reference
description: The animated PNG file format options
type: docs
weight: 10
url: /java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

The animated PNG file format options
## Constructors

| Constructor | Description |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Initializes a new instance of the [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) class. |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Initializes a new instance of the `ApngOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Gets the number of times to loop animation. 0 indicates infinite looping. |
| [setNumPlays(int value)](#setNumPlays-int-) | Sets the number of times to loop animation. 0 indicates infinite looping. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Gets the default frame duration. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Sets the default frame duration. |

## Example
The following example shows how to export to APNG file format.
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


## Example
The following example shows how to export apng APNG file format from other non-animated multi-page format.
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

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Gets the number of times to loop animation. 0 indicates infinite looping.

**Returns:**
int

**Example:**
The following example shows how to export to APNG file format.
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

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Sets the number of times to loop animation. 0 indicates infinite looping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example:**
The following example shows how to export to APNG file format.
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

