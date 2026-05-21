---
title: "WmfDibBitBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_DIBBITBLT kaydı, bir raster işlemi göre cihaz bağımsız biçimde bir piksel bloğunun aktarımını belirtir."
type: docs
weight: 28
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

META\_DIBBITBLT kaydı, raster işlemiyle cihaz bağımsız formatta bir piksel bloğunun aktarımını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Raster işlemini alır veya ayarlar. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Raster işlemini alır veya ayarlar. |
| [getSrcPos()](#getSrcPos--) | Kaynak konumunu alır veya ayarlar. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Kaynak konumunu alır veya ayarlar. |
| [getHeight()](#getHeight--) | Yüksekliği alır veya ayarlar. |
| [setHeight(short value)](#setHeight-short-) | Yüksekliği alır veya ayarlar. |
| [getWidth()](#getWidth--) | Genişliği alır veya ayarlar. |
| [setWidth(short value)](#setWidth-short-) | Genişliği alır veya ayarlar. |
| [getDstPos()](#getDstPos--) | DST konumunu alır veya ayarlar. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | DST konumunu alır veya ayarlar. |
| [getReserved()](#getReserved--) | Ayrılmış alanı alır veya ayarlar. |
| [setReserved(int value)](#setReserved-int-) | Ayrılmış alanı alır veya ayarlar. |
| [getSource()](#getSource--) | Kaynağı alır veya ayarlar. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Kaynağı alır veya ayarlar. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Raster işlemini alır veya ayarlar.

Değer: Kaynak pikseller, oynatma cihaz bağlamındaki mevcut fırça ve hedef pikseller yeni görüntüyü oluşturmak için birleştirilecektir. Bu kod Ternary Raster Operation Sıralamasındaki (bölüm 2.1.1.31) değerlerden biri OLMALIDIR.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Raster işlemini alır veya ayarlar.

Değer: Kaynak pikseller, oynatma cihaz bağlamındaki mevcut fırça ve hedef pikseller yeni görüntüyü oluşturmak için birleştirilecektir. Bu kod Ternary Raster Operation Sıralamasındaki (bölüm 2.1.1.31) değerlerden biri OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Kaynak konumunu alır veya ayarlar.

Değer: Kaynak dikdörtgenin mantıksal birimlerdeki koordinatları.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Kaynak konumunu alır veya ayarlar.

Değer: Kaynak dikdörtgenin mantıksal birimlerdeki koordinatları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Yüksekliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki yüksekliği.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Yüksekliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Genişliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki genişliği.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Genişliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


DST konumunu alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin mantıksal birimlerdeki koordinatları.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


DST konumunu alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin mantıksal birimlerdeki koordinatları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Ayrılmış alanı alır veya ayarlar.

Değer: Ayrılmış alan.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Ayrılmış alanı alır veya ayarlar.

Değer: Ayrılmış alan.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Kaynağı alır veya ayarlar.

Değer: Görüntü içeriğini tanımlayan değişken boyutlu DeviceIndependentBitmap Nesnesi (bölüm 2.2.2.9). Bu nesne, raster işlemi bir kaynak gerektirmese bile BELİRTİLMELİDİR.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Kaynağı alır veya ayarlar.

Değer: Görüntü içeriğini tanımlayan değişken boyutlu DeviceIndependentBitmap Nesnesi (bölüm 2.2.2.9). Bu nesne, raster işlemi bir kaynak gerektirmese bile BELİRTİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

