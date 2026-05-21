---
title: "ResizeType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد نوع تغيير الحجم."
type: docs
weight: 97
url: /ar/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

يحدد نوع تغيير الحجم.
## الحقول

| حقل | الوصف |
| --- | --- |
| [None](#None) | لا يتم الحفاظ على البكسلات أثناء عملية تغيير الحجم. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | النقطة اليسرى العليا للصورة الجديدة ستتطابق مع النقطة اليسرى العليا للصورة الأصلية. |
| [RightTopToRightTop](#RightTopToRightTop) | النقطة اليمنى العليا للصورة الجديدة ستتطابق مع النقطة اليمنى العليا للصورة الأصلية. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | النقطة اليمنى السفلية للصورة الجديدة ستتطابق مع النقطة اليمنى السفلية للصورة الأصلية. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | النقطة اليسرى السفلية للصورة الجديدة ستتطابق مع النقطة اليسرى السفلية للصورة الأصلية. |
| [CenterToCenter](#CenterToCenter) | مركز الصورة الجديدة سيتطابق مع مركز الصورة الأصلية. |
| [LanczosResample](#LanczosResample) | إعادة أخذ عينات باستخدام خوارزمية لانكوز مع a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | إعادة أخذ عينات باستخدام خوارزمية أقرب جار. |
| [AdaptiveResample](#AdaptiveResample) | إعادة أخذ عينات باستخدام خوارزمية تكيفية تعتمد على دالة عقلانية موزونة وممزوجة وخوارزميات استيفاء لانكوز3. |
| [BilinearResample](#BilinearResample) | إعادة أخذ عينات باستخدام استيفاء ثنائي الخطية. |
| [HighQualityResample](#HighQualityResample) | إعادة أخذ عينات عالية الجودة. |
| [CatmullRom](#CatmullRom) | طريقة استيفاء مكعبية Catmull-Rom. |
| [CubicConvolution](#CubicConvolution) | طريقة استيفاء Cubic Convolution. |
| [CubicBSpline](#CubicBSpline) | طريقة استيفاء CubicBSpline. |
| [Mitchell](#Mitchell) | طريقة استيفاء مكعبية Mitchell. |
| [SinC](#SinC) | طريقة الاستيفاء المكعب Sinc (Lanczos3) |
| [Bell](#Bell) | طريقة الاستيفاء Bell |

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


النقطة العليا اليسرى للصورة الجديدة ستتطابق مع النقطة العليا اليسرى للصورة الأصلية. سيتم القص إذا لزم الأمر.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


النقطة العليا اليمنى للصورة الجديدة ستتطابق مع النقطة العليا اليمنى للصورة الأصلية. سيتم القص إذا لزم الأمر.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


النقطة السفلية اليمنى للصورة الجديدة ستتطابق مع النقطة السفلية اليمنى للصورة الأصلية. سيتم القص إذا لزم الأمر.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


النقطة السفلية اليسرى للصورة الجديدة ستتطابق مع النقطة السفلية اليسرى للصورة الأصلية. سيتم القص إذا لزم الأمر.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


مركز الصورة الجديدة سيتطابق مع مركز الصورة الأصلية. سيتم القص إذا لزم الأمر.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


إعادة أخذ عينات باستخدام خوارزمية لانكوز مع a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


إعادة أخذ عينات باستخدام خوارزمية أقرب جار.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


إعادة أخذ عينات باستخدام خوارزمية تكيفية تعتمد على دالة عقلانية موزونة وممزوجة وخوارزميات استيفاء لانكوز3.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


إعادة أخذ عينات باستخدام الاستيفاء الثنائي الخط. يُسمح بتمهيد الصورة لإزالة الضوضاء قبل إعادة أخذ العينات عند الحاجة.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


إعادة أخذ عينات عالية الجودة.

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


طريقة استيفاء مكعبية Catmull-Rom.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


طريقة استيفاء Cubic Convolution.

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


طريقة استيفاء CubicBSpline.

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


طريقة استيفاء مكعبية Mitchell.

### SinC {#SinC}
```
public static final int SinC
```


طريقة الاستيفاء المكعب Sinc (Lanczos3)

### Bell {#Bell}
```
public static final int Bell
```


طريقة الاستيفاء Bell

