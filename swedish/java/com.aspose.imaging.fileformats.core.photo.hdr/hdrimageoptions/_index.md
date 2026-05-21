---
title: "HdrImageOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "HDR-bildalternativen"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/
---
**Inheritance:**
java.lang.Object
```
public class HdrImageOptions
```

HDR-bildalternativen
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [HdrImageOptions()](#HdrImageOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSmoothFactor()](#getSmoothFactor--) | Hämtar släthetsfaktorn. |
| [setSmoothFactor(int value)](#setSmoothFactor-int-) | Ställer in släthetsfaktorn. |
| [getSampleCount()](#getSampleCount--) | Hämtar antalet prover. |
| [setSampleCount(int value)](#setSampleCount-int-) | Ställer in antalet prover. |
| [getAlignImages()](#getAlignImages--) | Hämtar ett värde som indikerar om [align images]. |
| [setAlignImages(boolean value)](#setAlignImages-boolean-) | Ställer in ett värde som indikerar om [align images]. |
### HdrImageOptions() {#HdrImageOptions--}
```
public HdrImageOptions()
```


### getSmoothFactor() {#getSmoothFactor--}
```
public final int getSmoothFactor()
```


Hämtar släthetsfaktorn.

Värde: Släthetsfaktorn.

**Returns:**
int - släthetsfaktorn.

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


Ställer in släthetsfaktorn.

Värde: Släthetsfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | släthetsfaktorn. |


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


Hämtar antalet prover.

Värde: Antalet prover.

**Returns:**
int - antalet prover.

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


Ställer in antalet prover.

Värde: Antalet prover.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | antalet prover. |


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


Hämtar ett värde som indikerar om [align images].

Värde: `true` om [align images]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [align images].

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


Ställer in ett värde som indikerar om [align images].

Värde: `true` om [align images]; annars, `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [align images]. |


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

