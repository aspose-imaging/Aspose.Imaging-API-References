---
title: "EmfTransparentBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_TRANSPARENTBLT يحدد نقلًا كتليًا للبكسلات من صورة نقطية مصدر إلى مستطيل هدف مع معالجة لون محدد كشفاف، مع تمديد أو ضغط الناتج لتناسب أبعاد الهدف إذا لزم الأمر."
type: docs
weight: 154
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

سجل EMR\_TRANSPARENTBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى مستطيل هدف، مع معالجة لون محدد كشفاف، وتمديد أو ضغط الإخراج ليتناسب مع أبعاد الهدف إذا لزم الأمر.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfTransparentBlt`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [getXDest()](#getXDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setXDest(int value)](#setXDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getYDest()](#getYDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setYDest(int value)](#setYDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getCxDest()](#getCxDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة. |
| [setCxDest(int value)](#setCxDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة. |
| [getCyDest()](#getCyDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [setCyDest(int value)](#setCyDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد اللون في الصورة النقطية المصدر الذي يُعامل كشفاف. |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد اللون في الصورة النقطية المصدر الذي يُعامل كشفاف. |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getXformSrc()](#getXformSrc--) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | يحصل أو يعيّن كائن WMF ColorRef الذي يحدد لون الخلفية للصورة النقطية المصدر. |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | يحصل أو يعيّن كائن WMF ColorRef الذي يحدد لون الخلفية للصورة النقطية المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getCxSrc()](#getCxSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر. |
| [setCxSrc(int value)](#setCxSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر. |
| [getCySrc()](#getCySrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [setCySrc(int value)](#setCySrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من السجل EMR\_TRANSPARENTBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من السجل EMR\_TRANSPARENTBLT. |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfTransparentBlt`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد اللون في الصورة النقطية المصدر الذي يُعامل كشفاف.

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد اللون في الصورة النقطية المصدر الذي يُعامل كشفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


يحصل أو يعيّن كائن WMF ColorRef الذي يحدد لون الخلفية للصورة النقطية المصدر.

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


يحصل أو يعيّن كائن WMF ColorRef الذي يحدد لون الخلفية للصورة النقطية المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من السجل EMR\_TRANSPARENTBLT. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من السجل EMR\_TRANSPARENTBLT. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

