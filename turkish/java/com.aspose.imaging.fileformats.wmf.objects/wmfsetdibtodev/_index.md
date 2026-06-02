---
title: "WmfSetDibToDev"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_SETDIBTODEV kaydı, cihazdan bağımsız renk verileri kullanarak oynatma cihaz bağlamında bir piksel bloğu ayarlar."
type: docs
weight: 75
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

META\_SETDIBTODEV kaydı, cihazdan bağımsız renk verileri kullanarak oynatma cihaz bağlamında bir piksel bloğu ayarlar. Renk verisinin kaynağı bir DIB'dir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Renk kullanımını alır veya ayarlar. |
| [setColorUsage(int value)](#setColorUsage-int-) | Renk kullanımını alır veya ayarlar. |
| [getScanCount()](#getScanCount--) | Tarama sayısını alır veya ayarlar. |
| [setScanCount(int value)](#setScanCount-int-) | Tarama sayısını alır veya ayarlar. |
| [getStartScan()](#getStartScan--) | Başlangıç taramasını alır veya ayarlar. |
| [setStartScan(int value)](#setStartScan-int-) | Başlangıç taramasını alır veya ayarlar. |
| [getDibPos()](#getDibPos--) | dib konumunu alır veya ayarlar. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | dib konumunu alır veya ayarlar. |
| [getHeight()](#getHeight--) | Yüksekliği alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | Yüksekliği alır veya ayarlar. |
| [getWidth()](#getWidth--) | Genişliği alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Genişliği alır veya ayarlar. |
| [getDestPos()](#getDestPos--) | hedef konumunu alır veya ayarlar. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | hedef konumunu alır veya ayarlar. |
| [getDib()](#getDib--) | dib'i alır veya ayarlar. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | dib'i alır veya ayarlar. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Renk kullanımını alır veya ayarlar.

Değer: DIB'in Colors alanı açık RGB değerleri veya bir palete indeksler içerir. Bu, `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` Sıralamasındaki (bölüm 2.1.1.6) değerlerden biri OLMASI GEREKİR.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Renk kullanımını alır veya ayarlar.

Değer: DIB'in Colors alanı açık RGB değerleri veya bir palete indeksler içerir. Bu, `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` Sıralamasındaki (bölüm 2.1.1.6) değerlerden biri OLMASI GEREKİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Tarama sayısını alır veya ayarlar.

Değer: Kaynaktaki tarama satırlarının sayısı.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Tarama sayısını alır veya ayarlar.

Değer: Kaynaktaki tarama satırlarının sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Başlangıç taramasını alır veya ayarlar.

Değer: Kaynağın başlangıç tarama satırı.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Başlangıç taramasını alır veya ayarlar.

Değer: Kaynağın başlangıç tarama satırı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


dib konumunu alır veya ayarlar.

Değer: Kaynak dikdörtgenin mantıksal birimlerdeki koordinatları.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


dib konumunu alır veya ayarlar.

Değer: Kaynak dikdörtgenin mantıksal birimlerdeki koordinatları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Yüksekliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Yüksekliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Genişliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Genişliği alır veya ayarlar.

Değer: Kaynak ve hedef dikdörtgenlerin mantıksal birimlerdeki genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


hedef konumunu alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin mantıksal birimlerdeki koordinatları.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


hedef konumunu alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin mantıksal birimlerdeki koordinatları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


dib'i alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin mantıksal birimlerdeki y-koordinatı.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


dib'i alır veya ayarlar.

Değer: Hedef dikdörtgenin sol üst köşesinin mantıksal birimlerdeki y-koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

