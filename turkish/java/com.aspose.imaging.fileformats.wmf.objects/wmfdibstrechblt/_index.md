---
title: "WmfDibStrechBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_DIBSTRETCHBLT kaydı, olası genişleme veya daralma ile bir raster işlemi doğrultusunda cihaz bağımsız formatta bir piksel bloğunun aktarımını belirtir."
type: docs
weight: 30
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibstrechblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibStrechBlt extends WmfObject
```

META\_DIBSTRETCHBLT kaydı, raster işlemiyle cihaz bağımsız formatta bir piksel bloğunun aktarımını, olası genişleme veya daralma ile birlikte belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfDibStrechBlt()](#WmfDibStrechBlt--) | WMFs kaydı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Raster işlemini alır veya ayarlar. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Raster işlemini alır veya ayarlar. |
| [getSrcHeight()](#getSrcHeight--) | Kaynağın yüksekliğini alır veya ayarlar. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Kaynağın yüksekliğini alır veya ayarlar. |
| [getSrcWidth()](#getSrcWidth--) | Kaynağın genişliğini alır veya ayarlar. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Kaynağın genişliğini alır veya ayarlar. |
| [getYSrc()](#getYSrc--) | y kaynağını alır veya ayarlar. |
| [setYSrc(short value)](#setYSrc-short-) | y kaynağını alır veya ayarlar. |
| [getXSrc()](#getXSrc--) | x kaynağını alır veya ayarlar. |
| [setXSrc(short value)](#setXSrc-short-) | x kaynağını alır veya ayarlar. |
| [getDestHeight()](#getDestHeight--) | Hedefin yüksekliğini alır veya ayarlar. |
| [setDestHeight(short value)](#setDestHeight-short-) | Hedefin yüksekliğini alır veya ayarlar. |
| [getDestWidth()](#getDestWidth--) | Hedefin genişliğini alır veya ayarlar. |
| [setDestWidth(short value)](#setDestWidth-short-) | Hedefin genişliğini alır veya ayarlar. |
| [getYDest()](#getYDest--) | y hedefini alır veya ayarlar. |
| [setYDest(short value)](#setYDest-short-) | y hedefini alır veya ayarlar. |
| [getXDest()](#getXDest--) | x hedefini alır veya ayarlar. |
| [setXDest(short value)](#setXDest-short-) | x hedefini alır veya ayarlar. |
| [getSourceBitmap()](#getSourceBitmap--) | Kaynak bitmap'i alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Kaynak bitmap'i alır veya ayarlar. |
### WmfDibStrechBlt() {#WmfDibStrechBlt--}
```
public WmfDibStrechBlt()
```


WMFs kaydı.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Raster işlemini alır veya ayarlar.

Değer: Oynatma aygıt bağlamındaki mevcut fırça ve hedef pikselleri yeni görüntüyü oluşturmak için birleştirilecektir. Bu kod, Üçlü Raster İşlem Sıralaması (bölüm 2.1.1.31) içindeki değerlerden biri OLMAK ZORUNDADIR.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Raster işlemini alır veya ayarlar.

Değer: Oynatma aygıt bağlamındaki mevcut fırça ve hedef pikselleri yeni görüntüyü oluşturmak için birleştirilecektir. Bu kod, Üçlü Raster İşlem Sıralaması (bölüm 2.1.1.31) içindeki değerlerden biri OLMAK ZORUNDADIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Kaynağın yüksekliğini alır veya ayarlar.

Değer: Kaynak dikdörtgenin, mantıksal birimlerdeki yüksekliği.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Kaynağın yüksekliğini alır veya ayarlar.

Değer: Kaynak dikdörtgenin, mantıksal birimlerdeki yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Kaynağın genişliğini alır veya ayarlar.

Değer: Kaynak dikdörtgenin, mantıksal birimlerdeki genişliği.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Kaynağın genişliğini alır veya ayarlar.

Değer: Kaynak dikdörtgenin, mantıksal birimlerdeki genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


y kaynağını alır veya ayarlar.

Değer: Kaynak dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki y koordinatı.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


y kaynağını alır veya ayarlar.

Değer: Kaynak dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki y koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


x kaynağını alır veya ayarlar.

Değer: Kaynak dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki x koordinatı.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


x kaynağını alır veya ayarlar.

Değer: Kaynak dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki x koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Hedefin yüksekliğini alır veya ayarlar.

Değer: Hedef dikdörtgenin, mantıksal birimlerdeki yüksekliği.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Hedefin yüksekliğini alır veya ayarlar.

Değer: Hedef dikdörtgenin, mantıksal birimlerdeki yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Hedefin genişliğini alır veya ayarlar.

Değer: Hedef dikdörtgenin, mantıksal birimlerdeki genişliği.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Hedefin genişliğini alır veya ayarlar.

Değer: Hedef dikdörtgenin, mantıksal birimlerdeki genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getYDest() {#getYDest--}
```
public short getYDest()
```


y hedefini alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki y koordinatı.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


y hedefini alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki y koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


x hedefini alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki x koordinatı.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


x hedefini alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin, mantıksal birimlerdeki x koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Kaynak bitmap'i alır veya ayarlar.

Değer: Kaynak bitmap.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Kaynak bitmap'i alır veya ayarlar.

Değer: Kaynak bitmap.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

