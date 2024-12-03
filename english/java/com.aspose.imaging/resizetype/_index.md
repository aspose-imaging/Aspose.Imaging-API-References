---
title: ResizeType
second_title: Aspose.Imaging for Java API Reference
description: Specifies the resize type.
type: docs
weight: 97
url: /java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Specifies the resize type.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | The pixels are not preserved during resize operation. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Left top point of the new image will coincide with the left top point of the original image. |
| [RightTopToRightTop](#RightTopToRightTop) | Right top point of the new image will coincide with the right top point of the original image. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Right bottom point of the new image will coincide with the right bottom point of the original image. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Left bottom point of the new image will coincide with the left bottom point of the original image. |
| [CenterToCenter](#CenterToCenter) | Center of the new image will coincide with the center of the original image. |
| [LanczosResample](#LanczosResample) | Resample using lanczos algorithm with a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Resample using nearest neighbour algorithm. |
| [AdaptiveResample](#AdaptiveResample) | Resample using adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation algorithms. |
| [BilinearResample](#BilinearResample) | Resample using bilinear interpolation. |
| [HighQualityResample](#HighQualityResample) | The high quality resample |
| [CatmullRom](#CatmullRom) | The Catmull-Rom cubic interpolation method. |
| [CubicConvolution](#CubicConvolution) | The Cubic Convolution interpolation method |
| [CubicBSpline](#CubicBSpline) | The CubicBSpline cubic interpolation method |
| [Mitchell](#Mitchell) | The Mitchell cubic interpolation method |
| [SinC](#SinC) | The Sinc (Lanczos3) cubic interpolation method |
| [Bell](#Bell) | The Bell interpolation method |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```

### None {#None}
```
public static final int None
```


The pixels are not preserved during resize operation.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Left top point of the new image will coincide with the left top point of the original image. Crop will occur if required.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Right top point of the new image will coincide with the right top point of the original image. Crop will occur if required.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Right bottom point of the new image will coincide with the right bottom point of the original image. Crop will occur if required.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Left bottom point of the new image will coincide with the left bottom point of the original image. Crop will occur if required.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Center of the new image will coincide with the center of the original image. Crop will occur if required.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Resample using lanczos algorithm with a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Resample using nearest neighbour algorithm.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Resample using adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation algorithms.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Resample using bilinear interpolation. Image pre-filtering is allowed to remove the noice before resample, when needed

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


The high quality resample

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


The Catmull-Rom cubic interpolation method.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


The Cubic Convolution interpolation method

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


The CubicBSpline cubic interpolation method

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


The Mitchell cubic interpolation method

### SinC {#SinC}
```
public static final int SinC
```


The Sinc (Lanczos3) cubic interpolation method

### Bell {#Bell}
```
public static final int Bell
```


The Bell interpolation method

