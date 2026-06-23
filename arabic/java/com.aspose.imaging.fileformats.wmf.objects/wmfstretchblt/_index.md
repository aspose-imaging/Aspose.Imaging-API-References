---
title: "WmfStretchBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل META_STRETCHBLT يحدد نقل كتلة من البكسلات وفقًا لعملية نقطية مع إمكانية التوسع أو الانكماش."
type: docs
weight: 93
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
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
| [getRasterOperation()](#getRasterOperation--) | يحصل أو يضبط عملية النقطية. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | يحصل أو يضبط عملية النقطية. |
| [getSrcHeight()](#getSrcHeight--) | يحصل أو يضبط ارتفاع المصدر. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | يحصل أو يضبط ارتفاع المصدر. |
| [getSrcWidth()](#getSrcWidth--) | يحصل أو يضبط عرض المصدر. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | يحصل أو يضبط عرض المصدر. |
| [getSrcPosition()](#getSrcPosition--) | يحصل أو يضبط موضع المصدر. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | يحصل أو يضبط موضع المصدر. |
| [getDestHeight()](#getDestHeight--) | يحصل أو يضبط ارتفاع الوجهة. |
| [setDestHeight(short value)](#setDestHeight-short-) | يحصل أو يضبط ارتفاع الوجهة. |
| [getDestWidth()](#getDestWidth--) | يحصل أو يضبط عرض الوجهة. |
| [setDestWidth(short value)](#setDestWidth-short-) | يحصل أو يضبط عرض الوجهة. |
| [getDstPosition()](#getDstPosition--) | يحصل أو يضبط موضع DST. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | يحصل أو يضبط موضع DST. |
| [getReserved()](#getReserved--) | يحصل أو يضبط الحجز. |
| [setReserved(short value)](#setReserved-short-) | يحصل أو يضبط الحجز. |
| [getBitmap()](#getBitmap--) | يحصل أو يضبط الـ bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | يحصل أو يضبط الـ bitmap. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


يحصل أو يضبط عملية النقطية.

القيمة: يجب دمج بكسلات المصدر، والفرشاة الحالية في سياق جهاز التشغيل، وبكسلات الوجهة لتكوين الصورة الجديدة. يجب أن يكون هذا الرمز أحد القيم في تعداد عملية النقطية الثلاثية.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


يحصل أو يضبط عملية النقطية.

القيمة: يجب دمج بكسلات المصدر، والفرشاة الحالية في سياق جهاز التشغيل، وبكسلات الوجهة لتكوين الصورة الجديدة. يجب أن يكون هذا الرمز أحد القيم في تعداد عملية النقطية الثلاثية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


يحصل أو يضبط ارتفاع المصدر.

القيمة: ارتفاع المستطيل المصدر بوحدات منطقية.

**Returns:**
قصير
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


يحصل أو يضبط ارتفاع المصدر.

القيمة: ارتفاع المستطيل المصدر بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


يحصل أو يضبط عرض المصدر.

القيمة: العرض، بوحدات منطقية، للمستطيل المصدر.

**Returns:**
قصير
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


يحصل أو يضبط عرض المصدر.

القيمة: العرض، بوحدات منطقية، للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

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


يحصل أو يضبط ارتفاع الوجهة.

القيمة: ارتفاع المستطيل الوجهة بوحدات منطقية.

**Returns:**
قصير
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


يحصل أو يضبط ارتفاع الوجهة.

القيمة: ارتفاع المستطيل الوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


يحصل أو يضبط عرض الوجهة.

القيمة: عرض المستطيل الوجهة بوحدات منطقية.

**Returns:**
قصير
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


يحصل أو يضبط عرض الوجهة.

القيمة: عرض المستطيل الوجهة بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

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


يحصل أو يضبط الحجز.

القيمة: المحجوز. يجب تجاهل هذا الحقل.

**Returns:**
قصير
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


يحصل أو يضبط الحجز.

القيمة: المحجوز. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


يحصل أو يضبط الـ bitmap.

القيمة: خريطة البت.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


يحصل أو يضبط الـ bitmap.

القيمة: خريطة البت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

