---
title: "ResizeType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد نوع إعادة التحجيم."
type: docs
weight: 97
url: /ar/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

يحدد نوع إعادة التحجيم.
## الحقول

| حقل | الوصف |
| --- | --- |
| [None](#None) | لا يتم الحفاظ على البكسلات أثناء عملية تغيير الحجم. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | النقطة العليا اليسرى للصورة الجديدة ستتطابق مع النقطة العليا اليسرى للصورة الأصلية. |
| [RightTopToRightTop](#RightTopToRightTop) | النقطة العليا اليمنى للصورة الجديدة ستتطابق مع النقطة العليا اليمنى للصورة الأصلية. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | النقطة السفلية اليمنى للصورة الجديدة ستتطابق مع النقطة السفلية اليمنى للصورة الأصلية. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | النقطة السفلية اليسرى للصورة الجديدة ستتطابق مع النقطة السفلية اليسرى للصورة الأصلية. |
| [CenterToCenter](#CenterToCenter) | مركز الصورة الجديدة سيتطابق مع مركز الصورة الأصلية. |
| [LanczosResample](#LanczosResample) | إعادة أخذ عينات باستخدام خوارزمية لانكوز مع a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | إعادة العينة باستخدام خوارزمية أقرب جار. |
| [AdaptiveResample](#AdaptiveResample) | إعادة العينة باستخدام خوارزمية تكيفية تعتمد على الدالة النسبية الموزونة والمختلطة وخوارزميات استيفاء lanczos3. |
| [BilinearResample](#BilinearResample) | إعادة العينة باستخدام استيفاء ثنائي الخطية. |
| [HighQualityResample](#HighQualityResample) | إعادة العينة ذات الجودة العالية |
| [CatmullRom](#CatmullRom) | طريقة استيفاء مكعبية Catmull-Rom. |
| [CubicConvolution](#CubicConvolution) | طريقة استيفاء مكعبية Cubic Convolution |
| [CubicBSpline](#CubicBSpline) | طريقة استيفاء مكعبية CubicBSpline |
| [Mitchell](#Mitchell) | طريقة استيفاء مكعبية Mitchell |
| [SinC](#SinC) | طريقة استيفاء مكعبية Sinc (Lanczos3) |
| [Bell](#Bell) | طريقة استيفاء Bell |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
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


لا يتم الحفاظ على البكسلات أثناء عملية تغيير الحجم.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


النقطة العلوية اليسرى للصورة الجديدة ستتطابق مع النقطة العلوية اليسرى للصورة الأصلية. سيحدث القص إذا لزم الأمر.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


النقطة العلوية اليمنى للصورة الجديدة ستتطابق مع النقطة العلوية اليمنى للصورة الأصلية. سيحدث القص إذا لزم الأمر.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


النقطة السفلية اليمنى للصورة الجديدة ستتطابق مع النقطة السفلية اليمنى للصورة الأصلية. سيحدث القص إذا لزم الأمر.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


النقطة السفلية اليسرى للصورة الجديدة ستتطابق مع النقطة السفلية اليسرى للصورة الأصلية. سيحدث القص إذا لزم الأمر.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


مركز الصورة الجديدة سيتطابق مع مركز الصورة الأصلية. سيحدث القص إذا لزم الأمر.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


إعادة أخذ عينات باستخدام خوارزمية لانكوز مع a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


إعادة العينة باستخدام خوارزمية أقرب جار.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


إعادة العينة باستخدام خوارزمية تكيفية تعتمد على الدالة النسبية الموزونة والمختلطة وخوارزميات استيفاء lanczos3.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


إعادة العينة باستخدام استيفاء ثنائي الخطية. يُسمح بتمهيد الصورة مسبقًا لإزالة الضوضاء قبل إعادة العينة، عند الحاجة

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


إعادة العينة ذات الجودة العالية

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


طريقة استيفاء مكعبية Catmull-Rom.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


طريقة استيفاء مكعبية Cubic Convolution

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


طريقة استيفاء مكعبية CubicBSpline

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


طريقة استيفاء مكعبية Mitchell

### SinC {#SinC}
```
public static final int SinC
```


طريقة استيفاء مكعبية Sinc (Lanczos3)

### Bell {#Bell}
```
public static final int Bell
```


طريقة استيفاء Bell

