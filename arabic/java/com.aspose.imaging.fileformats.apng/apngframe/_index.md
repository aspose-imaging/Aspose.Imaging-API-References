---
title: "ApngFrame"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنشئ إطارات صور PNG المتحركة (APNG) من صور نقطية ذات صفحة واحدة باستخدام واجهة برمجة التطبيقات الخاصة بنا."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

أنشئ إطارات صور PNG المتحركة (APNG) من صور نقطية ذات صفحة واحدة باستخدام واجهة برمجة التطبيقات الخاصة بنا. قم بتعيين الرسوم المتحركة ومدة الإطار بسلاسة، برمجة عدد الإطارات، وضبط مستويات غاما والتباين، لضمان رسومات متحركة جذابة وقابلة للتخصيص وفق رؤيتك.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getFrameTime()](#getFrameTime--) | يحصل على مدة الإطار. |
| [setFrameTime(int value)](#setFrameTime-int-) | يضبط مدة الإطار. |
| [getFrameTop()](#getFrameTop--) | يحصل على إزاحة أعلى الإطار. |
| [getFrameLeft()](#getFrameLeft--) | يحصل على إزاحة يسار الإطار. |
| [getDisposalMethod()](#getDisposalMethod--) | يحصل على طريقة التخلص. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [hasAlpha()](#hasAlpha--) | احصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على ألفا. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على اللون الشفاف. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | اللون الشفاف. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يحصل على قيمة تشير إلى ما إذا كان لديها لون خلفية. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | قيمة تشير إلى ما إذا كان لديها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | لون الخلفية. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | يحصل على قيمة تشير إلى ما إذا كان [use alpha blending]. |
| [getFullFrame()](#getFullFrame--) | يحصل على الإطار الكامل. |
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

**Returns:**
int - عدد البتات لكل بكسل في الصورة.
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

**Returns:**
int - عرض الصورة.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


يحصل على مدة الإطار.

**Returns:**
int - مدة الإطار.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


يضبط مدة الإطار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | مدة الإطار. |

### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


يحصل على إزاحة أعلى الإطار.

**Returns:**
int - إزاحة أعلى الإطار.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


يحصل على إزاحة يسار الإطار.

**Returns:**
int - إزاحة يسار الإطار.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


يحصل على طريقة التخلص.

**Returns:**
int - طريقة التخلص.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


احصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على ألفا.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


يحصل على اللون الشفاف.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


اللون الشفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | اللون الشفاف. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


يحصل على قيمة تشير إلى ما إذا كان لديها لون خلفية.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان لديه لون خلفية.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


قيمة تشير إلى ما إذا كان لديها لون خلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان لديه لون خلفية. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


يحصل على قيمة تشير إلى ما إذا كان [use alpha blending].

القيمة: `true` إذا [use alpha blending]؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


يحصل على الإطار الكامل.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

