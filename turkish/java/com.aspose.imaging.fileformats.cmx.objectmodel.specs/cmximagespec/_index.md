---
title: "CmxImageSpec"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Raster görüntüler için belirtilen bilgiyi temsil eder."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

Raster görüntüler için belirtilen bilgiyi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | Sınırlama kutusunu alır. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | Sınırlama kutusunu ayarlar. |
| [getCropBox()](#getCropBox--) | Kırpma kutusunu alır. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | Kırpma kutusunu ayarlar. |
| [getMatrix()](#getMatrix--) | Dönüşüm matrisini alır. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Dönüşüm matrisini ayarlar. |
| [getImageType()](#getImageType--) | Görüntünün tipini alır. |
| [setImageType(int value)](#setImageType-int-) | Görüntünün tipini ayarlar. |
| [getImages()](#getImages--) | Görüntüleri alır. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Görüntüleri ayarlar. |
| [isCmx3Image()](#isCmx3Image--) | Bu örneğin CMX3 görüntüsü olup olmadığını gösteren bir değeri alır. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | Bu örneğin CMX3 görüntüsü olup olmadığını gösteren bir değeri ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


Sınırlama kutusunu alır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


Sınırlama kutusunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | sınırlama kutusu. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


Kırpma kutusunu alır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


Kırpma kutusunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | kırpma kutusu. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Dönüşüm matrisini alır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Dönüşüm matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | dönüşüm matrisi. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


Görüntünün tipini alır.

**Returns:**
int - görüntünün türü.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Görüntünün tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | görüntünün türü. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Görüntüleri alır.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - görüntüler.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Görüntüleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | görüntüler. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


Bu örneğin CMX3 görüntüsü olup olmadığını gösteren bir değeri alır.

Değer: bu örnek CMX3 görüntüsü ise `true`; aksi takdirde `false`.

**Returns:**
boolean - bu örneğin CMX3 görüntüsü olup olmadığını gösteren bir değer.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


Bu örneğin CMX3 görüntüsü olup olmadığını gösteren bir değeri ayarlar.

Değer: bu örnek CMX3 görüntüsü ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | bu örneğin CMX3 görüntüsü olup olmadığını gösteren bir değer. |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir String.
### toArray() {#toArray--}
```
public CmxRasterImage[] toArray()
```




**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[]
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
