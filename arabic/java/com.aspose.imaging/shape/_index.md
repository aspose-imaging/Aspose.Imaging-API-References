---
title: "الشكل"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الشكل."
type: docs
weight: 102
url: /ar/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

الشكل. مجموعة مستمرة من النقاط متصلة باستخدام قاعدة محددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Shape()](#Shape--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


يحصل على مركز الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

**Returns:**
com.aspose.imaging.ShapeSegment[] - مقاطع الشكل.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع.

**Returns:**
boolean - `True` إذا كان الشكل يحتوي على مقاطع؛ وإلا `false`.
