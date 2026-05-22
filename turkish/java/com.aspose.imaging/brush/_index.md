---
title: "Brush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Temel fırça sınıfı."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

Temel fırça sınıfı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Brush()](#Brush--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOpacity()](#getOpacity--) | Fırça opaklığını alır. |
| [setOpacity(float value)](#setOpacity-float-) | Fırça opaklığını ayarlar. |
| [deepClone()](#deepClone--) | Mevcut `Brush`'ın yeni bir derin klonunu oluşturur. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Fırça opaklığını alır. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir.

**Returns:**
float - Fırça opaklık değeri.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Fırça opaklığını ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Fırça opaklık değeri. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Mevcut `Brush`'ın yeni bir derin klonunu oluşturur.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
