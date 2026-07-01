---
title: "ConvolutionFilter"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة موفر مصفوفة النواة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

فئة موفر مصفوفة النواة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | يحصل على نواة الشحذ 3×3. |
| [getSharpen5x5()](#getSharpen5x5--) | يحصل على نواة الشحذ 5×5. |
| [getEmboss3x3()](#getEmboss3x3--) | يحصل على نواة النقش 3×3. |
| [getEmboss5x5()](#getEmboss5x5--) | يحصل على نواة النقش 5×5. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | يحصل على نواة تمويه الحركة. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | يحصل على النواة الغاوسية. |
| [getBlurBox(int size)](#getBlurBox-int-) | يحصل على نواة تمويه الصندوق. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | يحوّل `kernel` إلى نواة [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


يحصل على نواة الشحذ 3×3.

**Returns:**
double[][] - نواة الشحذ 3x3.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


يحصل على نواة الشحذ 5×5.

**Returns:**
double[][] - نواة الشحذ 5x5.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


يحصل على نواة النقش 3×3.

**Returns:**
double[][] - نواة النقش 3x3.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


يحصل على نواة النقش 5×5.

**Returns:**
double[][] - نواة النقش 5x5.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


يحصل على نواة تمويه الحركة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | حجم النواة. |
| angle | double | زاوية الحركة. |

**Returns:**
double[][] - نواة طمس الحركة.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


يحصل على النواة الغاوسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | حجم النواة. |
| sigma | double | قيمة سيغما في النطاق (0...]. |

**Returns:**
double[][] - النواة الغاوسية.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


يحصل على نواة تمويه الصندوق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | حجم النواة. |

**Returns:**
double[][] - نواة طمس الصندوق.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


يحوّل `kernel` إلى نواة [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نواة | double[][] | النواة. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - نواة [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).
