---
title: "FrameAlignerOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры выравнивателя кадров"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.core.photo/framealigneroptions/
---
**Inheritance:**
java.lang.Object
```
public class FrameAlignerOptions
```

Параметры выравнивателя кадров
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FrameAlignerOptions()](#FrameAlignerOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getStandardImageIndex()](#getStandardImageIndex--) | Получает индекс стандартного изображения. |
| [setStandardImageIndex(int value)](#setStandardImageIndex-int-) | Устанавливает индекс стандартного изображения. |
| [getThreshold()](#getThreshold--) | Получает порог. |
| [setThreshold(float value)](#setThreshold-float-) | Устанавливает порог. |
| [getMaxOffset()](#getMaxOffset--) | Получает максимальное смещение. |
| [setMaxOffset(int value)](#setMaxOffset-int-) | Устанавливает максимальное смещение. |
| [getModifyImages()](#getModifyImages--) | Получает значение, указывающее, следует ли [modify image]. |
| [setModifyImages(boolean value)](#setModifyImages-boolean-) | Устанавливает значение, указывающее, следует ли [modify image]. |

## Example: The example shows how to align a series of images relative to the first one.

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### FrameAlignerOptions() {#FrameAlignerOptions--}
```
public FrameAlignerOptions()
```


### getStandardImageIndex() {#getStandardImageIndex--}
```
public final int getStandardImageIndex()
```


Получает индекс стандартного изображения.

Значение: Индекс стандартного изображения.

**Returns:**
int - индекс стандартного изображения.

**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### setStandardImageIndex(int value) {#setStandardImageIndex-int-}
```
public final void setStandardImageIndex(int value)
```


Устанавливает индекс стандартного изображения.

Значение: Индекс стандартного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | индекс стандартного изображения. |


**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Получает порог.

Значение: Порог.

**Returns:**
float - порог.

**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Устанавливает порог.

Значение: Порог.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | порог. |


**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### getMaxOffset() {#getMaxOffset--}
```
public final int getMaxOffset()
```


Получает максимальное смещение.

Значение: Максимальное смещение.

**Returns:**
int - максимальное смещение.

**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### setMaxOffset(int value) {#setMaxOffset-int-}
```
public final void setMaxOffset(int value)
```


Устанавливает максимальное смещение.

Значение: Максимальное смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | максимальное смещение. |


**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### getModifyImages() {#getModifyImages--}
```
public final boolean getModifyImages()
```


Получает значение, указывающее, следует ли [modify image].

Значение: `true`, если [modify image]; иначе `false`.

**Returns:**
boolean - значение, указывающее, [modify image].

**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### setModifyImages(boolean value) {#setModifyImages-boolean-}
```
public final void setModifyImages(boolean value)
```


Устанавливает значение, указывающее, следует ли [modify image].

Значение: `true`, если [modify image]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, [modify image]. |


**Example: The example shows how to align a series of images relative to the first one.**

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

