---
title: "Şekil"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Şekil."
type: docs
weight: 102
url: /tr/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

Şekil. Belirli bir kural kullanılarak bağlanan sürekli bir nokta kümesi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Shape()](#Shape--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Şeklin merkezini alır.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Şekil segmentleri.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Şeklin segmentleri varsa `True`; aksi takdirde `false`.
