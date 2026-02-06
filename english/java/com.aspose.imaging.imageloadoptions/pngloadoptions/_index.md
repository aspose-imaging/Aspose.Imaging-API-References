---
title: PngLoadOptions
second_title: Aspose.Imaging for Java API Reference
description: The png load options.
type: docs
weight: 18
url: /java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

The png load options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Initializes a new instance of the `PngLoadOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Gets or sets a value indicating whether [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Gets or sets a value indicating whether [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Initializes a new instance of the `PngLoadOptions` class.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Gets or sets a value indicating whether [strict mode].

**Returns:**
boolean - a value indicating whether [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Gets or sets a value indicating whether [strict mode].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
The following example shows how to read PNG file : a strict mode. The strict mode allows to find potential problems : PNG images, e.g. unrecognized data blocks, unexpected end of file. Such files still can be opened : default (non-strict) mode by Aspose.Imaging and by common viewers as well. However any attempts to open them : the strict mode cause a corresponding exception.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Default mode (non-strict) - successful reading.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Strict mode - ImageLoadException : Unexpected end of file.
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

