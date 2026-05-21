---
title: "HdrImageOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры HDR‑изображения"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/
---
**Inheritance:**
java.lang.Object
```
public class HdrImageOptions
```

Параметры HDR‑изображения
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HdrImageOptions()](#HdrImageOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSmoothFactor()](#getSmoothFactor--) | Получает коэффициент сглаживания. |
| [setSmoothFactor(int value)](#setSmoothFactor-int-) | Устанавливает коэффициент сглаживания. |
| [getSampleCount()](#getSampleCount--) | Получает количество образцов. |
| [setSampleCount(int value)](#setSampleCount-int-) | Устанавливает количество образцов. |
| [getAlignImages()](#getAlignImages--) | Получает значение, указывающее, следует ли [align images]. |
| [setAlignImages(boolean value)](#setAlignImages-boolean-) | Устанавливает значение, указывающее, следует ли [align images]. |
### HdrImageOptions() {#HdrImageOptions--}
```
public HdrImageOptions()
```


### getSmoothFactor() {#getSmoothFactor--}
```
public final int getSmoothFactor()
```


Получает коэффициент сглаживания.

Значение: коэффициент сглаживания.

**Returns:**
int - коэффициент сглаживания.

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


Устанавливает коэффициент сглаживания.

Значение: коэффициент сглаживания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | коэффициент сглаживания. |


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


Получает количество образцов.

Значение: количество образцов.

**Returns:**
int - количество образцов.

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


Устанавливает количество образцов.

Значение: количество образцов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | количество образцов. |


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


Получает значение, указывающее, следует ли [align images].

Значение: `true`, если [align images]; иначе `false`.

**Returns:**
boolean — значение, указывающее, [align images].

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


Устанавливает значение, указывающее, следует ли [align images].

Значение: `true`, если [align images]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, [align images]. |


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

