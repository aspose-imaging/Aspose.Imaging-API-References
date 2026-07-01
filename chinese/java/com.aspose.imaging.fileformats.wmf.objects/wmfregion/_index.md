---
title: "WmfRegion"
second_title: "Aspose.Imaging for Java API 参考"
description: "Region Object 定义了一种可能非矩形的形状，由扫描线数组定义。"
type: docs
weight: 62
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

Region 对象定义了一种可能非矩形的形状，该形状由扫描线数组定义。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | 获取或设置链中的下一个。 |
| [setNextInChain(short value)](#setNextInChain-short-) | 获取或设置链中的下一个。 |
| [getObjectType()](#getObjectType--) | 获取或设置对象的类型。 |
| [setObjectType(short value)](#setObjectType-short-) | 获取或设置对象的类型。 |
| [getObjectCount()](#getObjectCount--) | 获取或设置对象计数。 |
| [setObjectCount(int value)](#setObjectCount-int-) | 获取或设置对象计数。 |
| [getRegionSize()](#getRegionSize--) | 获取或设置区域的大小。 |
| [setRegionSize(short value)](#setRegionSize-short-) | 获取或设置区域的大小。 |
| [getScanCount()](#getScanCount--) | 获取或设置扫描计数。 |
| [setScanCount(short value)](#setScanCount-short-) | 获取或设置扫描计数。 |
| [getMaxScan()](#getMaxScan--) | 获取或设置最大扫描。 |
| [setMaxScan(short value)](#setMaxScan-short-) | 获取或设置最大扫描。 |
| [getBoundingRectangle()](#getBoundingRectangle--) | 获取或设置边界矩形。 |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | 获取或设置边界矩形。 |
| [getAScans()](#getAScans--) | 获取或设置扫描。 |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | 获取或设置扫描。 |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


获取或设置链中的下一个。

值：必须忽略的值。

**Returns:**
短
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


获取或设置链中的下一个。

值：必须忽略的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


获取或设置对象的类型。

值：区域标识符。它必须为 0x0006。

**Returns:**
短
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


获取或设置对象的类型。

值：区域标识符。它必须为 0x0006。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


获取或设置对象计数。

值：必须忽略的值。

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


获取或设置对象计数。

值：必须忽略的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


获取或设置区域的大小。

值：区域的大小（字节）加上 aScans 的大小（字节）。

**Returns:**
短
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


获取或设置区域的大小。

值：区域的大小（字节）加上 aScans 的大小（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


获取或设置扫描计数。

值：组成区域的扫描线数量。

**Returns:**
短
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


获取或设置扫描计数。

值：组成区域的扫描线数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


获取或设置最大扫描。

值：此区域中任意一次扫描的最大点数。

**Returns:**
短
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


获取或设置最大扫描。

值：此区域中任意一次扫描的最大点数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


获取或设置边界矩形。

值：定义边界矩形的 Rect 对象（第 2.2.2.18 节）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


获取或设置边界矩形。

值：定义边界矩形的 Rect 对象（第 2.2.2.18 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


获取或设置扫描。

值：定义区域扫描线的 Scan 对象数组（第 2.2.2.21 节）。

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


获取或设置扫描。

值：定义区域扫描线的 Scan 对象数组（第 2.2.2.21 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

