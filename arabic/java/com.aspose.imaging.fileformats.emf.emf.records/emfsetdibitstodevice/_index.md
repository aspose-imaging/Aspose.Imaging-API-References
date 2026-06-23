---
title: "EmfSetDiBitsToDevice"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETDIBITSTODEVICE يحدد نقل كتلة من البكسلات من خطوط المسح المحددة لصور البت المصدر إلى مستطيل الوجهة."
type: docs
weight: 124
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

السجل EMR\_SETDIBITSTODEVICE يحدد نقل كتلة من البكسلات من خطوط المسح المحددة في bitmap المصدر إلى المستطيل الوجهة.

يدعم هذا السجل صور المصدر بصيغة JPEG و PNG. حقل Compression في رأس صورة البت المصدر يحدد صيغة الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfSetDiBitsToDevice`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحد الهدف بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحد الهدف بوحدات الجهاز. |
| [getXDest()](#getXDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [setXDest(int value)](#setXDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [getYDest()](#getYDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [setYDest(int value)](#setYDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الهدف. |
| [getXSrc()](#getXSrc--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي x بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي x بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي y بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي y بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر. |
| [getCxSrc()](#getCxSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض بالبكسل للمستطيل المصدر. |
| [setCxSrc(int value)](#setCxSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض بالبكسل للمستطيل المصدر. |
| [getCySrc()](#getCySrc--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| [setCySrc(int value)](#setCySrc-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getIStartScan()](#getIStartScan--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد أول سطر مسح في المصفوفة. |
| [setIStartScan(int value)](#setIStartScan-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد أول سطر مسح في المصفوفة. |
| [getCScans()](#getCScans--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد عدد أسطر المسح. |
| [setCScans(int value)](#setCScans-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد عدد أسطر المسح. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يضبط مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_SETDIBITSTODEVICE. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يضبط مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_SETDIBITSTODEVICE. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfSetDiBitsToDevice`.

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

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي x بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي x بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي y بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد إحداثي y بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض بالبكسل للمستطيل المصدر.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض بالبكسل للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بتًا يحدد الارتفاع بالبكسل للمستطيل المصدر.

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

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد أول سطر مسح في المصفوفة.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد أول سطر مسح في المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد عدد أسطر المسح.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد عدد أسطر المسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يضبط مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_SETDIBITSTODEVICE. وبناءً على ذلك، الحقول في هذا المخزن التي تم تسميةها "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يضبط مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_SETDIBITSTODEVICE. وبناءً على ذلك، الحقول في هذا المخزن التي تم تسميةها "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

