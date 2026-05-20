---
title: "EmfStretchDiBits"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_STRETCHDIBITS يحدد نقل كتلة من البكسلات من صورة البت المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة وفقًا لعملية رستر محددة، مع تمديد أو ضغط الإخراج ليتناسب مع أبعاد الوجهة إذا لزم الأمر."
type: docs
weight: 150
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

سجل EMR\_STRETCHDIBITS يحدد نقل كتلة من البكسلات من صورة مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الإخراج ليتناسب مع أبعاد الهدف إذا لزم الأمر.

يدعم هذا السجل صور المصدر بتنسيقات JPEG و PNG. يحدد حقل Compression في رأس صورة البت المصدر تنسيق الصورة. إذا اختلفت إشارات حقول الارتفاع والعرض للمصدر والوجهة، يحدد هذا السجل نسخة مرآة من صورة البت المصدر إلى الوجهة. أي أنه إذا كان لدى cxSrc و cxDest إشارات مختلفة، يتم تحديد صورة مرآة لصورة البت المصدر على محور x. وإذا كان لدى cySrc و cyDest إشارات مختلفة، يتم تحديد صورة مرآة على محور y.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfStretchDiBits`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [getXDest()](#getXDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setXDest(int value)](#setXDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getYDest()](#getYDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setYDest(int value)](#setYDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي x بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي x بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي y بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي y بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر. |
| [getCxSrc()](#getCxSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض بالبكسل للمستطيل المصدر. |
| [setCxSrc(int value)](#setCxSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض بالبكسل للمستطيل المصدر. |
| [getCySrc()](#getCySrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| [setCySrc(int value)](#setCySrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد رمز عملية الرستر. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد رمز عملية الرستر. |
| [getCxDest()](#getCxDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة. |
| [setCxDest(int value)](#setCxDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة. |
| [getCyDest()](#getCyDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [setCyDest(int value)](#setCyDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، ولا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_STRETCHDIBITS. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، ولا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_STRETCHDIBITS. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfStretchDiBits`.

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

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي x بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي x بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي y بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد إحداثي y بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض بالبكسل للمستطيل المصدر.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض بالبكسل للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد رمز عملية الرستر. تُعرّف هذه الرموز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الوجهة وربما نمط فرشاة، لتحقيق اللون النهائي.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد رمز عملية الرستر. تُعرّف هذه الرموز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الوجهة وربما نمط فرشاة، لتحقيق اللون النهائي.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، ولا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_STRETCHDIBITS. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، ولا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_STRETCHDIBITS. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

