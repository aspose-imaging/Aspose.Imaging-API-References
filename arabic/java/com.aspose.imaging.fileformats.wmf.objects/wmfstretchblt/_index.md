---
title: "WmfStretchBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل META_STRETCHBLT يحدد نقل كتلة من البكسلات وفقًا لعملية نقطية مع إمكانية التوسيع أو الانكماش."
type: docs
weight: 93
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

سجل META\_STRETCHBLT يحدد نقل كتلة من البكسلات وفقًا لعملية نقطية، مع إمكانية التوسيع أو الانكماش.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | يحصل أو يضبط عملية الراستر. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | يحصل أو يضبط عملية الراستر. |
| [getSrcHeight()](#getSrcHeight--) | يحصل أو يضبط ارتفاع المصدر. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | يحصل أو يضبط ارتفاع المصدر. |
| [getSrcWidth()](#getSrcWidth--) | يسترجع أو يعيّن عرض المصدر. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | يسترجع أو يعيّن عرض المصدر. |
| [getSrcPosition()](#getSrcPosition--) | يحصل أو يضبط موضع المصدر. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | يحصل أو يضبط موضع المصدر. |
| [getDestHeight()](#getDestHeight--) | يسترجع أو يعيّن ارتفاع الوجهة. |
| [setDestHeight(short value)](#setDestHeight-short-) | يسترجع أو يعيّن ارتفاع الوجهة. |
| [getDestWidth()](#getDestWidth--) | يسترجع أو يعيّن عرض الوجهة. |
| [setDestWidth(short value)](#setDestWidth-short-) | يسترجع أو يعيّن عرض الوجهة. |
| [getDstPosition()](#getDstPosition--) | يحصل أو يضبط موضع DST. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | يحصل أو يضبط موضع DST. |
| [getReserved()](#getReserved--) | يحصل أو يعيّن الحجز. |
| [setReserved(short value)](#setReserved-short-) | يحصل أو يعيّن الحجز. |
| [getBitmap()](#getBitmap--) | الحصول على أو تعيين الـ bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | الحصول على أو تعيين الـ bitmap. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


يحصل أو يضبط عملية الراستر.

القيمة: يجب دمج بكسلات المصدر، والفرشاة الحالية في سياق جهاز التشغيل، وبكسلات الوجهة لتكوين الصورة الجديدة. يجب أن يكون هذا الرمز أحد القيم في تعداد Ternary Raster Operation.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


يحصل أو يضبط عملية الراستر.

القيمة: يجب دمج بكسلات المصدر، والفرشاة الحالية في سياق جهاز التشغيل، وبكسلات الوجهة لتكوين الصورة الجديدة. يجب أن يكون هذا الرمز أحد القيم في تعداد Ternary Raster Operation.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


يحصل أو يضبط ارتفاع المصدر.

القيمة: ارتفاع المستطيل المصدر، بوحدات منطقية.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


يحصل أو يضبط ارتفاع المصدر.

القيمة: ارتفاع المستطيل المصدر، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


يسترجع أو يعيّن عرض المصدر.

القيمة: العرض، بوحدات منطقية، للمستطيل المصدر.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


يسترجع أو يعيّن عرض المصدر.

القيمة: العرض، بوحدات منطقية، للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


يحصل أو يضبط موضع المصدر.

القيمة: موضع المصدر.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


يحصل أو يضبط موضع المصدر.

القيمة: موضع المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


يسترجع أو يعيّن ارتفاع الوجهة.

القيمة: ارتفاع المستطيل الوجهة، بوحدات منطقية.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


يسترجع أو يعيّن ارتفاع الوجهة.

القيمة: ارتفاع المستطيل الوجهة، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


يسترجع أو يعيّن عرض الوجهة.

القيمة: عرض المستطيل الوجهة، بوحدات منطقية.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


يسترجع أو يعيّن عرض الوجهة.

القيمة: عرض المستطيل الوجهة، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


يحصل أو يضبط موضع DST.

القيمة: موضع الوجهة.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


يحصل أو يضبط موضع DST.

القيمة: موضع الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


يحصل أو يعيّن الحجز.

القيمة: reserved. يجب تجاهل هذا الحقل.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


يحصل أو يعيّن الحجز.

القيمة: reserved. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


الحصول على أو تعيين الـ bitmap.

القيمة: الـ bitmap.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


الحصول على أو تعيين الـ bitmap.

القيمة: الـ bitmap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

