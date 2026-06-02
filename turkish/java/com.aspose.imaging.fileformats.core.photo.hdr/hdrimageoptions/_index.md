---
title: "HdrImageOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "hdr görüntü seçenekleri"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/
---
**Inheritance:**
java.lang.Object
```
public class HdrImageOptions
```

hdr görüntü seçenekleri
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HdrImageOptions()](#HdrImageOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSmoothFactor()](#getSmoothFactor--) | Pürüzsüzlük faktörünü alır. |
| [setSmoothFactor(int value)](#setSmoothFactor-int-) | Pürüzsüzlük faktörünü ayarlar. |
| [getSampleCount()](#getSampleCount--) | Örnek sayısını alır. |
| [setSampleCount(int value)](#setSampleCount-int-) | Örnek sayısını ayarlar. |
| [getAlignImages()](#getAlignImages--) | Bir değeri alır ve bu değer [align images] gösterip göstermediğini belirtir. |
| [setAlignImages(boolean value)](#setAlignImages-boolean-) | Bir değeri ayarlar ve bu değer [align images] gösterip göstermediğini belirtir. |
### HdrImageOptions() {#HdrImageOptions--}
```
public HdrImageOptions()
```


### getSmoothFactor() {#getSmoothFactor--}
```
public final int getSmoothFactor()
```


Pürüzsüzlük faktörünü alır.

Değer: Pürüzsüzlük faktörü.

**Returns:**
int - pürüzsüzlük faktörü.

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


Pürüzsüzlük faktörünü ayarlar.

Değer: Pürüzsüzlük faktörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | pürüzsüzlük faktörü. |


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


Örnek sayısını alır.

Değer: Örnek sayısı.

**Returns:**
int - örnek sayısı.

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


Örnek sayısını ayarlar.

Değer: Örnek sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | örnek sayısı. |


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


Bir değeri alır ve bu değer [align images] gösterip göstermediğini belirtir.

Değer: `true` eğer [align images]; aksi takdirde, `false`.

**Returns:**
boolean - [align images] olup olmadığını gösteren bir değer.

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


Bir değeri ayarlar ve bu değer [align images] gösterip göstermediğini belirtir.

Değer: `true` eğer [align images]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [align images] olup olmadığını gösteren bir değer. |


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

