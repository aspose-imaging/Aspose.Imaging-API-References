---
title: "FrameAlignerOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات محاذاة الإطار."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.core.photo/framealigneroptions/
---
**Inheritance:**
java.lang.Object
```
public class FrameAlignerOptions
```

خيارات محاذاة الإطار.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FrameAlignerOptions()](#FrameAlignerOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStandardImageIndex()](#getStandardImageIndex--) | يحصل على فهرس الصورة القياسية. |
| [setStandardImageIndex(int value)](#setStandardImageIndex-int-) | يضبط فهرس الصورة القياسية. |
| [getThreshold()](#getThreshold--) | يحصل على العتبة. |
| [setThreshold(float value)](#setThreshold-float-) | يضبط العتبة. |
| [getMaxOffset()](#getMaxOffset--) | يحصل على الإزاحة القصوى. |
| [setMaxOffset(int value)](#setMaxOffset-int-) | يضبط الإزاحة القصوى. |
| [getModifyImages()](#getModifyImages--) | يحصل على قيمة تشير إلى ما إذا [modify image]. |
| [setModifyImages(boolean value)](#setModifyImages-boolean-) | يضبط قيمة تشير إلى ما إذا [modify image]. |

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


يحصل على فهرس الصورة القياسية.

القيمة: فهرس الصورة القياسية.

**Returns:**
int - فهرس الصورة القياسية.

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


يضبط فهرس الصورة القياسية.

القيمة: فهرس الصورة القياسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | فهرس الصورة القياسية. |


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


يحصل على العتبة.

القيمة: العتبة.

**Returns:**
float - العتبة.

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


يضبط العتبة.

القيمة: العتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العتبة. |


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


يحصل على الإزاحة القصوى.

القيمة: الحد الأقصى للإزاحة.

**Returns:**
int - الحد الأقصى للإزاحة.

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


يضبط الإزاحة القصوى.

القيمة: الحد الأقصى للإزاحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحد الأقصى للإزاحة. |


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


يحصل على قيمة تشير إلى ما إذا [modify image].

القيمة: `true` إذا [modify image]؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان [modify image].

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


يضبط قيمة تشير إلى ما إذا [modify image].

القيمة: `true` إذا [modify image]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [modify image]. |


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

