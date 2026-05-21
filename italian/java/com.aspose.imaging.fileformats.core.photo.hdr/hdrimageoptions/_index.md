---
title: "HdrImageOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni dell'immagine HDR"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/
---
**Inheritance:**
java.lang.Object
```
public class HdrImageOptions
```

Le opzioni dell'immagine HDR
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HdrImageOptions()](#HdrImageOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSmoothFactor()](#getSmoothFactor--) | Ottiene il fattore di levigatura. |
| [setSmoothFactor(int value)](#setSmoothFactor-int-) | Imposta il fattore di levigatura. |
| [getSampleCount()](#getSampleCount--) | Ottiene il conteggio dei campioni. |
| [setSampleCount(int value)](#setSampleCount-int-) | Imposta il conteggio dei campioni. |
| [getAlignImages()](#getAlignImages--) | Ottiene un valore che indica se [align images]. |
| [setAlignImages(boolean value)](#setAlignImages-boolean-) | Imposta un valore che indica se [align images]. |
### HdrImageOptions() {#HdrImageOptions--}
```
public HdrImageOptions()
```


### getSmoothFactor() {#getSmoothFactor--}
```
public final int getSmoothFactor()
```


Ottiene il fattore di levigatura.

Valore: Il fattore di levigatura.

**Returns:**
int - il fattore di levigatura.

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


Imposta il fattore di levigatura.

Valore: Il fattore di levigatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il fattore di levigatura. |


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


Ottiene il conteggio dei campioni.

Valore: Il conteggio dei campioni.

**Returns:**
int - il conteggio dei campioni.

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


Imposta il conteggio dei campioni.

Valore: Il conteggio dei campioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il conteggio dei campioni. |


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


Ottiene un valore che indica se [align images].

Valore: `true` se [align images]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [align images].

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


Imposta un valore che indica se [align images].

Valore: `true` se [align images]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [align images]. |


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

