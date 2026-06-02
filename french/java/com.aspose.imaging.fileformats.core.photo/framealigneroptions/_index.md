---
title: "FrameAlignerOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de l'alignement des cadres."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.core.photo/framealigneroptions/
---
**Inheritance:**
java.lang.Object
```
public class FrameAlignerOptions
```

Les options de l'alignement des cadres.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FrameAlignerOptions()](#FrameAlignerOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStandardImageIndex()](#getStandardImageIndex--) | Obtient l'index de l'image standard. |
| [setStandardImageIndex(int value)](#setStandardImageIndex-int-) | Définit l'index de l'image standard. |
| [getThreshold()](#getThreshold--) | Obtient le seuil. |
| [setThreshold(float value)](#setThreshold-float-) | Définit le seuil. |
| [getMaxOffset()](#getMaxOffset--) | Obtient le décalage maximal. |
| [setMaxOffset(int value)](#setMaxOffset-int-) | Définit le décalage maximal. |
| [getModifyImages()](#getModifyImages--) | Obtient une valeur indiquant si [modify image]. |
| [setModifyImages(boolean value)](#setModifyImages-boolean-) | Définit une valeur indiquant si [modify image]. |

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


Obtient l'index de l'image standard.

Valeur: l'index de l'image standard.

**Returns:**
int - l'index de l'image standard.

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


Définit l'index de l'image standard.

Valeur: l'index de l'image standard.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'index de l'image standard. |


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


Obtient le seuil.

Valeur: le seuil.

**Returns:**
float - le seuil.

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


Définit le seuil.

Valeur: le seuil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | le seuil. |


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


Obtient le décalage maximal.

Valeur: le décalage maximal.

**Returns:**
int - le décalage maximal.

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


Définit le décalage maximal.

Valeur: le décalage maximal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le décalage maximal. |


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


Obtient une valeur indiquant si [modify image].

Valeur: `true` si [modify image]; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si [modify image].

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


Définit une valeur indiquant si [modify image].

Valeur: `true` si [modify image]; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [modify image]. |


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

