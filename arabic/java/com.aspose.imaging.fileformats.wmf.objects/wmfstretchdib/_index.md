---
title: "WmfStretchDib"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن wmf Stretch DIB."
type: docs
weight: 94
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchdib/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchDib extends WmfObject
```

كائن wmf Stretch DIB.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfStretchDib()](#WmfStretchDib--) | سجل WMFs. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | يحصل أو يضبط عملية الراستر. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | يحصل أو يضبط عملية الراستر. |
| [getColorUsage()](#getColorUsage--) | يحصل أو يعيّن استخدام اللون. |
| [setColorUsage(int value)](#setColorUsage-int-) | يحصل أو يعيّن استخدام اللون. |
| [getSrcHeight()](#getSrcHeight--) | يحصل أو يضبط ارتفاع المصدر. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | يحصل أو يضبط ارتفاع المصدر. |
| [getSrcWidth()](#getSrcWidth--) | يسترجع أو يعيّن عرض المصدر. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | يسترجع أو يعيّن عرض المصدر. |
| [getYSrc()](#getYSrc--) | يسترجع أو يعيّن إحداثي y للمصدر. |
| [setYSrc(short value)](#setYSrc-short-) | يسترجع أو يعيّن إحداثي y للمصدر. |
| [getXSrc()](#getXSrc--) | يسترجع أو يعيّن إحداثي x للمصدر. |
| [setXSrc(short value)](#setXSrc-short-) | يسترجع أو يعيّن إحداثي x للمصدر. |
| [getDestHeight()](#getDestHeight--) | يسترجع أو يعيّن ارتفاع الوجهة. |
| [setDestHeight(short value)](#setDestHeight-short-) | يسترجع أو يعيّن ارتفاع الوجهة. |
| [getDestWidth()](#getDestWidth--) | يسترجع أو يعيّن عرض الوجهة. |
| [setDestWidth(short value)](#setDestWidth-short-) | يسترجع أو يعيّن عرض الوجهة. |
| [getYDest()](#getYDest--) | يسترجع أو يعيّن إحداثي y للوجهة. |
| [setYDest(short value)](#setYDest-short-) | يسترجع أو يعيّن إحداثي y للوجهة. |
| [getXDest()](#getXDest--) | يسترجع أو يعيّن إحداثي x للوجهة. |
| [setXDest(short value)](#setXDest-short-) | يسترجع أو يعيّن إحداثي x للوجهة. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن صورة البت المصدر. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن صورة البت المصدر. |
### WmfStretchDib() {#WmfStretchDib--}
```
public WmfStretchDib()
```


سجل WMFs.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


يحصل أو يضبط عملية الراستر.

القيمة: الفرشاة الحالية في سياق جهاز التشغيل، ويجب دمج بكسلات الوجهة لتشكيل الصورة الجديدة. يجب أن تكون هذه الشيفرة واحدة من القيم في تعداد عمليات الرستر الثلاثية (section 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


يحصل أو يضبط عملية الراستر.

القيمة: الفرشاة الحالية في سياق جهاز التشغيل، ويجب دمج بكسلات الوجهة لتشكيل الصورة الجديدة. يجب أن تكون هذه الشيفرة واحدة من القيم في تعداد عمليات الرستر الثلاثية (section 2.1.1.31).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


يحصل أو يعيّن استخدام اللون.

القيمة:

حقل Colors في DIB يحتوي على قيم RGB صريحة أو مؤشرات إلى لوحة ألوان. يجب أن تكون هذه القيمة في `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

التعداد (القسم 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


يحصل أو يعيّن استخدام اللون.

القيمة:

حقل Colors في DIB يحتوي على قيم RGB صريحة أو مؤشرات إلى لوحة ألوان. يجب أن تكون هذه القيمة في `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

التعداد (القسم 2.1.1.6).

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

القيمة: عرض المستطيل المصدر، بوحدات منطقية.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


يسترجع أو يعيّن عرض المصدر.

القيمة: عرض المستطيل المصدر، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


يسترجع أو يعيّن إحداثي y للمصدر.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل المصدر.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


يسترجع أو يعيّن إحداثي y للمصدر.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


يسترجع أو يعيّن إحداثي x للمصدر.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل المصدر.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


يسترجع أو يعيّن إحداثي x للمصدر.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


يسترجع أو يعيّن إحداثي y للوجهة.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل الوجهة.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


يسترجع أو يعيّن إحداثي y للوجهة.

القيمة: إحداثي y، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


يسترجع أو يعيّن إحداثي x للوجهة.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل الوجهة.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


يسترجع أو يعيّن إحداثي x للوجهة.

القيمة: إحداثي x، بوحدات منطقية، للزاوية العلوية اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يعيّن صورة البت المصدر.

القيمة: خريطة البتات المصدر.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن صورة البت المصدر.

القيمة: خريطة البتات المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

