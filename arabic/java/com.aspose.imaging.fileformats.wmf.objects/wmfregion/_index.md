---
title: "WmfRegion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن Region Object يحدد شكلًا قد يكون غير مستطيل يُعرّف بواسطة مصفوفة من خطوط المسح."
type: docs
weight: 62
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

كائن Region يحدد شكلًا قد يكون غير مستطيل يُعرّف بواسطة مصفوفة من خطوط المسح.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | يحصل أو يضبط العنصر التالي في السلسلة. |
| [setNextInChain(short value)](#setNextInChain-short-) | يحصل أو يضبط العنصر التالي في السلسلة. |
| [getObjectType()](#getObjectType--) | يحصل أو يعيّن نوع الكائن. |
| [setObjectType(short value)](#setObjectType-short-) | يحصل أو يعيّن نوع الكائن. |
| [getObjectCount()](#getObjectCount--) | يحصل أو يضبط عدد الكائنات. |
| [setObjectCount(int value)](#setObjectCount-int-) | يحصل أو يضبط عدد الكائنات. |
| [getRegionSize()](#getRegionSize--) | يحصل أو يضبط حجم المنطقة. |
| [setRegionSize(short value)](#setRegionSize-short-) | يحصل أو يضبط حجم المنطقة. |
| [getScanCount()](#getScanCount--) | يحصل أو يضبط عدد المسحات. |
| [setScanCount(short value)](#setScanCount-short-) | يحصل أو يضبط عدد المسحات. |
| [getMaxScan()](#getMaxScan--) | يحصل أو يضبط الحد الأقصى للمسح. |
| [setMaxScan(short value)](#setMaxScan-short-) | يحصل أو يضبط الحد الأقصى للمسح. |
| [getBoundingRectangle()](#getBoundingRectangle--) | الحصول أو تعيين المستطيل المحيط. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | الحصول أو تعيين المستطيل المحيط. |
| [getAScans()](#getAScans--) | الحصول أو تعيين المسحات. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | الحصول أو تعيين المسحات. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


يحصل أو يضبط العنصر التالي في السلسلة.

القيمة: قيمة يجب تجاهلها.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


يحصل أو يضبط العنصر التالي في السلسلة.

القيمة: قيمة يجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


يحصل أو يعيّن نوع الكائن.

القيمة: معرف المنطقة. يجب أن يكون 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


يحصل أو يعيّن نوع الكائن.

القيمة: معرف المنطقة. يجب أن يكون 0x0006.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


يحصل أو يضبط عدد الكائنات.

القيمة: قيمة يجب تجاهلها.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


يحصل أو يضبط عدد الكائنات.

القيمة: قيمة يجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


يحصل أو يضبط حجم المنطقة.

القيمة: حجم المنطقة بالبايت بالإضافة إلى حجم aScans بالبايت.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


يحصل أو يضبط حجم المنطقة.

القيمة: حجم المنطقة بالبايت بالإضافة إلى حجم aScans بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


يحصل أو يضبط عدد المسحات.

القيمة: عدد خطوط المسح التي تشكّل المنطقة.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


يحصل أو يضبط عدد المسحات.

القيمة: عدد خطوط المسح التي تشكّل المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


يحصل أو يضبط الحد الأقصى للمسح.

القيمة: الحد الأقصى لعدد النقاط في أي مسح واحد داخل هذه المنطقة.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


يحصل أو يضبط الحد الأقصى للمسح.

القيمة: الحد الأقصى لعدد النقاط في أي مسح واحد داخل هذه المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


الحصول أو تعيين المستطيل المحيط.

القيمة: كائن Rect (القسم 2.2.2.18) الذي يحدد المستطيل المحيط.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


الحصول أو تعيين المستطيل المحيط.

القيمة: كائن Rect (القسم 2.2.2.18) الذي يحدد المستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


الحصول أو تعيين المسحات.

القيمة: مصفوفة من كائنات Scan (القسم 2.2.2.21) التي تحدد خطوط المسح في المنطقة.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


الحصول أو تعيين المسحات.

القيمة: مصفوفة من كائنات Scan (القسم 2.2.2.21) التي تحدد خطوط المسح في المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

