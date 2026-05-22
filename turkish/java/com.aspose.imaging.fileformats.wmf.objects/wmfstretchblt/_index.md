---
title: "WmfStretchBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_STRETCHBLT kaydı, olası genişleme veya daralma ile bir raster işlemi göre bir piksel bloğunun aktarımını belirtir."
type: docs
weight: 93
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

META\_STRETCHBLT kaydı, olası genişleme veya daralma ile raster işlemi göre bir piksel bloğunun aktarımını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Raster işlemini alır veya ayarlar. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Raster işlemini alır veya ayarlar. |
| [getSrcHeight()](#getSrcHeight--) | Kaynağın yüksekliğini alır veya ayarlar. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Kaynağın yüksekliğini alır veya ayarlar. |
| [getSrcWidth()](#getSrcWidth--) | Kaynağın genişliğini alır veya ayarlar. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Kaynağın genişliğini alır veya ayarlar. |
| [getSrcPosition()](#getSrcPosition--) | Kaynak konumunu alır veya ayarlar. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Kaynak konumunu alır veya ayarlar. |
| [getDestHeight()](#getDestHeight--) | Hedefin yüksekliğini alır veya ayarlar. |
| [setDestHeight(short value)](#setDestHeight-short-) | Hedefin yüksekliğini alır veya ayarlar. |
| [getDestWidth()](#getDestWidth--) | Hedefin genişliğini alır veya ayarlar. |
| [setDestWidth(short value)](#setDestWidth-short-) | Hedefin genişliğini alır veya ayarlar. |
| [getDstPosition()](#getDstPosition--) | DST konumunu alır veya ayarlar. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | DST konumunu alır veya ayarlar. |
| [getReserved()](#getReserved--) | Ayrılmış alanı alır veya ayarlar. |
| [setReserved(short value)](#setReserved-short-) | Ayrılmış alanı alır veya ayarlar. |
| [getBitmap()](#getBitmap--) | Bit eşlemeyi alır veya ayarlar. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Bit eşlemeyi alır veya ayarlar. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Raster işlemini alır veya ayarlar.

Değer: Kaynak pikseller, oynatma aygıt bağlamındaki mevcut fırça ve hedef pikseller yeni görüntüyü oluşturmak için birleştirilecektir. Bu kod MUST Ternary Raster Operation Enumeration içindeki değerlerden biri olmalıdır.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Raster işlemini alır veya ayarlar.

Değer: Kaynak pikseller, oynatma aygıt bağlamındaki mevcut fırça ve hedef pikseller yeni görüntüyü oluşturmak için birleştirilecektir. Bu kod MUST Ternary Raster Operation Enumeration içindeki değerlerden biri olmalıdır.

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

Değer: Kaynak dikdörtgenin mantıksal birimlerdeki genişliği.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Kaynağın genişliğini alır veya ayarlar.

Değer: Kaynak dikdörtgenin mantıksal birimlerdeki genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Kaynak konumunu alır veya ayarlar.

Değer: Kaynak konumu.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Kaynak konumunu alır veya ayarlar.

Değer: Kaynak konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

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

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


DST konumunu alır veya ayarlar.

Değer: DST konumu.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


DST konumunu alır veya ayarlar.

Değer: DST konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Ayrılmış alanı alır veya ayarlar.

Değer: Ayrılmış. Bu alan MUST yok sayılmalıdır.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Ayrılmış alanı alır veya ayarlar.

Değer: Ayrılmış. Bu alan MUST yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Bit eşlemeyi alır veya ayarlar.

Değer: Bit eşlem.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Bit eşlemeyi alır veya ayarlar.

Değer: Bit eşlem.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

