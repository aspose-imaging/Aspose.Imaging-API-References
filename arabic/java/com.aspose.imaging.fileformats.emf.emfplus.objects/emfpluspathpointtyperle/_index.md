---
title: "EmfPlusPathPointTypeRle"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPathPointTypeRle يحدد قيم نوع مرتبطة بنقاط على مسار رسومي باستخدام ضغط RLE."
type: docs
weight: 62
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

كائن EmfPlusPathPointTypeRle يحدد قيم النوع المرتبطة بالنقاط على مسار رسومي باستخدام ضغط RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 بت): إذا تم تعيينه، تكون نقاط المسار على منحنى Bezier. إذا تم إلغاء تعيينه، تكون نقاط المسار على خط رسومي. RunCount (6 بت): عدد التكرارات، وهو عدد نقاط المسار التي يجب ربطها بالنوع في حقل PointType. PointType (1 بايت): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getData()](#getData--) | يحصل أو يعيّن البيانات. |
| [setData(int value)](#setData-int-) | يحصل أو يعيّن البيانات. |
| [getBezier()](#getBezier--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان `EmfPlusPathPointTypeRle` من نوع Bezier. |
| [setBezier(boolean value)](#setBezier-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان `EmfPlusPathPointTypeRle` من نوع Bezier. |
| [getRunCount()](#getRunCount--) | يحصل أو يعيّن عدد التكرارات. |
| [setRunCount(byte value)](#setRunCount-byte-) | يحصل أو يعيّن عدد التكرارات. |
| [getPointType()](#getPointType--) | يحصل أو يعيّن نوع النقطة. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | يحصل أو يعيّن نوع النقطة. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


يحصل أو يعيّن البيانات.

القيمة: البيانات.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


يحصل أو يعيّن البيانات.

القيمة: البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان `EmfPlusPathPointTypeRle` من نوع Bezier. إذا تم تعيينه، تكون نقاط المسار على منحنى Bezier. إذا تم إلغاء تعيينه، تكون نقاط المسار على خط رسومي.

القيمة: `true` إذا كان Bezier؛ وإلا `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان `EmfPlusPathPointTypeRle` من نوع Bezier. إذا تم تعيينه، تكون نقاط المسار على منحنى Bezier. إذا تم إلغاء تعيينه، تكون نقاط المسار على خط رسومي.

القيمة: `true` إذا كان Bezier؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


يحصل أو يعيّن عدد التكرارات. RunCount (6 بت): عدد التكرارات، وهو عدد نقاط المسار التي يجب ربطها بالنوع في حقل PointType

القيمة: عدد التكرارات.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


يحصل أو يعيّن عدد التكرارات. RunCount (6 بت): عدد التكرارات، وهو عدد نقاط المسار التي يجب ربطها بالنوع في حقل PointType

القيمة: عدد التكرارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


يحصل أو يعيّن نوع النقطة. PointType (1 بايت): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.

القيمة: نوع النقطة.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


يحصل أو يعيّن نوع النقطة. PointType (1 بايت): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.

القيمة: نوع النقطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

