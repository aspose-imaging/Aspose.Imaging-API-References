---
title: "EmfBitBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_BITBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى مستطيل هدف، ويمكن أن يكون ذلك مع نمط فرشاة وفقًا لعملية نقطية محددة."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfBitBlt extends EmfBitmapRecordType
```

سجل EMR\_BITBLT يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfBitBlt(EmfRecord source)](#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfBitBlt`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [getXDest()](#getXDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setXDest(int value)](#setXDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getYDest()](#getYDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setYDest(int value)](#setYDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getCxDest()](#getCxDest--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيلات المصدر والهدف. |
| [setCxDest(int value)](#setCxDest-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيلات المصدر والهدف. |
| [getCyDest()](#getCyDest--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيلات المصدر والهدف. |
| [setCyDest(int value)](#setCyDest-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيلات المصدر والهدف. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد رمز عملية الرستر. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد رمز عملية الرستر. |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getXformSrc()](#getXformSrc--) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يضبط مخزنًا يحتوي على صورة المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_BITBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يضبط مخزنًا يحتوي على صورة المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_BITBLT. |
### EmfBitBlt(EmfRecord source) {#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfBitBlt(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfBitBlt`.

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


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيلات المصدر والهدف.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيلات المصدر والهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيلات المصدر والهدف.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيلات المصدر والهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد رمز عملية النقطية. يعرّف هذا الرمز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف وربما نمط فرشاة، للحصول على اللون النهائي.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد رمز عملية النقطية. يعرّف هذا الرمز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف وربما نمط فرشاة، للحصول على اللون النهائي.

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

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر.

القيمة: لون ARGB 32‑بت

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر.

القيمة: لون ARGB 32‑بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يضبط مخزنًا يحتوي على صورة المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_BITBLT. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يضبط مخزنًا يحتوي على صورة المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_BITBLT. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

