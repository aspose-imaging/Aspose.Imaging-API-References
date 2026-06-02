---
title: "ObjectWithBounds"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Sınırları olan nesne."
type: docs
weight: 77
url: /tr/java/com.aspose.imaging/objectwithbounds/
---
**Inheritance:**
java.lang.Object
```
public abstract class ObjectWithBounds
```

Sınırları olan nesne.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ObjectWithBounds()](#ObjectWithBounds--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Nesnenin sınırlarını alır. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Belirtilen dönüşümü şekle uygular. |
### ObjectWithBounds() {#ObjectWithBounds--}
```
public ObjectWithBounds()
```


### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


Nesnenin sınırlarını alır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](../../com.aspose.imaging/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public abstract void transform(Matrix transform)
```


Belirtilen dönüşümü şekle uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Uygulanacak dönüşüm. |

