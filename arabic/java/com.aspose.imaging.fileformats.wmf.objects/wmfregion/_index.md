---
title: "WmfRegion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن المنطقة يحدد شكلاً غير مستطيل محتملًا يتم تعريفه بواسطة مصفوفة من خطوط المسح."
type: docs
weight: 62
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

كائن Region يعرّف شكلاً قد يكون غير مستطيل يتم تعريفه بواسطة مصفوفة من خطوط المسح.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | يحصل أو يعيّن التالي في السلسلة. |
| [setNextInChain(short value)](#setNextInChain-short-) | يحصل أو يعيّن التالي في السلسلة. |
| [getObjectType()](#getObjectType--) | يحصل أو يعيّن نوع الكائن. |
| [setObjectType(short value)](#setObjectType-short-) | يحصل أو يعيّن نوع الكائن. |
| [getObjectCount()](#getObjectCount--) | يحصل أو يعيّن عدد الكائنات. |
| [setObjectCount(int value)](#setObjectCount-int-) | يحصل أو يعيّن عدد الكائنات. |
| [getRegionSize()](#getRegionSize--) | يحصل أو يعيّن حجم المنطقة. |
| [setRegionSize(short value)](#setRegionSize-short-) | يحصل أو يعيّن حجم المنطقة. |
| [getScanCount()](#getScanCount--) | يحصل أو يعيّن عدد المسحات. |
| [setScanCount(short value)](#setScanCount-short-) | يحصل أو يعيّن عدد المسحات. |
| [getMaxScan()](#getMaxScan--) | يحصل أو يعيّن الحد الأقصى للمسح. |
| [setMaxScan(short value)](#setMaxScan-short-) | يحصل أو يعيّن الحد الأقصى للمسح. |
| [getBoundingRectangle()](#getBoundingRectangle--) | يحصل أو يعيّن المستطيل المحيط. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن المستطيل المحيط. |
| [getAScans()](#getAScans--) | يحصل أو يعيّن مسحًا. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | يحصل أو يعيّن مسحًا. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


يحصل أو يعيّن التالي في السلسلة.

القيمة: قيمة يجب تجاهلها.

**Returns:**
قصير
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


يحصل أو يعيّن التالي في السلسلة.

القيمة: قيمة يجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


يحصل أو يعيّن نوع الكائن.

القيمة: معرف المنطقة. يجب أن يكون 0x0006.

**Returns:**
قصير
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


يحصل أو يعيّن نوع الكائن.

القيمة: معرف المنطقة. يجب أن يكون 0x0006.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


يحصل أو يعيّن عدد الكائنات.

القيمة: قيمة يجب تجاهلها.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


يحصل أو يعيّن عدد الكائنات.

القيمة: قيمة يجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


يحصل أو يعيّن حجم المنطقة.

القيمة: حجم المنطقة بالبايتات بالإضافة إلى حجم aScans بالبايتات.

**Returns:**
قصير
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


يحصل أو يعيّن حجم المنطقة.

القيمة: حجم المنطقة بالبايتات بالإضافة إلى حجم aScans بالبايتات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


يحصل أو يعيّن عدد المسحات.

القيمة: عدد خطوط المسح التي تشكل المنطقة.

**Returns:**
قصير
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


يحصل أو يعيّن عدد المسحات.

القيمة: عدد خطوط المسح التي تشكل المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


يحصل أو يعيّن الحد الأقصى للمسح.

القيمة: الحد الأقصى لعدد النقاط في أي مسح واحد في هذه المنطقة.

**Returns:**
قصير
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


يحصل أو يعيّن الحد الأقصى للمسح.

القيمة: الحد الأقصى لعدد النقاط في أي مسح واحد في هذه المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


يحصل أو يعيّن المستطيل المحيط.

القيمة: كائن Rect (القسم 2.2.2.18) الذي يحدد المستطيل المحيط.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


يحصل أو يعيّن المستطيل المحيط.

القيمة: كائن Rect (القسم 2.2.2.18) الذي يحدد المستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


يحصل أو يعيّن مسحًا.

القيمة: مصفوفة من كائنات Scan (القسم 2.2.2.21) التي تحدد خطوط المسح في المنطقة.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


يحصل أو يعيّن مسحًا.

القيمة: مصفوفة من كائنات Scan (القسم 2.2.2.21) التي تحدد خطوط المسح في المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

