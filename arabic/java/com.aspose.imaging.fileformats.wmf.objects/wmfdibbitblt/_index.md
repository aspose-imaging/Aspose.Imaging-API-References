---
title: "WmfDibBitBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل META_DIBBITBLT يحدد نقل كتلة من البكسلات بتنسيق غير معتمد على الجهاز وفقًا لعملية نقطية."
type: docs
weight: 28
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

سجل META\_DIBBITBLT يحدد نقل كتلة من البكسلات بصيغة مستقلة عن الجهاز وفقًا لعملية نقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | يحصل أو يضبط عملية النقطية. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | يحصل أو يضبط عملية النقطية. |
| [getSrcPos()](#getSrcPos--) | يحصل أو يضبط موضع المصدر. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | يحصل أو يضبط موضع المصدر. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن الارتفاع. |
| [setHeight(short value)](#setHeight-short-) | يحصل أو يعيّن الارتفاع. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن العرض. |
| [setWidth(short value)](#setWidth-short-) | يحصل أو يعيّن العرض. |
| [getDstPos()](#getDstPos--) | يحصل أو يضبط موضع DST. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | يحصل أو يضبط موضع DST. |
| [getReserved()](#getReserved--) | يحصل أو يضبط الحجز. |
| [setReserved(int value)](#setReserved-int-) | يحصل أو يضبط الحجز. |
| [getSource()](#getSource--) | يحصل أو يضبط المصدر. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يضبط المصدر. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


يحصل أو يضبط عملية النقطية.

القيمة: بكسلات المصدر، والفرشاة الحالية في سياق جهاز التشغيل، وبكسلات الوجهة تُدمج لتكوين الصورة الجديدة. يجب أن تكون هذه الشفرة واحدة من القيم في تعداد Ternary Raster Operation Enumeration (section 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


يحصل أو يضبط عملية النقطية.

القيمة: بكسلات المصدر، والفرشاة الحالية في سياق جهاز التشغيل، وبكسلات الوجهة تُدمج لتكوين الصورة الجديدة. يجب أن تكون هذه الشفرة واحدة من القيم في تعداد Ternary Raster Operation Enumeration (section 2.1.1.31).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


يحصل أو يضبط موضع المصدر.

القيمة: إحداثيات المستطيل المصدر بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


يحصل أو يضبط موضع المصدر.

القيمة: إحداثيات المستطيل المصدر بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


يحصل أو يعيّن الارتفاع.

القيمة: ارتفاع المستطيلات المصدر والوجهة بوحدات منطقية.

**Returns:**
قصير
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


يحصل أو يعيّن الارتفاع.

القيمة: ارتفاع المستطيلات المصدر والوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


يحصل أو يعيّن العرض.

القيمة: عرض المستطيلات المصدر والوجهة بوحدات منطقية.

**Returns:**
قصير
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


يحصل أو يعيّن العرض.

القيمة: عرض المستطيلات المصدر والوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


يحصل أو يضبط موضع DST.

القيمة: إحداثيات الزاوية العلوية اليسرى للمستطيل الوجهة بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


يحصل أو يضبط موضع DST.

القيمة: إحداثيات الزاوية العلوية اليسرى للمستطيل الوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


يحصل أو يضبط الحجز.

القيمة: الحجز.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


يحصل أو يضبط الحجز.

القيمة: الحجز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


يحصل أو يضبط المصدر.

القيمة: كائن DeviceIndependentBitmap متغير الحجم (القسم 2.2.2.9) يحدد محتوى الصورة. يجب تحديد هذا الكائن، حتى إذا لم تتطلب عملية الرستر مصدرًا.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


يحصل أو يضبط المصدر.

القيمة: كائن DeviceIndependentBitmap متغير الحجم (القسم 2.2.2.9) يحدد محتوى الصورة. يجب تحديد هذا الكائن، حتى إذا لم تتطلب عملية الرستر مصدرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

