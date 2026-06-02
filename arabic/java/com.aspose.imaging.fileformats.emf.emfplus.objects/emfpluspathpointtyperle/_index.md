---
title: "EmfPlusPathPointTypeRle"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPathPointTypeRle يحدد قيم النوع المرتبطة بنقاط على مسار رسومي باستخدام ضغط RLE."
type: docs
weight: 62
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

كائن EmfPlusPathPointTypeRle يحدد قيم النوع المرتبطة بالنقاط على مسار رسومي باستخدام ضغط RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (بت واحد): إذا تم تعيينه، تكون نقاط المسار على منحنى بيزيير. إذا لم يتم تعيينه، تكون نقاط المسار على خط رسومي. RunCount (6 بتات): عدد التتابعات، وهو عدد نقاط المسار التي سيتم ربطها بالنوع في حقل PointType. PointType (بايت واحد): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getData()](#getData--) | يحصل أو يضبط البيانات. |
| [setData(int value)](#setData-int-) | يحصل أو يضبط البيانات. |
| [getBezier()](#getBezier--) | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusPathPointTypeRle` بيزيير. |
| [setBezier(boolean value)](#setBezier-boolean-) | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusPathPointTypeRle` بيزيير. |
| [getRunCount()](#getRunCount--) | يسترجع أو يعيّن عدد التتابعات. |
| [setRunCount(byte value)](#setRunCount-byte-) | يسترجع أو يعيّن عدد التتابعات. |
| [getPointType()](#getPointType--) | يسترجع أو يعيّن نوع النقطة. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | يسترجع أو يعيّن نوع النقطة. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


يسترجع أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusPathPointTypeRle` بيزيير. إذا تم تعيينه، تكون نقاط المسار على منحنى بيزيير. إذا لم يتم تعيينه، تكون نقاط المسار على خط رسومي.

القيمة: `true` إذا كان بيزيير؛ وإلا `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


يسترجع أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusPathPointTypeRle` بيزيير. إذا تم تعيينه، تكون نقاط المسار على منحنى بيزيير. إذا لم يتم تعيينه، تكون نقاط المسار على خط رسومي.

القيمة: `true` إذا كان بيزيير؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


يسترجع أو يعيّن عدد التتابعات. RunCount (6 بتات): عدد التتابعات، وهو عدد نقاط المسار التي سيتم ربطها بالنوع في حقل PointType

القيمة: عدد التتابعات.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


يسترجع أو يعيّن عدد التتابعات. RunCount (6 بتات): عدد التتابعات، وهو عدد نقاط المسار التي سيتم ربطها بالنوع في حقل PointType

القيمة: عدد التتابعات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


يسترجع أو يعيّن نوع النقطة. PointType (بايت واحد): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.

القيمة: نوع النقطة.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


يسترجع أو يعيّن نوع النقطة. PointType (بايت واحد): كائن EmfPlusPathPointType (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار.

القيمة: نوع النقطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

