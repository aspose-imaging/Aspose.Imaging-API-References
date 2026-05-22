---
title: "WmfRegion"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Region Nesnesi, tarama satırları dizisiyle tanımlanan potansiyel olarak doğrusal olmayan bir şekli tanımlar."
type: docs
weight: 62
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

Region Nesnesi, tarama satırları dizisiyle tanımlanan potansiyel olarak doğrusal olmayan bir şekil tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Zincirdeki sonraki öğeyi alır veya ayarlar. |
| [setNextInChain(short value)](#setNextInChain-short-) | Zincirdeki sonraki öğeyi alır veya ayarlar. |
| [getObjectType()](#getObjectType--) | Nesnenin türünü alır veya ayarlar. |
| [setObjectType(short value)](#setObjectType-short-) | Nesnenin türünü alır veya ayarlar. |
| [getObjectCount()](#getObjectCount--) | Nesne sayısını alır veya ayarlar. |
| [setObjectCount(int value)](#setObjectCount-int-) | Nesne sayısını alır veya ayarlar. |
| [getRegionSize()](#getRegionSize--) | Bölgenin boyutunu alır veya ayarlar. |
| [setRegionSize(short value)](#setRegionSize-short-) | Bölgenin boyutunu alır veya ayarlar. |
| [getScanCount()](#getScanCount--) | Tarama sayısını alır veya ayarlar. |
| [setScanCount(short value)](#setScanCount-short-) | Tarama sayısını alır veya ayarlar. |
| [getMaxScan()](#getMaxScan--) | Maksimum taramayı alır veya ayarlar. |
| [setMaxScan(short value)](#setMaxScan-short-) | Maksimum taramayı alır veya ayarlar. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Sınırlayıcı dikdörtgeni alır veya ayarlar. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Sınırlayıcı dikdörtgeni alır veya ayarlar. |
| [getAScans()](#getAScans--) | Bir taramayı alır veya ayarlar. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Bir taramayı alır veya ayarlar. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Zincirdeki sonraki öğeyi alır veya ayarlar.

Değer: YOK SAYILMASI GEREKEN bir değer.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Zincirdeki sonraki öğeyi alır veya ayarlar.

Değer: YOK SAYILMASI GEREKEN bir değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Nesnenin türünü alır veya ayarlar.

Değer: Bölge tanımlayıcısı. 0x0006 OLMASI GEREKİR.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Nesnenin türünü alır veya ayarlar.

Değer: Bölge tanımlayıcısı. 0x0006 OLMASI GEREKİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Nesne sayısını alır veya ayarlar.

Değer: YOK SAYILMASI GEREKEN bir değer.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Nesne sayısını alır veya ayarlar.

Değer: YOK SAYILMASI GEREKEN bir değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Bölgenin boyutunu alır veya ayarlar.

Değer: Bölgenin bayt cinsinden boyutu artı aScans'ın bayt cinsinden boyutu.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Bölgenin boyutunu alır veya ayarlar.

Değer: Bölgenin bayt cinsinden boyutu artı aScans'ın bayt cinsinden boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Tarama sayısını alır veya ayarlar.

Değer: Bölgeyi oluşturan tarama satırlarının sayısı.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Tarama sayısını alır veya ayarlar.

Değer: Bölgeyi oluşturan tarama satırlarının sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Maksimum taramayı alır veya ayarlar.

Değer: Bu bölgedeki herhangi bir taramada bulunan maksimum nokta sayısı.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Maksimum taramayı alır veya ayarlar.

Değer: Bu bölgedeki herhangi bir taramada bulunan maksimum nokta sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Sınırlayıcı dikdörtgeni alır veya ayarlar.

Değer: Sınırlayıcı dikdörtgeni tanımlayan bir Rect nesnesi (bölüm 2.2.2.18).

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Sınırlayıcı dikdörtgeni alır veya ayarlar.

Değer: Sınırlayıcı dikdörtgeni tanımlayan bir Rect nesnesi (bölüm 2.2.2.18).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Bir taramayı alır veya ayarlar.

Değer: Bölgedeki tarama satırlarını tanımlayan Scan nesnelerinin bir dizisi (bölüm 2.2.2.21).

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Bir taramayı alır veya ayarlar.

Değer: Bölgedeki tarama satırlarını tanımlayan Scan nesnelerinin bir dizisi (bölüm 2.2.2.21).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

