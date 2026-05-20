---
title: "WmfSetDibToDev"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل META_SETDIBTODEV يحدد كتلة من البكسلات في سياق جهاز التشغيل باستخدام بيانات ألوان مستقلة عن الجهاز."
type: docs
weight: 75
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

السجل META\_SETDIBTODEV يحدد كتلة من البكسلات في سياق جهاز التشغيل باستخدام بيانات ألوان مستقلة عن الجهاز. مصدر بيانات اللون هو DIB.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | يحصل أو يعيّن استخدام اللون. |
| [setColorUsage(int value)](#setColorUsage-int-) | يحصل أو يعيّن استخدام اللون. |
| [getScanCount()](#getScanCount--) | يحصل أو يضبط عدد المسحات. |
| [setScanCount(int value)](#setScanCount-int-) | يحصل أو يضبط عدد المسحات. |
| [getStartScan()](#getStartScan--) | الحصول أو تعيين مسح البداية. |
| [setStartScan(int value)](#setStartScan-int-) | الحصول أو تعيين مسح البداية. |
| [getDibPos()](#getDibPos--) | الحصول أو تعيين موضع الـ dib. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | الحصول أو تعيين موضع الـ dib. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن الارتفاع. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن الارتفاع. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن العرض. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن العرض. |
| [getDestPos()](#getDestPos--) | الحصول أو تعيين موضع الوجهة. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | الحصول أو تعيين موضع الوجهة. |
| [getDib()](#getDib--) | الحصول أو تعيين الـ dib. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | الحصول أو تعيين الـ dib. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


يحصل أو يعيّن استخدام اللون.

القيمة: حقل Colors في الـ DIB يحتوي على قيم RGB صريحة أو مؤشرات إلى لوحة ألوان. يجب أن يكون أحد القيم في تعداد `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (القسم 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


يحصل أو يعيّن استخدام اللون.

القيمة: حقل Colors في الـ DIB يحتوي على قيم RGB صريحة أو مؤشرات إلى لوحة ألوان. يجب أن يكون أحد القيم في تعداد `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (القسم 2.1.1.6).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


يحصل أو يضبط عدد المسحات.

القيمة: عدد خطوط المسح في المصدر.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


يحصل أو يضبط عدد المسحات.

القيمة: عدد خطوط المسح في المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


الحصول أو تعيين مسح البداية.

القيمة: خط المسح الابتدائي في المصدر.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


الحصول أو تعيين مسح البداية.

القيمة: خط المسح الابتدائي في المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


الحصول أو تعيين موضع الـ dib.

القيمة: إحداثيات المستطيل المصدر بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


الحصول أو تعيين موضع الـ dib.

القيمة: إحداثيات المستطيل المصدر بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن الارتفاع.

القيمة: ارتفاع المستطيلات المصدر والوجهة بوحدات منطقية.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن الارتفاع.

القيمة: ارتفاع المستطيلات المصدر والوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن العرض.

القيمة: عرض المستطيلات المصدر والوجهة بوحدات منطقية.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن العرض.

القيمة: عرض المستطيلات المصدر والوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


الحصول أو تعيين موضع الوجهة.

القيمة: إحداثيات الزاوية العلوية اليسرى للمستطيل الوجهة بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


الحصول أو تعيين موضع الوجهة.

القيمة: إحداثيات الزاوية العلوية اليسرى للمستطيل الوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


الحصول أو تعيين الـ dib.

القيمة: الإحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


الحصول أو تعيين الـ dib.

القيمة: الإحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

