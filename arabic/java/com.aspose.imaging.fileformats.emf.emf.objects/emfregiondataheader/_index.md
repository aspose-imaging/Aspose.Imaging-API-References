---
title: "EmfRegionDataHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن RegionDataHeader يصف خصائص كائن RegionData."
type: docs
weight: 34
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

كائن RegionDataHeader يصف خصائص كائن RegionData.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على عدد صحيح غير موقع 32‑بت يحدد حجم هذا الكائن بالبايت. |
| [setSize(int value)](#setSize-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم هذا الكائن بالبايت. |
| [getType()](#getType--) | يحصل على عدد صحيح غير موقع 32‑بت يحدد نوع المنطقة. |
| [setType(int value)](#setType-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع المنطقة. |
| [getCountRects()](#getCountRects--) | يحصل على عدد صحيح غير موقع 32‑بت يحدد عدد المستطيلات في هذه المنطقة. |
| [setCountRects(int value)](#setCountRects-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد المستطيلات في هذه المنطقة. |
| [getRgnSize()](#getRgnSize--) | يحصل على عدد صحيح غير موقع 32‑بت يحدد حجم المخزن المؤقت للمستطيلات بالبايت. |
| [setRgnSize(int value)](#setRgnSize-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم المخزن المؤقت للمستطيلات بالبايت. |
| [getBounds()](#getBounds--) | يحصل على كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19)، والذي يحدد حدود المنطقة. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يضبط كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19)، والذي يحدد حدود المنطقة. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


يحصل على عدد صحيح غير موقع 32‑بت يحدد حجم هذا الكائن بالبايت. يجب أن يكون هذا 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم هذا الكائن بالبايت. يجب أن يكون هذا 0x00000020.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


يحصل على عدد صحيح غير موقع 32‑بت يحدد نوع المنطقة. يجب أن يكون هذا RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع المنطقة. يجب أن يكون هذا RDH\_RECTANGLES (0x00000001).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


يحصل على عدد صحيح غير موقع 32‑بت يحدد عدد المستطيلات في هذه المنطقة.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد المستطيلات في هذه المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


يحصل على عدد صحيح غير موقع 32‑بت يحدد حجم المخزن المؤقت للمستطيلات بالبايت.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم المخزن المؤقت للمستطيلات بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل على كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19)، والذي يحدد حدود المنطقة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يضبط كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19)، والذي يحدد حدود المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

