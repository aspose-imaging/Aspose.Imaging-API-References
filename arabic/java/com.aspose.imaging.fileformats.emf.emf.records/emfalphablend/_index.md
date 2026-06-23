---
title: "EmfAlphaBlend"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_ALPHABLEND يحدد نقلًا كتليًا للبكسلات من صورة نقطية مصدر إلى مستطيل هدف بما في ذلك بيانات الشفافية ألفا وفقًا لعملية دمج محددة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfAlphaBlend extends EmfBitmapRecordType
```

سجل EMR\_ALPHABLEND يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfAlphaBlend(EmfRecord source)](#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا للفئة `EmfAlphaBlend`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحد الهدف بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحد الهدف بوحدات الجهاز. |
| [getXDest()](#getXDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [setXDest(int value)](#setXDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [getYDest()](#getYDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [setYDest(int value)](#setYDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [getCxDest()](#getCxDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الهدف. |
| [setCxDest(int value)](#setCxDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الهدف. |
| [getCyDest()](#getCyDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الهدف. |
| [setCyDest(int value)](#setCyDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الهدف. |
| [getBlendFunction()](#getBlendFunction--) | يحصل أو يعيّن بنية تحدد عمليات الدمج للصور النقطية المصدر والهدف |
| [setBlendFunction(EmfBlendFunction value)](#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) | يحصل أو يعيّن بنية تحدد عمليات الدمج للصور النقطية المصدر والهدف |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getXformSr()](#getXformSr--) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [setXformSr(Matrix value)](#setXformSr-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للصورة النقطية المصدر. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للصورة النقطية المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getCxSrc()](#getCxSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [setCxSrc(int value)](#setCxSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [getCySrc()](#getCySrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [setCySrc(int value)](#setCySrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، والذي لا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_ALPHABLEND. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، والذي لا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_ALPHABLEND. |
### EmfAlphaBlend(EmfRecord source) {#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAlphaBlend(EmfRecord source)
```


يُنشئ مثيلًا جديدًا للفئة `EmfAlphaBlend`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحد الهدف بوحدات الجهاز.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحد الهدف بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الهدف.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الهدف.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الهدف. يجب أن تكون هذه القيمة أكبر من الصفر.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الهدف. يجب أن تكون هذه القيمة أكبر من الصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الهدف. يجب أن تكون هذه القيمة أكبر من الصفر.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الهدف. يجب أن تكون هذه القيمة أكبر من الصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBlendFunction() {#getBlendFunction--}
```
public EmfBlendFunction getBlendFunction()
```


يحصل أو يعيّن بنية تحدد عمليات الدمج للصور النقطية المصدر والهدف

**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### setBlendFunction(EmfBlendFunction value) {#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void setBlendFunction(EmfBlendFunction value)
```


يحصل أو يعيّن بنية تحدد عمليات الدمج للصور النقطية المصدر والهدف

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getXformSr() {#getXformSr--}
```
public Matrix getXformSr()
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSr(Matrix value) {#setXformSr-com.aspose.imaging.Matrix-}
```
public void setXformSr(Matrix value)
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


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للصورة النقطية المصدر.

القيمة: لون ARGB 32‑بت

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للصورة النقطية المصدر.

القيمة: لون ARGB 32‑بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

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
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. يجب أن تكون هذه القيمة أكبر من الصفر.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. يجب أن تكون هذه القيمة أكبر من الصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. يجب أن تكون هذه القيمة أكبر من الصفر.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. يجب أن تكون هذه القيمة أكبر من الصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_ALPHABLEND. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_ALPHABLEND. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

