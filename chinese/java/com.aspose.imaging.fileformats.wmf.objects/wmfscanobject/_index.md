---
title: "WmfScanObject"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Scan 对象指定了一组扫描线。"
type: docs
weight: 69
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

Scan 对象指定了一组扫描线。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取或设置计数。 |
| [setCount(int value)](#setCount-int-) | 获取或设置计数。 |
| [getTop()](#getTop--) | 获取或设置顶部。 |
| [setTop(int value)](#setTop-int-) | 获取或设置顶部。 |
| [getBottom()](#getBottom--) | 获取或设置底部。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置底部。 |
| [getScanLines()](#getScanLines--) | 获取或设置扫描线。 |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | 获取或设置扫描线。 |
| [getCount2()](#getCount2--) | 获取或设置 count2。 |
| [setCount2(int value)](#setCount2-int-) | 获取或设置 count2。 |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


获取或设置计数。

值：`com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines` 数组中水平（x 轴）坐标的数量。该值必须是 2 的倍数，因为每条扫描线需要左、右端点来指定。

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


获取或设置计数。

值：`com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines` 数组中水平（x 轴）坐标的数量。该值必须是 2 的倍数，因为每条扫描线需要左、右端点来指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


获取或设置顶部。

值：顶部扫描线的垂直（y 轴）坐标，单位为逻辑单位。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


获取或设置顶部。

值：顶部扫描线的垂直（y 轴）坐标，单位为逻辑单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


获取或设置底部。

值：底部扫描线的垂直（y 轴）坐标，单位为逻辑单位。

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


获取或设置底部。

值：底部扫描线的垂直（y 轴）坐标，单位为逻辑单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


获取或设置扫描线。

值：扫描线数组，每条扫描线由其端点的左、右水平（x 轴）坐标指定。

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


获取或设置扫描线。

值：扫描线数组，每条扫描线由其端点的左、右水平（x 轴）坐标指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


获取或设置 count2。

值：与 `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count` 字段的值相同；此字段存在是为了允许在结构中向上遍历。

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


获取或设置 count2。

值：与 `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count` 字段的值相同；此字段存在是为了允许在结构中向上遍历。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

