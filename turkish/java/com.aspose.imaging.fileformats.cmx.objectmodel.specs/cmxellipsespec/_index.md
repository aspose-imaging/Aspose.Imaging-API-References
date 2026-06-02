---
title: "CmxEllipseSpec"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Elips için belirtilen geometrik bilgiyi temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Elips için belirtilen geometrik bilgiyi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAngle1()](#getAngle1--) | Pasta sektörü tanımlamak için kullanılan ilk açıyı alır. |
| [setAngle1(float value)](#setAngle1-float-) | Pasta sektörü tanımlamak için kullanılan ilk açıyı ayarlar. |
| [getAngle2()](#getAngle2--) | Pasta sektörü tanımlamak için kullanılan ikinci açıyı alır. |
| [setAngle2(float value)](#setAngle2-float-) | Pasta sektörü tanımlamak için kullanılan ikinci açıyı ayarlar. |
| [getRotation()](#getRotation--) | Elipsin dönüş açısını alır. |
| [setRotation(float value)](#setRotation-float-) | Elipsin dönüş açısını ayarlar. |
| [getPie()](#getPie--) | Bu [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) nesnesinin pasta olup olmadığını gösteren bir değer alır. |
| [setPie(boolean value)](#setPie-boolean-) | Bu [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) nesnesinin pasta olup olmadığını gösteren bir değeri ayarlar. |
| [getCenterX()](#getCenterX--) | Dikdörtgenin merkezinin X koordinatını alır. |
| [setCenterX(float value)](#setCenterX-float-) | Dikdörtgenin merkezinin X koordinatını ayarlar. |
| [getCenterY()](#getCenterY--) | Dikdörtgenin merkezinin Y koordinatını alır. |
| [setCenterY(float value)](#setCenterY-float-) | Dikdörtgenin merkezinin Y koordinatını ayarlar. |
| [getDiameterX()](#getDiameterX--) | Dikdörtgenin X boyutu için çapı alır. |
| [setDiameterX(float value)](#setDiameterX-float-) | Dikdörtgenin X boyutu için çapı ayarlar. |
| [getDiameterY()](#getDiameterY--) | Dikdörtgenin Y boyutu için çapı alır. |
| [setDiameterY(float value)](#setDiameterY-float-) | Dikdörtgenin Y boyutu için çapı ayarlar. |
| [getBoundingBox()](#getBoundingBox--) | Sınırlayıcı kutuyu alır. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Sınırlayıcı kutuyu ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Pasta sektörü tanımlamak için kullanılan ilk açıyı alır. `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ise etkilenmez. Radyan cinsinden ölçülür.

**Returns:**
float - pasta sektörü tanımlamak için kullanılan ilk açı.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Pasta sektörü tanımlamak için kullanılan ilk açıyı ayarlar. `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ise etkilenmez. Radyan cinsinden ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | pie sektörü tanımlamak için kullanılan ilk açı. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


pie sektörü tanımlamak için kullanılan ikinci açıyı alır. `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ise etkisi yoktur. Radyan cinsinden ölçülür.

**Returns:**
float - pie sektörü tanımlamak için kullanılan ikinci açı.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


pie sektörü tanımlamak için kullanılan ikinci açıyı ayarlar. `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ise etkisi yoktur. Radyan cinsinden ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | pie sektörü tanımlamak için kullanılan ikinci açı. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


elipsin dönüş açısını alır. Radyan cinsinden ölçülür.

**Returns:**
float - elipsin dönüş açısı.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


elipsin dönüş açısını ayarlar. Radyan cinsinden ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | elipsin dönüş açısı. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Bu [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) nesnesinin pasta olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - bu [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) bir pie olup olmadığını gösteren değer.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Bu [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) nesnesinin pasta olup olmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | bu [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) bir pie olup olmadığını gösteren değer. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Dikdörtgenin merkezinin X koordinatını alır. Ortak belge mesafe birimlerinde ölçülür.

**Returns:**
float - dikdörtgenin merkezinin X koordinatı.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Dikdörtgenin merkezinin X koordinatını ayarlar. Ortak belge mesafe birimlerinde ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | dikdörtgenin merkezinin X koordinatı. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Dikdörtgenin merkezinin Y koordinatını alır. Ortak belge mesafe birimlerinde ölçülür.

**Returns:**
float - dikdörtgenin merkezinin Y koordinatı.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Y koordinatını dikdörtgenin merkezi için ayarlar. Ortak belge mesafe birimlerinde ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | dikdörtgenin merkezinin Y koordinatı. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


dikdörtgenin X boyutu için çapı alır. Ortak belge mesafe birimlerinde ölçülür.

**Returns:**
float - dikdörtgenin X boyutu için çap.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


dikdörtgenin X boyutu için çapı ayarlar. Ortak belge mesafe birimlerinde ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | dikdörtgenin X boyutu için çap. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


dikdörtgenin Y boyutu için çapı alır. Ortak belge mesafe birimlerinde ölçülür.

**Returns:**
float - dikdörtgenin Y boyutu için çap.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


dikdörtgenin Y boyutu için çapı ayarlar. Ortak belge mesafe birimlerinde ölçülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | dikdörtgenin Y boyutu için çap. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Sınırlayıcı kutuyu alır.

Değer: Sınırlayıcı kutu.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Sınırlayıcı kutuyu ayarlar.

Değer: Sınırlayıcı kutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | sınırlayıcı kutu. |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir String.
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
