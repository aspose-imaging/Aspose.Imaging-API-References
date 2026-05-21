---
title: "FrameAlignerOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Optionen für den Frame‑Aligner"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.core.photo/framealigneroptions/
---
**Inheritance:**
java.lang.Object
```
public class FrameAlignerOptions
```

Die Optionen für den Frame‑Aligner
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FrameAlignerOptions()](#FrameAlignerOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStandardImageIndex()](#getStandardImageIndex--) | Ermittelt den Index des Standardbildes. |
| [setStandardImageIndex(int value)](#setStandardImageIndex-int-) | Setzt den Index des Standardbildes. |
| [getThreshold()](#getThreshold--) | Ermittelt den Schwellenwert. |
| [setThreshold(float value)](#setThreshold-float-) | Setzt den Schwellenwert. |
| [getMaxOffset()](#getMaxOffset--) | Ermittelt den maximalen Versatz. |
| [setMaxOffset(int value)](#setMaxOffset-int-) | Setzt den maximalen Versatz. |
| [getModifyImages()](#getModifyImages--) | Ermittelt einen Wert, der angibt, ob [modify image]. |
| [setModifyImages(boolean value)](#setModifyImages-boolean-) | Setzt einen Wert, der angibt, ob [modify image]. |

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


Ermittelt den Index des Standardbildes.

Wert: Der Index des Standardbildes.

**Returns:**
int - der Index des Standardbildes.

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


Setzt den Index des Standardbildes.

Wert: Der Index des Standardbildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Index des Standardbildes. |


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


Ermittelt den Schwellenwert.

Wert: Der Schwellenwert.

**Returns:**
float - der Schwellenwert.

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


Setzt den Schwellenwert.

Wert: Der Schwellenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | der Schwellenwert. |


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


Ermittelt den maximalen Versatz.

Wert: Der maximale Versatz.

**Returns:**
int - der maximale Versatz.

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


Setzt den maximalen Versatz.

Wert: Der maximale Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der maximale Versatz. |


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


Ermittelt einen Wert, der angibt, ob [modify image].

Wert: `true` wenn [modify image]; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob [modify image].

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


Setzt einen Wert, der angibt, ob [modify image].

Wert: `true` wenn [modify image]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [modify image]. |


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

