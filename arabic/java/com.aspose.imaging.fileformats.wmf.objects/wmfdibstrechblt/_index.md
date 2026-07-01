---
title: "WmfDibStrechBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل META_DIBSTRETCHBLT يحدد نقل كتلة من البكسلات بتنسيق مستقل عن الجهاز وفقًا لعملية نقطية مع إمكانية التوسع أو الانكماش."
type: docs
weight: 30
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibstrechblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibStrechBlt extends WmfObject
```

سجل META\_DIBSTRETCHBLT يحدد نقل كتلة من البكسلات بصيغة مستقلة عن الجهاز وفقًا لعملية نقطية، مع إمكانية التوسع أو الانكماش.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfDibStrechBlt()](#WmfDibStrechBlt--) | سجل WMFs. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | يحصل أو يضبط عملية النقطية. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | يحصل أو يضبط عملية النقطية. |
| [getSrcHeight()](#getSrcHeight--) | يحصل أو يضبط ارتفاع المصدر. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | يحصل أو يضبط ارتفاع المصدر. |
| [getSrcWidth()](#getSrcWidth--) | يحصل أو يضبط عرض المصدر. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | يحصل أو يضبط عرض المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يضبط إحداثي y للمصدر. |
| [setYSrc(short value)](#setYSrc-short-) | يحصل أو يضبط إحداثي y للمصدر. |
| [getXSrc()](#getXSrc--) | يحصل أو يضبط إحداثي x للمصدر. |
| [setXSrc(short value)](#setXSrc-short-) | يحصل أو يضبط إحداثي x للمصدر. |
| [getDestHeight()](#getDestHeight--) | يحصل أو يضبط ارتفاع الوجهة. |
| [setDestHeight(short value)](#setDestHeight-short-) | يحصل أو يضبط ارتفاع الوجهة. |
| [getDestWidth()](#getDestWidth--) | يحصل أو يضبط عرض الوجهة. |
| [setDestWidth(short value)](#setDestWidth-short-) | يحصل أو يضبط عرض الوجهة. |
| [getYDest()](#getYDest--) | يحصل أو يضبط إحداثي y للوجهة. |
| [setYDest(short value)](#setYDest-short-) | يحصل أو يضبط إحداثي y للوجهة. |
| [getXDest()](#getXDest--) | يحصل أو يضبط إحداثي x للوجهة. |
| [setXDest(short value)](#setXDest-short-) | يحصل أو يضبط إحداثي x للوجهة. |
| [getSourceBitmap()](#getSourceBitmap--) | الحصول أو تعيين صورة البت المصدر. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | الحصول أو تعيين صورة البت المصدر. |
### WmfDibStrechBlt() {#WmfDibStrechBlt--}
```
public WmfDibStrechBlt()
```


سجل WMFs.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


يحصل أو يضبط عملية النقطية.

القيمة: الفرشاة الحالية في سياق جهاز التشغيل، ويجب دمج بكسلات الوجهة لتكوين الصورة الجديدة. يجب أن يكون هذا الرمز إحدى القيم في تعداد عملية النقطية الثلاثية (القسم 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


يحصل أو يضبط عملية النقطية.

القيمة: الفرشاة الحالية في سياق جهاز التشغيل، ويجب دمج بكسلات الوجهة لتكوين الصورة الجديدة. يجب أن يكون هذا الرمز إحدى القيم في تعداد عملية النقطية الثلاثية (القسم 2.1.1.31).

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

القيمة: عرض المستطيل المصدر بوحدات منطقية

**Returns:**
قصير
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


يحصل أو يضبط عرض المصدر.

القيمة: عرض المستطيل المصدر بوحدات منطقية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


يحصل أو يضبط إحداثي y للمصدر.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
قصير
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


يحصل أو يضبط إحداثي y للمصدر.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


يحصل أو يضبط إحداثي x للمصدر.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
قصير
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


يحصل أو يضبط إحداثي x للمصدر.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


يحصل أو يضبط إحداثي y للوجهة.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
قصير
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


يحصل أو يضبط إحداثي y للوجهة.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


يحصل أو يضبط إحداثي x للوجهة.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
قصير
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


يحصل أو يضبط إحداثي x للوجهة.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


الحصول أو تعيين صورة البت المصدر.

القيمة: خريطة البتات المصدر.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


الحصول أو تعيين صورة البت المصدر.

القيمة: خريطة البتات المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

