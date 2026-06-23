---
title: "WmfSetDibToDev"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل META_SETDIBTODEV يحدد كتلة من البكسلات في سياق جهاز التشغيل باستخدام بيانات لون مستقلة عن الجهاز."
type: docs
weight: 75
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

سجل META\_SETDIBTODEV يحدد كتلة من البكسلات في سياق جهاز التشغيل باستخدام بيانات لون مستقلة عن الجهاز. مصدر بيانات اللون هو DIB.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | الحصول أو تعيين استخدام اللون. |
| [setColorUsage(int value)](#setColorUsage-int-) | الحصول أو تعيين استخدام اللون. |
| [getScanCount()](#getScanCount--) | يحصل أو يعيّن عدد المسحات. |
| [setScanCount(int value)](#setScanCount-int-) | يحصل أو يعيّن عدد المسحات. |
| [getStartScan()](#getStartScan--) | يحصل أو يعيّن مسح البداية. |
| [setStartScan(int value)](#setStartScan-int-) | يحصل أو يعيّن مسح البداية. |
| [getDibPos()](#getDibPos--) | يحصل أو يضبط موضع الـ dib. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | يحصل أو يضبط موضع الـ dib. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن الارتفاع. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن الارتفاع. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن العرض. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن العرض. |
| [getDestPos()](#getDestPos--) | يحصل أو يضبط موضع الوجهة. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | يحصل أو يضبط موضع الوجهة. |
| [getDib()](#getDib--) | يحصل أو يضبط الـ dib. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يضبط الـ dib. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


الحصول أو تعيين استخدام اللون.

القيمة: حقل Colors في الـ DIB يحتوي على قيم RGB صريحة أو مؤشرات إلى لوحة ألوان. يجب أن يكون أحد القيم في تعداد `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (القسم 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


الحصول أو تعيين استخدام اللون.

القيمة: حقل Colors في الـ DIB يحتوي على قيم RGB صريحة أو مؤشرات إلى لوحة ألوان. يجب أن يكون أحد القيم في تعداد `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (القسم 2.1.1.6).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


يحصل أو يعيّن عدد المسحات.

القيمة: عدد خطوط المسح في المصدر.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


يحصل أو يعيّن عدد المسحات.

القيمة: عدد خطوط المسح في المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


يحصل أو يعيّن مسح البداية.

القيمة: خط المسح الابتدائي في المصدر.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


يحصل أو يعيّن مسح البداية.

القيمة: خط المسح الابتدائي في المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


يحصل أو يضبط موضع الـ dib.

القيمة: إحداثيات المستطيل المصدر بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


يحصل أو يضبط موضع الـ dib.

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
| value | int |  |

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
| value | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


يحصل أو يضبط موضع الوجهة.

القيمة: إحداثيات الزاوية العلوية اليسرى للمستطيل الوجهة بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


يحصل أو يضبط موضع الوجهة.

القيمة: إحداثيات الزاوية العلوية اليسرى للمستطيل الوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


يحصل أو يضبط الـ dib.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


يحصل أو يضبط الـ dib.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

