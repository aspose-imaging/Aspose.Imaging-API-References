---
title: "HdrImageOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات صورة HDR."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/
---
**Inheritance:**
java.lang.Object
```
public class HdrImageOptions
```

خيارات صورة HDR.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HdrImageOptions()](#HdrImageOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSmoothFactor()](#getSmoothFactor--) | يحصل على معامل النعومة. |
| [setSmoothFactor(int value)](#setSmoothFactor-int-) | يضبط معامل النعومة. |
| [getSampleCount()](#getSampleCount--) | يحصل على عدد العينات. |
| [setSampleCount(int value)](#setSampleCount-int-) | يضبط عدد العينات. |
| [getAlignImages()](#getAlignImages--) | يحصل على قيمة تشير إلى ما إذا كان [align images]. |
| [setAlignImages(boolean value)](#setAlignImages-boolean-) | يضبط قيمة تشير إلى ما إذا كان [align images]. |
### HdrImageOptions() {#HdrImageOptions--}
```
public HdrImageOptions()
```


### getSmoothFactor() {#getSmoothFactor--}
```
public final int getSmoothFactor()
```


يحصل على معامل النعومة.

القيمة: معامل النعومة.

**Returns:**
int - معامل النعومة.

**Example: The example shows how HDR processing is carried out.**

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

### setSmoothFactor(int value) {#setSmoothFactor-int-}
```
public final void setSmoothFactor(int value)
```


يضبط معامل النعومة.

القيمة: معامل النعومة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | معامل النعومة. |


**Example: The example shows how HDR processing is carried out.**

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

### getSampleCount() {#getSampleCount--}
```
public final int getSampleCount()
```


يحصل على عدد العينات.

القيمة: عدد العينات.

**Returns:**
int - عدد العينات.

**Example: The example shows how HDR processing is carried out.**

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

### setSampleCount(int value) {#setSampleCount-int-}
```
public final void setSampleCount(int value)
```


يضبط عدد العينات.

القيمة: عدد العينات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | عدد العينات. |


**Example: The example shows how HDR processing is carried out.**

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

### getAlignImages() {#getAlignImages--}
```
public final boolean getAlignImages()
```


يحصل على قيمة تشير إلى ما إذا كان [align images].

القيمة: `true` إذا [align images]؛ وإلا `false`.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [align images].

**Example: The example shows how HDR processing is carried out.**

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

### setAlignImages(boolean value) {#setAlignImages-boolean-}
```
public final void setAlignImages(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [align images].

القيمة: `true` إذا [align images]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [align images]. |


**Example: The example shows how HDR processing is carried out.**

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

